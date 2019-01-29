### Code Smell 찾아 보기
* Magic Number
  - 특수한 값을 가지는 숫자를 의미한다.
  - 변경될 가능성이 있으면 여러 곳을 고쳐야 할 수 있다.
  - 코드에서 어떻게 처리되고 있는지 알아내기 힘들다.
  - 상수선언 기능을 이용하여 가독성을 높이고 유지보수성을 향상시킨다.

* 부정형 코드 블럭
  - 부정형은 긍정형보다 이해하기 힘들다.

* 복잡한 if 조건문
  - if 조건문안의 내용이 복잡하다면 가독성 있는 함수로 추출하도록 한다.
  - 코드의 용도가 명확하게 드러나고 로직의 흐름을 이해하기 쉽다.
  
### 팀명 정하고 역할자 나누기
* 개발리더
  - 리팩토링 브랜치를 생성한다.
  - Pull Request에 대한 Merge를 수행한다.
  - 릴리즈를 생성한다.

* 개발자1
  - Feature 브랜치를 생성한다.
  - Pull Request를 생성한다.(개발자2를 Reviewer로 지정하고 개발리더를 Assigner로 할당한다.)
  - 개발자2가 생성한 Pull Request에 대하여 코드리뷰를 수행한다.

* 개발자2
  - Feature 브랜치를 생성한다.
  - Pull Request를 생성한다.(개발자1를 Reviewer로 지정하고 개발리더를 Assigner로 할당한다.)
  - 개발자1가 생성한 Pull Request에 대하여 코드리뷰를 수행한다.

### 리팩토링 수행하기
1. 개발리더는 리팩토링 브랜치를 생성합니다. 브랜치명은 팀명_refactoring_yyyymmdd로 작성하고 master 브랜치로부터 생성합니다.
![리팩토링 브랜치 생성하기](https://user-images.githubusercontent.com/8435910/51890613-d8978a80-23df-11e9-9b99-3cea2d79aa82.GIF)
2. 개발자1은 feature 브랜치를 생성합니다.
![feature 브랜치 생성하기](https://user-images.githubusercontent.com/8435910/51891076-5b6d1500-23e1-11e9-90c0-16676f87b897.GIF)



  

  
  


