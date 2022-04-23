# GAS テスト

- ## スクリプトエディタを開く
  ![image](https://user-images.githubusercontent.com/1501327/164894727-ee55e785-fb41-41fe-b819-d514564b5045.png)
  - 保存してから実行
  ![image](https://user-images.githubusercontent.com/1501327/164894929-24533e8e-bef8-4747-b1f9-845bce6a5da2.png)
```javascript
function myFunction() {
  
  Logger.log("こんにちは世界");
  Logger.log("テストです");
  
  var now = new Date();
  GmailApp.sendEmail("メールアドレス", "件名", "本文\r\n " + now.toString());

}
```


