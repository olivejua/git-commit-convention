---
name: Enhancement
about: 기능 개선, 보완, 추가할 경우 사용한다.
title: "(ex) Board의 게시글 작성 기능을 개선한다."
labels: 'Type: Enhancement'
assignees: ''

---

**개선해야하는 계기**
게시글 작성 로직에 Exception 처리를 하지 않아 예외 파악을 하는데 시간이 걸림

**개선해야할 점**
Exception 규칙을 정하여 각 상황에 맞는 Custom Exception 메시지를 적용하여 처리를 함
