# 리눅스 (Linux)OS   
- - - 
> 
    1. 인터넷 서비스 서버 환경 익히기 
    2. 고급 운영체제 기능 직접 제어 
    3. UNIX 계열 OS 사용법 익히기 
- - -
### 리눅스란?
* 리눅스는 유닉스를 기반으로 만들어졌다.
두 OS 모두, __다중 사용자__, __멀티태스킹__, __다중 스레드__ 를 지원하는 네트워크 운영체제이다. 그래서 서버로 작동하는데 최적화 되어있다.


* 서버에 많이 사용되는 운영체제 
 ![설명](/images/linux.png)

* 프로그래밍을 할 때에도 많이 사용이 됩니다. 
> 
    프로그래머 -> 컴파일러 -> 컴퓨터 
    리눅스는 kernel + shell + system 기본 프로그래밍 
    --> 컴파일러로 전달되기때문에 window기반 운영체제보다 
    상대적으로 빠르다 (winodw는 수많은 보안프로그램)
    업무속도의 향상을 위해 많이 사용되는

 ![설명](/images/linux2.png)


> 
 * 간단한 __커널__ 설명    
 커널은 OS의 핵심이며 사용자와 하드웨어 간의 인터페이스 역할을합니다. 각 커널 하위 시스템에는 동시성, 가상 메모리, 페이징 및 가상 파일 시스템과 같은 특정 기능이 있습니다.

- - - 
* plain 하게 프로그래밍이 가능
    * ANSI C - C언어 표준  

* 클라우드 컴퓨팅에서 많이 쓰인다 
- - -
한번은 들어둬야 할 리눅스 배경, 역사, 철학 
## 리눅스 시작
  * 리누스 토발즈(Linus Torvalds)가 개발 
    * 대학에있는 UNIX 컴퓨터를 집에서 쓰고 싶다.
    * 다중 사용자, 다중 작업 (__시분할 시스템__, __멀티태스킹__)을 지원하는 유닉스(UNIX)와 유사한 운영체제

 * GNU 프로젝트 
    * GNU = Gnu is Not Unix
    * 유닉스 운영체제를 여러 회사에서 각자 개발, 소스를 공유하지 않는 문화에 반발
    * 리차드 스톨만 : 초기 컴퓨터 개발 공동체의 상호협력적인 문화로 돌아갈 것을 주장하며, 1985년도에 GNU 선언문을 발표 
    * GPL 라이선스 프로그램은 어떤 목적으로, 어떤 형태로든 사용할 수 있지만, 사용하거나 변경된 프로그램을 다시 배포하는 경우, 동일한 GPL 라이선스로 배포해야함.
    * 소스 오픈을 장려하기 위한 프로젝트 

 ![설명2](/images/operatingsystem.png)
* GNU 프로젝트와 GNU Hurd 
    * 운영체제 커널 개발 시도 - GNU Hurd 
    * 운영체제에 필요한 라이브러리, 컴파일러, 에디터, 쉘 개발 

* 정리
    * 오픈 소스 운동 
    * 운영체제 개발 - OS kernel, System call, Compiler, API(Library), Shell, Editor
    * 소스 라이선스 -GPL
    * GNU / Linux 
- - - 
