# Pet-shop dapp Custom
BlockChain lecture in Korea Aerospace University

pet-shop dapp은 Truffle에서 제공하는 Tutorial dapp이다

#Custom 내용
1. Smart contract인 Adoption.sol 작성
   - adopt함수를 이용하여 입양을 할수 있게끔 설정
   - getAdopters함수를 이용하여 입양해간 계좌주소를 볼 수 있음

2. 간단한 웹작업
   - 기존 강아지 pet-shop이었는데 유기묘 입양시설으로 변경

3. 웹에서 Adopt버튼을 누를 시 전송할 ether설정 가능
   - 많은 pet-shop 오픈소스들과 다른 점으로 app.js - handleAdopt 함수에서 contract call을 할 때 Transaction을 넘겨주는 방식으로 채택
