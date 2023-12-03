# 사전미션

### 1. 컨테이너 기술이란 무엇입니까? (100자 이내로 요약)
애플리케이션을 작동시키기 위해 필요한 라이브러리나 애플리케이션 등을 하나로 모아, 별도의 환경에서 실행할 수 있도록 가상환경을 만드는 것을 말한다.
### 2. 도커란 무엇입니까? (100자 이내로 요약)
docker는 애플리케이션을 신속하게 구축, 테스트 및 배포할 수 있는 소프트웨어 플랫폼이다. 소프트웨어를 컨테이너로 패키징하며 라이브러리, 코드 등 모든 것이 포함되어 있다.
### 3. 도커 파일, 도커 이미지, 도커 컨테이너의 개념은 무엇이고, 서로 어떤 관계입니까?
도커 파일이란 도커에서 이용하는 이미지를 기반으로 하여 내가 설정한 스크립트파일을 통해 새로운 이미지를 생성할 수 있는 설정파일이다.

도커 이미지는 파일로 어플리케이션 실행에 필요한 독립적인 환경을 포함하며, 런타임 환경을 위한 일종의 템플릿이다.

도커 컨테이너란 사용자가 기본 시스템에서 애플리케이션을 분리할 수 있는 가상화 런타임 환경이다. 하드웨어 수준에서 가상화가 이루어지는 vm과 달리 애플리케이션 계층에서 가상화된다.

도커파일은 도커 이미지를 빌드하는 방법을 정의하는 스크립트이며 이미지를 동적인 형태로 변경하여 실행하는 것이 컨테이너이다. 다시 말해 도커 컨테이너는 실행중인 이미지 인스턴스로 간주한다. 도커 컨테이너는 어플리케이션을 실행할 격리된 공간이다.

### 4. [실전미션] 도커 설치하기