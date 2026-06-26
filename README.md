# 李依凡 NFC 電子名片

這個資料夾是可直接上傳到 GitHub Pages 的靜態網站。

## 檔案結構

```text
index.html
assets/
  front.jpg
  back.jpg
.nojekyll
```

## 建議發布方式

1. 到 GitHub 建立一個新的 public repository，例如 `nfc-business-card`。
2. 上傳本資料夾內的所有檔案與資料夾，不要只上傳外層資料夾本身。
3. 進入 repository 的 `Settings`。
4. 左側選 `Pages`。
5. `Build and deployment` 的 `Source` 選 `Deploy from a branch`。
6. Branch 選 `main`，資料夾選 `/(root)`，然後按 `Save`。
7. 等 GitHub Pages 發布完成後，網址通常會是：

```text
https://你的GitHub帳號.github.io/repository名稱/
```

如果 repository 名稱是 `nfc-business-card`，網址會像：

```text
https://你的GitHub帳號.github.io/nfc-business-card/
```

把這個網址寫入 NFC 標籤即可作為電子名片使用。
