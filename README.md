# 자동차 경주: 기능 요구사항
주어진 기능 요구사항에서 논의를 통해 몇 가지의 요구사항이 추가되었습니다.

- [ ] 주어진 횟수 동안 n대의 자동차는 전진 또는 멈출 수 있다. 단, n은 1 이상의 정수이다.
- [ ] 각 자동차에 이름을 부여할 수 있다.
- [ ] 전진하는 자동차를 출력할 때 자동차 이름을 같이 출력한다. 나아간 정도는 `-`의 개수로 나타낸다.
- [ ] 자동차 이름은 쉼표(,)를 기준으로 구분하며 이름은 5자 이하만 가능하다. 이름은 공백이 될 수 없다.
- [ ] 사용자는 몇 번의 이동을 할 것인지를 입력할 수 있어야 한다. 이동 횟수는 1 이상 100 이하의 정수이다.
- [ ] 전진하는 조건은 0에서 9 사이에서 random 값을 구한 후 random 값이 4 이상일 경우 전진하고,
  3 이하의 값이면 멈춘다.
- [ ] 자동차 경주 게임을 완료한 후 누가 우승했는지를 알려준다. 우승자는 한 명 이상일 수 있다.
- [ ] 유효하지 않은 입력값을 받은 경우, `[ERROR]`로 시작하는 오류 메시지를 출력한 뒤, 해당 부분부터 다시 입력받는다.
