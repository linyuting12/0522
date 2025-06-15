## 互動場景設計

| **情境模擬** | **互動描述** |
|--------------|---------------|
| **劇荒** | 莫生人找不到想看的劇，說或輸入“No shows to watch”。1.3吋OLED顯示開心機器人與文字“Try Stranger Things!”，根據科幻偏好推薦，震動馬達短震1秒。按「確認/開始」按鈕確認選擇，OLED顯示“Enjoy the show!”。 |
| **無聊** | 莫生人感到無聊，說或輸入“I’m bored”。OLED顯示笑臉機器人與文字“Play a maze game or listen to music? Press OK!”，震動馬達短震1秒。按「確認/開始」按鈕啟動迷宮遊戲（與AI對戰，OLED顯示簡易迷宮，使用「左/右」按鈕移動）或音樂建議（如“Try some pop hits!”）。若選擇遊戲，OLED顯示迷宮路徑（如“X”為玩家，“O”為AI），玩家與AI競賽到達終點，贏時顯示“Winner!”，震動馬達短震1秒；輸時顯示“AI wins! Try again?”，震動馬達長震2秒。 |
| **久坐** | 距離感測器（HC-SR04）偵測莫生人靜止超過45分鐘（<30cm無移動）。OLED顯示站立機器人與文字“Time to stretch! Take a break!”，震動馬達長震2秒。按「確認/開始」按鈕確認休息，OLED顯示“Nice move! Relax!”，震動馬達短震1秒。 |
| **聊天** | 莫生人隨時說或輸入“How’s it going?”，OLED顯示笑臉機器人與文字“Pretty chill! How’s your day?”，震動馬達短震1秒。若輸入“I feel lonely”，OLED顯示關心機器人與文字“I’m here! Wanna chat or play?”，震動馬達短震1秒，提供情緒支持。 |