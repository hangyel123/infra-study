# AWS Practice Project

AWS 인프라 및 배포 실습을 위한 개인 학습 프로젝트입니다.  
실무 수준의 Git 브랜치 전략과 PR/MR 규칙을 적용하여 진행합니다.

---

## 📌 목표
- AWS 핵심 서비스 실습 (EC2, RDS, S3 등)
- Spring Boot 애플리케이션 배포
- GitHub 기반 협업 프로세스 연습
- PR 리뷰 · 승인 · 병합 흐름 체득

---

## 🧱 기술 스택
- Java 17
- Gradle
- AWS EC2 / RDS
- GitHub Actions (추후)
- IntelliJ IDEA

---

## 🌳 Git 브랜치 전략
```text
main        : 배포 기준
develop     : 개발 통합
feature/*   : 기능 개발
fix/*       : 버그 수정
docs/*      : 문서
