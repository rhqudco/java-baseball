# 미션 - 숫자 야구의 기능 구현 목록
1. 숫자 야구 게임을 시작하는 기능을 구현하자.
    1. 위 기능에는 다음과 같은 기능이 있을 것 이다.
        1. 게임 시작 문구 출력
        2. 중복되지 않는 세 자리의 랜덤한 숫자를 생성 후, 반환하는 기능.
2. 사용자가 문자를 입력하는 메소드를 만들자.
   1. 예외 사항이 발생하면 예외를 발생시키는 기능을 만들자.
      1. 예외 사항 목록은 다음과 같다.
         1. 3자리가 아닌 숫자
         2. 문자 입력(세상 모든 언어를 막을 수 없기에 특수문자, 영어, 한글로 제한)
         3. 0이 들어갈 경우
         4. 중복된 값이 입력될 경우
3. 숫자를 비교하기 위해 입력한 숫자를 자릿수마다 잘라서 반환하는 기능을 만들자.
4. 숫자를 비교하는 기능을 만들자.
   1. 숫자를 입력한다.
   2. 각 결과에 따라 스트라이크, 볼 `count`를 반환한다.
   3. 정답을 맞추면 6번을 수행한다.
5. 숫자를 비교하는 기능을 통해 반환된 `count`를 통해 해당 내용을 출력해준다.
   1. 스트라이크와 볼이 혼재하면 __볼을 먼저 알려__주고 스트라이크를 알려준다.
   2. 스트라이크, 볼 `count` __모두 0이면 낫싱을 출력__한다.
6. 정답을 맞추면 게임을 새로 시작할지, 종료할지 입력 받아 사용자의 요구에 맞게 다시 동작한다.
   1. 1번을 입력해서 새로 시작하면 다시 숫자 야구 게임을 시작
   2. 2번을 입력해서 종료하면 프로그램을 종료한다.
   3. 1, 2 외의 값을 입력하면 예외 발생