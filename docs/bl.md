# 解鎖、上鎖bootloader

## ***可能造成資料遺失！！！***
## ***可能造成資料遺失！！！***
## ***可能造成資料遺失！！！***  

## 使用 EAF 解鎖 bootloader（僅適用與Google提供的解鎖方式相同者）
1. 打開設定>關於手機>點擊版本號碼7次
2. 輸入密碼啟用開發人員選項
3. 回到設定首頁>系統>開發人員選項
4. 開啟允許 OEM 解鎖
5. 輸入密碼
6. 重啟到 bootloader 或 fastboot 模式 
7. 7a 在EAF中找到 fastboot flashing，選擇 unlock，點擊開始
    
    7b 在EAF中找到 fastboot oem，選擇 unlock，點擊開始

8. 依照手機提示操作

## 使用 EAF 上鎖 bootloader（僅適用與Google提供的解鎖方式相同者）
1. 重啟到 bootloader 或 fastboot 模式
2. 2a 在EAF中找到 fastboot flashing，選擇 lock，點擊開始
    
    2b 在EAF中找到 fastboot oem，選擇 lock，點擊開始
3. 依照手機提示操作