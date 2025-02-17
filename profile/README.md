# Balearn

## 📅 프로젝트 개요

💵 **기간**

2024.12.26 ~ 진행중

💵 **팀원 소개**

<table>
    <tr>
        <td><img src="https://avatars.githubusercontent.com/HMWG" width="180"></td>
        <td><img src="https://avatars.githubusercontent.com/JaeIn1" width="180"></td>
    </tr>
    <tr align=center>
        <td><a href='https://github.com/HMWG'>황민우</a></td>
        <td><a href='https://github.com/JaeIn1'>이재인</a></td>
    </tr>
</table>


**💡 기획 배경**

스터디 모임은 보통 정해진 날짜에 온라인 또는 오프라인으로 만나 진행하는 형태가 일반적입니다. 하지만, 기존 스터디 방식에는 효율적인 일정 관리와 지속적인 참여 유도를 위한 시스템이 부족합니다.

🔹 기존 스터디 모임의 한계<br/>
 * 일정 관리의 어려움 – 매일 정해진 일정이 있어도 잊어버리기 쉬움<br/>
 * 강제성 부족 – 자율적인 참여 방식이지만, 참여율이 점점 낮아지는 문제 발생<br/>
 * 비효율적인 자료 공유 – 카카오톡, 슬랙 등 여러 플랫폼을 통해 자료를 공유하면 찾기 번거로움<br/>

🚀 스터디 관리 서비스 기획
이러한 문제를 해결하기 위해, 스터디원들이 보다 체계적으로 학습하고 지속적으로 참여할 수 있도록 스터디 일정 관리 서비스를 개발했습니다.<br/>

✔ 주간 일정 & 오늘의 미션 – 캘린더를 활용해 스터디 일정을 등록하고, 한눈에 확인<br/>
✔ 미션 완료 시스템 – 오늘의 미션을 완료하면 점수가 반영되며, 이벤트성 요소를 통해 참여 유도<br/>
✔ 통합 자료 관리 – 한 곳에서 자료를 공유 및 관리하여 찾기 쉽고 활용도 증가<br/>

스터디를 더 체계적이고, 즐겁게!
이제, 스터디를 보다 효율적으로 운영하고, 참여율을 높이며, 학습 성과를 극대화할 수 있는 서비스를 경험해보세요!


💵 **공통 컴포넌트 주요 기능**
- 사이드 바
    -  각 페이지 라우팅 기능
    -  나의 모임 리스트 확인
    -  모임 생성하기
    -  모임 가입하기
 
- 헤더
    -  팀 프로필 정보
    -  로그아웃


💵 **페이지별 주요 기능**

-  소셜 로그인
    -  카카오 , 구글 로그인 기능

- 대시보드
    - 공지 확인
    - 스터디 목표 확인
    - 스터디 멤버 확인
    - 주간 일정 확인

-  캘린더
    -  일정 등록 , 수정 , 삭제 기능
    -  캘린더를 활용한 일정 시각화
    -  주간 , 월별 캘린더 확인 

-  채팅
    -  1:N 채팅 기능 제공

-  파일
    -  최근 열어본 파일 목록 확인
    -  drag & drop 파일 업로드 기능
    -  파일 리스트 확인
      
-  설정
    - 모임 수정
    - 회원 관리(회원 권한 수정 , 회원 탈퇴)
    - 초대 링크 공유
    - 공지 페이지(공지 CRUD)
- 리더보드
    - 1 ~ 3등 랭킹 확인
    - 모임 전체 랭킹 , 점수 확인
    - 오늘의 미션 확인 및 등록
       
 💵 **데이터 활용**  
 -  

## 💡서비스 소개

### Balearn

Balearn은, 스터디그룹 관리 서비스입니다.

> (사용자)  

1. 사용자는 모임을 먼저 생성합니다.
   - 모임 이미지 , 모임 명을 입력합니다.
2. 만들어진 모임을 대시보드에서 확인합니다.
3. 설정 페이지의 회원 관리에서 초대 코드를 생성한 뒤 공유합니다.
   - 초대 코드를 받은 인원은 사이드 바의 '모임 가입하기'를 눌러 코드를 입력하고 가입합니다.
4. 캘린더 페이지에서 스터디의 일정을 등록합니다.
5. 공유할 파일은 파일 페이지에서 업로드를 합니다.
6. 오늘 에정된 미션을 클리어하면 점수가 올라갑니다. 
   - 리더보드 페이지에서 미션을 클리어할 수 있습니다.
7. 팀원과 공유할 내용을 채팅 페이지에 올립니다.


### ⚙️ 기술 스택

### **프론트엔드**  

<p align="left">
  <img src="https://img.shields.io/badge/next.js-%2320232a.svg?style=for-the-badge&logo=next.js&logoColor=%2361DAFB" />
  <img src="https://img.shields.io/badge/typescript-3178C6.svg?style=for-the-badge&logo=typescript&logoColor=white" />
  <img src="https://img.shields.io/badge/tailwindcss-%06B6D4.svg?style=for-the-badge&logo=tailwindcss&logoColor=white" />
  <img src="https://img.shields.io/badge/zustand-%2320232a.svg?style=for-the-badge&logo=zustand&logoColor=white" />
  <img src="https://img.shields.io/badge/PWA-%235A0FC8.svg?style=for-the-badge&logo=pwa&logoColor=white" />
</p>

### **백엔드**  

<p align="left">
  <img src="https://img.shields.io/badge/spring--boot-%236DB33F.svg?style=for-the-badge&logo=springboot&logoColor=white" />
</p>

### **인프라**  

<p align="left">
  <img src="https://img.shields.io/badge/mysql-4479A1.svg?style=for-the-badge&logo=mysql&logoColor=white" />
  <img src="https://img.shields.io/badge/redis-%23DC382D.svg?style=for-the-badge&logo=redis&logoColor=white" />
  <img src="https://img.shields.io/badge/github%20actions-%232671E5.svg?style=for-the-badge&logo=githubactions&logoColor=white" />
  <img src="https://img.shields.io/badge/nginx-009639.svg?style=for-the-badge&logo=nginx&logoColor=white" />
  <img src="https://img.shields.io/badge/AWS-%23FF9900.svg?style=for-the-badge&logo=amazon-aws&logoColor=white" />
</p>

### **협업툴**  

<p align="left">
  <img src="https://img.shields.io/badge/Notion-%23000000.svg?style=for-the-badge&logo=notion&logoColor=white" />
  <img src="https://img.shields.io/badge/Slack-4A154B?style=for-the-badge&logo=slack&logoColor=white" />
  <img src="https://img.shields.io/badge/Discord-%235865F2.svg?style=for-the-badge&logo=discord&logoColor=white" />
  <img src="https://img.shields.io/badge/figma-%23F24E1E.svg?style=for-the-badge&logo=figma&logoColor=white" />
</p>


## 📂ERD 및 시스템 아키텍처  

**ERD**  

**MSA 아키텍처**  

**인프라 아키텍처**  


## 🖼 주요 화면

## 💵 로그인 페이지
<img width="600" alt="로그인" src="https://github.com/user-attachments/assets/e6488db5-3092-4e25-8eff-09551e77aec3" />

## 💵 대시보드 페이지
<img width="600" alt="대시보드" src="https://github.com/user-attachments/assets/84565815-b046-4708-9a91-e6b9eda010ba" />


## 💵 탤린더 페이지
<img width="600" alt="캘린더" src="https://github.com/user-attachments/assets/d613a5d0-5735-459a-9974-3afa3e8cb835" />
<img width="600" alt="캘린더-일정추가" src="https://github.com/user-attachments/assets/d5d84597-5a67-4c29-ada6-571bffa2d76e" />


## 💵 채팅 페이지
<img width="600" alt="스크린샷 2025-02-17 오후 3 48 18" src="https://github.com/user-attachments/assets/3f46bc14-6740-4c33-89d2-a8d2640fc8f2" />



## 💵 파일 페이지
<img width="600" alt="파일" src="https://github.com/user-attachments/assets/a16330db-6275-43e3-8a8e-077814d4b400" />




## 💵 설정 페이지
<img width="400" alt="설정" src="https://github.com/user-attachments/assets/29d87912-6803-442f-a4d7-243544ca1d2b" />
<img width="400" alt="설정-회원관리" src="https://github.com/user-attachments/assets/5f02aafe-40c5-4551-aea5-937b7d50de88" />
<img width="400" alt="모임수정" src="https://github.com/user-attachments/assets/b240a76e-2732-49a2-b6fd-540a805ae2e4" />
<img width="400" alt="공지" src="https://github.com/user-attachments/assets/cd7c61ee-8be8-4642-a4a6-6d224377b9c3" />


## 💵 리더보드 페이지
<img width="600" alt="리더보드" src="https://github.com/user-attachments/assets/6332608d-24ea-4d18-9b58-e5f20aabee31" />



## 컨벤션

### 📍 Git 컨벤션

```
<컨벤션> : <설명>
```

| 컨벤션   | 설명                                                                                                                            |
| -------- | ------------------------------------------------------------------------------------------------------------------------------- |
| feat     | 새로운 기능과 관련된 것을 의미한다.                                                                                             |
| fix      | 오류와 같은 것을 수정했을 때 사용한다.                                                                                          |
| docs     | 문서와 관련하여 수정한 부분이 있을 때 사용한다.                                                                                 |
| style    | 코드의 변화와 관련없는 포맷이나 세미콜론을 놓친 것과 같은 부분들을 의미한다.                                                    |
| refactor | 코드의 리팩토링을 의미한다.                                                                                                     |
| test     | test를 추가하거나 수정했을 때를 의미한다.                                                                                       |
| chore    | build와 관련된 부분, 패키지 매니저 설정 등 여러가지 production code와 무관한 부분 들을 의미한다. 말 그대로 자질구레한 일들이다. |
| add      | 이미지 등의 정적 자원 추가를 의미한다.                                                                                          |
| init     | 초기 설정 세팅을 의미한다.                                                                                                      |
| rename   | 파일 혹은 폴더 명을 수정하거나 옮기는 작업을 의미한다.                                                                          |
