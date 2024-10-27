# javascript-racingcar-precourse

## 소개

초간단 자동차 경주 게임입니다.

## 입출력

- 입력

  - 자동차 이름

    - 공백은 이름으로 사용할 수 없습니다.
    - 이름은 5자 이하로 입력해주세요.
    - 2대 이상의 자동차 이름을 입력해주세요.
    - 여러 대의 이름을 입력할 경우 콤마(,)를 구분자로 사용해주세요.
    - 여러 대의 이름을 입력할 경우, 서로 다른 이름을 사용해주세요.

  - 총 이동 횟수

    - 이동 횟수는 양수로 입력해주세요. ( 음수, 소수 ,0, 공백, 문자는 X )

- 출력

  - 게임 진행

    - 자동차 이름과 각 자동차들의 이동 상태를 '-'를 사용해 출력합니다.

  - 결과값
    - 우승자 이름( 여려 명일 경우 콤마(,)로 구분됩니다 )
  - 사용자가 잘못된 값을 입력할 경우, 에러 메세지를 출력합니다.
    - "[ERROR]"로 시작하는 메시지를 출력하고 애플리케이션은 종료됩니다.

## 기능 목록

- 사용자 입력값을 검증하는 기능

- 자동차 경주 게임을 완료한 후 누가 우승했는지를 알려주는 기능

  - 우승자는 여러명일 수 있다.
  - 공동 우승인 경우 쉼표를 이용하여 구분한다.

- 자동차를 전진시키는 기능
  - 무작위 값이 4이상인 경우 전진
  - 4미만인 경우 정지

## 활용한 모듈

- @woowacourse/mission-utils에서 제공하는 Random 및 Console API를 사용.
  - Random 값 추출 : Random.pickNumberInRange()를 활용
  - 사용자의 값을 입력 및 출력 : Console.readLineAsync()와 Console.print()를 활용
