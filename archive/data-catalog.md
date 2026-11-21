# Ada 자료 목록

실험마다 날짜와 질문, 모델·엔진·하네스 조건, 시행 수, 로그에서 확인한 실패, 수정 후 검사, 리뷰어가 개입한 지점을 함께 보관합니다. 확인할 수 없는 조건은 문서에 그대로 표시합니다.

| 분야 | 보관 중인 자료 | 현재 공개된 기록 |
| --- | --- | --- |
| 모델·추론 엔진 | 모델 비교, 양자화, 추론 예산, KV 형식, 속도, VRAM·RAM, 자원 부족과 재시작 | [1M 컨텍스트 메모리 점검](../cases/long-context-memory.md) |
| 하네스·벤치마크 | 같은 과제의 런, 중단·재시도, 결정 지점 재생, 압축 검증, 평가 기준과 통과 수 | [네 하네스 구성 비교](harness-rules-comparison.md), [외부 실행 환경 사전 점검](runner-preflight.md) |
| 기억·노하우 | A스페이스 실험, 계획 갱신, 스킬을 읽은 기록, 성찰일지와 다음 작업에서 관찰한 행동 | [A스페이스 비교와 시행별 표](../cases/aspace-voxel.md), [촬영 진단 재사용](../cases/godot-blank-screen.md#무엇을-보고-수정했나) |
| 앱과 작업 도구 | 앱의 버전별 화면, 권한 확인, 명령·파일 작업 내역과 촬영 도구 | [앱 패치 기록](../app/patch-history.md), [채팅과 작업 보기](../cases/ada-app-execution-view.md) |
| 게임·3D | 복셀·비행·2D 슈터 결과물 비교, Godot 코스, Blender 에셋, 캐릭터 리깅과 애니메이션 | [Neon Blaster 5종 실행 비교](../cases/neon-blaster-comparison.md), [3D 작업 다섯 단계](../cases/godot-curriculum.md) |
| 이전 공개글 | 주간 일지, 3D 진행 일지, 모델별 결과물 갤러리 | [주제별 이전 글 목록](index.md) |

## 바로 열 수 있는 데이터

| 파일 | 행의 의미 | 연결 문서 |
| --- | --- | --- |
| [A스페이스 복셀 실험 CSV](../data/aspace/voxel-runs.csv) | 초기 배치와 재실행의 시행 한 건. 장애는 점수 칸을 비우고 종료 상태에 표시 | [실험 해설](../cases/aspace-voxel.md) |
| [하네스 비교 92회 CSV](../data/harness/edge2-trials.csv) | 배치·변형·시드·실제 소요 시간·통과·종료 코드 | [두 배치 비교](harness-rules-comparison.md) |
| [Neon Blaster 단일 HTML](../artifacts/neon-blaster.html) | Ada가 만든 오프라인 실행 파일. 외부 후보는 비교 문서에서 실제 화면과 원본 링크로 확인 | [모델별 제작 조건과 결과](../cases/neon-blaster-comparison.md) |
| [걷기 기본](../data/foot-slide/walk-natural.csv), [걷기 보정](../data/foot-slide/walk-measured.csv) | 걷기 테스트의 프레임 번호와 각 발 좌표 | [걷기·달리기 측정법](../cases/godot-foot-slide.md) |
| [달리기 기본](../data/foot-slide/run-natural.csv), [달리기 보정](../data/foot-slide/run-measured.csv) | 달리기 테스트의 프레임 번호와 각 발 좌표 | [걷기·달리기 측정법](../cases/godot-foot-slide.md) |

모델 출력과 도구 로그가 남아 있어도, 사람 개입이나 변경 조건을 대조해야 수치를 해석할 수 있습니다. 이 표의 공개 링크가 붙은 주제는 해당 문서와 자료를 함께 볼 수 있습니다. 공개 문서는 개인정보와 내부 작업 설정을 걷어낸 발췌와 집계본을 사용합니다.
