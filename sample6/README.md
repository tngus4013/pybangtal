# pybangtal_sample6
##프로젝트
방탈출 게임(중급)
## 중요사항
- 이 프로그램의 소스 코드는 방탈 게임서버 버전 0.2.0.0에서 작성되었습니다.
- 만약 빌드 오류가 발생하실 경우, 방탈 라이브러리의 버전이 0.1.0.0인지 확인해주시길 바랍니다.
- sample 폴더 내의 image 폴더에 이미지를 모두 포함하여야만 프로그램을 시작할 수 있습니다. (개발자들은 이미지를 변경 또는 추가하여 개발할 수 있습니다.)

## 개요
- 방탈 라이브러리를 이용해 제작한 방탈출 게임입니다.

## 게임 설명
- 방 문을 열어 탈출하는 게임입니다.

## 게임 조작
- 모든 게임 조작은 마우스 클릭으로 이루어집니다.

##함수 설명
- def onMouseAction_door1(x, y, action) : door1 객체의 callback 함수

- def onMouseAction_door2(x, y, action) : door2 객체의 callback 함수

- def onMouseAction_door3(x, y, action) : door3 객체의 callback 함수

- def onMouseAction_key(x, y, action) : key 객체의 callback 함수

- def onMouseAction_flowerpot(x, y, action) : flowerpot 객체의 callback 함수

- def onMouseAction_keypad(x, y, action) : keypad 객체의 callback 함수

- def onKeypad() : keypad를 해결한 경우에 호출되는 callback 함수

- def onMouseAction_clock(x, y, action) : 시계 객체의 callback 함수
