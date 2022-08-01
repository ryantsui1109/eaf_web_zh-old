# 刷入和擦除分區

## ***可能造成資料遺失！！！***
## ***可能造成資料遺失！！！***
## ***可能造成資料遺失！！！***  


## <a name="flashimg"></a>刷入鏡像（如 .img、.bin 等）
### **不適用於三星裝置**  

1. 重啟到 bootloader 或 fastboot 模式 （請使用組合鍵或 adb 指令）
2. 選擇欲刷入的分區（或自行輸入）
3. 選擇欲刷入的鏡像檔
4. 點擊”開始“並**等待直到完成**

## <a name="flashzip"></a>安裝ZIP

請先重啟到 bootloader, fastboot, recovery or sideload 模式

bootloader (fastboot) 模式:
1. 在 "Fastboot update" 中選擇欲刷入的zip檔案
2. 點擊”開始“並**等待直到完成**

recovery 或 sideload 模式
1. 切到 EAF 中的 "Recovery" 頁面
2. 在 "Sideload Flashable Zip" 中選擇欲刷入的zip檔案
3. 點擊”開始“並**等待直到完成**

## <a name="erase"></a>擦除與格式化分區

1. 重啟到 bootloader 或 fastboot 模式
2. 選擇欲擦除或格式化的分區（或自行輸入）
3. 如果分區原有檔案系統而非raw格式，可以勾選 "Use format instead of erase"，將會刷入空檔案系統而非擦除分區
4. 點擊”開始“並**等待直到完成**