---
title: 系統操作
nav_order: 5001
has_children: false
parent: 按鍵綁定
grand_parent: 設定
---


# 系統操作


## 重新載入設定

* [設定片段](https://github.com/samwhelp/note-about-labwc/blob/gh-pages/_demo/config/labwc-config/main/rc.xml#L128-L130)

| 按鍵組合           | 功能        | 執行指令             |
| ----------------- | ------------ | -------------------- |
| `Alt + Shift + x`  | Show Exit Panel | `wlogout` |


## 登出

* [設定片段](https://github.com/samwhelp/note-about-labwc/blob/gh-pages/_demo/config/labwc-config/main/rc.xml#L131-L136)

| 按鍵組合           | 功能        | 執行指令             |
| ----------------- | ------------ | -------------------- |
| `Alt + Shift + x`  | Show Exit Panel | `wlogout` |
| `Alt + Ctrl + x`  | Exit | `Exit` (openbox 內建) |


## 關機

* [設定片段](https://github.com/samwhelp/note-about-labwc/blob/gh-pages/_demo/config/labwc-config/main/rc.xml#L137-L142)

| 按鍵組合           | 功能        | 執行指令             |
| ----------------- | ------------ | -------------------- |
| `Alt + Shift + z`  | Show Exit Panel | `wlogout` |
| `Alt + Ctrl + z`  | Exit | `systemctl -i poweroff` |
