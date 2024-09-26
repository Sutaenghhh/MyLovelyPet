반려동물 용품 무인매장 관리 시스템 

프로젝트 개발 목적  
도난 재범 방지 블랙리스트관리 기능 , 사람을 대신하여 사용할 수 있는 챗봇 서비스 , 사건발생시 대응할 수 있는 실시간 cctv 동작인식의 
기능을 개발하여 무인매장에서 발생하는 문제점을 해결하기 위해 이 프로젝트를 개발하였습니다. 

개발기간 
2024. 07 - 2024. 08 (8주) 

개발인원
4인 개발 프로젝트

나의 역할 
- 프로젝트 총 기획 ( PM )
- ERD 설계
- 점주 웹 UI/UX 총괄 개발
- 키오스크 블랙리스트 관리 기능 개발
- 팀 내의 분위기를 살리는 막내 

--------------------------------------------------------------------------------------------------
적용스킬 

BE 
-  ![JAVA](	https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white) ![SPRING](	https://img.shields.io/badge/Spring-6DB33F?style=for-the-badge&logo=spring&logoColor=white)
 

FE
- ![JS](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=JavaScript&logoColor=white)
![react](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB) ![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white) ![CSS](	https://img.shields.io/badge/CSS-239120?&style=for-the-badge&logo=css3&logoColor=white) 

DB 
- ![MYSQL](https://img.shields.io/badge/MySQL-00000F?style=for-the-badge&logo=mysql&logoColor=white)
-------------------------------------------------------------------------------------------------------------------
협업 TOOL

-![GIT](https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white) 
![NOTION](https://img.shields.io/badge/Notion-000000?style=for-the-badge&logo=notion&logoColor=white) ![FIGMA](https://img.shields.io/badge/Figma-F24E1E?style=for-the-badge&logo=figma&logoColor=white) ![DISCORD](	https://img.shields.io/badge/Discord-7289DA?style=for-the-badge&logo=discord&logoColor=white) ![POSTMAN](https://img.shields.io/badge/Postman-FF6C37?style=for-the-badge&logo=postman&logoColor=white)


외부 API 
- COOLSMS
- GEMINI
- TossPayments
----------------------------------------------------------------------------------------------------------------------------
아키텍처
<image src="https://github.com/user-attachments/assets/40224973-7375-452d-92ae-29df05afe29d" with="200" height="200"/>
---------------------------------------------------------------------------------------------------------------------------------
ERD 
<image src="https://github.com/user-attachments/assets/628b52df-1676-43f7-8665-4bf09ace69d9" with="200" height="200"/>
----------------------------------------------------------------------------------------------------------------------------------
점주 웹 
- 매출
 <image src="https://github.com/user-attachments/assets/4c2e3c9f-66d1-4d58-84c0-0d929dbd2e4c" with="200" height="200"/>
 
- 로그인(얼굴인식)
 <image src="https://github.com/user-attachments/assets/de4e14fc-844e-46a9-a8da-0e1083d7635b" with="200" height="200"/>

- 회원가입
  
  <image src="https://github.com/user-attachments/assets/08cc7477-eae7-4d9d-831a-364eb2a6cf6c" with="200" height="200"/> <image src="https://github.com/user-attachments/assets/9998d6d8-d287-4e37-a747-e43fb75f3ad6" with="200" height="200"/>

 - 재고현황
   
   <image src="https://github.com/user-attachments/assets/40d98c38-09e1-457e-b86c-604ebc354c26" with="200" height="200"/>
  
- 발주
 <image src="https://github.com/user-attachments/assets/1d2c879f-83f2-4eae-ad2c-71cfb53e5e96" with="200" height="200"/>

- 검수
 <image src="https://github.com/user-attachments/assets/1b79dd24-9925-468d-a507-b99f1491b5aa" with="200" height="200"/>

- 실시간 CCTV
- 
 화재경보 <image src="https://github.com/user-attachments/assets/3debcbc9-ea41-45f6-926b-520ac0210c57" with="200" height="200"/>
 
 응급환자 발생 <image src="https://github.com/user-attachments/assets/90503859-19b1-4cc7-b1aa-bcee5de4f1d2" with="200" height="200"/>




 키오스크 웹 
 - 상품 스캔(QR코드)
  <image src="https://github.com/user-attachments/assets/10d5c210-a059-4090-8af8-3dd6e0d530be" with="200" height="200"/>
  
 - TossPayments 결제
  <image src="https://github.com/user-attachments/assets/e67fde50-6341-43b9-ae52-91c9ec630e29" with="200" height="200"/>

 - 결제내역 SMS 전송
   <image src="https://github.com/user-attachments/assets/99a9b8b8-d696-4569-a718-3d742a2123cc" with="200" height="200"/>

- 블랙리스트 관리
  * 장바구니페이지에서 결제를 하지 않고 넘어가는 사람들을 AWS Recognition Collection에 저장후 다음번에 또 와서 키오스크 이용시 장바구니 페이지에서 블랙리스트 얼굴 인식 후 점주에게 안내메일 전송 
