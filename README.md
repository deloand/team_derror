
### **Travel with 소개**
---

Treavel with 는 **파편화된 해외 여행 정보를 한 사이트 내에서 모두 볼 수 있도록 하고 맞춤화된 방식으로 일정을 계획하고 경험할 수 있도록 제작한 웹사이트**입니다.


Treavel with 는 한 번의 조회로 다양한 여행지와 공연 정보를 제공하여 여행 계획을 단순화하고, 일정 관리를 용이하게 하며, AI 검색으로 개인화된 여행지 추천을 제공합니다. 또한, 여행 커뮤니티를 통해 정보 교환을 가능하게 하여, 사용자가 빠르고 쉽게 특별한 여행 경험을 만들 수 있도록 지원합니다.

### **팀원 소개**
---
|팀원|링크|역할|
|------|---|---|
|이종현|깃허브|버전 관리 및 DB 설계|
|||챗봇 도우미 구현|
|서현기|깃허브|홈, 항공, 숙박, 캘린더 페이지 구현|
|||API활용한 페이징 구현, 캘린더 CRUD 구현|
|임승빈|깃허브|로그인 및 회원가입|
|||회원페이지|
|장고운|깃허브|게시판(공지사항, 자유, 공유) CRUD 구현|
|||검색창, 목록필터, 페이징 구현|
|김종선|깃허브|이벤트 정보 조회, 페이징 구현|
|||이벤트 상세 정보 페이지, 일정 추가 구현|


### **기술 스텍**
---
![](https://velog.velcdn.com/images/goun3596/post/8cdfb2b8-8d06-40ac-9572-1398d33cf893/image.png)




### **개발 기간**
---
**2023.11.20 ~ 2023.12.27(총 5주)**

|주차 |구분 |활동|
|:----:|:----:|:----|
|1주차|사전기획   |  프로젝트 주제 선정 및 기획안 작성  | 
|2주차|데이터 수집   |  해외공연, 관광지 API 수집  |  
||   |  항공편, 숙박 API수집  |
|3주차|데이터 전처리   |  데이터 정제 및 정규화  |  
|4주차|모델링   |  기본  CSS 작성  |  
|5주차|서비스 구축   |  웹 서비스 시스템 설계| 
|||최적화, 오류 수정| 


### **시스템 설계**
---
![](https://velog.velcdn.com/images/goun3596/post/c2702687-ef69-4e7c-a707-f1573a1f524a/image.png)


시스템 설계는 스프링부트 프레임워크를 통한 MVC 패턴으로 작성되었습니다. 
컨트롤러는 세부적으로 비즈니스로직을 따라 작동하고 있습니다.
데이타베이스는 MySQL을 사용하였고 모델과 데이타베이스 Mapping을 위해 mybatis를 사용하였습니다.
### **서비스 기능 소개**
---
#### 로그인
![](https://velog.velcdn.com/images/goun3596/post/00925dd3-354d-4670-94ee-2ec15078d556/image.gif)

---


#### 이벤트
![](https://velog.velcdn.com/images/goun3596/post/05d9461b-25f0-4a14-a95b-9153c3394480/image.gif)

---

#### 항공
![](https://velog.velcdn.com/images/goun3596/post/d993e9ee-8aac-4d6b-a612-2dd1a8e5a192/image.gif)

---

#### 숙박

![](https://velog.velcdn.com/images/goun3596/post/fcd8ae84-5b7e-4b15-96e8-1231e5a2d460/image.gif)

---

#### 달력
![](https://velog.velcdn.com/images/goun3596/post/638b95b9-009f-4174-a7b3-4b208aeb3813/image.gif)

---

#### 게시판
![](https://velog.velcdn.com/images/goun3596/post/babdf628-b04c-49cf-9316-66c354afc9a6/image.gif)

---

#### 도우미
![](https://velog.velcdn.com/images/goun3596/post/484a6a6a-23a2-4c26-915c-04ded130dc74/image.gif)

---
#### 마이페이지
![](https://velog.velcdn.com/images/goun3596/post/7367edf6-b23e-4021-bce5-9a3e462f5f22/image.gif)

---


