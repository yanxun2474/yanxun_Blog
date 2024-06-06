---
title: 更換hexo背景
date: 2024-06-06 15:24:33
tags: hexo
categories: 部落格架設
---

## 修改 next/\_config.yml 的 Custom\_file_path 設定
<!--more-->
```yaml=
# Define custom file paths.
# Create your custom files in site directory `source/_data` and uncomment needed files below.
custom_file_path:
  #head: source/_data/head.swig
  #header: source/_data/header.swig
  #sidebar: source/_data/sidebar.swig
  #postMeta: source/_data/post-meta.swig
  #postBodyEnd: source/_data/post-body-end.swig
  #footer: source/_data/footer.swig
  #bodyEnd: source/_data/body-end.swig
  #variable: source/_data/variables.styl
  #mixin: source/_data/mixins.styl
  style: source/_data/styles.styl
```
把第13行註解取消

## 在 /source 建立 _data 資料夾

這邊要注意的地方是在==myblog底下的source資料夾內新建一個_data 資料夾==

==不是在theme主題樣式下的source資料夾==

![圖片](/images/自訂樣式撰寫.png)

## 寫樣式
![圖片](/images/部落格路徑.png)

## 結果圖
![圖片](/images/換背景圖片演示.png)

### 參考資料
[【學習筆記】如何更換 Hexo 主題 & 自訂樣式](https://hackmd.io/@Heidi-Liu/hexo-theme)