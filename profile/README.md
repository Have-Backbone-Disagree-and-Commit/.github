<!--
## Hi there 👋
**Here are some ideas to get you started:**

🙋‍♀️ A short introduction - what is your organization all about?
🌈 Contribution guidelines - how can the community get involved?
👩‍💻 Useful resources - where can the community find your docs? Is there anything else the community should know?
🍿 Fun facts - what does your team eat for breakfast?
🧙 Remember, you can do mighty things with the power of [Markdown](https://docs.github.com/github/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax)
-->
<div align="center">

![header](https://capsule-render.vercel.app/api?type=soft&color=F7DF1E&text=AWS%20Bootcamp-nl-Slack%20Project)

</div>
<div>

  # 📌 Introduction
  ### Project Objective
  <ul>
    <li>2023 AWS Bootcamp는 Slack을 소통 창구로 사용</li>
    <li>참가자들의 가장 공통된 목표는 취업</li>
    <li>개발직무 관련 취업 공고를 크롤링하여 주기적으로 출력</li>
    <li>취업 공고를 데이터베이스에 담아 추후 데이터 분석 및 에 활용</li>
  </ul>
  
  ### Project Scope and Goal
  <ul>
    <li>MSA 아키텍처 구현</li>
    <li>컨테이너 사용</li>
    <li>ElasticSearch 사용</li>
    <li>CI/CD 자동화</li>
  </ul>
  
  ### To-Be Architecture
  ![To-Be Architecture](https://github.com/Have-Backbone-Disagree-and-Commit/.github/blob/main/presentation/%EC%8A%AC%EB%9D%BC%EC%9D%B4%EB%93%9C0006.jpg)
  <br/>
  <br/>
  
  # 💻 Project Outcome
  ### As-Is Architecture
  ![As-Is Architecture](https://github.com/Have-Backbone-Disagree-and-Commit/.github/blob/main/presentation/%EC%8A%AC%EB%9D%BC%EC%9D%B4%EB%93%9C0009.jpg)
  🚨 As-Is Architecture 기반의 1차 개발·배포 이후, AWS Lambda를 중점적으로 사용하는 Architecture 기반의 2차 개발·배포가 이루어짐
  
  ### Main Functions
  - Crawlers
    - 웹 사이트에서 취업 공고를 크롤링
    - [📁<strong>job_crawlers</strong> Repositry 바로가기](https://github.com/Have-Backbone-Disagree-and-Commit/job_crawlers)
  
  - SlackbotAPI Server
    - Slackbot과 통신을 담당
    - (기존에는 AWS EC2 기반 컨테이너에 올렸는데 지금은 AWS Lambda로 대체함) 
    - [📁<strong>slack_bot</strong> Repositry 바로가기](https://github.com/Have-Backbone-Disagree-and-Commit/slack_bot)
  - ElasticAPI Server
  
    - Elastic Cloud와 통신을 담당
    - [📁<strong>elastic_api_server</strong> Repositry 바로가기](https://github.com/Have-Backbone-Disagree-and-Commit/elastic_api_server)
  
  - ICS File Generator
    - 캘린더 파일(.ics)을 생성하고, 캘린더 파일(.ics)에 대한 퍼블릭 접근을 허용
    - [📁<strong>ics_generator</strong> Repositry 바로가기](https://github.com/Have-Backbone-Disagree-and-Commit/ics_generator)
  
  - Database
    - ElasticSearch에 크롤링한 취업 공고를 저장
  
  ### Sequence Diagram
  <!--슬라이드0011.jpg-->
  ![Sequence Diagram](https://github.com/Have-Backbone-Disagree-and-Commit/.github/blob/main/presentation/%EC%8A%AC%EB%9D%BC%EC%9D%B4%EB%93%9C0011.jpg)
  
  ### Project Output
  <!--슬라이드0012.jpg-->
  ![Project Output](https://github.com/Have-Backbone-Disagree-and-Commit/.github/blob/main/presentation/%EC%8A%AC%EB%9D%BC%EC%9D%B4%EB%93%9C0012.jpg)
  <br/>
  <br/>
  
  # 💡 Conclusion
  ### Areas for Improvement
  <ul>
    <li>To-Be 아키텍처 구현</li>
    <li>IaaS 👉 PaaS, SaaS로 대체</li>
    <li>취업 공고 데이터 분석 및 시각화</li>
    <li>지속적인 커뮤니티 운영</li>
  </ul>
  
  ###  What We Learned
  <ul>
    <li>서비스 선정 능력</li>
    <li>아키텍처 설계, 구현 능력</li>
    <li>AWS 서비스에 대한 Hands-on Experience</li>
    <li>협업 능력</li>
    <li>AWS Secret Key를 퍼블릭 깃허브에 올리면 발생하는 재앙</li>
  </ul>
  
<!--
  ## 🔧 Tech Stack
  ### Backend
  <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=JavaScript&logoColor=white"/>
  <img src="https://img.shields.io/badge/Express-000000?style=flat-square&logo=Express&logoColor=white"/>

  ### ETC
-->
  
</div>
