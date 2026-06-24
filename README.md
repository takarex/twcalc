# 台灣免費財務計算工具集合站

六大免費計算器，幫台灣人看清每一個財務決定的真實數字。

## 包含工具
- 🏠 **房貸試算（進階）** — 月付金、總利息、提前還款vs投資效益、寬限期代價
- 💼 **跳槽加薪試算** — 含通勤費、年終差異、年資損失、5/10年累積比較
- 🧾 **綜合所得稅試算** — 自動比較標準vs列舉扣除，附稅率級距表
- 🚗 **買車總持有成本** — 折舊+利息+油費+停車+保險+稅費，支援電動車
- 🌅 **退休金缺口計算** — 含通膨調整、勞保月退、投資複利
- ⚖️ **租屋vs買房** — 含頭期款機會成本、裝潢費、房價漲幅比較

## 技術特色
- 純靜態 HTML，**零運行成本**（僅需網域費約 400 元/年）
- 所有計算在瀏覽器完成，不蒐集任何個人資料
- 深色模式自動支援
- 手機版響應式設計
- Google AdSense 廣告位預留
- SEO 優化（標題、描述、Schema.org 結構化資料）

## 部署到 Vercel（免費）

### 方式一：GitHub + Vercel（推薦）
1. 到 github.com 建立免費帳號
2. 新增 repository（如 `twcalc`）
3. 上傳 `index.html` 和 `vercel.json`
4. 到 vercel.com，用 GitHub 登入，點 New Project
5. 選你的 repository，直接 Deploy
6. 幾秒內完成，獲得免費網址如 `twcalc.vercel.app`

### 方式二：Vercel CLI（更快）
```bash
npm i -g vercel
cd 你的資料夾
vercel
```

## 加入 Google AdSense
1. 到 adsense.google.com 申請帳號（需網站有一定內容才會核准）
2. 取得 Publisher ID（格式：ca-pub-XXXXXXXXXXXXXXXX）
3. 搜尋 index.html 中三處 `ca-pub-XXXXXXXXXXXXXXXX` 並替換
4. 搜尋 `<div class="ad-box">` 並改為 AdSense 程式碼
5. 重新部署

## 每年費率更新（約 1–2 月）
搜尋以下數值並更新：
| 項目 | 搜尋字串 | 更新時機 |
|------|---------|---------|
| 免稅額 | `97000` | 每年公告 |
| 標準扣除額 | `131000` | 每年公告 |
| 薪資扣除額上限 | `218000` | 每年公告 |
| 牌照稅（1600cc）| `7120` | 不常改 |
| 牌照稅（2400cc）| `11230` | 不常改 |

## 自訂網域
1. 購買 `.tw` 網域（推薦：GoDaddy、Cloudflare、Gandi），約 NT$ 400–800/年
2. 在 Vercel 專案設定中加入 Custom Domain
3. 依指示設定 DNS 即完成
