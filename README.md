# 🚗 IsItEmpty-BE: 서울시 불법 주정차 문제 해결을 위한 실시간 주차 정보 제공 서비스
<br/>

> 💻 개발 기간 | 2025.03.01 ~ 2024.05.12

<p align="center">
  <img width="822" height="462" alt="main" 
       src="https://github.com/user-attachments/assets/b21e26e7-642b-436d-8063-3b836e5b2d9b" />
</p>

---
<br/>

## 💎 서비스 소개

> **주차 공간 찾느라 낭비되는 시간, 이제 그만!**
> 
**IsItEmpty**는 서울 시내 주차 공간 부족과 불법 주정차로 인한 사회적 비용을 줄이기 위해 탄생했습니다. 운전자에게 **실시간 주차장 정보, 주차 단속 카메라 위치, 인근 공용 화장실 정보**를 제공하여 보다 편리하고 스마트한 주차 경험을 제공하는 것을 목표로 합니다.

<br/>

## ✨ 주요 기능

- **🅿️ 실시간 주차 정보:** 서울시 공영 주차장의 실시간 빈자리, 요금, 운영 시간 등 상세 정보 제공
- **🗺️ 위치 기반 검색:** 내 주변 가장 가까운 주차장 및 편의시설 검색
- **📸 주차 단속 알림:** 주차 단속 카메라 위치 정보를 제공하여 불법 주정차 예방
- **🚽 공용 화장실 안내:** 주차장 및 주변 지역의 공용 화장실 위치 정보 제공
- **⭐ 개인화 기능:** 자주 이용하는 주차장을 '즐겨찾기'로 등록하고 관리
- **✍️ 리뷰 및 평점:** 다른 사용자와 주차장 이용 경험을 공유하고 평가

<br/>

## 👨‍💻 팀원 소개

<br/>

<table align="center">
  <tr>
    <td align="center" width="20%">
      <img width="460" height="460" alt="Image" src="https://github.com/user-attachments/assets/057399e3-32c3-43b1-8104-c9d1ee0e694e" /><br/>
      <b>정원준</b><br/>
      <code>PM, Backend Developer</code><br/>
      <a href="https://github.com/dietken1">GitHub</a>
    </td>
    <td align="center" width="20%">
      <img width="460" height="460" alt="member2" src="https://github.com/user-attachments/assets/f409fcba-aa3d-4bcc-80f9-00059550167e" /><br/>
      <b>김현진</b><br/>
      <code>Backend Developer</code><br/>
      <a href="https://github.com/blueoxygens">GitHub</a>
    </td>
    <td align="center" width="20%">
      <img width="460" height="460" alt="member3" src="https://github.com/user-attachments/assets/4fa3878a-e867-4c39-bf90-25f2b1c33a8a" /><br/>
      <b>김태린</b><br/>
      <code>Backend Developer</code><br/>
      <a href="https://github.com/ttaerrin">GitHub</a>
    </td>
    <td align="center" width="20%">
      <img width="460" height="460" alt="member3" src="https://github.com/user-attachments/assets/cdff07bc-10ae-481e-baaa-ac2a32a1000a" /><br/>
      <b>박태희</b><br/>
      <code>Frontend Developer, Designer</code><br/>
      <a href="https://github.com/ansrudgh">GitHub</a>
    </td>
    <td align="center" width="20%">
      <img width="460" height="460" alt="member3" src="https://github.com/user-attachments/assets/4c7033ad-4611-4ffb-8639-980b08df62e9" /><br/>
      <b>임유지</b><br/>
      <code>Frontend Developer, Designer</code><br/>
      <a href="https://github.com/lim-yuji">GitHub</a>
    </td>
  </tr>
</table>
<br/>

## ⚙️ 기술 스택
| 📂 Category | 🛠️ Tech | 📝 Description |
|:---:|:---:|:---|
| **`Backend`** | <img src="https://img.shields.io/badge/Java-17-ED8B00?style=flat-square&logo=openjdk&logoColor=white"/> <img src="https://img.shields.io/badge/Spring_Boot-3.4-6DB33F?style=flat-square&logo=spring-boot&logoColor=white"/> <img src="https://img.shields.io/badge/Gradle-02303A?style=flat-square&logo=gradle&logoColor=white"/> | 핵심 비즈니스 로직 및 API 서버 구현 |
| **`Database`** | <img src="https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white"/> <img src="https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white"/> | 영속 데이터 저장 및 실시간 데이터 캐싱 |
| **`Authentication`** | <img src="https://img.shields.io/badge/Spring_Security-6DB33F?style=flat-square&logo=spring-security&logoColor=white"/> <img src="https://img.shields.io/badge/OAuth2.0-2C5BB4?style=flat-square"/> <img src="https://img.shields.io/badge/JWT-000000?style=flat-square&logo=json-web-tokens&logoColor=white"/> | 소셜 로그인 및 토큰 기반의 안전한 인증/인가 |
| **`DevOps`** | <img src="https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white"/> <img src="https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=github-actions&logoColor=white"/> | 컨테이너화 및 CI/CD 파이프라인 구축 |

<br/>

## 🌳 백엔드 패키지 구조
```
src/main/java/com/isitempty
├── IsitemptyApplication.java
├── backend
│   ├── camera         # 📸 주차 단속 카메라
│   ├── favorite       # ⭐ 즐겨찾기
│   ├── oauthlogin     # 🔐 소셜 로그인 및 인증
│   ├── parkinglot     # 🅿️ 주차장
│   ├── question       # ❓ 문의사항
│   ├── realtimeinfo   # ⚡ 실시간 정보
│   ├── review         # ✍️ 리뷰
│   ├── toilet         # 🚽 공용 화장실
│   └── utils          # 🛠️ 유틸리티
└── config             # ⚙️ 프로젝트 전역 설정 (Redis, Security 등)
```
