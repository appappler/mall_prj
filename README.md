# 🛍️ Donutted - JSP 기반 온라인 쇼핑몰

<img width="705" height="1016" alt="image" src="https://github.com/user-attachments/assets/8da5be06-5f50-49b0-83ea-74a9b335d059" />


<br/>

## 📑 목차  
- [📝 프로젝트 소개](#project-intro)
- [🛠 기술 스택](#tech-stack)
- [💾 ERD](#erd)
- [✨ 주요 기능 소개](#main-features)
- [🎬 시연영상](#demo-video)
- [💁‍♂️ 팀원 소개](#team-members)


<br/>

<h2 id="project-intro">📝 프로젝트 소개</h2>
기존 오프라인/문서 기반 상품 판매 방식의 문제점을 해결하고자 개발한 통합 온라인 쇼핑몰 플랫폼입니다.
고객은 다양한 상품을 검색하고 구매할 수 있으며, 관리자는 상품 및 주문을 효율적으로 관리할 수 있습니다.
실시간 주문 처리, 결제 시스템, 리뷰 관리 등 실제 쇼핑몰의 핵심 기능들을 구현하여 완전한 전자상거래 경험을 제공합니다.

**Donutted**는 JSP와 Oracle을 기반으로 구축된 풀스택 전자상거래 플랫폼입니다. 8명의 개발팀이 6주간 협업하여 개발했으며, 사용자와 관리자를 위한 완전한 온라인 쇼핑 경험을 제공합니다.

- **개발 기간**: 2025.04.01 ~ 2025.05.14 (6주)
- **팀 구성**: 8명 
- **아키텍처**: Model1 패턴 기반 웹 애플리케이션

<br/>

<h2 id="tech-stack">🛠 기술 스택</h2>

### Backend
- **Language**: Java (JDK 11)
- **Framework**: JSP/Servlet
- **Database**: Oracle Database
- **Connection Pool**: DBCP
- **Server**: Apache Tomcat 9

### Frontend
- **Markup**: HTML5, CSS3
- **Template**: JSP, JSTL, EL
- **Scripting**: JavaScript, jQuery
- **Framework**: Bootstrap

### Development Environment
- **IDE**: Eclipse IDE
- **OS**: Windows 10
- **Version Control**: Git

<img src="https://img.shields.io/badge/java-007396?style=for-the-badge&logo=java&logoColor=white"> <img src="https://img.shields.io/badge/html5-E34F26?style=for-the-badge&logo=html5&logoColor=white"> <img src="https://img.shields.io/badge/css-1572B6?style=for-the-badge&logo=css3&logoColor=white"> <img src="https://img.shields.io/badge/javascript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black"> <img src="https://img.shields.io/badge/jquery-0769AD?style=for-the-badge&logo=jquery&logoColor=white"> <img src="https://img.shields.io/badge/bootstrap-7952B3?style=for-the-badge&logo=bootstrap&logoColor=white"> <img src="https://img.shields.io/badge/oracle-F80000?style=for-the-badge&logo=oracle&logoColor=white"> <img src="https://img.shields.io/badge/apache tomcat-F8DC75?style=for-the-badge&logo=apachetomcat&logoColor=white"> <img src="https://img.shields.io/badge/eclipse-2C2255?style=for-the-badge&logo=eclipseide&logoColor=white"> <img src="https://img.shields.io/badge/git-F05032?style=for-the-badge&logo=git&logoColor=white"> <img src="https://img.shields.io/badge/github-181717?style=for-the-badge&logo=github&logoColor=white">

<br/>

<h2 id="erd">💾 ERD</h2>

<img width="856" height="733" alt="4조_erd" src="https://github.com/user-attachments/assets/cec08d44-a2ec-480f-abf2-c2b7025dc6ca" />


<br/>

<h2 id="main-features">✨ 주요 기능 소개</h2>

### 👥 사용자 기능
- 🛒 상품 검색 및 상세 정보 확인
- 📦 장바구니 관리 및 주문 처리
- 💳 실시간 주문 상태 추적
- ⭐ 리뷰 시스템 (작성/수정/삭제)
- 👤 개인정보 관리 및 주문 이력
- 🔄 주문 취소 및 환불 요청

### 👨‍💼 관리자 기능
- 📊 실시간 대시보드 (매출, 주문, 배송 현황)
- 👤 회원 관리 (가입/탈퇴/정보 수정)
- 📦 주문 관리 (상태 변경, 배송 처리)
- 📝 리뷰 관리 및 모니터링
- 💰 환불 승인/거부 처리
- 📈 매출 분석 및 통계
- 💬 FAQ/1대1문의 관리
- 📢 공지사항/이벤트 관리

<br/>

<h2 id="demo-video">🎬 시연영상</h2>

[![Video Title](https://img.youtube.com/vi/18uK3ZxTMpc/0.jpg)](https://www.youtube.com/watch?v=18uK3ZxTMpc)

<br/>

<h2 id="team-members">💁‍♂️ 팀원 소개</h2>

- **김민진** [팀장]  
  - 프로젝트 전체 일정 관리 및 기능 연동 총괄  
  - 사용자 메인 화면 설계·구현 (헤더, 푸터, 메인 UI, 슬라이드 상·하단 구역)  
  - 로그인, 회원가입, 아이디/비밀번호 찾기 기능 개발  
  - 관리자 회원 관리(목록/검색/상태 처리) 기능 개발  
  - 최종 통합 테스트 및 시연 발표 진행  

- **김세형** [부팀장 / DBA]  
  - 개발 환경 및 디렉터리 구조 설계  
  - Oracle DB 설계 및 구축  
  - 사용자 주문·환불·리뷰·마이페이지 내정보 수정/탈퇴 기능 개발  
  - 관리자 주문·환불·회원·리뷰·대시보드 구현  

- **정성재**  
  - 사용자 공통 레이아웃, 상품 목록·상세, 리뷰 기능  
  - 관리자 상품 관리, 리뷰 관리

- **심규민**  
  - 사용자 찜하기·장바구니 기능 구현

- **박선은**  
  - 사용자 공지사항·이벤트 조회  
  - 관리자 공지사항·이벤트 관리  


- **최승재**  
  - 사용자 1:1 문의, FAQ 조회  
  - 관리자 1:1 문의·FAQ 관리
  - 
- **이장훈**  
  - 사용자 메인 화면 일부 및 주문 시스템 개발  
  - 관리자 주문 관리  

- **정제균**  
  - 사용자 브랜드 소개, 리뷰 기능  
  - 관리자 리뷰 관리  



<br/>

---

**© 2025 Donutted Project Team. 본 프로젝트는 교육 목적으로 개발되었습니다.**

> 🙋 README 작성: 김민진
