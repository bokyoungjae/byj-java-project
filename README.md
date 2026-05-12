# 🎮 Java RPG Game Project

> Java Swing 기반 턴제 RPG 게임 프로젝트

![Java](https://img.shields.io/badge/Java-17-orange)
![Swing](https://img.shields.io/badge/GUI-Swing-blue)
![IDE](https://img.shields.io/badge/IDE-Eclipse-purple)

---

## 📌 프로젝트 소개
플레이어가 다양한 직업과 스킬을 활용하여 몬스터와 전투하는
턴제 RPG 게임입니다.

Java OOP 설계와 Swing GUI 구현을 중심으로 제작했습니다.

---

## 🕹 주요 기능

### 캐릭터 시스템
- 전사 / 마법사 / 궁수 선택
- 체력, 마나, 공격력 관리

### 전투 시스템
- 일반 공격
- 스킬 사용
- 아이템 사용
- 몬스터 AI 공격

### 아이템 시스템
- 포션 사용
- 장비 관리

### GUI
- 캐릭터 상태창
- 스킬 버튼
- 전투 로그 출력

---

## 📷 실행 화면
<img width="380" height="267" alt="1" src="https://github.com/user-attachments/assets/9f841153-a4e9-4190-843c-8f6375e87922" />

### 메인 화면
<img width="837" height="619" alt="4" src="https://github.com/user-attachments/assets/b5ba228b-f68c-4e49-bfa4-b139d99be08e" />

### 전투 화면
<img width="840" height="630" alt="3" src="https://github.com/user-attachments/assets/efdc6f74-4fb9-47ba-b8fa-d5d4bd63dc6d" />
<img width="837" height="619" alt="5" src="https://github.com/user-attachments/assets/53a2b5f2-5af9-484e-b50c-96bc4df03608" />


---

## 🗂 프로젝트 구조
src
├─ gui
├─ model
├─ item
├─ interfaces
├─ exception


---

## ⚙ 기술 스택
- Java
- Swing
- OOP
- Eclipse

---

## 🔥 Trouble Shooting

### 1. GUI 이벤트 처리 문제
- ActionListener 이벤트 충돌 발생
- 버튼별 Action 분리로 해결

### 2. 캐릭터/몬스터 타겟 처리
- 잘못된 target 접근 예외 발생
- 예외 클래스 추가 후 처리

---

## 💡 느낀 점
처음에는 GUI 구조 설계와 클래스 분리가 어려웠지만,
MVC 느낌으로 역할을 나누며 코드 유지보수성을 개선했습니다.

특히 Java OOP 구조와 예외 처리에 대한 이해가 깊어졌습니다.
