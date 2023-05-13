## Pragmas

<br>

*Pragma?*

> pragma는 특정 컴파일러 기능 또는 검사를 활성화하는 데 사용됩니다. 

<br>

##### Pragma
---

Solidity에서 pragma는 계약을 컴파일하는데 사용하는데 사용될 `컴파일러의 버전을 특정`하는데 필요한 컴파일러 지시어입니다. 

pragma 문은 Solidity 계약 파일의 시작 부분에 배치됩니다.

pragma 지시문은 항상 소스 파일에 로컬이므로, 전체 프로젝트에서 활성화하려면 `모든 파일에 pragma를 추가해야 합니다`.


<br>

<br>

#### Version Pragma 

---

```solidity
pragma solidity ^0.8.0;

pragma solidity >=0.4.0 <0.9.0;
```

첫번째 줄의 ^ 는 0.8.0 이상 0.9.0 미만의 Solidity 버전을 사용하여 계약을 컴파일할 수 있음을 나타냅니다. 즉, 0.8.1, 0.8.2 등과 같은 범위 내에서 호환 가능한 컴파일러 버전을 사용하여 계약을 컴파일할 수 있습니다.

두 번째 줄은 소스 코드가 Solidity 버전 0.4.0을 포함해 0.9.0까지의 버전으로 작성되었음을 알려주는 pragma 지시문입니다.


<br>

<br>

<br>

##### [참고 자료]

- [docs.soliditylang](https://docs.soliditylang.org/en/develop/layout-of-source-files.html#import)
- [Solidity - Basic Syntax](https://www.tutorialspoint.com/solidity/solidity_basic_syntax.htm)
