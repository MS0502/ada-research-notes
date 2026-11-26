# Ada 연구일지

RTX 3060 12GB가 달린 개인 PC에서 로컬 AI 에이전트 Ada에 파일·코드·3D 작업을 맡기고 있습니다. 이곳에는 작업이 막힌 화면, 원인을 좁힌 과정, 수정 후 확인한 결과를 남깁니다.

## 1. 기술 연구 데이터

| 기록 | 이 글에서 확인할 수 있는 것 |
| --- | --- |
| [Godot 로그는 깨끗했는데 왜 화면이 비었을까](cases/godot-blank-screen.md) | 충돌체 크기 오류 3건을 고친 뒤에도 비었던 화면, 최소 장면 검사, 주변광·안개 수정 전후 |
| [캐릭터의 발이 밀리는 구간을 재서 걷기 맞추기](cases/godot-foot-slide.md) | 접지 구간의 정의, 클립 재생 길이 후보 비교, 재계산 가능한 걷기·달리기 기록 |
| [3D 작업 1–5단계의 판정과 재사용 기록](cases/godot-curriculum.md) | 과제별 시간·검사·개입, 가져오기 캐시와 면 감김 진단, 화면 비교 |
| [Neon Blaster 결과물 다섯 개 비교](cases/neon-blaster-comparison.md) | 제작 조건과 사용량, 모델별 플레이 화면, Ada가 만든 오프라인 게임 |
| [같은 최적화 과제를 네 하네스로 비교](archive/harness-rules-comparison.md) | 두 배치의 통과 수·실행 시간·404, 시행별 CSV |
| [A스페이스를 켜고 끈 복셀 과제](cases/aspace-voxel.md) | 초기 서버 장애와 재실행, 자동 인출과 토큰 비용, 남은 게임 결함 |
| [RTX 3060 eGPU에서 Inkling-2-Mini 4비트 돌리기](cases/inkling2-rtx3060-egpu.md) | 프리필·디코드 실측, MoE 버그 수정, NInfer 비교와 요청별 CSV |
| [1M 컨텍스트를 시험하고 262K로 돌아온 이유](cases/long-context-memory.md) | 엔진·KV별 실행 결과와 RAM 병목 |
| [외부 검증기를 실행하기 전에 확인한 것](archive/runner-preflight.md) | 기존 GitHub 저장소에서 가져온 실행 환경 사전 점검 |

[실험 자료와 공개 현황](archive/data-catalog.md) · [이전 연구 기록 찾아보기](archive/index.md)

## 2. 실사용 앱 개선

- [앱 패치 기록](app/patch-history.md)에서 변경 이유, 사용자 요청·Ada 관찰·외부 에이전트 제안, 구현과 검증, 남은 문제를 확인할 수 있습니다.
- [채팅 실행 기록과 우측 작업 보기](cases/ada-app-execution-view.md)는 실제 화면을 보며 두 기능의 쓰임을 설명합니다.

X에는 각 사건의 요약과 실제 화면을 올립니다. 이곳에는 모델·과제·측정 조건 중 확인할 수 있는 항목, 로그나 결과물로 확인한 수정, 리뷰어 개입을 적습니다. [Ada Labs on X](https://x.com/Ada_labs_F)
