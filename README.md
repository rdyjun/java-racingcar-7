# java-racingcar-precourse

## 🚀 기능 목록

### 🏁 CarRacing 객체

- [x] 자동차 이름에 대한 입력 힌트를 출력한다.
- [ ] 자동차 정보를 저장한다.
  - [ ] 자동차 이름을 입력받는다.
  - [ ] 쉼표를 기준으로 이름을 나눈다.
  - [ ] 각 이름의 유효성을 검사한다.
    - [ ] ⚠️ 이름은 5글자 이하이다.
    - [ ] 유효하지 않을 경우 `IllegalArgumentException`을 발생시킨다.
  - [ ] 각 이름을 토대로 Car 인스턴스를 생성한다.
    - [ ] 각 자동차 인스턴스를 멤버 변수로 저장한다.
- [ ] 이동할 횟수에 대한 입력 힌트를 출력한다.
- [ ] 이동할 횟수를 입력받는다.
  - [ ] 이동할 횟수를 멤버 변수로 저장한다.
- [ ] 자동차의 수 만큼 Random 값을 생성한다.
- [ ] 순서대로 자동차의 위치를 이동시킨다.
- [ ] 이전 과정을 이동할 횟수만큼 반복한다.
- [ ] 각 자동차의 위치를 출력한다.
- [ ] 각 자동차의 위치 중 가장 큰 값을 찾는다.
- [ ] 가장 큰 값을 가진 자동차의 이름을 출력한다.

### 🏎️ Car 객체

- [ ] 생성자 메소드에서 이름을 입력받아 멤버변수에 저장한다.
- [ ] 생성자 메소드 실행 시 위치를 0으로 초기화한다.
- [ ] 전진 값을 입력받아 위치를 업데이트한다.
- [ ] 자신의 위치를 출력한다.
