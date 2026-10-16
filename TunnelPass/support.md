# 隧行 TunnelPass 支援與常見問題（App Support & FAQ）

感謝您使用「隧行 TunnelPass」！若您遇到問題、想回報錯誤或有功能建議，請先參考下方常見問題，或直接來信聯絡我們。

## 常見問題（FAQ）

**Q1：這個 App 在做什麼？**
答：用交通部高速公路局公開的車輛偵測器與即時影像資料，顯示國道隧道各車道的車速、前方車輛數、預估通過時間、前方壅塞起點與車流趨勢，並建議目前較快的車道。

**Q2：目前涵蓋哪些隧道？**
答：國道 5 號雪山、彭山、石碇；國道 3 號基隆、福德、木柵、新店、蘭潭、中寮；國道 4 號豐原 1 號、豐原 3 號；國道 6 號國姓 1 號、埔里，共 13 座。之後會陸續增加。

**Q3：資料是即時的嗎？準不準？**
答：資料每分鐘更新，但高公局的偵測資料本身約有 3～4 分鐘延遲；建議車道與通過時間皆為估計值，**僅供參考**，請以現場標誌與路況為準。若兩條車道差距很小，App 會顯示「各線差不多」。

**Q4：為什麼首頁的縮圖有時比較舊，或顯示「影像過期」？**
答：清單與詳情頁的縮圖由我們的伺服器輪流更新，約每 10 分鐘一輪；超過 15 分鐘沒更新才會標示過期。點開單一攝影機會直接連線高公局，畫面是即時的。若影像一直載入不出來，通常是高公局串流暫時限流，App 會自動重連。

**Q5：語音提醒怎麼用？**
答：語音建議預設為開啟（隧道頁面右上角的喇叭圖示為綠色），可隨時點一下關閉或重新開啟。為了省電，**App 在背景超過 1 小時沒有開啟，語音提醒會自動暫停**（會有一則通知告知），再次開啟 App 就會恢復。當您朝著隧道行駛，距離入口約 3 公里、1.5 公里、800 公尺會各提醒一次；前方有壅塞時，距壅塞起點約 3 公里、1 公里也會提醒。可在 iOS「設定」確認已允許通知與定位。

**Q6：語音提醒沒有播報？**
答：請依序確認：
1. 該隧道的喇叭圖示為開啟狀態（綠色），且 iOS「設定 → 隧行 → 位置」為「永遠」或「使用 App 期間」。
2. 手機沒有靜音模式以外的限制；鎖定畫面或背景時，語音需要音訊與定位背景功能保持開啟。
3. 您必須在國道上、朝著隧道方向、時速約 20 公里以上，才會觸發提醒。
4. 隧道內沒有 GPS，兩座隧道相連時（例如雪山與彭山之間），第二座隧道的提醒會在出洞口取得定位後才播報。

**Q7：首頁為什麼知道我在哪個方向？**
答：開啟定位並正在國道上行駛時，App 會用手機的位置與行進方向，在卡片上標示「目前：往○○」，並自動把最近的隧道排在前面。位置只在手機上計算，不會上傳。

**Q8：會耗很多流量嗎？**
答：一般資料很少。單一攝影機的直連即時影像約每分鐘 5 MB，請留意行動數據用量；離開該畫面即停止。

**Q9：影像裡的車牌看得到嗎？**
答：清單與詳情頁縮圖由伺服器轉送並會模糊車牌區域；單一攝影機放大畫面是直接連線高公局的原始影像，未經本站處理。

**Q10：App 會收集或上傳我的資料嗎？**
答：不會上傳您的位置或個人資料。App 內有 Google AdMob 廣告，詳見[隱私權政策](DataPrivacy.md)。

**Q11：行車中可以操作嗎？**
答：請專心駕駛，需要查看時請在停車時進行，並遵守交通法規。

## 資料來源與聲明

顯名聲明：交通部高速公路局「交通資料庫」。本應用程式為獨立開發，並非政府機關所提供。

## 聯絡我們（Contact Us）

支援電子郵件：lee.hsien95@gmail.com

回報問題時，附上以下資訊能讓我們更快找出原因：

- 哪一座隧道、哪一個方向、大約什麼時間
- iPhone 型號與 iOS 版本、App 版本
- 問題描述或重現步驟（可附截圖）

我們會在收到來信後盡快於 1～2 個工作天內回覆。

---

# TunnelPass — Support & FAQ (English summary)

**What does it do?** It uses open data from Taiwan's Freeway Bureau to show, for freeway tunnels, per-lane speed, vehicles ahead, estimated passing time, the start of congestion ahead and a traffic trend, and suggests the currently faster lane.

**Tunnels covered (13):** National Freeway 5 — Hsuehshan, Pengshan, Shiding; Freeway 3 — Keelung, Fude, Muzha, Xindian, Lantan, Zhongliao; Freeway 4 — Fengyuan 1 and 3; Freeway 6 — Guosing 1, Puli.

**Accuracy.** Data updates every minute but the source itself lags by about 3–4 minutes. Lane advice and passing times are estimates for reference only; follow road signs and conditions.

**Voice advice.** Voice advice is on by default (the speaker icon at the top right of a tunnel page is green); tap it to turn it off or on again. While you drive toward the tunnel (about 20 km/h or faster, on the route), you are reminded at roughly 3 km, 1.5 km and 800 m; with congestion ahead, at roughly 3 km and 1 km. Allow notifications and location in iOS Settings. There is no GPS inside tunnels, so for connected tunnels the next reminder is spoken after you exit.

**Images.** List thumbnails are refreshed about every 10 minutes (marked "stale" after 15). Opening one camera connects directly to the Freeway Bureau stream (about 5 MB per minute; not processed by us, so plates are not blurred there).

**Privacy.** We do not upload your location or personal data. The app shows Google AdMob ads — see the [Privacy Policy](DataPrivacy.md).

Contact: lee.hsien95@gmail.com — please include the tunnel, direction and time, your iPhone model / iOS / app version, and a description or screenshot.
