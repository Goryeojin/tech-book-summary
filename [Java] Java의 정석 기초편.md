# Java의 정석 기초편 핵심 개념 정리

<img src="https://github.com/user-attachments/assets/722ece1b-793b-4d03-9c78-a07559b2c449" width="200px" height="300px" title="Github_Logo"/>   

### [ch1] 자바의 특징
      - 운영체제에 독립적이다.
      자바가상머신(JVM)이 자바 응용프로그램으로부터 전달 받은 명령을 해당 운영체제가 이해할 수 있도록 변환하여 전달한다.
      Write once, run awaywhere

      - 객체지향 언어
      OOP의 특성인 상속, 캡슐화, 다형성을 갖고 있다.

      - 자동 메모리 관리. Garbage Collection
      가비지 컬렉터가 자동적으로 메모리를 관리하여 개발자의 수고를 덜 수 있다.

      - multi-thread 지원

      - 동적 로딩 지원

### [ch1] 자바 가상 머신 JVM
      - OS -> JVM -> Java Application을 거쳐 실행됨
      - JVM은 OS 종속적

### [ch2] 상수와 리터럴
      - 상수(constant)는 '값을 저장할 수 있는 공간'이지만,
      초기화 후 다른 값으로 변경할 수 없는 불변의 값이다.
      ex) fianl int MAX_VALUE = 10;
      final 키워드를 붙여 사용한다.

### [ch2] 기본형과 참조형
      - 기본형(primitive type)
      논리형(boolean), 문자형(char), 정수형(byte, short, int, long), 실수형(float, double)

      - 참조형(reference type)
      객체의 주소를 저장하는 기본형을 제외한 나머지 타입
