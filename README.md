# 2018-2 객체지향 프로그래밍 프로젝트 - Street Football Game
구성원: 2-2 박혜준 | 2-3 김이룸 | 2-4 조현준

## 1. 주제
3:3 Street Football Game

## 2. 동기
기존의 풋살 게임은 두 명의 플레이어가 각각 다수의 선수를 번갈아 가며 제어하는 방식이다. 이에 따라 여러 명의 선수 중 한 명을 방향키와 슛, 패스 등의 키보드 입력을 통해 컨트롤하는 동안, 나머지 선수들은 컴퓨터의 알고리즘에 따라 상황에 맞게 자율적으로 움직인다. 하지만 이와 같은 방식의 경우 선수들을 계속 바꿔야 하므로 플레이에 어려움이 있으며, 상황에 맞게 자동으로 선수를 바꿔준다고 해도 내가 조종하고 싶은 선수를 순간적으로 조종할 수 없다는 문제점이 있다. 따라서 기존의 풋살 게임 방식보다 현실성을 반영한 파이썬 풋살 게임 프로젝트를 진행하게 되었다.

## 3. 프로그램 사용 대상
기존의 축구 게임과 달리 현실의 축구와 더 비슷한 축구 게임을 즐기고 싶은 사용자 그룹.

## 4. 목적
축구 게임을 통해 축구에 대한 흥미를 증진하며, 게임 내의 기능을 통해 축구의 규칙을 익힐 수 있게 한다.

## 5. 주요기능
1. 다수의 플레이어가 한 화면으로 게임에 참여할 수 있다.
2. 다수의 플레이어가 키보드 위치에 따라 팀을 선택할 수 있으며, 동시에 게임을 시작할 수 있다.
3. 다수의 플레이어가 동시에 자신의 캐릭터를 제어할 수 있으며, 이것이 플레이어의 화면에 GUI를 통해 연속적으로 표현된다.
4. 다수의 플레이어가 패스, 슛 등의 기능을 이용하여 실제 축구와 비슷한 게임을 할 수 있다.
5. 정해진 시간에 게임이 시작되고 끝난다.

## 6. 프로젝트 핵심
플레이어가 각각 이동, 슛 등의 기능이 개별적으로 제어할 수 있도록 한다.

## 7. 구현에 필요한 라이브러리나 기술
thread, pygame

## 8. **분업 계획**
게임 세부 규칙 확립
플레이어의 이동 및 패스, 슛 기능 구현
공, 플레이어 간의 상호작용 구현
공-골대 간의 상호작용 구현

## 9. 기타
### 게임 규칙
1. 경기에는 총 6명의 플레이어가 참여하여 3:3으로 경기한다.
2. 경기는 전후반 총 10분으로 한다.
3. 상대 팀이 파울을 하면 프리킥 기회가 주어지고, 만약 골키퍼 에어리어 안에서 파울을 하면 페널티를 준다.

### 구현 계획
1. 모든 플레이어의 초기 포메이션은 주어진다.
2. 플레이어와 공이 접촉할 경우 공을 드리블하거나 패스 또는 슛을 할 수 있다.
3. 키보드로 제어 가능한 기능은 위치 이동, 슛, 패스, 태클이다.
4. 태클할 때 공보다 플레이어에 먼저 접촉하면 파울로 판정한다.

## 10. 실행 방법
1. https://drive.google.com/open?id=1BpccwUTOk1CDg_V4DMTHWEvpIdkT3qHn 로 접근하여 images_and_songs.zip 파일을 다운받는다. (용량이 커서 Github에 업로드가 불가함)
2. Github의 Final.py를 다운받는다.
3. 두 파일이 같은 상위 폴더 아래에 있음을 확인한다.
4. Pygame library를 다운받는다.
5. 실행한다.

음원 파일 출처 
- Intro song: Blur - Song 2 - FIFA 98 Soundtrack - HD
- BGM song: Best soccer song ever

사진 파일 출처
- Intro display - https://www.youtube.com/embed/pCVF0CSRTYA
- sportsmanship display - http://www.seoul.co.kr/news/newsView.php?id=20180701500014
- End display - http://blog.naver.com/PostView.nhn?blogId=ktri8888&logNo=221329988118&categoryNo=0&parentCategoryNo=0&viewDate=&currentPage=1&postListTopCurrentPage=1&from=postView

<hr>

#### readme 작성관련 참고하기 [바로가기](https://heropy.blog/2017/09/30/markdown/)

#### 예시 계획서 [[예시 1]](https://docs.google.com/document/d/1hcuGhTtmiTUxuBtr3O6ffrSMahKNhEj33woE02V-84U/edit?usp=sharing) | [[예시 2]](https://docs.google.com/document/d/1FmxTZvmrroOW4uZ34Xfyyk9ejrQNx6gtsB6k7zOvHYE/edit?usp=sharing)
