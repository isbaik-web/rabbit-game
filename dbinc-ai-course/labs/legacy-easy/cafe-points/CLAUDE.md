# cafe-points 작업 지침

## 컨벤션

- 파이썬 이름은 영어를 써요. 함수와 변수는 snake_case, 상수는 UPPER_SNAKE_CASE, 클래스는 CapWords예요(PEP 8, Google Python 스타일 가이드).
- 등급은 `grades.py`의 `Grade` enum으로만 처리해요.
- 적립률, VIP 기준, 쿠폰 금액 같은 정책 숫자는 설정 한 곳에 둬요.
- 화면 코드는 TypeScript(`.tsx`, `.ts`)로 통일해요. 컴포넌트 안에서 다른 컴포넌트를 정의하지 않아요.
- 리팩터링은 동작을 유지해요. 수정 전후 결과를 비교하고 단계마다 커밋해요.
