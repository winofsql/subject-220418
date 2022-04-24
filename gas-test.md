# GAS テスト

- ## スクリプトエディタを開く
  ![image](https://user-images.githubusercontent.com/1501327/164957524-3774be3d-ddb3-4e7d-ba03-0ea1c2cd5ed8.png)
  - 保存してから実行
  ![image](https://user-images.githubusercontent.com/1501327/164957537-e32d3d6a-6ee5-43aa-9c42-f2c1facd2333.png)
```javascript
function myFunction() {
  
  Logger.log("こんにちは世界");
  Logger.log("テストです");
  
  var now = new Date();
  GmailApp.sendEmail("メールアドレス", "件名", "本文\r\n " + now.toString());

}
```

- ## 初回実行は権限の確認が行われる
  ![image](https://user-images.githubusercontent.com/1501327/164895034-69d11368-7846-42d9-b411-44599d15ab27.png)\
  ![image](https://user-images.githubusercontent.com/1501327/164895058-c1e7c481-a9e5-4390-87fa-49cd33e15748.png)\
  ![image](https://user-images.githubusercontent.com/1501327/164895105-5d0e72e2-47a8-4365-ad2f-151a596a9a3e.png)\
  ![image](https://user-images.githubusercontent.com/1501327/164957556-eb7a250e-18b4-441e-8a68-e0ebb3670c82.png)


