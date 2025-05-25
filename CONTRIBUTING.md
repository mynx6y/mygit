# 팀 Git 사용 규칙

## 브랜치 전략

| 브랜치 | 설명 |
|--------|------|
| main | 배포용, 최종 코드만 존재 |
| dev (선택) | 통합 개발 브랜치 |
| feature/이름 | 기능 개발 브랜치 (ex: feature/jiyoon) |
| bugfix/이름 | 버그 수정 브랜치 |

## 작업 흐름

1. main 최신화: `git checkout main && git pull`
2. 새 브랜치 생성: `git checkout -b feature/이름`
3. 작업 후 커밋 & 푸시
4. GitHub에서 PR 생성
5. 코드 리뷰 & 승인 후 병합

## 병합 규칙

- main 브랜치에 직접 push 금지
- 반드시 PR로 병합할 것
- 최소 1명 리뷰 승인 필수

## 브랜치 이름 규칙

- 기능 추가: `feature/이름`
- 버그 수정: `bugfix/이름`
- 문서 변경: `docs/이름`

