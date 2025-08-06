# Loop – 해외 학교 커뮤니티 플랫폼

> 해외 학교 학생들을 위한 커뮤니티 플랫폼으로, 정보 공유와 소통을 지원합니다.

## 📌 프로젝트 개요
Loop는 해외 학교 학생들이 자유롭게 소통하고 정보를 공유할 수 있는 온라인 커뮤니티 플랫폼입니다.  
게시글 작성, 댓글/대댓글, 좋아요, 인기글 랭킹, 이미지 업로드 기능 등을 제공합니다.

## 🛠 기술 스택
### Frontend
- **React (Vite)**
- **Tailwind CSS**
- **Axios**
- **React Router**

### Backend
- **Spring Boot (Java)**
- **Spring Security + JWT**
- **JPA (Hibernate)**
- **MySQL (AWS RDS)**

### Infra & DevOps
- **AWS EC2 (Docker)**
- **AWS S3 (이미지 업로드)**
- **Nginx**
- **Vercel (Frontend Hosting)**
- **GitHub Actions (CI/CD)**

---

## ✨ 주요 기능
- **회원가입 / 로그인** (JWT 인증)
- **게시글 작성 / 수정 / 삭제**
- **이미지 업로드** (AWS S3)
- **댓글 / 대댓글 작성**
- **좋아요 & 인기글 랭킹**
- **카테고리별 게시글 조회**
- **광고 페이지**

---

## 📂 프로젝트 구조
loop/
├─ backend/ # Spring Boot API
│ ├─ domain/ # 엔티티, 서비스, 컨트롤러
│ └─ global/ # 보안, 예외 처리 등
├─ frontend/ # React + Vite
│ ├─ src/components
│ ├─ src/pages
│ └─ src/api
└─ docker/ # Dockerfile & 배포 스크립트

---

## 🚀 배포
- **Frontend**: [Vercel](https://loop.o-r.kr)
- **Backend**: AWS EC2 (Docker + Nginx)
- **이미지 저장소**: AWS S3

---

## 💡 배운 점 & 트러블슈팅
- **JWT 기반 인증/인가** 구현 및 토큰 재발급 로직 설계
- **AWS EC2 + Docker + Nginx**를 활용한 안정적인 배포
- **CORS 이슈 해결** 및 보안 강화
- **이미지 업로드 최적화** 및 누락 문제 해결
- **댓글/대댓글 계층 구조 설계** 및 성능 최적화

---

## 📌 향후 개선점
- 실시간 알림 기능 (WebSocket)
- 다국어 지원
- 반응형 디자인 개선

---

## 👥 팀원
- **Backend & Infra**:  배석현
- **Frontend**:  배석현
- **기획 & 디자인**:  배석현

---

