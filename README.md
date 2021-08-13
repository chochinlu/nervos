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

![Screen Shot 2021-08-12 at 15 51 08](https://user-images.githubusercontent.com/1825273/129179485-0a9b9836-8b99-4ef4-a38d-fa376f9992eb.png)


5. The SUDT ID from the console output after executing the deposit script (in text format).

1926

## Task 5

1. A screenshot of the console output immediately after deploying smart contract.

![Screen Shot 2021-08-12 at 18 29 53](https://user-images.githubusercontent.com/1825273/129183196-2dd7797a-dda9-4ef1-a680-54715684902f.png)


2. The address of the ERC20 Proxy Contract you deployed (in text format).

```
0x9E9A3B134aB2E20ab9aDf07BaF3a718f6fA25D64
```

3. A screenshot of the console output immediately after checking your SUDT balance.

![Screen Shot 2021-08-12 at 18 36 13](https://user-images.githubusercontent.com/1825273/129183273-ace4b513-0467-4765-ba18-e7de4b151873.png)


4. The Ethereum address that was checked (in text format).

```
0x4BA7d69ab5eb67ba6d5edc7f2d0216A448E94f87
```

## Task 6

1. A screenshot of the console output immediately after you have successfully generated your Deposit Receiver Address.

![Screen Shot 2021-08-13 at 15 26 46](https://user-images.githubusercontent.com/1825273/129321400-d2d4f621-9691-4a71-ad96-593daf613d72.png)

2. Your Deposit Receiver Address (in text format).

```
ckt1q3dz2p4mdrvp5ywu4kk5edl2uc4p03puvx07g7kgqdau3n3dmypkqnxzuefxyp9wdghglncj77k5wt6p59sx6kukyjlwh5s467qgp8m25yqqqqqsqqqqqvqqqqqfjqqqqpyt39x9h5lzuf0vemv3nmfl3qujkt9lgsa0dgynqanyzyhyp3cgs6gqqqqpqqqqqqcqqqqqxyqqqqx7asf60w8pqpte2sfcfn90fdfzxue7ff2g8sawe9wacnqat6jmygqngqqqqpxv9ejjvgz2u63w3l839aadguh5rgtqd4devf97a0fpt4uqsz0k5ja866dtt6m8hfk4ahrl95ppdfzga98cwq9rqgqqqqqqcq9ve5l3
```

3. The Ethereum address used to generate the Deposit Receiver Address (in text format).

```
0x4BA7d69ab5eb67ba6d5edc7f2d0216A448E94f87
```

4. A link to the Etherscan explorer for the successful Force Bridge transaction. This can be found on Force Bridge under History→Succeed.

link: https://rinkeby.etherscan.io/tx/0x8e3b7b2974dc1cad9c97045c0a8067a33d9cdc1c0bb2a7922569c773b979203b


5. A link to the Nervos explorer for the successful Force bridge transaction. This can be found on Force Bridge under History→Succeed.

link: https://explorer.nervos.org/aggron/transaction/0x7774a7af35d6bae948291d3e63e529c4b6f527422c12370f925fe1b2224e662c


## Task 7

- Screenshots or video of your application running on Godwoken.

- Link to the GitHub repository with your application which has been ported to Godwoken. This must be a different application than the one covered in this guide.

- If you deployed any smart contracts as part of this tutorial, please provide the transaction hash of the deployment transaction, the deployed contract address, and the ABI of the deployed smart contract. (Provide all in text format.)
