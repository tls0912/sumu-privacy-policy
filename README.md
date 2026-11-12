# sumu 隱私政策

本儲存庫只提供 sumu 的公開隱私政策頁面，不包含應用程式原始碼、使用者內容或憑證。

公開網址：https://tls0912.github.io/sumu-privacy-policy/

GitHub Pages 來源：`main` 分支的根目錄。`index.html` 為完整頁面，不需要建置工具或外部資源。

聯絡入口：[GitHub Issues](https://github.com/tls0912/sumu-privacy-policy/issues)。留言公開，請勿提供 Token 或私人資料。

2026-11-12 更新：政策同時涵蓋本機發文與私人 ChatGPT Sites MCP 雲端發文。兩種模式都須先預覽，再由使用者明確確認發布。私人信箱不公開。

雲端模式使用 Sites 託管的 Cloudflare Workers，D1 保存身分、完整預覽文字、狀態及發布／去重紀錄；R2 保存照片原始內容，不主動移除 EXIF。App Secret 與舊版 Page Token 使用 Sites 後端秘密設定管理。Meta 連線模式的 User／Page Token 加密後存入 D1，另保存期限與短期 OAuth state 驗證紀錄。憑證更新不會自行發布文章。預覽建立 24 小時後失效；失效不代表資料已刪除。去重紀錄與貼文 ID 持續保存。

發布前核對：草稿及照片的實際留存與刪除機制仍須與後端實作核對。目前政策不承諾自動清除期限、自助刪除介面或固定刪除完成期限。若後端提供清除機制或改變資料欄位，須先同步政策。此目錄的文字更新不代表已完成遠端發布或部署驗收。
