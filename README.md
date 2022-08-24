<div align="center">

  <h1>AIOps Dashboard Project</h1>
  
  <p>
    <h3>
      AIOps-Spring-Gateway codes
    </h3>
    <br/>
    <a href="https://spring.io/projects/spring-cloud-gateway">
      Spring Cloud Gateway
    </a>
    <span>
      를 이용하여 Gateway API 구현
    </span>
  </p>
</div>

<br />

<!-- About the Project -->
## :star2: About the Project


<!-- Screenshots -->
### :camera: Screenshots

<div align="center"> 
  <img src="https://placehold.co/600x400?text=Your+Screenshot+here" alt="screenshot" />
</div>


<!-- TechStack -->
### :space_invader: Tech Stack

- Frontend

  ![Vue.js](https://img.shields.io/badge/vuejs-4FC08D.svg?style=flat-square&logo=vuedotjs&logoColor=white)
  ![JavaScript](https://img.shields.io/badge/javascript-F7DF1E.svg?style=flat-square&logo=javascript&logoColor=black)
  ![SASS](https://img.shields.io/badge/SASS-hotpink.svg?style=flat-square&logo=SASS&logoColor=white)
  ![Bootstrap](https://img.shields.io/badge/bootstrap-7952B3?style=flat-square&logo=bootstrap&logoColor=white)
  
  ![Node.js](https://img.shields.io/badge/node.js-339933?style=flat-square&logo=Node.js&logoColor=white)
  ![NPM](https://img.shields.io/badge/npm-CB3837.svg?style=flat-square&logo=npm&logoColor=white)
  
- Backend

  ![Java](https://img.shields.io/badge/java-%23ED8B00.svg?style=flat-square&logo=java&logoColor=white)
  ![Spring Boot](https://img.shields.io/badge/SpringBoot-%236DB33F.svg?style=flat-square&logo=springboot&logoColor=white)
  ![Spring Cloud Gateway](https://img.shields.io/badge/SpringCloudGateway-%236DB33F.svg?style=flat-square&logo=spring&logoColor=white)
  
  ![Gradle](https://img.shields.io/badge/gradle-02303A.svg?style=flat-square&logo=gradle&logoColor=white)
  ![Hibernate](https://img.shields.io/badge/hibernate-59666C.svg?style=flat-square&logo=hibernate&logoColor=white)

- Database

  ![MariaDB](https://img.shields.io/badge/mariadb-003545.svg?style=flat-square&logo=mariadb&logoColor=white)

- DevOps

  ![Jenkins](https://img.shields.io/badge/Jenkins-D24939?style=flat-square&logo=jenkins&logoColor=white)
  ![macOS](https://img.shields.io/badge/mac%20os-000000?style=flat-square&logo=macos&logoColor=white)
  ![Ubuntu](https://img.shields.io/badge/Ubuntu-E95420?style=flat-square&logo=ubuntu&logoColor=white)

<!-- Features -->
### :dart: Features

- 회원가입 / 로그인 기능
- log 및 metric 데이터 대시보드 기능
- Highcharts로 column, pie 차트 위젯 및 테이블 위젯 표현
- **Spring Cloud Gateway를 이용하여 Gateway API를 구현하고 이를 통하여 Api 호출**
- Jenkins로 App, Api 서버 배포

<!-- Contributing -->
## :wave: 느낀점

<a href="https://github.com/Louis3797/awesome-readme-template/graphs/contributors">
  <img src="https://contrib.rocks/image?repo=Louis3797/awesome-readme-template" />
</a>

처음 Gateway API를 사용해 보면서 최소한의 지식으로, 최소한의 설정을 가지고 프로젝트를 진행하려고 하다보니
Gateway 라는 기능은 동작될지언정 완전한 느낌은 들지 않아서 그 부분이 조금 아쉬웠지만,
그래도 첫 삽을 떴다는 것에 의미를 두고자 한다!

## :scroll: 피드백

- **application.yml, properties** 파일을 dev용 파일로 분리
  + ip 등 기타 정보들은 jar 파일과는 따로 분리되며 젠킨스 빌드 시 참고할 수 있도록 관리 필요
