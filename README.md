# TaskGitHub_01

[課前最終作業二](https://panyensu.github.io/TaskGitHub_01/flex-finalhomework_02/index.html)

https://panyensu.github.io/TaskGitHub_01/

[Week01](https://panyensu.github.io/TaskGitHub_01/CSSweek01_個人履歷/%E8%AA%B2%E5%89%8D%E6%9C%80%E7%B5%82%E4%BD%9C%E6%A5%AD_%E5%80%8B%E4%BA%BA%E5%B1%A5%E6%AD%B7.html)

[Week02](https://panyensu.github.io/TaskGitHub_01/CSSweek02_個人網站/week02.html)

[Week03](https://panyensu.github.io/TaskGitHub_01/CSSweek03/index.html)

## 部署 gh-pagse 流程
```
git add .
git commit -m 'first commit'
git remote add origin [GitHub Repositories Url]
git push -u origin master // 僅限第一次輸入，往後只需要輸入 git push
```
將 Gulp 初次部署之後就可以輸入 gulp build 進入生產模式，當生產完畢之後最後只需要輸入 gulp deploy 即可完成 GitHub Pages 部署。
## 安裝 Gulp

* 安裝 Node.js，輸入 node -v 看是否有顯示版本號
* npm i gulp@4 -g
* gulp -v 看是否有顯示版本號
* 下載此[資料夾](https://github.com/hexschool/web-layout-training-gulp) 並cd 移動到該資料夾
* npm install 安裝插件
* gulp 執行

## Gulp 指令
* gulp - 執行開發模式(會開啟模擬瀏覽器並監聽相關檔案)
* gulp build - 執行編譯模式(不會開啟瀏覽器)
* gulp clean - 清除 dist 資料夾
* gulp deploy - 將 dist 資料夾部署至 GitHub Pages

