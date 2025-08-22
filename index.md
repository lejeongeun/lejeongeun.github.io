---
layout: home
author_profile: true
title: "👩🏻‍💻 정은의 포트폴리오"
---

## 👋 About Me
- 이름: **이정은**  
- 생년월일: 2002.05.13  
- 연락처: 010-7370-3090  
- 이메일: [log4jeong@gmail.com](mailto:log4jeong@gmail.com)  
- GitHub: [github.com/lejeongeun](https://github.com/lejeongeun)  
- 학력: **컴퓨터소프트웨어학과 졸업**  
- 자격증: 📚 정보처리기사, SQLD 취득

---

## 🧩 Project 1. **여기보개 (HereDoggy) — 체험 기반 유기동물 입양 플랫폼**
- 기간: **2025.05 ~ 2025.07 (고도화 진행중)**  
- 역할: **팀 리더 · PM** (프론트 2명, 백엔드 2명)  
- 기술 스택:  
  - **Frontend**: Flutter, React  
  - **Backend**: Java 17, Spring Boot, Spring Security, JPA, Redis, JWT  
  - **Database**: PostgreSQL  
  - **Others**: Toss Payments API, Postman, Notion, Figma  

**📌 주요 기능**
- 산책 예약, 입양 신청, 후원 결제, 커뮤니티, 추천 시스템 제공  
- 산책 체험 → 입양까지 연결하는 통합 플랫폼  

**📊 성과**
1. **설계 & 문서화 100% 진행**  
   API 명세서, ERD, 기능 정의서 완성  
2. **성능 개선**  
   - 문제: 보호소·동물 데이터 조회 시 **3초 이상 지연 (N+1, 병목 현상)**  
   - 해결: JMeter 부하 테스트 → 병목 구간 분석 → DB 인덱싱, 쿼리 최적화, Redis 캐시  
   - 결과: **3s → 0.3s (90% 개선)**, **TPS 210/sec → 987/sec (4.6배 향상)**  
3. **추천 시스템**  
   - Rule-Based 알고리즘 + Top-N 랭킹 쿼리  
   - 설문 기반 추천 품종 클릭률 약 **35% 증가**  
4. **팀 리딩 & 협업 개선**  
   - Discord·Notion·Jira 기반 문서 협업 체계 구축  
   - 일정 지연 0건, 요구사항 반영률 100%  
5. **백엔드 구현**  
   예약 시스템, 입양 신청, 후원 API 등 **주요 핵심 기능 전반 구현**  

**🔗 링크**
- GitHub 바로가기: [HereDoggy Repo](https://github.com/lejeongeun/HereDoggy)  
- 기획/설계 PPT: [여기보개 PDF](https://www.canva.com/design/DAGqmb-TDII/GZqwAjIzQFgCmIp36RH_Pg/view?utm_content=DAGqmb-TDII&utm_campaign=designshare&utm_medium=link2&utm_source=uniquelinks&utlId=hd7f41eaf50)
- 시연 영상: [영상1](https://youtube.com/shorts/c8ACWo5Klcc), [영상2](https://youtube.com/shorts/4gfNtyfD0WI)  

---

## 🧩 Project 2. **WHERE GO — 나의 맞춤 여행 계획 & 커뮤니티 플랫폼**
- 기간: **2025.05 ~ 2025.06**  
- 역할: **팀 리더 · PM** (프론트 3명, 백엔드 2명)  
- 기술 스택:  
  - **Frontend**: React  
  - **Backend**: Java 17, Spring Boot, Spring Security, JPA, Redis, JWT  
  - **Database**: MySQL  
  - **Others**: Google Maps API, Place API, Postman, Notion, Figma  

**📌 주요 기능**
- 여행지 등록 → 일정 계획, 근처 맛집/환전/날씨/커뮤니티 통합 제공  

**📊 성과**
1. **서비스 구조 & DB 설계 고도화**  
   Google API 연동 → 검색 경험 최적화 (위치·평점 기준 정렬 정확도 향상)  
2. **게시판 성능 개선**  
   - 문제: 다중 연관관계로 인한 N+1, 데이터 조회 속도 저하  
   - 해결: 페이징, Redis 캐싱, 쿼리 최적화  
   - 결과: 부하 테스트 100% 성공 응답  
3. **실시간 알림 체계 구축**  
   WebSocket 기반 댓글/좋아요 알림 시스템  
4. **API 안정성·확장성 강화**  
   체크리스트, 장소 저장, 커뮤니티 CRUD + 예외 처리 강화  
5. **협업 환경 개선**  
   - Figma로 UI/UX 흐름도  
   - Notion·Discord 기반 문서 협업 → 일정 지연 없이 진행  

**🔗 링크**
- GitHub 바로가기: [WhereGo Repo](https://github.com/lejeongeun/whereGo)  
- 기획/설계 PPT: WHERE GO PDF (https://www.canva.com/design/DAGmRQXuwpU/RC_3bGf77Wx_qZzxfNNu2A/view?utm_content=DAGmRQXuwpU&utm_campaign=designshare&utm_medium=link2&utm_source=uniquelinks&utlId=hc0b10e9069) 
- 시연 영상: [시연영상](https://youtu.be/RLhTnzDKkt0)  

---

## 🏆 Skills
- **Backend**: Java, Spring Boot, Spring Security, JPA, Redis, JWT  
- **Database**: PostgreSQL, MySQL  
- **Frontend**: React, Flutter  
- **Infra & Tools**: Docker, AWS EC2, JMeter, Postman  
- **Collaboration**: Git Flow, Jira, Notion, Discord, Figma  

---

<div class="notice--success">
📌 <strong>요약:</strong> 성능을 수치로 개선하는 것(3s → 0.3s, 4.6배 TPS 향상), 
추천 시스템과 실시간 알림 같은 확장 기능 설계, 
그리고 팀 리딩 및 문서 기반 협업까지 경험했습니다.  
</div>