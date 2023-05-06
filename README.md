# 8ボタン　IoTタイムスタンプ
ボタンを押したら、WEB上のgoogle spreadsheetに  
押したボタン番号と時間とステータス(0/1)が記録されます。  
コストパフォーマンス優先で、ESP32-C3-WROOM02-N4を使用しました。  
## Main PCB  
<img src="https://user-images.githubusercontent.com/44044800/236591860-a33f93b5-0a1a-4116-a17f-4ec67a4c1056.png" width="600px">  
## Switch PCB  
<img scr="https://user-images.githubusercontent.com/44044800/236592204-7be12f47-f304-4879-a2df-b811b6666226.png" width="800px">  
  
## spreadsheetの状態  
<img src="https://user-images.githubusercontent.com/44044800/236590864-9081fc97-92b7-49e4-a0a1-696463e1dc3f.png" width="320px">  

  
spreadsheetの設定は下記を参照。  
https://raspberry-pi.nomad-life.net/1917477/memo/esp32%e3%81%a7google%e3%82%b9%e3%83%97%e3%83%ac%e3%83%83%e3%83%89%e3%82%b7%e3%83%bc%e3%83%88%e3%81%ab%e6%9b%b8%e3%81%8d%e8%be%bc%e3%82%93%e3%81%a7%e3%81%bf%e3%82%8b/%e3%80%90arduino_ide%e3%80%91googlesheet%e3%81%ab%e6%9b%b8%e3%81%8d%e8%be%bc%e3%82%93%e3%81%a7%e3%81%bf%e3%81%9f  

（参考：https://www.haruirosoleil.com/entry/2020/02/02/101937）  
  
## arduino IDE書き込み設定  
arduino IDEの書き込み時の設定は下記。（USB-UARTブリッジ等を使わず、ESP32で内蔵USB-JTAGを使う場合）  
<img src="https://user-images.githubusercontent.com/44044800/236589669-b7789ccb-04f2-46ec-88a8-865c9b4ca2c5.png" width="560px">
