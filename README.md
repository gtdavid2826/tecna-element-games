# TECNA 元素遊戲中心 — 豪華雲端部署版

## 內容
- index.html：遊戲入口
- element-battle.html：元素大作戰（豪華視覺 + Supabase 雲端排行榜）
- element-shootout.html：元素神槍手（豪華視覺 + Supabase 雲端排行榜）
- assets/：gzip 壓縮資料分段，瀏覽器啟動時自動還原完整豪華版
- vercel.json：Vercel 靜態部署設定

## 架構
GitHub 保存版本 → Vercel 提供公開遊戲網址 → Supabase 儲存全體學生共用排行榜。

Supabase 已寫入遊戲，不需另設環境變數。