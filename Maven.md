## Maven이란?
Maven은 프로젝트의 전체적인 라이프사이클을 관리하는 도구로<br>
프로젝트 컴파일, 빌드, 수행 및 테스트와 서버 측 Deploy 자원 관리, 라이브러리 관리 기능이 있다.
<br><br>

## 왜 필요한가?
프로젝트를 진행하게 되면 단순히 자신이 작성한 코드만으로 개발하는 것이 아니라 많은 라이브러리들을 활용해서 개발을 하게 된다. 
이 때 사용되는 라이브러리들의 수가 많아서 관리하기 힘든 경우가 발생한다.
<br>
Maven은 내가 사용할 라이브러리 뿐만 아니라 해당 라이브러리가 작동하는데 필요한 다른 라이브러리들까지 관리하고 네트워크를 통해 자동으로 다운받아준다.
<br>
이렇게 Maven은 라이브러리나 모듈을 직접 다운로드 받지 않고 관리해줘서 편하게 개발에 집중할 수 있게 해준다.

## pom.xml
pom은 Project Object Model의 약자로 Maven의 기본 환경 설정 파일이다.
<br>
주요하게 다루는 기능들
* 프로젝트 정보 : 프로젝트의 이름, 개발자 목록, 라이센스 등
* 빌드 설정 : 소스, 리소스, 라이프 사이클별 실행한 플러그인(goal)등 빌드와 관련된 설정
* 빌드 환경 : 사용자 환경 별로 달라질 수 있는 프로파일 정보
* pom 연관 정보 : 의존 프로젝트(모듈), 상위 프로젝트, 포함하고 있는 하위 모듈 등
