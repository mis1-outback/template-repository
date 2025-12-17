# Git Commit Message Convention

## 1. 기본 구조

```
[type]: [subject]

[body]

[footer]
```

- `body`, `footer`는 선택 사항

## 2. 예시

feat: add JWT authentication

- validate access token
- add refresh token logic

issue: #12

## 3. Type 정의

| Type     | 설명                   |
|----------|----------------------|
| feat     | 새로운 기능 추가            |
| fix      | 버그 수정                |
| refactor | 리팩토링 (기능 변경 없음)      |
| docs     | 문서, 주석 수정            |
| test     | 테스트 코드 추가 또는 수정      |
| style    | 코드 스타일 변경 (포맷, 공백 등) |

## 4. Subject 규칙

- subject만 읽어도 커밋 내용을 유추할 수 있도록 작성
- 마침표(`.`) 사용 금지
- 50자 이내 권장

## 5. Body 규칙 (선택)

- 변경한 **이유(Why)** 와 **내용(What)** 을 설명
- 여러 줄 작성 가능

## 6. Footer 규칙 (선택)

- Issue 번호 명시
