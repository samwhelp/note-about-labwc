---
title: 音量控制
nav_order: 5052
has_children: false
parent: 按鍵綁定
grand_parent: 設定
---


# 音量控制


* [設定片段](https://github.com/samwhelp/note-about-labwc/blob/gh-pages/_demo/config/labwc-config/main/rc.xml#L242-L250)

| 按鍵組合               | 功能           | 執行指令                                    |
| ---------------------- | -------------- | ------------------------------------------- |
| `XF86_AudioMute (XF86AudioMute)`        | 音量切換成靜音 | `amixer -q -D pulse sset Master toggle`     |
| `XF86_AudioLowerVolume (XF86AudioLowerVolume)` | 減小音量       | `amixer -q -D pulse sset Master 5%- unmute` |
| `XF86_AudioRaiseVolume (XF86AudioRaiseVolume)` | 增加音量       | `amixer -q -D pulse sset Master 5%+ unmute` |



* [設定片段](https://github.com/samwhelp/note-about-labwc/blob/gh-pages/_demo/config/labwc-config/main/rc.xml#L164-L166)

| 按鍵組合          | 功能             | 執行指令                                    |
| ----------------- | ---------------- | ------------------------------------------- |
| `Alt + Shift + v` | 開啟音量控制面板 | `mate-volume-control`                       |


* [設定片段](https://github.com/samwhelp/note-about-labwc/blob/gh-pages/_demo/config/labwc-config/main/rc.xml#L251-L265)

| 按鍵組合          | 功能             | 執行指令                                    |
| ----------------- | ---------------- |
| `Alt + m`         | 音量切換成靜音   | `amixer -q -D pulse sset Master toggle`     |


| 按鍵組合          | 功能             | 執行指令                                    |
| ----------------- | ---------------- |
| `Alt + Ctrl + ,`  | 緩慢地減小音量   | `amixer -q -D pulse sset Master 1%- unmute` |
| `Alt + Ctrl + .`  | 緩慢地增加音量   | `amixer -q -D pulse sset Master 1%+ unmute` |




> TODO: Fix Not Work!

| 按鍵組合          | 功能             | 執行指令                                    |
| ----------------- | ---------------- |
| `Alt + Shift + <` | 減小音量         | `amixer -q -D pulse sset Master 5%- unmute` |
| `Alt + Shift + >` | 增加音量         | `amixer -q -D pulse sset Master 5%+ unmute` |
