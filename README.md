# java-calculator-precourse


# 기능 목록

1. 입력 값 처리
    - 사용자가 입력한 문자열을 Console.readLine()으로 입력받음.
    - 입력값이 비어 있으면 결과를 0으로 출력
2. 숫자와 구분자 구분
    - 기본 구분자 , 또는 :를 사용하여 입력된 문자열을 숫자로 분리
    - 입력된 값이 숫자와 구분자로만 이루어져 있는지 검증
3. 커스텀 구분자 처리
    - //로 시작하는 경우, 커스텀 구분자를 사용할 수 있도록 구현
    - 커스텀 구분자는 \\n 이후 문자열에서 사용
4. 음수 처리
    - 입력된 숫자에 음수가 포함된 경우, 예외를 발생
    - “음수가 입력되었습니다.“라는 메시지와 함께 IllegalArgumentException을 던짐
5. 숫자 형식 검증
    - 입력된 값이 숫자가 아닌 경우, 예외를 발생
    - “숫자 형식이 아닙니다.“라는 메시지와 함께 IllegalArgumentException을 던짐
6. 결과 출력
    - 입력된 숫자들을 모두 더한 후, 그 결과를 출력