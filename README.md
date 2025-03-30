# 特選簡章 Discord 通知

每小時去 [甄戰](https://www.reallygood.com.tw/newExam/inside?str=932DEFBF9A06471E3A1436C3808D1BB7) 看一下簡章有沒有更新。

> [!NOTE]
> 畢竟已經特選完了，這個 Repo 先 Archive 了。如果之後還想要使用可以自行 fork 並修改原始碼裡的網址跑看看。
> 
> 如果你想特選的話也許你會想看看我的[部落格文章](https://emtech.cc/tag/特殊選才)？

![demo](demo.png)

## 如何使用

1. **留下一顆星星**。你懂的。
2. **Fork 這個專案**，右上角那個。
3. **設定 Secrets**
   
   在你的專案頁面點選 `Settings` -> `Secrets` -> `actions` -> `Repository secrets`，新增 Secrets：
   - `WEBHOOK_URL`: Discord Webhook URL。請到你的 Discord 伺服器設定 --> 整合 --> Webhook --> 新 Webhook，複製 Webhook URL。
