# Git Conventions

## Branch Naming Convention

| 이름 | 규칙 | 설명 | 분기점 | 병합점 |
|---|---|---|---|---|
| Master | `main` | 배포 가능한 최종 상태의 브랜치 | - | Develop |
| Develop | `develop` | 기능 개발을 위한 분기 및 병합 지점으로 사용하는 브랜치 | Master | Release |
| Release | `release/v<release-version>` | 배포를 위한 마무리 작업 브랜치 | Develop | Master |
| Hotfix | `hotfix/v<hotfix-version>` | 배포 버전에서 발생한 버그 긴급 수정 작업 브랜치 | Master | Master, Develop |
| Feature | `feature/<feature-name>` | 기능 개발 브랜치 | Develop | Develop |
| Refactoring | `refactor/<feature-name>` | 리팩토링 브랜치 | Develop | Develop |
