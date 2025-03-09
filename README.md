# computer-deep-dive-study

## 1. 💁‍♀️ Who need this study

☁️ **아무리 공부해도 컴퓨터과학 내용이 실감나지 않는 클.둥.이** ☁️  
☁️ **이론으로만 외운 컴퓨터 지식이랑 친해지고 싶은 클.둥.이** ☁️  
☁️ **코드가 실행될 때 컴퓨터의 저수준 계층에서는 어떤 일이 일어나는지 궁금한 클.둥.이** ☁️   

운영체제, 컴퓨터구조 및 시스템에 대한 사전 지식을 바탕으로,  
컴파일러 / 스레드 / 동기&비동기 / 레지스터 등에 대한 이해도를 높일 수 있을 것 같습니다.   
무조건 외우는 지식이 아니라 생각하고 이해하며 콤퓨타 세상을 탐험해보아요~  

## 2. 🕑 Schedule

매주 수요일 10시 온라인 미팅 (클클 Discord)

## 3. 👽 Our Squad

| [권시경](https://github.com/kweonsikyung) | [김민우](https://github.com/KimMinWoooo) | [박지혜(스터디장)](https://github.com/jeeheaG) | [이승연](https://github.com/tmddus2) | [임예준](https://github.com/dpwns523) | [임수현(스터디장)](https://github.com/suhyenim) | [장지원](https://github.com/yucori) |
|:--:|:--:|:--:|:--:|:--:|:--:|:--:|
| ![권시경](https://github.com/kweonsikyung.png) | ![김민우](https://github.com/KimMinWoooo.png) | ![박지혜(스터디장)](https://github.com/jeeheaG.png) | ![이승연](https://github.com/tmddus2.png) | ![임예준](https://github.com/dpwns523.png) | ![임수현(스터디장)](https://github.com/suhyenim.png) | ![장지원](https://github.com/yucori.png) |

## 4. 📏 GitHub Collaboration Guidelines

1. `computer-deep-dive-study` 레포를 fork한다.
2. fork한 레포에서 `week1` 브랜치를 생성한다.
3. `./week1/{영어이름}` 폴더를 생성한 후 해당 주차에 공부한 내용을 커밋한다.
4. PR 템플릿에 따라 PR을 작성한다.

## 5. ⛳ Curriculum

| 주차 | 주제 | 세부 내용 |
| --- | --- | --- |
| **Week 1** | **OT** | ⭐ 아이스브레이킹<br>⭐ 그라운드룰 결정 |
| **Week 2** | **1장 프로그래밍 언어 (50p)** | 1.1 여러분이 프로그래밍 언어를 발명한다면?<br>1.2 컴파일러는 어떻게 동작하는 것일까?<br>1.3 링커의 말할 수 없는 비밀<br>1.4 컴퓨터 과학에서 추상화가 중요한 이유 |
| **Week 3** | **2장 프로세스 1/2 (60p)** | 2.1 운영 체제, 프로세스, 스레드의 근본 이해하기<br>2.2 스레드 간 공유되는 프로세스 리소스<br>2.3 스레드 안전 코드는 도대체 어떻게 작성해야 할까?<br>2.4 프로그래머는 코루틴을 어떻게 이해해야 할까? |
| **Week 4** | **2장 프로세스 2/2 (60p)** | 2.5 콜백 함수를 철저하게 이해한다<br>2.6 동기와 비동기를 철저하게 이해한다<br>2.7 아 맞다! 블로킹과 논블로킹도 있다<br>2.8 높은 동시성과 고성능을 갖춘 서버 구현<br>2.9 컴퓨터 시스템 여행: 데이터, 코드, 콜백, 클로저에서 컨테이너, 가상 머신까지 |
| **Week 5** | **3장 메모리 (90p)** | 3.1 메모리의 본질, 포인터와 참조<br>3.2 프로세스는 메모리 안에서 어떤 모습을 하고 있을까?<br>3.3 스택 영역: 함수 호출은 어떻게 구현될까?<br>3.4 힙 영역: 메모리의 동적 할당은 어떻게 구현될까?<br>3.5 메모리를 할당할 때 저수준 계층에서 일어나는 일<br>3.6 고성능 서버의 메모리 풀은 어떻게 구현될까?<br>3.7 대표적인 메모리 관련 버그<br>3.8 왜 SSD는 메모리로 사용할 수 없을까? |
| **Week 6** | **4장 CPU (80p)** | 4.1 이 작은 장난감을 CPU라고 부른다<br>4.2 CPU는 유휴 상태일 때 무엇을 할까?<br>4.3 CPU는 숫자를 어떻게 인식할까?<br>4.4 CPU가 if문을 만났을 때<br>4.5 CPU 코어 수와 스레드 수 사이의 관계는 무엇일까?<br>4.6 CPU 진화론(상): 복잡 명령어 집합의 탄생<br>4.7 CPU 진화론(중): 축소 명령어 집합의 탄생<br>4.8 CPU 진화론(하): 절체절명의 위기에서 반격<br>4.9 CPU, 스택과 함수 호출, 시스템 호출, 스레드 전환, 인터럽트 처리 통달하기 |
| **Week 7** | **5장 캐시 (60p)** | 5.1 캐시, 어디에나 존재하는 것<br>5.2 어떻게 캐시 친화적인 프로그램을 작성할까?<br>5.3 다중 스레드 성능 방해자<br>5.4 봉화희제후와 메모리 장벽 |
| **Week 8** | **6장 입출력 (50p) + 회고** | ⭐ 블로그 글 등의 결과물 남겨보기<br>6.1 CPU는 어떻게 입출력 작업을 처리할까?<br>6.2 디스크가 입출력을 처리할 때 CPU가 하는 일은 무엇일까?<br>6.3 파일을 읽을 때 프로그램에는 어떤 일이 발생할까?<br>6.4 높은 동시성의 비율: 입출력 다중화<br>6.5 mmap: 메모리 읽기와 쓰기 방식으로 파일 처리하기<br>6.6 컴퓨터 시스템의 각 부분에서 얼마큼 지연이 일어날까? |

## 6. 📑 References

[Cloud Club 6기 시즌2 - Observability 기초 스터디](https://github.com/cloud-club/o11y-basic-study)
