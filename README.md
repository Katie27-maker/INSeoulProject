<h1>KIT 해커톤 제1회 SW 및 AI 융합 공모전 수상작(장려상)</h1>

<h1>"in 서울"</h1>
<h2>Team 희희낙락</h2>
<blockquote><h3>시연 영상</h3></blockquote>
<a href="https://github.com/Katie27-maker/INSeoulProject">서울시 주거&문화정보 제공 서비스 <바로가기></a>
<br>
<h1>개요</h1>
<ul>
  <li>개요: "in 서울"은 서울에 사는 사람들뿐만 아니라, 서울로 이사를 계획하고 목표로 하는 사람들에게도 주거 정보와 다양한 문화 활동 정보를 제공하는 웹사이트입니다. 또한, MBTI 성격 유형을 기반으로 한 사용자 커뮤니티를 구성하여 정보 교류와 의사 소통을 촉진하며, 사용자 맞춤 정보를 제공하기 위해 사용자의 추천 데이터와 MBTI 성격 유형 정보를 활용합니다.</li>
</ul>

---------------------------------------------------------------------------------------------
**공허한 내용**
<p>참여도 : 40%</p>
<ul>
  <li>데이터 요청 및 출력 : jQuery, Ajax</li>
  <li>반응형 웹 화면 구성 : HTML5, CSS3, BootStrap, JavaScript, jQuery, Summernote API</li>
  <li>결과를 얻어오기 위한 서버 액션 : JAVA, JSP</li>
  <li>DB액션 처리 : MyBatis</li>
  <li>개발 Tool : IntelliJ IDEA Ultimate, Visual Studio Code, Apache Gradle</li>
  <li>협업 툴 : Git, Figma</li>
  <li>UX/UI : 사용자 편리를 위한 디자인 협업 툴(Figma)을 팀원들이게 제공 & 사용자 경험과 사용자 인터페이스 설계</li>
</ul>

**Frontend**
  - HTML5, CSS3, Bootstrap, jQuery를 사용하여 UI 디자인 및 개발.
  - Figma를 사용하여 디자인 작업을 진행하고 팀원들과 협업하여 디자인을 공유 및 수정.
  - Ajax를 사용하여 비동기적으로 서버와 통신하여 부드러운 사용자 경험 제공.
  - 디자인 툴(Figma)를 활용하여 UX/UI 디자인 설계와, 팀원들과의 협업 촉진
  - HTML5, CSS3, BootStrap, JAVA, Jqury, JSP, MySQL, Ajax, summer-note API, Git

**Backend**
  - Java 기반의 웹 애플리케이션으로 JSP를 사용하여 동적 웹 페이지 생성.
  - MySQL 데이터베이스를 사용하여 매핑.
  - Git을 사용하여 버전 관리 및 협업.

---------------------------------------------------------------------------------------------
**기능 설계**
  - **CRUD** : 게시글 및 댓글의 생성, 조회, 수정, 삭제 기능을 구현하고, summer-note API를 활용해 작성 페이지 구성.
  - **페이징** : 게시글 목록을 페이지별로 나누어 표시하고 사용자가 페이지를 이동할 수 있는 기능 제공.
  - **첨부파일** : 게시글에 이미지 또는 파일을 첨부할 수 있는 기능 구현.
  - **댓글** : 게시글에 댓글을 달고 조회, 수정, 삭제할 수 있는 기능 추가.
  - **필터링 구현** :  게시판 리스트에서  MBTI별 필터링 구현
![프로젝트](https://github.com/Tomneng/INSeoulProject/assets/59760987/279ebce2-d2e9-4797-a766-790c06b7f1d1)
![image](https://github.com/Tomneng/INSeoulProject/assets/59760987/876bccbf-78a5-43f6-847b-e0d3e756b55e)
![수정 화면](https://github.com/Tomneng/INSeoulProject/assets/59760987/9bd410bb-8af2-4dfc-b935-d1d5e1cab05e)

---------------------------------------------------------------------------------------------

**UX/UI 디자인 및 협업:**

**디자인 단계**:
   - Figma를 사용하여 초기 디자인을 작성하고, 팀원들과 공유하여 피드백을 받음.
   - UI 컴포넌트, 색상, 레이아웃 등을 설계하고 사용자 경험을 고려하여 조정.
![스크린샷 2024-03-22 오후 2 40 49](https://github.com/Tomneng/INSeoulProject/assets/59760987/15c62993-e4dc-44eb-ac83-24236f40d14e)

---------------------------------------------------------------------------------------------

**ERD 설계**
  - 팀원들 5명이 참여하여 erd를 작성하고 설계.

![스크린샷 2024-03-22 오후 5 08 06](https://github.com/Tomneng/INSeoulProject/assets/59760987/3ee9c975-fae5-4265-80f8-13e48c540c94)

---------------------------------------------------------------------------------------------

**트러블 슈팅 경험**

  - 데이터 베이스 테이블과 xml 매핑 과정
데이터 베이스에서는  post_id(_)을 쓸 수 있다. 하지만 매핑 과정에서는 (_)이라는 문자를 읽지 못하므로 별칭을 줌으로써 불편함을 해소한다.

  - 게시판에서 게시글 등록을 해야하는데 user없이 한다면 상관없지만 테이블에서부터 참조키로 설정 되어 있는 상태에서 했기 때문에 에러가 생김
    해결 : user를 없앴더니 에러가 사라짐

---------------------------------------------------------------------------------------------

**프로젝트를 통해 얻은 것**

기획한 프로젝트는 공모전 참가를 위해 클론 코딩과는 다르게 아이디어부터 데이터베이스 설계, 기획, 디자인까지 모두 함께 정하고 개발해야 했어서 프로젝트 기간이 조금 길어졌고, 여러 차례의 회의가 필요했던 것 같습니다.
현재 자퇴(디자인학과 자퇴 -> (현) 컴퓨터 과학과 편입)를 하였지만 디자인을 전공 했던 경험으로, 팀원들이 기획이나 디자인 단계에서 어떤 편리함을 누릴 수 있을지 고민하다가 Figma 디자인 협업 툴을 제안하였고, 이렇게 함께 작업하면서 디자인을 개선하고 화면을 보며 개발할 수 있는 환경을 제공했습니다. 팀원들이 편리하게 협업할 수 있도록 고심한 덕분에 팀원으로서 큰 도움을 주었습니다.
프로젝트 아이디어를 결정하는 과정에서 각자의 다양한 의견을 조합하여 '서울'이라는 주제를 택하였고, 부동산 추천부터 맛집 정보, 그리고 MBTI를 필터링하는 기능과 사진 첨부 기능을 갖춘 게시판까지 기능을 추가하여 공모전 주제와 잘 맞추어 장려상을 수상하게 되었습니다.
