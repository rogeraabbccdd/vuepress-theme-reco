<p align="center"><a href="https://vuejs.org" target="_blank" rel="noopener noreferrer"><img width="150" src="./images/icon_vuepress_reco.png" alt="Vue logo"></a></p>

## 說明 
本分支為自用修改版 [Live Demo](https://rogeraabbccdd.github.io/blog/)  

## 修改內容
- 移除騰訊 404 頁面
- 繁體中文化
- 修正中文字體，加上微軟雅黑和微軟正黑體
- 移除 iconfont 的阿里 cdn，改用本地檔案
- 移除華為文案
- 程式碼使用微軟 Cascadia Code 字形
- 新增主題設定 intro，個人檔案下的小說明
  ```js
  intro: "🍰 It's Muffin Time!"
  ```
- 新增個人檔案下的 SMS icon 連結
  ```js
  infoSMS: [
    {
      icon: "reco-home",
      link: "https://homeurl.com"
    },
    {
      link: "https://github.com/",
      icon: "reco-github"
    }
  ],
  ```
- 修正文章作者字體
- 新增黑暗模式設定
  - themePicker 會出現黑暗模式開關選項
  - `defaultDark` 設定可以調整是否預設開啟黑暗模式
  - 如果使用者的裝置有開啟黑暗模式的話會自動套用，不可關閉
- 新增許多 footer 設定並移除備案資訊
  ```js
  themeConfig: {
    // 自訂 footer 文字
    footerCustom: "Made with ❤ by XXX",
    // 是否在 footer 顯示主題連結
    footerTheme: false,
    // 是否在 footer 顯示年分
    footerYear: false,
  }
  ```
