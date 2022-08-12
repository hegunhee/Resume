# Resume
안녕하세요
안드로이드 개발자를 꿈꾸는 이건희 입니다.  
Android와 Kotlin, Clean Code에 관심이 많고 꾸준히 공부하고 있습니다.  
코드를 작성하는것 뿐만 아니라 개발자간의 커뮤니케이션, 소프트웨어 아키텍쳐에 관심이 많습니다.  
* 이메일 : gunhee0072@gmail.com  
* [github](https://github.com/hegunhee)  
* [blog](https://hegunhee.tistory.com)  
* [notion](https://unleashed-redcurrant-8ed.notion.site/37a87b80bbca4e6ab5391c46e3d0486f)
## Education
* 동양미래대학교 정보통신공학과 3년제 졸업
  * 2018.03 ~ 2022.02
* 인천 산곡고등학교 졸업
  * 2015.03 ~ 2018.02  
## Skills  
* Programing Language
  * Java
  * Kotlin  
* Framework/Library
  * Room
  * Koin
  * Coroutine  
  * Hilt  
## Projects  
[Routiner](https://github.com/hegunhee/Routiner)  
* [앱 링크](https://play.google.com/store/apps/details?id=com.hegunhee.routiner)
* 계획 플래너  
* 개인 프로젝트로 진행했습니다.  
* 기간  
  * 2022.06.21 ~ 2022.07.11(앱출시) 지속적으로 업데이트중  
  * 2022.07.29 카테고리 기능 추가  
* 작업  
  * **AAC-ViewModel** 적용  
 Activity나 Fragment에 보여줄 data를 가지고있습니다.  
 Activity나 Fragment가 화면 회전 등의 이유로 Destroy 상태가 되어도  
 AAC-ViewModel은 재 생성되지 않기때문에 데이터를 쉽게 관리할 수 있습니다.
 그리고 ViewModelScope를 사용해 비동기 코드를 쉽게 작성할 수 있습니다.  
* **Flow** 적용  
 지속적으로 데이터를 받을 수 있는 Flow를 사용해 오늘의 루틴을 받을 수 있습니다.  
* **DataBinding** 적용  
 dataBinding을 사용하여 findViewById를 사용하지 않으며 xml 파일과 데이터 객체를 연결해줍니다.  
* **Hilt** 적용  
 의존성 주입을 사용해서 테스트를 쉽게 사용하고 코드 내부에서 의존관계를 만들지 않고 관심사를 외부로 돌립니다.  
* **Room Database** 적용  
 루틴들을 저장하고 불러오는데 Room Database를 사용하였습니다.  
   
[덜 편한 가계부](https://github.com/hegunhee/SimpleMemoApp)  
* 지금 사용중인 편한 가계부라는 앱을 모티브로해서 만든 어플리케이션
* 개인 프로젝트로 진행했습니다. 
* 기간
  * 2022.03.04 ~ 2022.04.16
* 작업
  * **Android Clean Architecture** 적용  
    기존에 안드로이드를 공부할때는 모든 활동을 Activity에서 구현했지만  
    AAC를 공부하고나서 로직 분리와 의존성 분리의 중요성을 깨닫고 프로젝트에 적용하였습니다.  
  * **Room DataBase** 적용  
    가계부라는 특성상 가계부 데이터를 저장하고 불러오는 과정이 필요한데  
    Room을 이용해서 데이터베이스 생성, 테이블 관리, DAO(Data Access Object)를 쉽게 관리하였습니다.
  * **Coroutine** 적용  
    Room을 사용하거나 가계부 정보들을 정렬하는데 많은 시간이 필요하기때문에  
    Coroutine을 사용해서 main Thread의 부담을 줄일 수 있음
  * **Koin** 적용
    Activity에서 ViewModel을 사용할때 의존성이나 Model의 Repository를 사용할때  
    의존성 주입을 위해 Koin을 사용하였습니다.  
    러닝커브가 낮고 사용하기 쉬웠습니다.  
  * **Hilt** 적용  
    코드의 양과 주입해야될 객체의 양이 늘어날경우 Koin의 경우 에러가 발생하기 쉬워  
    Koin -> Hilt로 DI를 변경하였습니다.
