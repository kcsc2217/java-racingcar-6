# 기능 목록
- [O] : 자동차에 입력할 이름을 부여한다: CarNamedSet.class
	-> 예외 처리는 클래스를 만들어서 처리 
- [O] : 자동차 기능 초기화 : CarFuctSet.class
	-> [O] : 자동차가 몇 번의 이동을 할 것인지를 입력한다 
	-> [O] : 전진하는 조건 0에서 9 사이에서 무작위 값을 구한 후 무작위 값이 4 이상일 경우 
	-> [O] : 4이상인 경우 "-" 리턴
	-> [O] : 자동차의 전진 출력 
- [O] : 게임 실행 결과 : PrintResult.class
- [O] : 게임 실행 : CarGameStart.class
     	-> 횟수대로 입력 결과 출력
	-> 최종 우승자 색출: 우승자
- [O] : 예외 처리 클래스 : Validation.class
	-> (예외) : 자동차 이름의 유효성을 검사합니다. 이름이 5자 이상인 경우 예외를 발생시킵니다.
	-> (예외) : 자동차 이름 형식의 유효성을 검사합니다. 이름이 쉼표(,)로 구분되지 않으면 예외를 발생시킵니다.





#기능 요구사항 

초간단 자동차 경주 게임을 구현한다.

- 주어진 횟수 동안 n대의 자동차는 전진 또는 멈출 수 있다.
- 각 자동차에 이름을 부여할 수 있다. 전진하는 자동차를 출력할 때 자동차 이름을 같이 출력한다.
- 자동차 이름은 쉼표(,)를 기준으로 구분하며 이름은 5자 이하만 가능하다.
- 사용자는 몇 번의 이동을 할 것인지를 입력할 수 있어야 한다.
- 전진하는 조건은 0에서 9 사이에서 무작위 값을 구한 후 무작위 값이 4 이상일 경우이다.
- 자동차 경주 게임을 완료한 후 누가 우승했는지를 알려준다. 우승자는 한 명 이상일 수 있다.
- 우승자가 여러 명일 경우 쉼표(,)를 이용하여 구분한다.
- 사용자가 잘못된 값을 입력할 경우 IllegalArgumentException을 발생시킨 후 애플리케이션은 종료되어야 한다.



# 추가 요구사항
- indent(인덴트, 들여쓰기) depth를 3이 넘지 않도록 구현한다. 2까지만 허용한다.
- 예를 들어 while문 안에 if문이 있으면 들여쓰기는 2이다.
- 힌트: indent(인덴트, 들여쓰기) depth를 줄이는 좋은 방법은 함수(또는 메서드)를 분리하면 된다.
- 3항 연산자를 쓰지 않는다.
- 함수(또는 메서드)가 한 가지 일만 하도록 최대한 작게 만들어라.


# Car 클래스를 자료형 처럼 사용하기 ex: List<Car> 

# 사용자가 잘못된 값을 입력할 경우 IllegalArgumentException을 발생시킨 후 애플리케이션은 종료되어야 한다.
 - 따로 예외클래스 만들어서 처리

   
