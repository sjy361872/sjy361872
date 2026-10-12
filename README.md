### 신지용 · AI 서비스 개발

LLM 서비스의 의도 분류, 멀티 에이전트 설계, sLLM 파인튜닝, 서빙과 배포를 한 흐름으로 만들어 봤습니다.
점수보다 서비스 목적에 맞는 지표를 기준으로 모델을 고릅니다.

#### 프로젝트

| 프로젝트 | 내용 | 담당 |
|---|---|---|
| [DUDE](https://github.com/SKNETWORKS-FAMILY-AICAMP/SKN21-FINAL-3TEAM) | 사내 업무용 멀티 에이전트 AI 비서 (2026.01–03, 4명) | PM, LangGraph 오케스트레이터, 문서 Agent, sLLM 파인튜닝·서빙 |
| [PyMate](https://github.com/SKNETWORKS-FAMILY-AICAMP/SKN21_3rd_4Team) | Python 학습용 RAG 챗봇 (2026.01–02) | 검색(하이브리드 검색, 공식문서 전처리), AWS 배포 |

- DUDE: 문서 작성 sLLM(Kanana-1.5-8B, QLoRA)에서 입력에 없는 내용을 지어내는 비율 44.3% → 17.9%

#### 기술
LangGraph · LangChain · OpenAI API · Transformers · PEFT(QLoRA) · vLLM · RunPod · Qdrant · FastAPI · Django · PostgreSQL · Docker Compose · Nginx · AWS EC2·RDS

#### 연락
jiyong1110@naver.com
