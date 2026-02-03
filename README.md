# 🛩️ AITG Project
**"Empowering War Thunder Communities with Seamless Automation and Real-time Data"**

AITG 프로젝트는 글로벌 게임 'War Thunder' 유저들을 위한 맞춤형 커뮤니티 생태계를 구축합니다. 
단순한 봇을 넘어, 전용 백엔드 서버와 모니터링 시스템을 결합하여 1년 이상 안정적인 실서비스를 제공하고 있습니다.

---

## 🏗️ System Architecture
AITG는 확장성과 유지보수성을 위해 마이크로서비스 지향 아키텍처를 채택하고 있습니다.

- **AITG-Backend:** FastAPI 기반의 중앙 데이터 허브로, 모든 데이터 파이프라인과 비즈니스 로직을 담당합니다.
- **AITG-Bot:** discord.py 기반의 클라이언트 서비스로, 백엔드 API와 통신하여 유저 인터페이스를 제공합니다.
- **LogFlare-CAU:** 실시간 에러 로그 수집 및 장애 대응을 위한 자체 구축 모니터링 시스템입니다.



---

## 🚀 Key Features
사용자 중심의 기능을 제공하며, 모든 데이터는 백엔드 파이프라인을 통해 실시간으로 가공됩니다.

- **실시간 뉴스 구독:** 공식 홈페이지의 최신 소식을 스크래핑하여 지정된 채널로 자동 배달합니다.
- **비행대원(클랜) 관리:** 인게임 활동 내역 대조 및 계정 연동을 통한 효율적인 커뮤니티 관리를 지원합니다.
- **지상 장비 검색:** 배틀레이팅(BR), 국가별 성능 등 복잡한 장비 데이터를 직관적인 Embed 형식으로 제공합니다.
- **클랜전 일정 자동화:** 인원 모집부터 시작 전 알림까지 전체 프로세스를 슬래시 명령어로 자동화합니다.
- **글로벌 다국어 지원:** JSON 기반 Localization 시스템을 통해 한국어와 영어 환경을 모두 지원합니다.

---

## 🛠️ Tech Stack
신뢰성 있는 서비스를 위해 검증된 기술 스택을 상황에 맞게 유연하게 활용합니다.

- **Languages:** Python 3.12, Java, JavaScript, Kotlin
- **Backend:** FastAPI, SQLAlchemy (ORM), Alembic (Migration), Pydantic
- **Database:** SQLite (aiosqlite) 및 PostgreSQL 호환 아키텍처
- **Infrastructure:** AWS, Docker, docker-compose, Cloudflare Tunnel
- **Monitoring:** Grafana, Firebase Cloud Messaging (FCM), LogFlare-CAU
- **CI/CD:** GitHub Actions 기반 테스트 및 자동화 배포 파이프라인

---

## 📈 Service Performance
지속적인 유지보수와 최적화를 통해 실서비스의 가치를 증명하고 있습니다.

- **1년 이상의 무중단 운영:** 안정적인 비동기 처리 로직을 통해 다수 서버의 동시 요청을 처리합니다.
- **데이터 기반 의사결정:** 유저 피드백과 모니터링 로그를 분석하여 주단위 기능 업데이트를 수행합니다.
- **효율적인 인프라 운영:** 홈 서버와 클라우드를 결합한 하이브리드 환경에서 비용 효율적인 시스템을 운용합니다.

---

## 📫 Contact & Support
AITG 프로젝트는 개발 자체에 대한 깊은 흥미와 사용자 중심의 사고를 바탕으로 성장하고 있습니다.

- **GitHub:** [macqueen0987](https://github.com/macqueen0987)
- **Email:** [me@code0987.com](mailto:me@code0987.com)
- **Support Discord:** [Join AITG Support Server](https://discord.gg/FZuM8F5xBz)
