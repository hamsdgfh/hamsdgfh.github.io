---
title: "GitHub Profile"
excerpt: "GitHub 프로필 README와 소개를 커스터마이징한 프로젝트입니다."
collection: portfolio
---

## 🧑‍💻 GitHub Profile & README

[![GitHub Repo](https://img.shields.io/badge/GitHub-Repository-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/hamsdgfh/hamsdgfh)

---

🚀 **프로젝트 개요**  
GitHub의 프로필 전용 저장소(`hamsdgfh/hamsdgfh`)를 활용해, **개인 소개와 주요 프로젝트·학습 현황을 한눈에 볼 수 있는 README 페이지**를 구성한 프로젝트입니다.  
정적인 자기소개 문서가 아니라, **뱃지·통계·애니메이션·스크린샷** 등을 활용해 시각적으로 정보가 잘 전달되도록 설계했습니다.  

---

🛠️ **사용 기술 및 환경**  
- **Languages & Markup:** Markdown, HTML(간단한 정렬/레이아웃용)  
- **Badges & UI:** Shields.io, 캡슐형 헤더/푸터 배너  
- **CI/CD & Automation:** GitHub Actions (Snake Game Contributions 생성)  
- **Stats & Widgets:** GitHub Readme Stats, 방문자 카운터 등  
- **Assets:** 프로젝트 데모 스크린샷(`demo_home.png`, `demo_cards.png`)  

---

✨ **주요 구현 내용**  
- **개인 소개 섹션 구성**  
  - About Me, Highlights, Education, Roadmap 등으로 정보 구조화  
  - 학습 중인 내용, 관심 분야, 강점 등을 리스트 형태로 표현  
- **프로젝트 소개 블록**  
  - `Information Website`, `C Study Repository` 등 주요 프로젝트를 카드 형태로 정리  
  - `<details>` 태그로 스크린샷(홈 화면, 카드 UI) 토글 표시  
- **GitHub 활동 시각화**  
  - GitHub Readme Stats를 활용해 커밋/언어 사용량 그래프 삽입  
  - 방문자 수, 활동 지표를 뱃지 형태로 표시  
- **Snake Contributions 애니메이션 자동 생성**  
  - `Platane/snk` GitHub Action을 사용해 contribution snake SVG 생성  
  - 매일 정해진 시간에 워크플로우가 실행되도록 cron 스케줄 설정  

---

🧩 **프로젝트 특징**  
- GitHub 프로필에 접속하는 것만으로 **자기소개 페이지 역할** 수행  
- 텍스트 위주 소개가 아니라, **이미지·뱃지·그래프를 활용한 시각적 포트폴리오**  
- 워크플로우를 통해 일부 콘텐츠(Snake 애니메이션)가 **자동으로 최신 상태 유지**  
- 추후 프로젝트가 늘어나도 README 내 섹션만 확장하면 되도록 **유지보수 용이하게 설계**  

---

📝 **배운 점**  
이 프로젝트를 통해 다음과 같은 점을 경험했습니다.

- GitHub 프로필 전용 저장소를 활용한 **개인 브랜딩 방법** 이해  
- Markdown과 HTML을 섞어 사용하는 **README 레이아웃 구성 요령**  
- Shields.io, Readme Stats 등 외부 서비스를 활용한 **시각적 정보 전달 방식**  
- GitHub Actions 워크플로우(snake 애니메이션 생성)를 설정하며  
  **CI/CD와 자동화 파이프라인의 기본 개념**을 익혔습니다.  
