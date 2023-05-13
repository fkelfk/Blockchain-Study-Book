## State Variable

<br>

*State Variable?*

> 컨트랙트 상태의 일부로 블록체인에 영구적으로 저장되는 변수입니다.

<br>

##### 상태변수란?

---

상태 변수는 여러 함수 호출과 트랜잭션에서 지속되어야 하는 정보를 저장하고 관리하는 데 사용됩니다.

솔리디티는 정적으로 타입이 지정된 언어이므로 선언하는 동안 상태 또는 로컬 변수 타입을 지정해야 합니다. 선언된 각 변수에는 항상 유형에 따른 기본값이 있습니다. "undefined" 또는 "null"이라는 개념은 없습니다.

함수 호출 범위 내에서만 사용할 수 있는 로컬 변수와 달리 상태 변수는 콘트랙트 내 어디에서나 액세스할 수 있습니다. 따라서 컨트랙트의 상태를 관리하고 복잡한 로직을 구현하는 데 강력한 도구가 됩니다.

상태 변수는 블록체인에 영구적으로 저장되기 떄문에 로컬 변수에 비해 가스비 측면에서 비용이 더 높습니다.


<br>

<br>

#### 코드

---

```solidity
pragma solidity ^0.5.0;
contract SolidityTest {
   uint256 storedData;      // State variable
   constructor() public {
      storedData = 10;   // Using State variable
   }
}
```
위의 코드는 SolidityTest라는 계약을 정의합니다. 

`uint256 storedData;` storedData 변수를 상태 변수로 선언합니다. 즉, 계약 상태의 일부로 블록체인에 영구적으로 저장됩니다. 이를 통해 계약 내 어디에서나 변수에 액세스하고 수정할 수 있습니다.




<br>

<br>

<br>

##### [참고 자료]

- [docs.soliditylang](https://docs.soliditylang.org/en/develop/layout-of-source-files.html#import)
- [Solidity - Variables](https://www.tutorialspoint.com/solidity/solidity_variables.htm)
