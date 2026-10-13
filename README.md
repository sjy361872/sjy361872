### 신지용 · AI 서비스 개발

LLM 서비스의 의도 분류, 멀티 에이전트 설계, sLLM 파인튜닝, 서빙과 배포까지 한 흐름으로 설계하고 구현했습니다.
점수보다 서비스 목적에 맞는 지표를 기준으로 모델을 고릅니다.

#### 프로젝트

**[DUDE](https://github.com/SKNETWORKS-FAMILY-AICAMP/SKN21-FINAL-3TEAM)** — 사내 업무용 멀티 에이전트 AI 비서 (2026.01–03, 4명)
PM · LangGraph 오케스트레이터 · 문서 Agent · sLLM 파인튜닝·서빙
- 문서 작성 sLLM(Kanana-1.5-8B, QLoRA)에서 입력에 없는 내용을 지어내는 비율 **44.3% → 17.9%**
- 다른 점수가 올랐어도 이 비율이 나빠진 후속 모델은 기각
- RunPod Serverless(vLLM)에 파인튜닝 모델 서빙 구축, Reranker 지연(245초, 요청이 겹치면 440초) 문제를 원인별로 해결

**PyMate** ([3차 검색](https://github.com/SKNETWORKS-FAMILY-AICAMP/SKN21_3rd_4Team) · [4차 배포](https://github.com/SKNETWORKS-FAMILY-AICAMP/SKN21-4th-4Team)) — Python 학습용 RAG 챗봇 (2026.01–02)
3차 검색 · 4차 배포·인프라
- Python 공식문서(RST) 전처리, 검색 설정 7가지를 비교해 하이브리드 검색(벡터 + 키워드) 채택
- Django·Nginx·Qdrant를 Docker Compose로 묶어 AWS EC2 배포, DB를 RDS PostgreSQL로 전환

#### 기술
`LangGraph` `LangChain` `OpenAI API` `Transformers` `PEFT(QLoRA)` `vLLM` `RunPod` `Qdrant`
`FastAPI` `Django` `PostgreSQL` `Docker Compose` `Nginx` `AWS EC2·RDS`

#### 연락
📧 jiyong1110@naver.com
