# Gabi Weekly Planner

가비의 주간 계획을 HTML로 생성하고, GitHub Pages로 배포해 모바일에서 바로 열어볼 수 있게 만드는 저장소입니다.

## What This Repo Does

이 프로젝트는 아래 흐름을 기준으로 운영합니다.

1. 옵시디언의 알림장 Markdown을 읽습니다.
2. 자연어 내용을 파싱해 `마감`, `루틴`, `독서` 항목으로 정리합니다.
3. 주간 계획표를 HTML로 생성합니다.
4. 생성된 파일을 아카이브합니다.
5. GitHub에 푸시하면 GitHub Pages로 자동 배포합니다.

## Output Convention

- 파일명 형식: `YYYY-Www.html`
- 예시: `2026-W24.html`

배포 후에는 아래 형식의 주소로 접속할 수 있습니다.

`https://<github-username>.github.io/<repo-name>/2026-W24.html`

## Recommended Repository Setup

처음 한 번만 아래처럼 설정하면 됩니다.

1. GitHub에 전용 공개 저장소를 만듭니다.
2. `Settings > Pages`에서 GitHub Pages를 켭니다.
3. 배포 소스를 `Deploy from a branch`로 설정합니다.
4. 브랜치는 `main`, 폴더는 `/(root)`를 선택합니다.

## Suggested Folder Role

- `outputs/`: 사용자에게 보여주거나 보관할 결과물
- `work/`: 작업 중간 산출물과 임시 파일

## Notes

- 이 저장소의 README는 프로젝트 소개용입니다.
- 에이전트 프롬프트나 내부 동작 규칙은 별도 문서로 관리하는 것을 권장합니다.
