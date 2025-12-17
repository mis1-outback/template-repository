# Pull Request 규칙

## 생성법

### 1. 진행하고자 하는 Issue 클릭

### 2. Development 항목에서 create a branch 클릭하여 원격 브랜치 새로 생성
- Branch source로 "release" 선택
- 브랜치 이름은 영어로 작성하되, 해당 Issue를 잘 표현하도록 작성
  > "feature/signup"  
  > "fix/login"
- 위 방법으로 브랜치를 생성한 후, push 하게되면 PR이 자동으로 Issue와 연동됨

### 3. 생성된 branch를 Local에 Pull

### 4. 해당 Backlog를 In Progress로 옮기기

### 5. 코드 작성 후 push

### 6. Pull Request 생성


## 작성법

### 1. "Able to merge" 문구 확인
- 충돌이 일어난 경우 로컬에서 해결한 다음 다시 push
- 충돌 해결은 **충돌 당사자와 반드시 협의**

### 2. Title, Description 간략히 작성
- Title은 해당 기능에 대해 간결하게 작성
- Description은 템플릿에 맞춰 작성

### 3. Reviewers 지정
- chocolaggibbiddori 혹은 Manager Team으로 지정

### 4. Assignees 지정
- 본인 지정(assign yourself 문구 클릭)


## 수정법

### 1. Pull Request를 생성한 후, 커밋 수정이 필요한 경우에는, Local에서 커밋 생성 후 다시 push
> PR을 닫거나, 삭제할 필요가 없습니다.

### 2. Comment를 잘 읽어보고 다음 동작을 수행
- 수정할 부분은 수정
- 해당 comment에 대해 질문이 있거나 궁금한 것은 comment로 답변
- PR 안에서도 대화를 주고 받을 수 있습니다. 해당 PR에 대한 내용은 PR 안에서 기록을 남길 수 있게 최대한 comment를 이용

### 3. 결재가 되면, 관리자가 Merge
- PR 당사자는 merge를 수행하지 않음
