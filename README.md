# 🐾 Dogs (도그스)
유기견 분양+커뮤니티, 도그스

# 📖 프로젝트 개요
유기견 분양과 커뮤니티의 결합, 그리고 상품까지 한 번에!

.


.


.

주제 선정 계기
유기당한 강아지들이 많아지고 있음
배운 것들을 활용하기엔 분양 사이트라는 테마 안에 아이템이 많다고 판단


기대 효과
분양 사이트를 통해 유기견 분양 및 강아지에 대한 관심을 증대시킬 수 있음
강아지들에 대해 사회적 시선의 바람직한 방향을 제시해 줄 수 있음


# 📆 개발 기간
23.11.06 ~ 23.12.08


# ⚙️ 개발 환경 🛠️
Java 11


IDE: STS3


DBMS: Oracle


빌드 도구: Maven


ORM: MyBatis


형상 관리: Github, SourceTree(Git)


# 👩‍💻 팀원 구성 및 역할 👨‍💻

공통
- DB 설계
- 데이터 수집

유승민
- DB 설계 및 구성
- 커뮤니티, 예약, 상세 페이지 제작


박현우
- DB 설계
- 매인, 관리자, 로그인, 회원가입, 마이 페이지 제작


정유림
- 소개, 상세 정보, 영상보기 페이지 제작
- 설문 테스트 제작
- 로고 및 캐릭터 디자인


최지우
- 신규 분양, 상세 리뷰, 분양 후기 페이지 제작
- 광고 배너 이미지 제작 (Adobe Photoshop 사용)


# 📌 주요 기능


메인 페이지
![1](https://github.com/user-attachments/assets/9a3767af-7973-4d14-a65d-90de2b76ac7b)
![2](https://github.com/user-attachments/assets/702d5139-f76b-4ba9-b46d-5ed53311fd61)
![3](https://github.com/user-attachments/assets/68c1b919-4ef0-4e32-b93c-4a8970460060)

---------

나에게 맞는 강아지 찾기 (간단 테스트)
![4](https://github.com/user-attachments/assets/8a6113c8-2ef4-4cd3-a25e-1ce3aa32dc62)
![20](https://github.com/user-attachments/assets/b5e41435-bf2d-4de6-9e94-00325d3fa05c)

---------

회원가입 페이지
![5](https://github.com/user-attachments/assets/cdb59aba-d99a-4945-ab60-054a937cb386)

mailx, context support 라이브러리를 통해 Naver SMTP 서버와 연결하여 이메일 인증 가능
![6](https://github.com/user-attachments/assets/80cdaf5f-27a9-49b8-9bc3-51666e98c603)

Daum의 우편번호 Api를 통해 주소 등록 가능
![8](https://github.com/user-attachments/assets/34d22ffe-1eef-475d-805a-dab8a81e78ef)

---------

로그인 후 메인 페이지
![10](https://github.com/user-attachments/assets/0b1ce629-784e-4f56-be52-31af754fc719)

---------

신규 분양 -> 강아지 자세히 보기 페이지
![19](https://github.com/user-attachments/assets/1811b972-2b70-49a4-b117-8b9e25fd1e90)

---------

방문 예약 페이지

jQuery 플러그인(DateTimePicker) + quartz scheduler을 통해 날짜 및 시간 입력

"CoolSMS"를 통해 Api key를 발급 받아 SMS 인증 기능 도입

![12](https://github.com/user-attachments/assets/1981c23c-b7c3-45c5-bfc2-a3e9da231ddc)
![11](https://github.com/user-attachments/assets/20d40c2e-e70b-4971-a931-2844c0219858)

---------

분양 후기 페이지
![13](https://github.com/user-attachments/assets/a3ba3dcd-a681-4e5a-9dd0-c5eb2220c274)
![14](https://github.com/user-attachments/assets/4a7a526b-280c-4c72-be31-e82d4118feba)
![15](https://github.com/user-attachments/assets/c23fca10-c21e-4173-b9ec-8b60b178abb6)

---------

커뮤니티 -> 글쓰기 페이지
![16](https://github.com/user-attachments/assets/a4060668-244a-4ebf-b21a-aab9ca539243)


커뮤니티 -> 작성된 글 페이지
![17](https://github.com/user-attachments/assets/29fdb75b-16c9-477b-a357-21a2f8434cf9)


커뮤니티 -> 작성된 글에 댓글 달기
![18](https://github.com/user-attachments/assets/6a9a11a5-39e2-4e05-a49e-84d77c452143)

---------

관리자 로그인 시 메인 페이지
![21](https://github.com/user-attachments/assets/59073190-6a9c-4b3d-a13c-94467ea9a10e)


관리자 기능 페이지
![22](https://github.com/user-attachments/assets/21bc7ad3-4a5e-4208-a636-8084332c0844)


# ⛓ DB 다이어그램

![dogsDB1](https://github.com/user-attachments/assets/e0e11783-01fd-4db8-b35b-0e2d4b083a1c)
![dogsDB2](https://github.com/user-attachments/assets/c7498cfc-1514-44ed-a482-95af4a3480b3)
