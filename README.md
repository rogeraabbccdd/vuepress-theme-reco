<p align="center"><a href="https://vuejs.org" target="_blank" rel="noopener noreferrer"><img width="150" src="./images/icon_vuepress_reco.png" alt="Vue logo"></a></p>

本分支為自用修改版  

修改內容:
- 移除騰訊 404 頁面
- 繁體中文化
- 修正中文字體，加上微軟雅黑和微軟正黑體
- 移除 iconfont 的阿里 cdn，改用本地檔案
- 移除華為文案
- 程式碼使用微軟 Cascadia Code 字形
- 新增主題設定 footer，
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
- 新增黑暗模式 `darkTheme: true` 設定，themePicker 會出現黑暗模式開關選項，如果 themePicker 設為 false 的話則預設開啟黑暗模式