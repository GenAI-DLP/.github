---

# 🛡️ LLM Data Loss Prevention(DLP) for Enterprise 🛡️
기업용 LLM 사용을 위한 AI 기반 **Data Loss Prevention(DLP) 시스템**입니다.

### 💡 Core Idea

Go 프록시 서버에서 LLM 트래픽을 가로채고, FastAPi 기반 백엔드에서 멀티턴 문맥 기반 PII 탐지 및 마스킹을 수행합니다. 검증이 완료된 요청만 외부 LLM으로 전달하여 민감정보 유출을 사전에 방지합니다.

### 🔗 Github Links
1. [DLP Proxy Server](https://github.com/GenAI-DLP/dlp-proxy-server)
2. [Main DLP Server](https://github.com/GenAI-DLP/dlp-server)
3. [Gateway](https://github.com/GenAI-DLP/gateway)
4. [Dashboard](https://github.com/GenAI-DLP/dashboard)

### 📝 Documents
- [Docs](https://github.com/GenAI-DLP/docs)
- 위 repo에는 architecture 및 구현 세부 사항과 관련된 md파일들이 정리되어 있습니다.




---
# 🛠️ Architecture

![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![Go](https://img.shields.io/badge/Go-00ADD8?style=flat-square&logo=go&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![AWS](https://img.shields.io/badge/AWS-232F3E?style=flat-square&logo=amazonaws&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![React](https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=black)

<img width="1058" height="694" alt="image" src="https://github.com/user-attachments/assets/4895f6dc-1106-4c8c-b0a5-fde9f08881c7" />



---
# 🎨 Flowchart


<div align="center">
  <img src="./architecture.svg" alt="DLP Workflow" width="900">
</div>


