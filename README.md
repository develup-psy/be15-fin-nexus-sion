
#  SION

<div align="center">
  <img width="946" height="530" alt="image" src="https://github.com/user-attachments/assets/207386af-1634-45ae-82d0-ae0a6b739ee0" />
</div>
<br><br>


##  DEVELOPERS


<table>
  <tr>
    <td align="center">
      <img width="950" height="950" alt="image" src="https://github.com/user-attachments/assets/1b8d3b61-2049-4986-96e3-f7507a8fe0e7" />
    </td>
    <td align="center">
      <img width="950" height="950" alt="image" src="https://github.com/user-attachments/assets/33862a0a-2e67-41ba-a1dd-88153581af46" />
    </td>
    <td align="center">
      <img width="950" height="950" alt="image" src="https://github.com/user-attachments/assets/942e97cc-b367-4c9a-bfff-530d23f9ad0b" />
    </td>
    <td align="center">
      <img width="950" height="950" alt="image" src="https://github.com/user-attachments/assets/ac811761-38fc-4fa2-9c64-da1ff194bfe3" />
    </td>
    <td align="center">
      <img width="950" height="950" alt="image" src="https://github.com/user-attachments/assets/5301d6b3-cd1a-4f4e-9a08-393c9ebd1500" />
    </td>
    <td align="center">
      <img width="950" height="950" alt="image" src="https://github.com/user-attachments/assets/90b431ec-cc55-4cc0-9a8a-24fdb2c131a9" />
    </td>
  </tr>
  <tr>
    <td align="center">
      <a href="https://github.com/Kihong12"><b>김기홍</b></a>
    </td>
    <td align="center">
      <a href="https://github.com/kimjy8937"><b>김진영</b></a>
    </td>
    <td align="center">
      <a href="https://github.com/sezeme"><b>김채원</b></a>
    </td>
    <td align="center">
      <a href="https://github.com/develup-psy"><b>박성용</b></a>
    </td>
    <td align="center">
      <a href="https://github.com/ckaudgh"><b>차명호</b></a>
    </td>
    <td align="center">
      <a href="https://github.com/didiha"><b>하채린</b></a>
    </td>
  </tr>
</table>


<br>

##  목차

<a href="#project-intro">1. 프로젝트 소개</a><br>
<a href="#planning">2. 프로젝트 기획서</a><br>
<a href="#tech-stack">3. 기술 스택</a><br>
<a href="#requirements">4. 요구사항 명세서</a><br>
<a href="#architecture">5. 시스템 아키텍쳐</a><br>
<a href="#cicdplan">6. CI/CD 계획</a><br>
<a href="#wbs">7. WBS</a><br>
<a href="#erd">8. ERD</a><br>
<a href="#figma">9. Figma(화면설계서)</a><br>
<a href="#api">10. API 명세서</a><br>
<a href="#unit-test">11. 단위 테스트</a><br>
<a href="#intg-test">12. 통합 테스트</a><br>
<a href="#demo">13. 시연 gif</a><br>
<a href="#cicd">14. CI/CD</a>

<h2 id="project-intro">1. 프로젝트 소개</h2>

###  **1-1. 프로젝트 선정 배경**

<img width="600" height="300" alt="image" src="https://github.com/user-attachments/assets/a6db1ad2-c812-4634-a691-753020b5094c" />
<img width="600" height="300" alt="image" src="https://github.com/user-attachments/assets/6f7755e4-085f-4615-b570-11620cf2b0ae" />


###  **1-2. 기존 서비스와 차별점**

<img width="600" height="300" alt="image" src="https://github.com/user-attachments/assets/0029b027-55b8-4048-b9c3-05420b8b4a94" />



###  **1-3. SION: AI 기반으로 기술 중심 인재를 추천하고 관리하는 통합 인사 운영 시스템**

> 이 프로젝트는 프로젝트 수행에 필요한 인력을 빠르고 정확하게 구성할 수 있도록 돕는 AI 기반 인재풀 추천 및 스쿼드 구성 웹 어플리케이션입니다.
사용자는 프로젝트의 도메인, 기술스택, 예산, 기간, 인원 구성 등의 조건을 입력하면, 시스템은 과거 이력과 기술 점수 등을 종합적으로 분석하여 최적의 인재를 자동
추천합니다.


###  1-4. 주요 서비스 기능

 **1-4-1. 개발자 관리**  
기능 요약: 사내 모든 개발자 정보를 조회·관리

상세 설명:

- 기술스택, 프로젝트 이력, 자격/교육 등 상세 이력 확인
- 이름, 상태, 직무 등 다양한 조건으로 필터·검색 가능
- 신규 개발자 일괄 등록, 수정, 퇴사 처리 및 복구
- 등록 이력 및 수정 기록 관리

 **1-4-2. 프로젝트 관리**  
기능 요약: 프로젝트 정보 등록 및 평가 기능 제공

상세 설명:
- 도메인, 기술스택, 인력 구성, 예산 등의 정보 입력
- 프로젝트 종료 시 성과 평가 및 참여자의 기술점수 반영
- 프로젝트별 이력 관리 및 분석 가능

 **1-4-3. 통계 및 기술 트렌드 분석**  
기능 요약: 시각화된 통계와 기술 트렌드 분석 제공

상세 설명:
- 기술스택별 인력 분포, 평균 경력, 활용 빈도 시각화
- 직무별 참여 현황, 등급/단가/상태 기반 분석
- 시계열 기반 기술 트렌드 및 성장 흐름 분석

 **1-4-4. AI 기반 스쿼드 추천**  
기능 요약: 조건 기반 자동 인재 추천 기능

상세 설명:
- 프로젝트 조건(도메인, 기술, 예산 등)에 맞는 개발자 자동 추천
- 직무별 인재 리스트 제공, 구성원 교체·재추천 가능
- 추천 근거 설명, 비교 기능, 결과 시각화 지원

 **1-4-5. 스쿼드 관리 및 배치**  
기능 요약: 스쿼드 저장·편집 및 프로젝트 배치 연동

상세 설명:
- 스쿼드 저장, 조회, 수정 가능
- 스쿼드의 상태(예: 배치됨, 임시저장) 관리
- 프로젝트와 연동되어 실제 배치 가능

 **1-4-6. 스쿼드 관리 및 배치**  
기능 요약: 기업 단위 데이터 보안 및 독립성 보장

상세 설명:
- 각 회사는 별도의 DB에서 인재·프로젝트 정보 관리
- 접근 권한과 관리자 권한 분리로 보안성 강화

<h3 id="planning">
  <a href="https://docs.google.com/document/d/1sGixpxJ4l9nXPV3sTUZbL084y2LVurlD_iGcDL25UAs/edit?tab=t.0" target="_blank">
   2. 프로젝트 기획서
  </a>
</h3> <br>

<h2 id="tech-stack">3. 기술 스택</h2>

<div align="center">

###  Backend
<img src="https://img.shields.io/badge/Spring-6DB33F?style=for-the-badge&logo=spring&logoColor=white" />
<img src="https://img.shields.io/badge/Spring_Boot-6DB33F?style=for-the-badge&logo=springboot&logoColor=white" />
<img src="https://img.shields.io/badge/Spring_Security-6DB33F?style=for-the-badge&logo=springsecurity&logoColor=white" />
<img src="https://img.shields.io/badge/Spring_Data_JPA-6DB33F?style=for-the-badge" />
<img src="https://img.shields.io/badge/Gradle-02303A?style=for-the-badge&logo=gradle&logoColor=white" />
<img src="https://img.shields.io/badge/JWT-000000?style=for-the-badge&logo=JSON%20web%20tokens&logoColor=white" />
<img src="https://img.shields.io/badge/Hibernate-59666C?style=for-the-badge&logo=hibernate&logoColor=white" />
<img src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white" />
<img src="https://img.shields.io/badge/JOOQ-555555?style=for-the-badge" />
<img src="https://img.shields.io/badge/SSE-1572B6?style=for-the-badge" />
<img src="https://img.shields.io/badge/Rekognition-1572B6?style=for-the-badge" />
<img src="https://img.shields.io/badge/CloudFront-7D1B7E?style=for-the-badge" />

</div>

<div align="center">

###  Frontend
<img src="https://img.shields.io/badge/Vue.js-4FC08D?style=for-the-badge&logo=vue.js&logoColor=white" />
<img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black" />
<img src="https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white" />
<img src="https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white" />
<img src="https://img.shields.io/badge/Axios-5A29E4?style=for-the-badge" />
<img src="https://img.shields.io/badge/Vue_Router-4FC08D?style=for-the-badge" />
<img src="https://img.shields.io/badge/Pinia-F7DF1E?style=for-the-badge&logo=pinia&logoColor=black" />
<img src="https://img.shields.io/badge/Tailwind-2496ED?style=for-the-badge&logo=Tailwind&logoColor=white" />
<img src="https://img.shields.io/badge/ToastUi-2496ED?style=for-the-badge&logo=toastui&logoColor=white" />

</div>

<div align="center">

###  Database
<img src="https://img.shields.io/badge/MariaDB-003545?style=for-the-badge&logo=mariadb&logoColor=white" />
<img src="https://img.shields.io/badge/Redis-DC382D?style=for-the-badge&logo=redis&logoColor=white" />
<img src="https://img.shields.io/badge/Amazon_S3-569A31?style=for-the-badge&logo=amazonaws&logoColor=white" />

</div>

<div align="center">

###  Devops
<img src="https://img.shields.io/badge/AWS-232F3E?style=for-the-badge&logo=amazonaws&logoColor=white" />
<img src="https://img.shields.io/badge/Kubernetes-326CE5?style=for-the-badge&logo=kubernetes&logoColor=white" />
<img src="https://img.shields.io/badge/Jenkins-DC382D?style=for-the-badge&logo=Jenkins&logoColor=white" />
<img src="https://img.shields.io/badge/Argo-FF6C37?style=for-the-badge&logo=Argo&logoColor=white" />
</div>

<div align="center">

###  Tools
<img src="https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white" />
<img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white" />
<img src="https://img.shields.io/badge/Figma-F24E1E?style=for-the-badge&logo=figma&logoColor=white" />
<img src="https://img.shields.io/badge/Discord-5865F2?style=for-the-badge&logo=discord&logoColor=white" />
<img src="https://img.shields.io/badge/Postman-FF6C37?style=for-the-badge&logo=postman&logoColor=white" />
<img src="https://img.shields.io/badge/Jira-326CE5?style=for-the-badge&logo=jira&logoColor=white" />

</div>

<h3 id="requirements">
  <a href="https://docs.google.com/spreadsheets/d/1GrDOmd987vaQiI3pSXLBK9NU2OWbMYGAb3edGdWXD0o/edit?gid=230510313#gid=230510313" target="_blank">
    4. 요구사항 명세서
  </a>
</h3> <br>

<h3 id="architecture">5. 시스템 아키텍쳐</h3>
<img src="https://github.com/user-attachments/assets/72200dee-6cf9-48b9-9f65-f8bb48cb1e90" />
<br>

<h2 id="cicdplan">6. CI/CD 계획</h2>
<img width="8760" height="3610" alt="CICD (1)" src="https://github.com/user-attachments/assets/43c3c97b-9526-43db-af51-eabaf7c5ff2d" />

<h3 id="wbs">
  <a href="https://docs.google.com/spreadsheets/d/1GrDOmd987vaQiI3pSXLBK9NU2OWbMYGAb3edGdWXD0o/edit?gid=108925002#gid=108925002" target="_blank">
    7. WBS
  </a>
</h3> 
<br>

<h3 id="erd">8. ERD</h3>
<img src="https://github.com/user-attachments/assets/a07a5d5a-6a9d-47db-a4db-0b7da8d493a9" />
<br>

<h3 id="figma">
  <a href="https://www.figma.com/design/TW7n0XzdVkNInCWernHCvD/be-15-fin?node-id=413-1769&t=sBHWtZHO7Nf4EZ2s-0" target="_blank">
    9. Figma(화면설계서)
  </a>
</h3> 
<img src="https://github.com/user-attachments/assets/147417a4-a61e-4ee1-bce2-570c2dd22933" />
<br>

<h3 id="api">
  <a href="https://docs.google.com/spreadsheets/d/1GrDOmd987vaQiI3pSXLBK9NU2OWbMYGAb3edGdWXD0o/edit?gid=1268650155#gid=1268650155" target="_blank">
    10. API 명세서
  </a>
</h3> 
<br>

<h3 id="unit-test">
  <a href="https://drive.google.com/file/d/17vMFeUcY3hxOw3yBqv8Zc5Tg1UwTVfYy/view" target="_blank">
    11. 단위 테스트 결과서
  </a>
</h3> 
<br>

<h3 id="intg-test">
  <a href="https://docs.google.com/spreadsheets/d/1GrDOmd987vaQiI3pSXLBK9NU2OWbMYGAb3edGdWXD0o/edit?gid=1613105521#gid=1613105521" target="_blank">
    12. 통합 테스트 결과서
  </a>
</h3> 
<br>


<h3 id="demo">13. 시연 gif</h3>


<details><summary><strong>회원</strong></summary>

  <details><summary>로그인</summary>
    <img src="https://github.com/user-attachments/assets/a84ce5d6-7917-4103-9a53-302d42ab0f6d" alt="로그인" />
  </details>
  
  <details><summary>로그아웃</summary>
    <img src="https://github.com/user-attachments/assets/edb743c8-df3b-40eb-b4b4-a246db1e8144" alt="로그아웃" />
  </details>

  <details><summary>회원가입</summary>
    <img src="https://github.com/user-attachments/assets/4a484924-3ab2-4181-b5e1-043832400ceb" alt="회원가입" />
  </details>

</details>

<br>

<details><summary><strong>개발자</strong></summary>

  <details><summary>개발자 등록</summary>
  
  <img src="https://github.com/user-attachments/assets/d08f1955-0af5-46d6-9a13-0d4a5abb722d" alt="개발자 등록" />
  </details>
  
  <details><summary>개발자 목록 조회</summary>
  <img src="https://github.com/user-attachments/assets/beb450e6-c32c-4ce7-9d79-4d154ea71aa8" alt="개발자 목록 조회" />
  </details>
  
  <details><summary>개발자 상세 조회</summary>
  <img src="https://github.com/user-attachments/assets/26913065-d88f-4e7d-864a-9c9a75aa0c89" alt="개발자 상세 조회" />
  </details>
  
  <details><summary>개발자 상태 변경</summary>
  <img src="https://github.com/user-attachments/assets/175e3b29-b394-4196-a6cf-2333325fbaf2" alt="개발자 상태 변경" />
  </details>
  
  <details><summary>개발자 수정</summary>
  <img src="https://github.com/user-attachments/assets/12f67485-8ec9-4269-bcc6-dcdc40d7c16f" alt="개발자 수정" />
  </details>
  
  <details><summary>개발자 삭제</summary>
  <img src="https://github.com/user-attachments/assets/b514293a-8e75-4bea-9c70-1ea1cb633860" alt="개발자 삭제" />
  </details>

</details>

<br>

<details><summary><strong> 프로젝트 </strong></summary>

  <details><summary>프로젝트 등록(관리자)</summary>
  <img src="https://github.com/user-attachments/assets/eb56b347-830b-41fa-b2dc-bdbd17c41025" alt="프로젝트 등록" />
  </details>
  
  <details><summary>프로젝트 수정/삭제(관리자)</summary>
  <img src="https://github.com/user-attachments/assets/b14fe9e7-f0b7-46a3-8f2c-c5c10d62c5da" alt="프로젝트 삭제" />
  </details>
  
  <details><summary>프로젝트 종료(관리자)</summary>
  <img src="https://github.com/user-attachments/assets/0b7dcf2c-a04d-4e99-83ae-7f4b70784b0d" alt="프로젝트 종료" />
  </details>
  
  <details><summary>프로젝트 목록 조회(필터)</summary>
  <img src="https://github.com/user-attachments/assets/3dc99650-d3dd-4ed4-9482-62516bc2b464" alt="프로젝트 목록 조회 필터" />
  </details>
  
  <details><summary>프로젝트 목록 조회(검색어)</summary>
  <img src="https://github.com/user-attachments/assets/6daaa2f3-dcf4-4381-b65e-99bdea64b1c4" alt="프로젝트 목록 조회 검색어" />
  </details>
  
  <details><summary>프로젝트 상세 조회</summary>
  <img src="https://github.com/user-attachments/assets/f7f14f87-ec96-4954-86ff-85db48cd3144" alt="프로젝트 상세 조회" />
  </details>
  
  <details><summary>개발자의 프로젝트 이력 등록 요청</summary>
  <img src="https://github.com/user-attachments/assets/7d60ca91-a5bc-405a-a092-f346ddcf4e8b" alt="프로젝트 이력 등록 요청" />
  </details>
  
  <details><summary>관리자의 프로젝트 이력 등록 요청 거부</summary>
  <img src="https://github.com/user-attachments/assets/cdc3e27d-85dd-4bec-8108-e25d650a0379" alt="프로젝트 이력 등록 요청 거부" />
  </details>
  
  <details><summary>개발자의 프로젝트 이력 등록 재요청</summary>
  <img src="https://github.com/user-attachments/assets/a926df2e-c48f-4d2c-ac01-47a25fb8876b" alt="프로젝트 이력 등록 재요청" />
  </details>
  
  <details><summary>관리자의 프로젝트 이력 등록 승인</summary>
  <img src="https://github.com/user-attachments/assets/fa2fa2c0-8b24-4b9c-90cc-28b792fda9cb" alt="프로젝트 이력 등록 승인" />
  </details>
  
  <details><summary>개발자의 프로젝트 이력 등록 승인 확인</summary>
  <img src="https://github.com/user-attachments/assets/041c3548-2884-4965-a0e9-3b834ac95329" alt="프로젝트 이력 등록 승인 확인" />
  </details>
  
  <details><summary>프로젝트 인원 대체 및 추천</summary>
  <img src="https://github.com/user-attachments/assets/cce57e1f-a699-441b-82f8-d516694e840e" alt="프로젝트 인원 대체 및 추천" />
  </details>
</details>

<br>

<details><summary><strong>스쿼드</strong></summary>
  
<details><summary>스쿼드 등록</summary>
    <img src="https://github.com/user-attachments/assets/196d50ce-62b3-4ed6-961a-18010c7b69b1" alt="스쿼드 등록" />
  </details>

  <details><summary>스쿼드 추천</summary>
    <img src="https://github.com/user-attachments/assets/fe5c8fe5-a554-4dfe-bc96-22c84a3cd668" alt="스쿼드 추천" />
  </details>

  <details><summary>스쿼드 수정</summary>
    <img src="https://github.com/user-attachments/assets/4a898a31-b917-4465-a47c-c1c966c44993" alt="스쿼드 수정" />
  </details>

  <details><summary>스쿼드 공유</summary>
    <img src="https://github.com/user-attachments/assets/079190c3-6bb1-4e3b-9740-51f38b8d5b6d" alt="스쿼드 공유" />
  </details>

<br>

</details>

<br>

<details><summary><strong>프리랜서</strong></summary>
<details><summary>프리랜서 목록 조회 및 외부 개발자 등록</summary>
<img src="https://github.com/user-attachments/assets/6771b008-39ac-4fd0-8022-58597b837530" alt="외부 개발자 등록" />
</details>
</details>

<br>

<details><summary><strong>통계</strong></summary>

<details><summary>기간별 인기 기술 스택 조회</summary>
<img src="https://github.com/user-attachments/assets/43f142eb-eca0-474d-a14b-3cf9fbefffa4" alt="기간별 인기 기술 스택 조회" />
</details>

<details><summary>기술 스택별 구성원 조회</summary>
<img src="https://github.com/user-attachments/assets/188e1e57-3fab-4968-9426-ba5814ee0383" alt="기술 스택별 구성원 조회" />
</details>

<details><summary>기술 스택 도입률 변화 추이 조회</summary>
<img src="https://github.com/user-attachments/assets/ac1c5aec-239e-46fc-8f5a-0844c28f0d2a" alt="기술 스택 도입률 변화 추이 조회" />
</details>

<details><summary>기술 스택별 평균 경력 조회</summary>
<img src="https://github.com/user-attachments/assets/05800413-7c2f-4838-8e8d-73b565b44661" alt="기술 스택별 평균 경력 조회" />
</details>

<details><summary>등급별 대기 상태 인원수 조회</summary>
<img src="https://github.com/user-attachments/assets/7fd6e750-5e6c-41cb-a8ba-2e2efb2efd92" alt="등급별 대기 상태 인원수 조회" />
</details>

<details><summary>등급별 연봉 분포 조회</summary>
<img src="https://github.com/user-attachments/assets/9b7a91bf-e0e5-4c79-b2a8-b9b71b33733f" alt="등급별 연봉 분포 조회" />
</details>

<details><summary>직무별 등록된 인원수 조회</summary>
<img src="https://github.com/user-attachments/assets/dc7ca0aa-c94e-4d25-b297-edf653cc3c6d" alt="직무별 등록된 인원수 조회" />
</details>

</details>

<br>

<details><summary><strong>자기계발</strong></summary>
  
<details><summary>추천 교육 조회</summary>
<img src="https://github.com/user-attachments/assets/27776da8-94c0-4a66-8f96-e7089a15865e" alt="추천 교육 조회" />
</details>

<details><summary>자격증 종류 조회</summary>
<img src="https://github.com/user-attachments/assets/d8db0292-f239-4874-aa14-adb5a8269acd" alt="자격증 종류 조회" />
</details>

<details><summary>보유 자격증 조회</summary>
<img src="https://github.com/user-attachments/assets/760c90cf-82a9-4320-b408-6f3c4b37251d" alt="보유 자격증 조회" />
</details>

</details>

<br>

<details><summary><strong>알림</strong></summary>
    
  <details><summary>알림 조회</summary>
  <img src="https://github.com/user-attachments/assets/b53df560-97aa-4997-aaf0-b0f45a028034" alt="알림 조회" />
  </details>
  
  <details><summary>알림 발송 시 실시간 알림</summary>
  <img src="https://github.com/user-attachments/assets/8fd5f0b1-ca6a-4d17-b2f5-a0ffce32840b" alt="알림 발송 시 실시간 알림" />
  </details>
  
  <details><summary>알림 하나 읽음</summary>
  <img src="https://github.com/user-attachments/assets/abc9bb17-57c2-46e1-95cd-f41d70f07021" alt="알림 하나 읽음" />
  </details>
  
  <details><summary>알림 전부 읽음</summary>
  <img src="https://github.com/user-attachments/assets/f001ec1e-1ae5-4ffc-9683-9924ace7f2fb" alt="알림 전부 읽음" />
  </details>

</details>

<br>

<details><summary><strong>관리자 설정</strong></summary>

<details><summary>기술 스택 관리</summary>
<img src="https://github.com/user-attachments/assets/5e6bc4ce-9910-4843-a858-92c4d1fbd6f0" alt="기술 스택 관리" />
</details>

<details><summary>직무 관리</summary>
<img src="https://github.com/user-attachments/assets/a832dd5d-ef01-4005-bad8-3a9b576faedc" alt="직무 관리" />
</details>

<details><summary>도메인 관리</summary>
<img src="https://github.com/user-attachments/assets/1b6430af-2706-4276-967c-b02008fc621f" alt="도메인 관리" />
</details>

<details><summary>고객사 관리</summary>
<img src="https://github.com/user-attachments/assets/df636124-8f3c-4115-88e6-a8fb32a89ee0" alt="고객사 관리" />
</details>

<details><summary>구간별 단가 관리</summary>
<img src="https://github.com/user-attachments/assets/2e4ed6f1-7334-4d18-81e9-184d1b1cd1c1" alt="구간별 단가 관리" />
</details>

<details><summary>초기 스택 점수 관리</summary>
<img src="https://github.com/user-attachments/assets/ee8bbf86-f514-4dfe-8040-5aef35350b7a" alt="초기 스택 점수 관리" />
</details>

<details><summary>자격증 종류 관리</summary>
<img src="https://github.com/user-attachments/assets/3c8d69fd-b8cf-47ff-a017-519682dfbf6e" alt="자격증 종류 관리" />
</details>

<details><summary>자격증 승인 관리</summary>
<img src="https://github.com/user-attachments/assets/50aea1fd-d11f-453b-9035-db2a1651b5e7" alt="자격증 승인 관리" />
</details>
</details>
<br>


<h2 id="cicd">14. CI/CD</h2>
  <details><summary>Frontend CI/CD GithubAction workflow</summary>
  <img src="https://github.com/user-attachments/assets/e79ab596-96d6-403f-861a-b4681d037ecd" alt="frontend cicd" />
  </details>
  <details><summary>Backend CI/CD GithubAction workflow</summary>
  <img src="https://github.com/user-attachments/assets/73d69f9c-2793-4148-a80e-b38f3ee4b1be" alt="frontend cicd" />
  </details>
  <details><summary>AI Server CI/CD GithubAction workflow</summary>
  <img src="https://github.com/user-attachments/assets/1b80a8b7-ee56-4b5a-9aab-b06e32c1bd88" alt="frontend cicd" />
  </details>
  <details><summary>ArgoCD Application</summary>
  <img src="https://github.com/user-attachments/assets/f304629d-9c66-4deb-ae63-e6b857770c16" alt="frontend cicd" />
  </details>




