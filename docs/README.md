# 미션 - 자판기

## 🔍 구현할 기능 목록

---

### 입력
  - `자판기 보유 금액`을 입력받는다.
    - **[예외]** : 자판기 보유 금액은 10원 이상이어야한다.
    - **[예외]** : 자판기 보유 금액은 10원 단위로 잘려야한다.
    - **[예외]** : 보유 금액은 숫자여야 한다.

  - `상품과 가격, 수량` 을 입력 받는다.
  - `투입 금액` 을 입력 받는다.
    - **[예외]** : 투입 금액은 상품의 최솟값보다 커야한다. 
  - `구매할 상품` 을 입력 받는다.

### 기능
  - 최초에 자판기 보유 금액 들어오면, 해당 금액 만큼 `랜덤으로 동전을 생성`한다.
  - `음료를 구매`한다. 
  - `남은 잔돈을 계산`한다.
  - `음료를 더 구매할 수 있는지 확인`한다.
    - `있을 경우` 1,2,3 을 반복
    - `없을 경우` (남은 금액이 살수 있는 제품 최저가 보다 적거나, 상품 수량이 0 일 경우)
      - `최소 동전 갯수로 잔돈을 반환`한다.
  
### 출력
  - `입력 안내문`을 `내림차순`으로 출력한다.
  - `보유한 동전`을 출력한다.
  - `현재 남아있는 금액`을 출력한다.
  - `잔돈`을 출력한다.

