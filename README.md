# Codyssey AI Native — 입학연수과정

코디세이 AI 네이티브 **입학연수과정**에서 수행한 미션 기록 저장소입니다.
모든 미션은 하나의 결과물인 **영화 티어리스트** 웹페이지를 단계적으로 발전시킨 과정입니다.

각 미션 폴더에는 결과물뿐 아니라 무엇을 시도했고, 어떻게 확인했고, 왜 그렇게 선택했는지를 함께 기록합니다.

🔗 **배포 페이지**: https://dt-oksuu.github.io/codyssey-native-onboarding/M2_deploy-worker/

## Mission Map

| 미션 | 핵심 주제 | 주요 결과물 | 기록 |
|---|---|---|---|
| [M1](./M1_ai-draft-compare/) | 기획서 작성, 두 AI로 초안을 만들어 같은 행동으로 비교 | `영화_A_초안.html`, `영화_B_초안.html` | [미션1_기록](./M1_ai-draft-compare/미션1_기록.md) |
| [M2](./M2_deploy-worker/) | GitHub Pages 배포, API 키를 Cloudflare Worker로 숨기기 | `index.html`(배포본), `worker/worker.js` | [미션2_기록](./M2_deploy-worker/미션2_기록.md) |
| [M3](./M3_feedback/) | 받은 피드백을 기획서 기준으로 직접 확인하고 반영·보류·되묻기 | `피드백.md` | [미션3_기록](./M3_feedback/미션3_기록.md) |
| [M4](./M4_feature-recovery/) | 기능 추가와 복구, 두 AI 버전 비교·검증, 추천 기능 버전 | `Tier_v1·v2.html`, `index_v2~v4.html`, `제작검증기록.md` | [미션4_기록](./M4_feature-recovery/미션4_기록.md) |

## 공통 문서

| 문서 | 내용 |
|---|---|
| [기획서](./docs/기획서.md) | 영화 티어리스트 + 추천 기능 기획서 (최신본) |
| [기획서_양식](./docs/기획서_양식.md) | 기획서 작성 양식 |

## 사용 기술

HTML · CSS · JavaScript, TMDB API, Cloudflare Workers, GitHub Pages

## Repository Structure

```
codyssey-native-onboarding/
├── docs/                  # 미션 공통 기획 문서
├── M1_ai-draft-compare/   # 두 AI 초안 비교
├── M2_deploy-worker/      # 배포 + API 키 보호 (Worker)
├── M3_feedback/           # 피드백 검증
├── M4_feature-recovery/   # 기능 추가·복구, 버전 비교
└── README.md
```
