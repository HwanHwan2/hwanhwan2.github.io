---
layout: post
title: Git
nav_order: 1
---

## **커밋 메시지** 
--- 

### **커밋 메시지 7가지 규칙** 
#### 1. 제목과 본문을 빈 행으로 구분한다.
#### 2. 제목은 50글자 이내로 제한한다.
#### 3. 제목의 첫 글자는 대문자로 작성한다.
#### 4. 제목 끝에는 마침표를 넣지 않는다.
#### 5. 제목은 명령문으로 사용하며 과거형을 사용하지 않는다.
#### 6. 본문의 각 행은 72글자 내로 제한한다.
#### 7. 어떻게 보다는 무엇과 왜를 설명한다. 

### **작성 규칙**
```
<타입이름>:<제목> //필수

<본문> //생략 가능

<바닥글> //생략 가능
```

|타입 이름|내용|
|--|--|
|feat|새로운 기능에 대한 커밋|
|fix|버그 수정에 대한 커밋|
|build|빌드 관련 파일 수정 / 모듈 설치 또는 삭제에 대한 커밋|
|chore|그 외 자잘한 수정에 대한 커밋|
|ci|ci 관련 설정 수정에 대한 커밋|
|docs|문서 수정에 대한 커밋|
|style|코드 스타일 또는 포맷 등에 관한 커밋|
|refactor|코드 리팩토링에 대한 커밋|
|test|테스트 코드 수정에 대한 커밋|
|perf|성능 개선에 대한 커밋|