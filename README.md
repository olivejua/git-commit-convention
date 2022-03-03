### 지향하는 방향: 최대한 덜 귀찮게 간단한 형식으로!

# Github을 이용한 작업 순서
1. 이슈를 작성한다.
2. 이슈 기반의 작업하여 커밋을 한다.
3. 작업을 완료하면 이슈를 종료한다.

## 1. 이슈를 작성한다.

### Templates
- [Feature](https://github.com/olivejua/git-commit-convention/issues/new?assignees=&labels=Type%3A+Feature&template=feature.yml)
- [Enhancement](https://github.com/olivejua/git-commit-convention/issues/new?assignees=&labels=Type%3A+Enhancement&template=enhancement.yml)
- [Bug](https://github.com/olivejua/git-commit-convention/issues/new?assignees=&labels=Type%3A+Bug&template=bug.yml)
   - 정말 자잘한 버그일 수 있다. 커밋 제목만으로도 설명이 가능하다면 이슈 작성을 하지 않아도 된다!
   - 하지만 앞으로 같은 버그가 일어날 가능성이 있다거나 간단한 버그가 아닐 경우에는 작성하는 것이 좋다.
- Custom Template
  
### Labels
|name|description|
|----|---------|
|Priority: Critical|우선순위: 매우 높음|
|Priority: High|우선순위: 높음|
|Priority: Medium|우선순위: 중간|
|Priority: Low|우선순위: 낮음|
|Status: Confirmed|작업 상태: 확인됨|
|Status: Feedback Needed|작업 상태: 피드백 필요|
|Status: In Progress|작업 상태: 진행 중|
|Status: Complete|작업 상태: 완료|
|Status: On Hold|작업 상태: 보류|
|Status: Review Needed|작업 상태: 리뷰 필요|
|Status: Wont do/fix|작업 상태: 대응하지 않거나 작업을 계속 하지 않음|
|Type: Bug|타입: 버그 관련|
|Type: Feature|타입: 기능 구현|
|Type: Question|타입: 협의가 필요한 질문|
|Type: Idea|타입: 제안 또는 적용할법한 참고할 거리|
|Type: Enhancement|타입: 새로운 기능 요청 또는 기능 개선 사항|
|Type: Help Needed|타입: 이 이슈에 대해 도움이 필요|



## 2. 커밋을 한다.
### Convention
```
type: subject (#issue number)
(한줄 띄움)
body
(한줄 띄움)
footer
```

#### Convention: type
|name|description|examples|
|:----:|-----------|-------------|
|feat|새로운 기능 추가|로그인 기능 구현, 커뮤니티 게시글 작성 등|
|fix|버그 해결|앱 접속 에러 등|
|chore|프로젝트 세팅 관련|build task 추가, dependency 추가, properties 수정 등|
|ci|CI 관련 수정에 대한 커밋|merge 하기 위한 코드 수정 등|
|docs|문서 수정|READ ME 등 등|
|style|코드 스타일 혹은 포맷 (코드 변경이 없는 경우)|서식지정, 세미콜론 누락, 띄어쓰기 한줄, 오타 한글자 등|
|refactor|코드 리팩토링|이름 변경, 코드파일 이동 등| 
|test|테스트코드 작성|게시글 작성 테스트 코드 구현, 수정 등|

#### Convention: subject
- 한글로 작성한다.
- 길이는 50글자 내로 제한한다.
- 제목 끝에 마침표를 넣지 않는다.

#### Convention: body (Optional)
- 대부분 커밋제목만으로 내용을 파악할 수 있다. 따라서 부연설명이 필요할 경우만 작성한다.
- 어떻게 (X) / 무엇을, 왜 (O)
- 제목과 구분되기 때문에 한칸 띄어 작성한다.

#### Convention: footer (Optional)
- 선택사항이니 반드시 작성하지 않아도 된다.
- 주로 이슈트래킹 용도로 사용한다.


## 3. 이슈를 종료한다.
별거없다.  
close 버튼을 눌러 종료하자! 


* * *
#### 참고한 곳들
- https://udacity.github.io/git-styleguide/
- https://blog.adam-marsden.co.uk/better-github-labels-f1360b43e0a7
- https://docs.github.com/en/communities/using-templates-to-encourage-useful-issues-and-pull-requests/configuring-issue-templates-for-your-repository#creating-issue-forms

#### Git을 잘 활용하고 있는 참고할만한 곳들
- https://github.com/angular/angular
