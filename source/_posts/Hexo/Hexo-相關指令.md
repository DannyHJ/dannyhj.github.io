---
title: Hexo 相關指令
date: 2022-04-21 15:10:53
tags: hexo
---

## Hexo 指令

### 安裝 hexo

`npm install hexo-cli -g`

### 顯示 hexo 版本資訊

`hexo version`
`hexo -v`
<!-- more -->

### 建立 hexo 專案

`hexo init 資料夾名稱`

### 建立新檔案

`hexo new '檔案名稱'`

### 將檔案編譯為靜態檔案

`hexo generate`

### 開啟內部伺服器

`hexo server`
`hexo s`

### 關閉內部伺服器

`Ctrl + C`

### 清除暫存檔案(有問題時可以使用)

`hexo clean`

### 部署靜態檔案

`hexo deploy`
`hexo -d`

### 建立 about 頁面

`hexo new page about`

### 編譯及佈署網頁

`hexo d -g`

### 去除模板(在網頁檔案最面插入)

```
---
layout: false
---
```

### 注意事項

- 避免 hexo 編譯檔案，在檔案最前面加上 下底線

## npm 指令

### 查看 npm 版本

`npm -v`

### 專案 npm 初始化(建立新專案時需要使用)

`npm init`

### 跳過輸入專案資訊流程

`npm init -y`

### 安裝依賴套件

`npm install 套件名稱 --save`

### 安裝開發依賴套件(開發時才會使用到的套件)

`npm install 套件名稱 --save-dev`

### 移除套件

`npm uninstall 套件名稱`

### 移除本機套件

`npm uninstall 套件名稱 -g`

### 還原安裝過套件

`npm install`

### 安裝部署套件

`npm install --save hexo-deployer-git`