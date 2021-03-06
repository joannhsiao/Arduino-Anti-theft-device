# Arduino-防盜裝置
Arduino Final Project  
## Team member
> 黃姵馨, 蕭名誼

## Descrption:  
當有人靠近時 (距離小於50cm)，會亮黃燈警告，手機上也會跳出提醒有人靠近，此人可能為主人或陌生人，系統要知道是誰，所以要求輸入門禁密碼，若密碼正確，則判斷為主人，門口的燈轉為綠燈，危機即解除，大門將開啟，手機上的警訊也會消失；若密碼輸入錯誤，此人則為小偷，門口的紅燈會亮起，警報器也會啟動，以警示有小偷入侵，手機也會有警示告知主人，這樣的門禁防盜系統同時也達到遠端監控的功能，為類物聯網的概念。

!!!出了一些狀況:
我們接完線測試後發現，keypad跟blynk(esp8266)不能同時接，會一直disconnected，若兩者分開操作皆可執行，由此可見，並非code的問題，以附上兩段分別操作皆可執行之影片。
所以，若以完整性，需拿掉連接blynk的部分，內容將沒有遠端監控的功能，但門的防盜系統還是有作用的。

## 材料:  
| 物件 | Type No. | 數量 |
| :---: | :---: | :---: |
| 控制器 | Arduino UNO | 1 |
| 超音波 | SR04 | 1 |
| Wifi | ESP8266 | 1 |
| LCD | 1602 | 1 |
| Buzzer |  | 1 |
| Keypad |  | 1 |
| 燈泡	 | LED | 3 |

## Circuit
![circuit](https://github.com/joannhsiao/Arduino-Anti-theft-device/blob/main/Circuit_2.jpg)
![接腳](https://github.com/joannhsiao/Arduino-Anti-theft-device/blob/main/circuit.jpg)
