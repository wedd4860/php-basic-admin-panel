# PHP Basic Admin Panel

## 📋 프로젝트 개요
`php-basic-admin-panel`은 PHP 5.5 환경에서 제작된 관리자 패널 프로젝트입니다.  
초기 PHP 학습을 목적으로, **MySQL > MySQLi > PDO** 연결 방식을 학습하며 데이터베이스와의 효율적인 통신을 구현했습니다.  
템플릿 기반 뷰 처리와 프론트엔드/백엔드 분리를 시도하며, 유지보수성을 고려한 설계를 실습했습니다.

---

## ⚙️ 기술 스택 및 개발 환경
- **언어**: PHP 5.5  
- **데이터베이스**: MySQL  
- **웹 서버**: Apache  
- **운영 체제**: Linux  

---

## 🛠 주요 기능
1. **데이터베이스 연결 방식 전환**  
   - MySQL에서 MySQLi, PDO로 전환하며 보안과 효율성 개선.  

2. **템플릿 기반 뷰 처리**  
   - 백엔드에서 데이터를 가공하여 프론트엔드 템플릿으로 전달.  
   - MVC는 아니지만 프론트엔드와 백엔드 역할 분리 시도.  

3. **로그 시스템 구축**  
   - `/logs` 디렉토리를 통해 에러 로그 기록 및 디버깅 가능.  

---

## 📂 주요 폴더 구조
```plaintext
/project-root
├── /action           # (back-end) db의 직접적인 처리를 담당하는 디렉토리
├── /bower_components # (front-end) bower를 통해 설치된 자바스크립트 라이브러리들
├── /dist             # (front-end) front의 css, js, img 디렉토리
├── /download         # (back-end) 엑셀 다운로드에 필요한 디렉토리
├── /include          # (back-end) php 설정 및 utils, class 정의
├── /install          # (back-end) db관련 정보를 볼 수 있는 디렉토리
├── /logs             # (back-end) front의 에러 내용을 텍스트 파일로 저장하는 디렉토리
├── /plugins          # (front-end) front의 공통 js 디렉토리
├── /templates        # (front-end) templates를 사용하여 view 처리
├── index.php         # 메인 엔트리 포인트
└── README.md         # 프로젝트 설명
