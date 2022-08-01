# 安裝 Magisk（面具root）

## 第一種方法
1. 安裝 Magisk APP
1. 取得 boot.img，並放入“內建儲存空間”
2. 在 Magisk APP 中修補
3. 將修補完成的 img 複製到電腦上
4. 將修補完的 img 刷入 boot 分區

## 第二種方法（僅限第三方 Recovery）
1. 在電腦上下載 Magisk APK
2. 將手機重啟到 recovery 或 sideload 模式
3. 切換到 Recovery 頁面, 在“安裝Zip刷機包”中選擇magisk.apk並繼續

## 第三種方法 (僅限安裝官方ROM的三星裝置)
1. 下載該裝置適用的官方 ROM（需為相同版本）並找到 AP.tar 或 .tar.md5
2. 將 AP.tar 並放入“內建儲存空間”
3. 在 Magisk APP 中修補
4. 將修補完成的 tar 複製到電腦上
5. 使用 Odin 刷入