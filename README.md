# Ether Transfer

Safely transfer your ETH/ETC without split. 

## Watch Contract

Watch our contract to deal with it:

### Ether Transfer on both chains

Address: [0xb6Db69e99f7E3ccB352FaBde7D98A8FAe0De4297](https://etherscan.io/address/0xb6Db69e99f7E3ccB352FaBde7D98A8FAe0De4297)

<img src="https://etcrelay.github.io/images/contents/ether-transfer-address.png">

### ABI (JSON Interface)
 
```javascript
[{"constant":false,"inputs":[],"name":"WithDraw","outputs":[{"name":"","type":"bool"}],"type":"function"},{"constant":false,"inputs":[{"name":"ETHAddress","type":"address"}],"name":"SendETH","outputs":[{"name":"","type":"bool"}],"type":"function"},{"constant":true,"inputs":[],"name":"IsEthereum","outputs":[{"name":"","type":"bool"}],"type":"function"},{"constant":false,"inputs":[{"name":"ETCAddress","type":"address"}],"name":"SendETC","outputs":[{"name":"","type":"bool"}],"type":"function"},{"inputs":[],"type":"constructor"},{"anonymous":false,"inputs":[{"indexed":true,"name":"From","type":"address"},{"indexed":true,"name":"To","type":"address"},{"indexed":false,"name":"Value","type":"uint256"}],"name":"ETHTransfer","type":"event"},{"anonymous":false,"inputs":[{"indexed":true,"name":"Return","type":"address"},{"indexed":false,"name":"Value","type":"uint256"}],"name":"ETCReturn","type":"event"},{"anonymous":false,"inputs":[{"indexed":true,"name":"From","type":"address"},{"indexed":true,"name":"To","type":"address"},{"indexed":false,"name":"Value","type":"uint256"}],"name":"ETCTransfer","type":"event"},{"anonymous":false,"inputs":[{"indexed":true,"name":"Return","type":"address"},{"indexed":false,"name":"Value","type":"uint256"}],"name":"ETHReturn","type":"event"}]
```

<img src="https://etcrelay.github.io/images/contents/watch-contract.png">

## Send ETH

<img src="https://etcrelay.github.io/images/contents/send-eth.png">

*SendETC is available but your cannot use it on ETH chain.*

## Send ETC

<img src="https://etcrelay.github.io/images/contents/send-etc.png">

*SendETH is available but your cannot use it on ETC chain.*

## Example

### ETH

<img src="https://etcrelay.github.io/images/contents/eth-transfer.png">

### ETC

<img src="https://etcrelay.github.io/images/contents/etc-transfer.png">

## Donate

I'd like it (ETC and ETH are accepted) : *0xf79B6AF78E962eFFBb3fCC197911f1e0DC6A91B8*