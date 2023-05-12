# Unit Test 예시 프로젝트 - Cafe Kiosk

## 1. 사용 기술
- SpringBoot 2.7.7
- H2 Database
- Spring Data JPA

## 2. 요구사항
- 주문 목록에 음료 추가/삭제 기능
- 주문 목록 전체 지우기
- 주문 목록 총 금액 계산하기
- 주문 생성하기
- 한 종류의 음료 여러 잔을 한번에 담는 기능
- 가게 운영 시간(10:00~22:00) 외에는 주문을 생성할 수 없다
- 키오스크 주문을 위한 상품 후보 리스트 조회 하기
  - 상품의 판매 상태 : 판매중, 판매보류, 판매 중지
    -> 판매중, 판매보류인 상태의 상품을 화면에 보여준다.
  - 필요한 값 : id, 상품 번호, 상품 타입, 판매 상태, 상품 이름, 가격

