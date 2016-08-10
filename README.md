# Ether Transfer

Safely transfer your ETH/ETC without split. 

## Watch Contract

Watch our contract to deal with it:

### Ether Transfer on both chains

<img src="https://etcrelay.github.io/images/contents/ether-transfer-address.png">

Address: [0x50491518707B238f91981849A6F241c77f948Fc8](https://etherscan.io/address/0x50491518707B238f91981849A6F241c77f948Fc8)

### ABI (JSON Interface)
 
```javascript
[{"constant":false,"inputs":[],"name":"WithDraw","outputs":[{"name":"","type":"bool"}],"type":"function"},{"constant":false,"inputs":[{"name":"ETHAddress","type":"address"}],"name":"SendETH","outputs":[{"name":"","type":"bool"}],"type":"function"},{"constant":false,"inputs":[{"name":"ETCAddress","type":"address"}],"name":"SendETC","outputs":[{"name":"","type":"bool"}],"type":"function"},{"anonymous":false,"inputs":[{"indexed":true,"name":"From","type":"address"},{"indexed":true,"name":"To","type":"address"},{"indexed":false,"name":"Value","type":"uint256"}],"name":"ETHTransfer","type":"event"},{"anonymous":false,"inputs":[{"indexed":true,"name":"From","type":"address"},{"indexed":true,"name":"To","type":"address"},{"indexed":false,"name":"Value","type":"uint256"}],"name":"ETCTransfer","type":"event"}]
```

<img src="https://etcrelay.github.io/images/contents/watch-contract.png">

## Send ETH

<img src="https://etcrelay.github.io/images/contents/send-eth.png">

*SendETC is available but your cannot use it on ETH chain.*

## Send ETC

<img src="https://etcrelay.github.io/images/contents/send-etc.png">

*SendETH is available but your cannot use it on ETC chain.*

## Example

<img src="https://etcrelay.github.io/images/contents/eth-transfer.png">

https://etherscan.io/tx/0x0bb132078852b889341489df989f05c5ac89f0ddc8f15c5c01ebcb17f2a8c235

<img src="https://etcrelay.github.io/images/contents/etc-transfer.png">

https://gastracker.io/tx/0x02a949ec4809bd58f74f256e699a4de2b5b399daa8acfecd36e695577a76b187

## Donate

I'd like it (ETC and ETH are accepted) : *0xf79B6AF78E962eFFBb3fCC197911f1e0DC6A91B8*