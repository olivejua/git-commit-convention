# Commit

## Convention
```
type: subject (#issue number)
(한줄 띄움)
body
(한줄 띄움)
footer
```

### Convention: type
|name|description|examples|
|:----:|-----------|-------------|
|feat|새로운 기능 추가|로그인 기능 구현, 커뮤니티 게시글 작성 등|
|fix|버그 해결|앱 접속 에러 등|
|chore|빌드 관련 수정|build task 추가, dependency 추가 등|
|ci|CI 관련 수정에 대한 커밋|merge 하기 위한 코드 수정 등|
|docs|문서 수정|READ ME 등 등|
|style|코드 스타일 혹은 포맷 (코드 변경이 없는 경우)|서식지정, 세미콜론 누락, 띄어쓰기 한줄, 오타 한글자 등|
|refactor|코드 리팩토링|이름 변경, 코드파일 이동 등| 
|test|테스트코드 작성|게시글 작성 테스트 코드 구현, 수정 등|

### Convention: subject
- 한글로 작성한다.
- 길이는 50글자 내로 제한한다.
- 제목 끝에 마침표를 넣지 않는다.

### Convention: body (Optional)
- 대부분 커밋제목만으로 내용을 파악할 수 있다. 따라서 부연설명이 필요할 경우만 작성한다.
- 어떻게 (X) / 무엇을, 왜 (O)
- 제목과 구분되기 때문에 한칸 띄어 작성한다.

### Convention: footer (Optional)
- 선택사항이니 반드시 작성하지 않아도 된다.
- 주로 이슈트래킹 용도로 사용한다.


_Git을 잘 활용하고 있는 참고할만한 곳들_
- https://github.com/angular/angular
