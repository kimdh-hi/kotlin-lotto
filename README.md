# kotlin-lotto

## 로또 (자동)

### 요구사항
- [ ] 로또 구입 금액을 입력하면 구입 금액에 해당하는 로또를 발급한다.
  - 로또 1장의 가격은 1000원이다.
- [ ] 당첨 번호를 입력받는다.
- [ ] 당첨 통계를 계산한다.
  - 3개 일치: 5_000원
  - 4개 일치: 50_000원
  - 5개 일치: 1_500_000원
  - 6개 일치: 2_000_000_000원
- [ ] 수익률을 계산한다.
  - 로또 구매액을 기준치로 1로 설정하여 계산한다.


---

## 문자열 덧셈 계산기

### 요구사항
- [x] 쉼표(,) 또는 콜론(:)을 구분자로 가지는 문자열을 전달하는 경우 구분자를 기준으로 분리한 각 숫자의 합을 반환한다.
- [x] 앞의 기본 구분자(쉼표, 콜론) 외에 커스텀 구분자를 지정할 수 있다.
  - [x] 커스텀 구분자는 문자열 앞부분의 “//”와 “\n” 사이에 위치하는 문자를 커스텀 구분자로 사용한다.
  - [x] 예를 들어 “//;\n1;2;3”과 같이 값을 입력할 경우 커스텀 구분자는 세미콜론(;)이며, 결과 값은 6이 반환되어야 한다.
- [x] 문자열 계산기에 숫자 이외의 값 또는 음수를 전달하는 경우 RuntimeException 예외를 throw 한다.

---