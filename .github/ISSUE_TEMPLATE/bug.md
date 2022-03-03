---
name: Bug
about: 버그가 발생할 경우 사용한다.
title: "(ex) 아파트명 검색 시 버그 발생"
labels: 'Type: Bug'
assignees: ''

---

**버그 설명**
아파트명 작성후 검색 버튼을 클릭하면 500 에러가 발생한다.
```
java.lang.NullPointerException: Cannot invoke "java.sql.Connection.prepareStatement(String)" because "this.conn" is null
```

_해결한 점들을 공유하고 싶거나 논의점들은 Comment로 소통한다._
