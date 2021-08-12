# nervos

## Task 0

![Screen Shot 2021-08-11 at 09 52 15](https://user-images.githubusercontent.com/1825273/128962086-5c2d67d7-36c1-48e8-8837-3fb5984fb3c5.png)


![Screen Shot 2021-08-11 at 09 52 53](https://user-images.githubusercontent.com/1825273/128962096-d1fa5292-9b0c-4aa9-b172-3958bda02e2f.png)

## Task 1

1. A screenshot of the accounts you created:

![Screen Shot 2021-08-11 at 11 37 37](https://user-images.githubusercontent.com/1825273/129129919-0436c43e-19ee-49d1-9f56-ee970075dd8d.png)

2. A link to the Layer 1 address you funded on the Testnet Explorer:

link: https://explorer.nervos.org/aggron/address/ckt1qyqpta5actjvmtlpx87dgysuvle3466hanxs9g0xu4

3. A screenshot of the console output immediately after you have successfully submitted a deposit to Layer 2.

![Screen Shot 2021-08-12 at 10 47 42](https://user-images.githubusercontent.com/1825273/129130804-92751d63-263f-4a1a-a8d4-5c6691c34177.png)


## Task 2 

1. A screenshot of the console output immediately after you have successfully deployed a smart contract.

![Screen Shot 2021-08-12 at 14 17 38](https://user-images.githubusercontent.com/1825273/129147524-bfbf5592-1b21-4b6d-86eb-aa5b9ae6597a.png)

2. The transaction hash from the contract deployment (in text format).

```
0xa13119457bc5ab67cc91ef57c0a10b048d6dfca3c7d9aed72b64386c28e2c711
```

3. The deployed contract address from the contract deployment (in text format).

```
0xa9dc32387C28CA262204EE0C7d0ABbabA4D0777E
```

## Task 3

1. A screenshot of the console output immediately after you have successfully issued a smart contract call.

![Screen Shot 2021-08-12 at 15 04 30](https://user-images.githubusercontent.com/1825273/129152665-f0472c83-45b4-4ca7-9d66-3aac8181200e.png)


2. The transaction hash from the console output (in text format).

```
0xd240ef366d989d9ad23d6777f89d58fcfa02fa6568945adedb2248d45d496223
```

3. The contract address that you called (in text format).

```
0xa9dc32387C28CA262204EE0C7d0ABbabA4D0777E
```

4. The ABI for contract you made a call on (in text format).

``` js
 [
      {
        "inputs": [],
        "stateMutability": "payable",
        "type": "constructor"
      },
      {
        "inputs": [
          {
            "internalType": "uint256",
            "name": "x",
            "type": "uint256"
          }
        ],
        "name": "set",
        "outputs": [],
        "stateMutability": "payable",
        "type": "function"
      },
      {
        "inputs": [],
        "name": "get",
        "outputs": [
          {
            "internalType": "uint256",
            "name": "",
            "type": "uint256"
          }
        ],
        "stateMutability": "view",
        "type": "function"
      }
  ]
```

## Task 4

1. A link to the Layer 1 address you funded on the Testnet Explorer.

link: https://explorer.nervos.org/aggron/address/ckt1qyqpta5actjvmtlpx87dgysuvle3466hanxs9g0xu4

2. A screenshot of the console output immediately after using sudt-cli to create your SUDT tokens on Layer 1.

![Screen Shot 2021-08-12 at 15 21 59](https://user-images.githubusercontent.com/1825273/129155352-3e3691ad-cbb0-477d-89f1-7bf45a8d597c.png)


3. A link to the transaction ID created by sudt-cli on the Testnet Explorer.

link: https://explorer.nervos.org/aggron/transaction/0x75236215959d28fe59573ce7eceb69c8829c6355a81d8a21e9e5dd32792c876b

4. A screenshot of the console output immediately after you have successfully submitted a deposit to Layer 2 using the account-cli tool.

5. The SUDT ID from the console output after executing the deposit script (in text format).
