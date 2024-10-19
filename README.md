# CollaTime

###  프로젝트 소개 및 개요
#### CollaTime(Collaboration Time) : 협업 스케줄러

대학생 혹은 협업에 익숙하지 않은 사용자들을 주 타겟층으로 한 협업 스케쥴러 프로젝트입니다. <br>
현재의 협업툴들은 인터페이스와 사용법들이 전문가들에게 최적화된 기능들을 제공하고 있다. <br>
그렇기에 협업에 익숙하지 않은 분(이하 초보자)들 혹은 학생들이 접근하기에는 다소 어려움이 있을 것이라는 생각에서 시작하게 되었고 초보자나 학생들이 편하게 쓸 수 있는 협업 스케줄러를 만들자는 취지로 이 프로젝트를 기획했다. <br>
코로나 팬데믹의 여파로 인해 협업툴을 쓰는 회사들이 많아졌고 현재 많은 기업들에 있어 협업툴은 선택이 아니라 필수가 되어가고 있다. <br>
하지만 취업을 준히바는 초보자 혹은 학생들에게 있어서 기존 시장에 출시되어 있는 협업툴들을 처음부터 사용하기에는 인터페이스와 사용법들에 대한 진입장벽이 높다. <br>
이를 위해 본 CollaTime은 가시성이 좋은 인터페이스와 간편한 사용법을 제공하여 초보자 혹은 학생들에게 협업에 대한 경험을 제공하는 것이 목표이다. <br>

-----------------------------------------------

### 개발 기간

2024년 10월 16일 ~ 2024년 10월 (미정) <br>

-----------------------------------------------

### 팀원 소개

| PM<br>(Project Manager) | CM<br>(Configuration Manager) | DB<br>(Database Manager) | DB<br>(Database Manager) |
| :------: | :------: | :------: | :------: |
| [![HS](https://github.com/user-attachments/assets/ffa4bca8-78d9-45e9-90a4-48fab251ffcf)](https://github.com/Passbob) | [![JH](https://github.com/user-attachments/assets/a19bb3f7-1878-41d6-9559-0225c43df88c)](https://github.com/JUHYE0925) | [![SW](https://github.com/user-attachments/assets/6aeba65b-7681-48ef-97b7-d1c905e0cc04)](https://github.com/suwanpp) | [![HE](https://github.com/user-attachments/assets/dd9d01b0-aefa-409b-8dd2-db6197aeade2)](https://github.com/gkdsm) 
| 팀장 : 조형석 | 팀원 : 김주혜 | 팀원 : 박수완 | 팀원 : 이하은 |

-----------------------------------------------

### 프로젝트 주요 기능

#### <회원관리>

1. 로그인
   - 아이디와 비밀번호를 통해서 로그인 가능하며 로그인 시 메인 화면으로 들어갈 수 있다. <br>
   - 만약 아이디와 비밀번호가 맞지 않는다면 실패하게 된다. <br>
   - 로그인 화면에서 회원가입 창에 들어갈 수 있도록 만들어야한다. <br>

2. 보안
   - !!!!!!! 추후 추가할 예정!!!!!!! <br>

3. 회원가입
   - 이름, 닉네임, 이메일 주소, 아이디, 비밀번호를 필수로 입력한다. <br>
   - 비밀번호는 영문자, 숫자, 특수 문자 모두 사용해 최소 8글자 이상으로 만들어야 한다. <br>
   - 아이디와 비밀번호는 기존 DB정보와 비교해 중복 여부를 확인한다. <br>

4. 회원정보 관리
   - 새로운 회원의 정보를 DB에 저장한다. <br>
   - 기존 정보가 있는 회원들은 정보를 수정할 수 있다. <br>
   - 회원은 회원 탈퇴를 할 수 있으며 회원 탈퇴 시에 DB에 있는 정보를 즉시 삭제한다. <br>

#### <프로젝트 관리>

1. 프로젝트 생성
   - 새 프로젝트를 생성할 수 있으며 프로젝트 생성 시 프로젝트 설정 창으로 넘어간다. <br>
   - 새 프로젝트 생성 시 프로젝트명, 개요, 목표 및 목적, 시작 날짜, 종료 날짜를 필수로 지정한다. <br>
   - 프로젝트 성격에 따라 카테고리로 나눠 관리할 수 있도록 한다. <br>
   - 프로젝트 참여자에 대한 글 작성, 조회, 접근 권한을 설정한다 <br>
   - 프로젝트 데이터 저장 유효 기간에 대해 고지한다. <br>
   - 필수 입력사항을 기입하지 않거나, 데이터 저장 유효기간에 비동의 시 새 프로젝트 생성은 실패한다. <br>
   - 프로젝트 생성 완료 시 메인 창으로 넘어가며 방금 생성한 프로젝트도 메인 창에 추가한다. <br>
   - 프로젝트 정보를 DB에 저장한다. <br>

2. 팀원 관리
   - 프로젝트 참여 인원을 이메일을 통해 초대하여 추가한다. <br>
   - 프로젝트 참여 인원을 삭제하며 삭제 시 프로젝트 참여 시 부여된 권한 및 정보는 제거된다. <br>

3. 프로젝트 수정
   - 프로젝트 정보를 수정할 수 있다. <br>

4. 프로젝트 삭제
   - 프로젝트 정보를 DB에서 삭제한다. <br>
   - 삭제한 프로젝트는 메인 창에서 제거한다. <br>

5. 권한 위임
   - 프로젝트 관리 권한을 위임한다. <br>
- 

#### <스케줄러>

#### <관리자 페이지>

-----------------------------------------------

https://www.freecodecamp.org/korean/news/gisheobeu-peurojegteue-rideumi-paileul-jal-jagseonghaneun-bangbeob/
