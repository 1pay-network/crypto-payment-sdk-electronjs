# 1PAY.network - Crypto Payment SDK

Website: [1pay.network](https://1pay.network)

Documents: [1pay.network/documents](https://1pay.network/documents)

Full example of 1PAY.network integration for Android app

> Focus on file /index.html

```html
<!DOCTYPE html>
<html>
  <head>
    <meta charset="UTF-8">
    <title>1PAY.Network example for ElectronJS</title>
  </head>
  <body>
    <h1>1Pay.Network SDK Example</h1>
    <button onclick="onepay(0.1, 'usdt', 'example payment')">Start</button>

    <script src="./renderer.js"></script>
    <script src="https://1pay.network/onepay.js?recipient=0x8d70EC40AAd376aa6fD08e4CFD363EaC0AB2c174&network=ethereum,arbitrum,optimism,bsc&token=usdt,usdc,dai"></script>
  </body>
</html>
```
