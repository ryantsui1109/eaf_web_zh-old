# 取得 fastboot 中儲存的變數
## 取得 fastboot 中儲存的變數
- 所有變數 
  - 列出 fastboot 中所有儲存的變數
- currnt-slot
  - 若為AB分區，則打印當前所在分區（結果為A或B）
- unlocked
  - 打印出 BootLoader 是否已經解鎖
- is-userspace
  - 若為 VAB 分區，打印出是否處於用戶空間 fastboot，只有用戶空間 fastboot 下才可存取 super 分區中的鏡像，如 system, vendor 等
- anti
  - 打印小米的防回滾數值，欲刷入 ROM 的 anti 值 >= 手機中的 anti 值時才可刷入
- 其他變數
  - 請自行輸入欲查看者