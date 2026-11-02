# 極速狂飆

純前端 Canvas 賽車遊戲，直接開啟 `index.html`，或使用 GitHub Pages：
https://lphky.github.io/5E01_new/

方向鍵或 WASD 控制方向、煞車和氮氣；P 暫停。手機使用畫面按鈕。
遊戲進度與排行榜儲存在瀏覽器本機，介面樣式使用 Tailwind CDN。

GitHub Pages 從 `main` 分支根目錄發布。

## 2026-11-02 修正與驗證

- 修復主迴圈缺少括號導致的 `SyntaxError: Unexpected end of input`。
- 接回賽道繪製、敵車定時生成、道具、警車及特效更新。
- 重新開始時重設敵車生成計時與煞車狀態。
- 通過 Node.js 語法檢查及瀏覽器執行檢查。
- 瀏覽器驗證：開始、左右移動、定時生成敵車、碰撞結束、重新開始、暫停與繼續。
- 390 × 844 手機尺寸驗證觸控按下／放開狀態；未測試真實手機與陀螺儀。
