# Git 네이밍 컨벤션 > Branch Naming

꼭 지켜야 되는 부분:
- 명령적인 현재 시제로 짧은 서술 요약을 포함합니다.
- 단어를 구분하기 위해 하이픈을 사용합니다.

아마도 지켜야 되는 부분:
- 작업 타입을 포함합니다: feature, refactor, bugfix, hotfix, etc.
- 대응하는 ticket/story id를 포함합니다. (e.g. Jira, GitHub issue, 등에서 발췌.)

권장되는 형태:   
*{작업 타입 e.g.}/{2-3 단어 요약}/{스토리 또는 티켓의 id}_*

예시:
```git
git checkout -b feature/oauth-migration/ATL-244
```