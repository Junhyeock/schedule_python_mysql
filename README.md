# 📅 Schedule Manager (Python + MySQL)

간단한 **CLI 기반 일정 관리 프로그램**입니다.  
`Python (pymysql)`을 이용해 **MySQL 데이터베이스**에 일정 추가, 조회, 완료 처리를 할 수 있습니다.  

<p align="center">
  <img src="https://img.shields.io/badge/python-3.9+-blue?logo=python">
  <img src="https://img.shields.io/badge/MySQL-8.0-orange?logo=mysql">
  <img src="https://img.shields.io/badge/pymysql-Installed-green">
  <img src="https://img.shields.io/badge/License-MIT-lightgrey">
</p>

---

## 🚀 기능

✅ **일정 추가** → 제목, 설명, 시작/종료 시간을 입력받아 DB에 저장  
✅ **일정 조회** → 등록된 모든 일정을 불러와 상태(완료/미완료)와 함께 출력  
✅ **일정 완료 처리** → 선택한 일정의 상태를 `완료`로 업데이트  
✅ **메뉴 기반 실행** → CLI 메뉴로 간단히 조작 가능  

---

## 🛠️ 설치 및 실행 방법

### 1. 환경 준비
- Python **3.9 이상**
- MySQL 서버 (**localhost:3307**, DB 이름: `schedule_db`)

### 2. 필수 라이브러리 설치
```bash
pip install pymysql pywin32
