# 조창희: FullstackDeveloper

안녕하세요.

개발을 좋아하며 소프트웨어 아키텍트의 꿈이 있는 개발자 조창희입니다.

자발적인 필요성에 의해 즐겁게 공부하며

배운것을 적용시켜 기존의것을 개선하는것을 좋아합니다.

부족한점이 많지만 코드 한줄한줄에 깊은 고민을 담아내는 개발자가 되고 싶습니다.


## :computer:프로젝트 이력

### 1. [같이하실](https://apps.apple.com/kr/app/%EA%B0%99%EC%9D%B4%ED%95%98%EC%8B%A4/id1618195217)(팀) - IOS

같이하실은 배달앱 사용시 높은 최소주문금액과 배달팁에 부담을 느끼는 1인가구를 위해

주문하고자 하는 가게를 중심으로 사용자들이 모이고, 함께 주문할 수 있도록 돕는 서비스 입니다.

![img1](https://raw.githubusercontent.com/hee000/portfolio/main/images/g_preview_1.jpg) | ![img2](https://raw.githubusercontent.com/hee000/portfolio/main/images/g_preview_2.jpg)
---|---|

#### 기술스택

`SwiftUI` `UIKit` `Combine` `Photos` `RealmSwift` `Socket.io`

#### 특징

- 실제 서비스를 했었으나 서버 유지비 문제로 현재 서비스 중단 상태입니다.

[Repository(App)](https://github.com/hee000/IOS_DormitoryDelivery)


<hr>

### 2. [이미지 갤러리](http://nenekomashiro.com)(개인) - Fullstack 

<img src="https://raw.githubusercontent.com/hee000/portfolio/main/images/i_preview.jpg" width="60%">

#### 개요

특정 주제를 가진 사진들을 업로드하고 모아보는 웹을 Nest.js 백엔드와 React 프론트엔드를 통해서 구현했습니다.

#### 기술스택

`NestJS` `TypeScript` `Python` `TypeORM` `MySQL` `Google Cloud Platform` `React` `React-router`

웹서버 프레임워크는 NestJS를 사용했으며 데이터베이스는 ORM으로 MySQL를 사용했습니다. 객체지향적 특징을 더 잘 활용할 수 있도록 백엔드 또한 TypeScript로 구현했습니다.

#### 특징

- NestJS를 도입해 Controller, Service, Domain의 레이어드 구조로 개발했습니다.

- 서버의 이미지 저장 로직 중 python 스크립트를 실행합니다.

  클라이언트의 네트워크 최적화를 하기 위해 백엔드로 업로드 된 이미지를 python 스크립트에서 압축하여 썸네일을 생성하도록 구현했습니다.

- 클라이언트의 사용자 경험 최적화

  클라이언트는 이미지를 30개 단위로 로드하고 스크롤에 따라서 연속적으로 이미지를 추가 로드합니다. 단, 브라우저의 뷰포인트 외부의 이미지는 썸네일을 로드하고 해당 이미지가 뷰포인트 내부로 진입 시에 원본 이미지를 로드합니다.

  다양한 보기 옵션(정렬, 검색, 카테고리, 이미지 크기)과 테마(라이트/다크)를 지원합니다. 반응형 웹으로 모바일과 태블릿, 데스크탑 모든 기기에 대응합니다.

[Repository(server)](https://github.com/hee000/image_gallery_server)

[Repository(client)](https://github.com/hee000/image_gallery_client)

<hr>

### 3. [이미지 갤러리 업로더](https://chrome.google.com/webstore/detail/%EC%8A%A4%ED%85%94%EB%9D%BC%EC%9D%B4%EB%B8%8C-%EC%82%AC%EC%A7%84-%EA%B0%A4%EB%9F%AC%EB%A6%AC-%EC%97%85%EB%A1%9C%EB%8D%94/ljalcmcaglogpengicjoagdpmdkeidpa?hl=ko)(개인) - Chrome Extension

![img1](https://raw.githubusercontent.com/hee000/portfolio/main/images/e_preview_1.png) | ![img2](https://raw.githubusercontent.com/hee000/portfolio/main/images/e_preview_2.png)
---|---|

#### 개요

웹에 있는 이미지를 [이미지 갤러리](https://github.com/hee000/image_gallery_server)에 업로드하는 크롬 확장프로그램입니다.

#### 기술스택
`Chrome Extensions`

[Repository](https://github.com/hee000/image_gallery_chrome_extension)

<hr>

### 4. [쓰기나름](https://apps.apple.com/kr/app/%EC%93%B0%EA%B8%B0%EB%82%98%EB%A6%84/id6443413796)(개인) - IOS

#### 개요

애플의 클라우드킷을 활용한 다이어리 앱을 개발했습니다.

![img1](https://raw.githubusercontent.com/hee000/portfolio/main/images/s_preview_1.jpg) | ![img2](https://raw.githubusercontent.com/hee000/portfolio/main/images/s_preview_2.jpg)
---|---|

#### 기술 스택

`SwiftUI` `UIKit` `CoreData` `CloudKit` `Combine` `Photos` `Socket.io`

#### 특징

- CloudKit을 통한 동일 아이클라우드 계정 기기간, 다른 사용자와의 공유 다이어리 실시간 동기화

- 드래그 앤 드롭 기능을 적극 활용하여 간편한 메모 병합

- 메모의 제목, 내용 등을 통한 검색 기능

- 라이트/다크 모드 테마를 지원

[Repository(App)](https://github.com/hee000/IOS_DormitoryDelivery)

<hr>

### 5. 임베디드 게임 프로그램(개인) - Embedded

#### 개요

'[길건너 친구들](https://www.crossyroad.com/)'에서 영감을 받아 ARM 프로세서 기반에 임베디드 리눅스에서 8x8 도트 매트릭스 상에 장애물과 유저를, LED에 신호등을, CLCD에 최고 점수를, FND에 현재 점수를 출력하고 택트 스위치로 조작하며 이루어지는 장애물 피하기 게임 프로그램을 개발했습니다.

![demo](https://raw.githubusercontent.com/hee000/portfolio/main/images/Embedded.png)

#### 규칙 설명

목적은 최대한 앞으로 전진하며 높은 점수를 획득하는 것입니다.  
이동의 경우 전후좌우 이동이 가능합니다.  
이동하는 경로에는 장애물이 설치되어 있으며 일부 장애물들과 접촉하게 되는 경우 게임이 끝나게 됩니다.  
플레이어의 이동과 무관하게 맵이 앞으로 이동하므로 오랜 시간 가만히 있어 맵의 뒷부분과 닿게 되어도 게임이 끝나게 됩니다.
플레이어는 신호등이 파란색, 노란색인 경우에만 이동이 가능하며 빨간색일 때 이동한다면 게임이 끝나게 됩니다.

#### 특징

- 도트 매트릭스

  게임이 이루어지는 공간으로 메인 로직과 그래픽 관련 로직을 분리해서 플레이어와 장애물들을 표현하는 구조체를 정의하고 이러한 구조체를 리스트에 담아서 보내기만 하면 각 요소들의 좌표를 계산하고 바이너리 값을 계산해서 8x8 매트릭스 디바이스 쓰기 작업을 통해서 실제로 불이 들어오도록 만들었습니다.

  ```cpp
  // cross.cpp
  typedef struct coord {
      int y;
      int x;
  } coord;

  typedef struct obstacle {
    bool isMoving;
    bool direction;
    vector<coord> crd;

  } obstacle;

  class Cross {
    coord currentYX;
    vector<obstacle> obstacles;

    ...

    coord get() { return currentYX; }
    vector<obstacle> getObstacle() { return obstacles; }
  }

  // main.cpp
  void print(int microSec) {
    vector2Matrix(s.getObstacle()); // Cross s
    DM.set(s.get());
    DM.drawToMatrix(microSec);
  }

  ```

  > 메인 로직에서 각각의 도트 매트릭스가 어떻게 켜지는지 알 수 없어도 가능하도록 추상화했습니다.

[Repository](https://github.com/hee000/IoT_Lecture)
