# GenieQ - AI 기반 지문 및 문항 생성 서비스

<p>
  <img src="./images/파비콘.png" width="50" style="vertical-align: middle; margin-right: 12px;" />
  GenieQ는 교육자를 위한 생성형 AI 기반 국어 비문학 지문 및 문항 생성 서비스입니다.
</p>

<p>
  👉 <a href="http://43.202.6.90/team/genius">소개 페이지 바로가기</a></br>
  🌐 <a href="http://43.202.6.90">GenieQ 배포 웹사이트 바로가기</a>
</p>

## 👥 팀 구성원
<a id="section1"></a>
<table>
  <tr>
    <td align="center">
      <a href="https://github.com/hoonee-math">
        <img src="https://github.com/hoonee-math.png" width="100px;" alt="hoonee-math" style="border-radius:50%; border: 2px solid #00000033;"/>
        <br/>
        <sub><b>최광훈</b></sub>
      </a>
    </td>
    <td align="center">
      <a href="https://github.com/daineee424">
        <img src="https://github.com/daineee424.png" width="100px;" alt="daineee424" style="border-radius:50%; border: 2px solid #00000033;"/>
        <br/>
        <sub><b>정다인</b></sub>
      </a>
    </td>
    <td align="center">
      <a href="https://github.com/blue032">
        <img src="https://github.com/blue032.png" width="100px;" alt="blue032" style="border-radius:50%; border: 2px solid #00000033;"/>
        <br/>
        <sub><b>이예진</b></sub>
      </a>
    </td>
    <td align="center">
      <a href="https://github.com/woogamjaa">
        <img src="https://github.com/woogamjaa.png" width="100px;" alt="woogamjaa" style="border-radius:50%; border: 2px solid #00000033;"/>
        <br/>
        <sub><b>우민혁</b></sub>
      </a>
    </td>
    <td align="center">
      <a href="https://github.com/my2min0">
        <img src="https://github.com/my2min0.png" width="100px;" alt="my2min0" style="border-radius:50%; border: 2px solid #00000033;"/>
        <br/>
        <sub><b>이민영</b></sub>
      </a>
    </td>
    <td align="center">
      <a href="https://github.com/minho0802">
        <img src="https://github.com/minho0802.png" width="100px;" alt="minho0802" style="border-radius:50%; border: 2px solid #00000033;"/>
        <br/>
        <sub><b>김민호</b></sub>
      </a>
    </td>
  </tr>
</table>

## 🛠 기술 스택

### 🎨 Frontend
<div align="left">
  <img src="https://img.shields.io/badge/Vue.js-35495E?style=for-the-badge&logo=vuedotjs&logoColor=4FC08D" />
  <img src="https://img.shields.io/badge/Pinia-76D275?style=for-the-badge&logo=pinia&logoColor=white" />
  <img src="https://img.shields.io/badge/VueRouter-4FC08D?style=for-the-badge&logo=vue.js&logoColor=white" />
  <img src="https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white" />
</div>

### 🧩 Backend
<div align="left">
  <img src="https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white" />
  <img src="https://img.shields.io/badge/Spring_Boot-6DB33F?style=for-the-badge&logo=springboot&logoColor=white" />
  <img src="https://img.shields.io/badge/Spring_Security-6DB33F?style=for-the-badge&logo=springsecurity&logoColor=white" />
  <img src="https://img.shields.io/badge/JPA-59666C?style=for-the-badge&logo=hibernate&logoColor=white" />
  <img src="https://img.shields.io/badge/Maven-C71A36?style=for-the-badge&logo=apachemaven&logoColor=white" />
</div>

### 🗄️ Database / DevOps
<div align="left">
  <img src="https://img.shields.io/badge/Oracle-F80000?style=for-the-badge&logo=oracle&logoColor=white" />
  <img src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white" />
  <img src="https://img.shields.io/badge/Nginx-009639?style=for-the-badge&logo=nginx&logoColor=white" />
  <img src="https://img.shields.io/badge/AWS EC2-FF9900?style=for-the-badge&logo=amazonaws&logoColor=white" />
</div>

### 🧑‍💻 개발 환경
<div align="left">
  <img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white" />
  <img src="https://img.shields.io/badge/IntelliJ IDEA-000000?style=for-the-badge&logo=intellijidea&logoColor=white" />
  <img src="https://img.shields.io/badge/VS Code-007ACC?style=for-the-badge&logo=visualstudiocode&logoColor=white" />
</div>


## 📂 레포지토리

| 구분 | 링크 | 
|------|------|
| 🖥️ Frontend | [2nd_GenieQ_FrontEnd](https://github.com/ChunJae-Full-Stack-FinalProject/2nd_GenieQ_FrontEnd) 
| 🛠️ Backend  | [2nd_GenieQ_BackEnd](https://github.com/ChunJae-Full-Stack-FinalProject/2nd_GenieQ_BackEnd) 
<details>
<summary>🖥️ 프론트엔드 구조 보기</summary>
<pre><code>
├─📁 components/
│  ├─📁 auth/
│  │  ├─📄 PasswordSearch.vue
│  │  ├─📄 SingUpPage.vue
│  │  └─📄 TempPasswordNotice.vue
│  │
│  ├─📁 common/
│  │  ├─📁 button/
│  │  │  ├─📄 BaseButton.vue
│  │  │
│  │  ├─📄 Footer.vue
│  │  └─📄 Sidebar.vue
│  │
│  ├─📁 generation/
│  │  ├─📁 passage/
│  │  │  ├─📁 PassageContent/
│  │  │  │  ├─📄 InputPassageTitle.vue
│  │  │  │  ├─📄 PassageContentMain.vue
│  │  │  │  └─📄 PassageSummary.vue
│  │  │  │
│  │  │  ├─📁 PassageMain/
│  │  │  │  └─📄 CreatePassageMain.vue
│  │  │  │
│  │  │  ├─📄 PassageContent.vue
│  │  │  └─📄 PassageMain.vue
│  │  │
│  │  ├─📁 question/
│  │  │  ├─📁 GenerateQuestion/
│  │  │  │  ├─📁 EditPassageQuestion/
│  │  │  │  │  ├─📄 EditPassage.vue
│  │  │  │  │  ├─📄 EditQuestion.vue
│  │  │  │  │  ├─📄 EditTitle.vue
│  │  │  │  │  └─📄 SymbolTooltip.vue
│  │  │  │  │
│  │  │  │  ├─📄 PassageTitle.vue
│  │  │  │  └─📄 QuestionDescription.vue
│  │  │  │
│  │  │  ├─📁 QuestionMain/
│  │  │  │  ├─📄 InsertPassage.vue
│  │  │  │  ├─📄 StoresInsertPassage.vue
│  │  │  │  └─📄 UserInsertPassage.vue
│  │  │  │
│  │  │  ├─📄 GenerateQuestion.vue
│  │  │  └─📄 QuestionMain.vue
│  │  │
│  │  └─📄 PaymentUsage.vue
│  │
│  ├─📁 mainhome/
│  │  ├─📁 MainContent/
│  │  │  ├─📄 NoticeList.vue
│  │  │  ├─📄 NotionLink.vue
│  │  │  ├─📄 ToFAQ.vue
│  │  │  ├─📄 WelcomInfo.vue
│  │  │  └─📄 WorkList.vue
│  │  │
│  │  └─📄 MainHome.vue
│  │
│  ├─📁 mypage/
│  │  ├─📄 Faq.vue
│  │  ├─📄 Info.vue
│  │  ├─📄 MyPageContent.vue
│  │  ├─📄 MyPageWrapper.vue
│  │  ├─📄 Notice.vue
│  │  ├─📄 NoticeDetail.vue
│  │  └─📄 Ticket.vue
│  │
│  ├─📁 portfolio/
│  │  ├─📄 GenieQShortcut.vue
│  │  ├─📄 PortfolioMember.vue
│  │  └─📄 PortfolioTeam.vue
│  │
│  ├─📁 storage/
│  │  ├─📁 storageContent/
│  │  │  └─📁 MainCompo/
│  │  │     ├─📄 LikeList1.vue
│  │  │     └─📄 WorkList1.vue
│  │  │
│  │  ├─📄 LikeMain.vue
│  │  ├─📄 StorageMain.vue
│  │  └─📄 WorkListMain.vue
│  │
│  └─📁 test/
│     ├─📄 DelayComponent.vue
│     ├─📄 ImmediatelyComponent.vue
│     ├─📄 TestHomeComponent.vue
│     └─📄 TestSideNavBarComponent.vue
│
├─📁 router/
│  ├─📄 auth.routes.js
│  ├─📄 common.routes.js
│  ├─📄 generation.routes.js
│  ├─📄 index.js
│  ├─📄 mypage.routes.js
│  └─📄 storage.routes.js
│
├─📁 stores/
│  ├─📄 auth.js
│  ├─📄 globalNameStore.js
│  └─📄 passage.js
│
├─📁 views/
│  ├─📄 Frame.vue
│  ├─📄 LoginView.vue
│  └─📄 TeamView.vue
│
├─📄 App.vue
└─📄 main.js
</code></pre>
</details>

<details>
<summary>🛠️ 백엔드 구조 보기</summary>
<pre><code>
├─📁 main/
│  ├─📁 java/
│  │  ├─📁 com/
│  │  │  └─📁 cj/
│  │  │     └─📁 genieq/
│  │  │        ├─📁 common/
│  │  │        │  ├─📁 config/
│  │  │        │  │  ├─📄 SecurityConfig.java
│  │  │        │  │  ├─📄 SwaggerConfig.java
│  │  │        │  │  └─📄 WebMvcConfig.java
│  │  │        │  │
│  │  │        │  ├─📁 interceptor/
│  │  │        │  │  └─📄 AuthInterceptor.java
│  │  │        │  │
│  │  │        │  └─📁 token/
│  │  │        │
│  │  │        ├─📁 format/
│  │  │        │  ├─📁 controller/
│  │  │        │  │  └─📄 FormatController.java
│  │  │        │  │
│  │  │        │  ├─📁 dto/
│  │  │        │  │  └─📄 Format.java
│  │  │        │  │
│  │  │        │  ├─📁 entity/
│  │  │        │  │  └─📄 FormatEntity.java
│  │  │        │  │
│  │  │        │  ├─📁 repository/
│  │  │        │  │  └─📄 FormatRepository.java
│  │  │        │  │
│  │  │        │  └─📁 service/
│  │  │        │     ├─📄 FormatService.java
│  │  │        │     └─📄 FormatServiceImpl.java
│  │  │        │
│  │  │        ├─📁 member/
│  │  │        │  ├─📁 controller/
│  │  │        │  │  └─📄 MemberController.java
│  │  │        │  │
│  │  │        │  ├─📁 dto/
│  │  │        │  │  ├─📁 request/
│  │  │        │  │  │  ├─📄 FindPasswordRequestDto.java
│  │  │        │  │  │  ├─📄 LoginRequestDto.java
│  │  │        │  │  │  ├─📄 SignUpRequestDto.java
│  │  │        │  │  │  ├─📄 UpdateNameRequestDto.java
│  │  │        │  │  │  ├─📄 UpdatePasswordRequestDto.java
│  │  │        │  │  │  ├─📄 UpdateTypeRequestDto.java
│  │  │        │  │  │  └─📄 WithdrawRequestDto.java
│  │  │        │  │  │
│  │  │        │  │  ├─📁 response/
│  │  │        │  │  │  ├─📄 LoginMemberResponseDto.java
│  │  │        │  │  │  └─📄 MemberInfoResponseDto.java
│  │  │        │  │  │
│  │  │        │  │  └─📄 Member.java
│  │  │        │  │
│  │  │        │  ├─📁 entity/
│  │  │        │  │  └─📄 MemberEntity.java
│  │  │        │  │
│  │  │        │  ├─📁 repository/
│  │  │        │  │  └─📄 MemberRepository.java
│  │  │        │  │
│  │  │        │  └─📁 service/
│  │  │        │     ├─📄 AuthService.java
│  │  │        │     ├─📄 AuthServiceImpl.java
│  │  │        │     ├─📄 InfoService.java
│  │  │        │     └─📄 InfoServiceImpl.java
│  │  │        │
│  │  │        ├─📁 notice/
│  │  │        │  ├─📁 controller/
│  │  │        │  │  └─📄 NoticeController.java
│  │  │        │  │
│  │  │        │  ├─📁 dto/
│  │  │        │  │  ├─📁 response/
│  │  │        │  │  │  ├─📄 NoticeListResponseDto.java
│  │  │        │  │  │  └─📄 NoticeResponseDto.java
│  │  │        │  │  │
│  │  │        │  │  └─📄 Notice.java
│  │  │        │  │
│  │  │        │  ├─📁 entity/
│  │  │        │  │  └─📄 NoticeEntity.java
│  │  │        │  │
│  │  │        │  ├─📁 repository/
│  │  │        │  │  └─📄 NoticeRepository.java
│  │  │        │  │
│  │  │        │  └─📁 service/
│  │  │        │     ├─📄 NoticeService.java
│  │  │        │     └─📄 NoticeServiceImpl.java
│  │  │        │
│  │  │        ├─📁 passage/
│  │  │        │  ├─📁 controller/
│  │  │        │  │  └─📄 PassageController.java
│  │  │        │  │
│  │  │        │  ├─📁 dto/
│  │  │        │  │  ├─📁 request/
│  │  │        │  │  │  ├─📄 PassageDeleteRequestDto.java
│  │  │        │  │  │  ├─📄 PassageFavoriteRequestDto.java
│  │  │        │  │  │  ├─📄 PassageInsertRequestDto.java
│  │  │        │  │  │  ├─📄 PassageUpdateRequestDto.java
│  │  │        │  │  │  ├─📄 PassageUpdateTitleRequestDto.java
│  │  │        │  │  │  └─📄 PassageWithQuestionsRequestDto.java
│  │  │        │  │  │
│  │  │        │  │  ├─📁 response/
│  │  │        │  │  │  ├─📄 PassageFavoriteResponseDto.java
│  │  │        │  │  │  ├─📄 PassagePreviewListDto.java
│  │  │        │  │  │  ├─📄 PassageSelectResponseDto.java
│  │  │        │  │  │  ├─📄 PassageStorageEachResponseDto.java
│  │  │        │  │  │  ├─📄 PassageStorageMainResponseDto.java
│  │  │        │  │  │  └─📄 PassageWithQuestionsResponseDto.java
│  │  │        │  │  │
│  │  │        │  │  └─📄 Passage.java
│  │  │        │  │
│  │  │        │  ├─📁 entity/
│  │  │        │  │  └─📄 PassageEntity.java
│  │  │        │  │
│  │  │        │  ├─📁 repository/
│  │  │        │  │  └─📄 PassageRepository.java
│  │  │        │  │
│  │  │        │  └─📁 service/
│  │  │        │     ├─📄 PassageService.java
│  │  │        │     ├─📄 PassageServiceImpl.java
│  │  │        │     ├─📄 PdfService.java
│  │  │        │     ├─📄 TxtService.java
│  │  │        │     └─📄 WordService.java
│  │  │        │
│  │  │        ├─📁 payment/
│  │  │        │  ├─📁 controller/
│  │  │        │  │  └─📄 PaymentController.java
│  │  │        │  │
│  │  │        │  ├─📁 dto/
│  │  │        │  │  ├─📁 request/
│  │  │        │  │  │  └─📄 PaymentRequestDto.java
│  │  │        │  │  │
│  │  │        │  │  ├─📁 response/
│  │  │        │  │  │  └─📄 PaymentListResponseDto.java
│  │  │        │  │  │
│  │  │        │  │  └─📄 Payment.java
│  │  │        │  │
│  │  │        │  ├─📁 entity/
│  │  │        │  │  └─📄 PaymentEntity.java
│  │  │        │  │
│  │  │        │  ├─📁 repository/
│  │  │        │  │  └─📄 PaymentRepository.java
│  │  │        │  │
│  │  │        │  └─📁 service/
│  │  │        │     ├─📄 PaymentService.java
│  │  │        │     └─📄 PaymentServiceImpl.java
│  │  │        │
│  │  │        ├─📁 question/
│  │  │        │  ├─📁 controller/
│  │  │        │  │  └─📄 QuestionController.java
│  │  │        │  │
│  │  │        │  ├─📁 dto/
│  │  │        │  │  ├─📁 request/
│  │  │        │  │  │  ├─📄 QuestionInsertRequestDto.java
│  │  │        │  │  │  └─📄 QuestionUpdateRequestDto.java
│  │  │        │  │  │
│  │  │        │  │  ├─📁 response/
│  │  │        │  │  │  └─📄 QuestionSelectResponseDto.java
│  │  │        │  │  │
│  │  │        │  │  ├─📄 Question.java
│  │  │        │  │  └─📄 QuestionDto.java
│  │  │        │  │
│  │  │        │  ├─📁 entity/
│  │  │        │  │  └─📄 QuestionEntity.java
│  │  │        │  │
│  │  │        │  ├─📁 repository/
│  │  │        │  │  └─📄 QuestionRepository.java
│  │  │        │  │
│  │  │        │  └─📁 service/
│  │  │        │     ├─📄 QuestionService.java
│  │  │        │     └─📄 QuestionServiceImpl.java
│  │  │        │
│  │  │        ├─📁 test/
│  │  │        │  ├─📁 controller/
│  │  │        │  │  ├─📄 TestMemberCommandLineRunner.java
│  │  │        │  │  └─📄 TestMemberController.java
│  │  │        │  │
│  │  │        │  ├─📁 dto/
│  │  │        │  │  └─📄 TestMember.java
│  │  │        │  │
│  │  │        │  ├─📁 entity/
│  │  │        │  │  └─📄 TestMemberEntity.java
│  │  │        │  │
│  │  │        │  ├─📁 repository/
│  │  │        │  │  └─📄 TestMemberRepository.java
│  │  │        │  │
│  │  │        │  └─📁 service/
│  │  │        │     ├─📄 TestMemberService.java
│  │  │        │     └─📄 TestMemberServiceImpl.java
│  │  │        │
│  │  │        ├─📁 ticket/
│  │  │        │  ├─📁 entity/
│  │  │        │  │  └─📄 TicketEntity.java
│  │  │        │  │
│  │  │        │  └─📁 repository/
│  │  │        │     └─📄 TicketRepository.java
│  │  │        │
│  │  │        ├─📁 usage/
│  │  │        │  ├─📁 controller/
│  │  │        │  │  └─📄 UsageController.java
│  │  │        │  │
│  │  │        │  ├─📁 dto/
│  │  │        │  │  └─📁 response/
│  │  │        │  │     └─📄 UsageListResponseDto.java
│  │  │        │  │
│  │  │        │  ├─📁 entity/
│  │  │        │  │  └─📄 UsageEntity.java
│  │  │        │  │
│  │  │        │  ├─📁 repository/
│  │  │        │  │  └─📄 UsageRepository.java
│  │  │        │  │
│  │  │        │  └─📁 service/
│  │  │        │     ├─📄 UsageService.java
│  │  │        │     └─📄 UsageServiceImpl.java
│  │  │        │
│  │  │        └─📄 GenieqApplication.java
│  │  │
│  │
│  ├─📁 resources/
│  │  ├─📁 fonts/
│  │  │
│  │  ├─📁 initdata/
│  │  │
│  │  ├─📁 templates/
│  │  │
│  │  ├─📄 application-private.properties
│  │  ├─📄 application-private.properties.template
│  │  ├─📄 application.properties
│  │  └─📄 datasource.properties
│  │ 
</code></pre>
</details>

## ✨ 주요 기능


### 📝 지문 생성

사용자는 다양한 분야(인문, 예술, 사회, 과학, 기술)와 제재를 선택해 AI가 생성한 맞춤형 지문을 받아볼 수 있습니다. 핵심 논점이 자동 추출되며, 편집 및 PDF·Word·TXT 포맷으로의 출력이 가능합니다.
<img src="./images/passage_generate.gif" width="100%" alt="지문 생성 시연" />


### ❓ 문항 생성

AI는 생성된 지문 또는 직접 입력한 텍스트를 바탕으로 객관식 문항을 자동 생성하며, 정답과 해설도 함께 제공합니다. 문항은 수정·추가가 가능하여 학습 목적에 맞게 조정할 수 있습니다.
<img src="./images/question_generate.gif" width="100%" alt="문항 생성 시연" />

### 📂 자료실

생성한 지문과 문항을 체계적으로 저장·관리할 수 있으며, 최근 작업과 즐겨찾기를 통해 빠르게 접근할 수 있습니다. 최대 150개 자료까지 보관 가능하며, 다양한 포맷으로 추출해 수업에 활용할 수 있습니다.
<img src="./images/storage.gif" width="100%" alt="자료실 시연" />


## 🧭 화면
🎨 [Figma 디자인 시안](https://www.figma.com/design/5Wf8PhVSI48Rvd3nLshRiH/%5B%EA%B0%9C%EB%B0%9C%ED%98%91%EC%97%85%5D%EA%B5%AD%EC%96%B4-%EC%A7%80%EB%AC%B8%2C-%EB%AC%B8%ED%95%AD-%EC%83%9D%EC%84%B1-%EC%84%9C%EB%B9%84%EC%8A%A4?node-id=1490-14096&t=ifwDthlKzWAce4iL-0)

서비스의 전체 사용자 흐름을 보여주는 플로우 차트입니다.

<img src="./images/플로우 차트.png" alt="화면 플로우 차트" width="100%" />


## 🗂 ERD 설계도

GenieQ 서비스의 데이터베이스 구조를 시각적으로 표현한 ERD입니다.

<img src="./images/erd.png" alt="ERD 설계도" width="100%" />

