# java-calculator-precourse

## 기능 목록 
___
### 입력
- 사용자로부터 구분자와 양수로 구성된 문자열을 입력받는다.
  - 사용자가 입력하는 값은 `camp.nextstep.edu.missionutils.Console`의 `readLine()`을 활용한다.
  - 기본 구분자(쉼표, 콜론) 외에 커스텀 구분자를 기준으로 분리한다.
    - 커스텀 구분자는 문자열 앞부분의 "//"와 "\n" 사이에 위치하는 문자를 커스텀 구분자로 사용한다.
  - 예외 : 기본 구분자(쉼표, 콜론), 커스텀 구분자가 아닌 경우
- 예외 처리 : `IllegalArgumentException`을 발생시킨 후 애플리케이션을 종료한다.

### 출력
  - 분리한 각 숫자의 합을 반환한다.
  - 빈 문자열은 0으로 출력한다.
