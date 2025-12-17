# Git Branch Workflow

## 브랜치 구조

- `release`: 배포 준비가 완료된 코드
- `dev`: 개발 통합 브랜치
- `feature/*`: 개별 기능 개발 브랜치
- `fix/*`: 버그 수정 브랜치

## feature 브랜치

1. 해당 Issue를 통해 `dev` 브랜치에서 새로운 feature 브랜치 생성
2. 변경사항 작업 및 커밋
3. 원격 저장소에 변경사항 푸시
4. `dev` 브랜치로 [Pull Request 작성](./PULL_REQUEST_GUIDE.md)

## dev 브랜치

- 모든 기능 개발은 `dev`로 병합

## release 브랜치

- 배포에 사용할 브랜치
