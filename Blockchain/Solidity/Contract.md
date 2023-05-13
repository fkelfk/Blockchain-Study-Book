## Contract

<br>

*컨트랙트란?*

> Solidity의 관점에서 컨트랙트란 무수한 코드들(함수)과 데이터(상태 변수)가 Ethereum 블록체인의 특정 주소에 존재하는 것입니다. 

<br>

##### Contract

---

Solidity의 계약은 객체 지향 언어의 `클래스`와 유사합니다. 

Contract는 블록체인의 특정 주소에 있는 `코드(함수)`와 `데이터(상태 변수)`의 모음입니다.

`토큰, 스마트 계약, 분산 응용 프로그램(dApp)` 등과 같은 다양한 유형의 디지털 자산을 나타내는 데 사용할 수 있습니다. 

Solidity 프로그래밍 언어로 작성되고 `EVM(Ethereum Virtual Machine)`에서 실행할 수 있는 바이트코드로 컴파일됩니다.


<br>

<br>

#### 계약 생성하기

---

```solidity
// SPDX-License-Identifier: GPL-3.0
pragma solidity >=0.4.22 <0.9.0;

contract HelloWorld {
    // code
}
```

계약을 생성하려면 contract 키워드 뒤에 `계약이름`을 입력해 줍니다.

{} 안에 변수와 함수를 생성합니다.

<br>

<br>

<br>

##### [참고 자료]

- [docs.soliditylang](https://docs.soliditylang.org/en/v0.8.19/contracts.html)
- [What is a contract in Solidity?](https://https://www.educative.io/answers/what-is-a-contract-in-solidity.com/611)
