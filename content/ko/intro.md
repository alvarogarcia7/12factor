머리말
============

오늘날 소프트웨어는 보통 서비스로 제공되고, 웹앱 혹은 SaaS(Software As A Service)로 불립니다. Twelve-Factor app은 아래와 같은 SaaS 앱을 만들기 위한 방법론입니다.

* 설정 자동화를 위해 **선언적(declarative)** 양식을 사용하여 새로운 개발자들이 프로젝트에 참여하는데 드는 시간과 비용을 최소화합니다.
* OS에 대한 **종속성을 명확히**하고, 실행 환경 사이의 **극대화된 이식성**을 제공한다.
* 현대적인 **클라우드 플랫폼** 상에 **배포되기** 적합하고, 서버와 시스템의 관리를 필요하지 않게 합니다.
* 개발 환경과 운영 환경의 **차이를 최소화**하고 민첩성을 극대화하기 위해 **지속적인 배포**가 가능하게 합니다.
* 툴, 아키텍처, 개발 방식을 크게 바꾸지 않고 **확장(scale up)** 할 수 있습니다.

Twelve-Factor 방법론은 어떤 프로그래밍 언어로 작성된 애플리케이션이든 적용이 가능합니다. 그리고 어떤 백엔드 서비스(데이터베이스, 큐, 메모리 캐시 등)과의 조합에도 사용될 수 있습니다.