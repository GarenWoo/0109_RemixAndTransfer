# 练习题（01.09）

![IMG0_Task](./0109_RemixAndTransfer/images/IMG0_Task.png)

## 安装 Metamask、并创建好账号、向同桌的地址执⾏⼀次转账

![IMG1_Metamask](./0109_RemixAndTransfer/images/IMG1_Metamask.png)

**区块链网络：**

Ethereum Goerli Testnet

**接收者（同桌 CH）地址：**

0xd69a6C7B90ffC279E6faeD97aD7E5eCeceCF6B57

**交易 URL：**

https://goerli.etherscan.io/tx/0x6fc24e590792e57f4b668e7ec0cf8bec0034d5a747419f693a3f96ceae77046e

![IMG2_Tx](./0109_RemixAndTransfer/images/IMG2_Tx.png)

## 使⽤ Remix 创建⼀个Counter合约并部署到测试⽹:

#### 要求：Counter 合约添加⼀个 add(x) ⽅法

```solidity
//SPDX-License-Identifier: MIT
pragma solidity ^0.8.0;

contract Counter {
	uint public counter;
	
	constructor() {
		counter = 0;
	}
	
	function count() public {
		counter += 1;
	} 
	
	function add(uint x) public {
		counter += x;
	}
}
```

**部署网络：**

Ethereum Goerli Testnet

**已部署合约 URL：**

https://goerli.etherscan.io/address/0x0faf332fd35c3dccdb3ba96ce351d8587aa387de#code
