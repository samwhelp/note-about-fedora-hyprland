---
title: 視窗基本操作
nav_order: 5020
has_children: false
parent: 按鍵綁定
grand_parent: 設定
---


# 視窗基本操作

* [關閉視窗](#關閉視窗)
* [全螢幕](#全螢幕)
* [浮動切換](#浮動切換)


## 關閉視窗

* [設定片段](https://github.com/samwhelp/fedora-hyprland-adjustment/blob/main/prototype/main/hyprland-config/Main/asset/overlay/etc/skel/.config/hypr/hyprland.conf#L290)

| 按鍵組合          | 功能     | 執行指令         |
| ----------------- | -------- | ---------------- |
| `Win + q`         | 關閉視窗 | `killactive` (hyprland 內建) |


> 一般「關閉視窗」的按鍵綁定是在「`Alt + F4`」。


## 全螢幕

* [設定片段](https://github.com/samwhelp/fedora-hyprland-adjustment/blob/main/prototype/main/hyprland-config/Main/asset/overlay/etc/skel/.config/hypr/hyprland.conf#L291)

| 按鍵組合  | 功能       | 執行指令                      |
| --------- | ---------- | ----------------------------- |
| `Win + f` | 視窗全螢幕 | `fullscreen` (hyprland 內建) |

> 一般「視窗全螢幕」的按鍵綁定是在「F11」。


## 浮動切換

* [設定片段](https://github.com/samwhelp/fedora-hyprland-adjustment/blob/main/prototype/main/hyprland-config/Main/asset/overlay/etc/skel/.config/hypr/hyprland.conf#L292)

| 按鍵組合          | 功能     | 執行指令         |
| ----------------- | -------- | ---------------- |
| `Win + Esc`         | 浮動切換 | `togglefloating` (hyprland 內建) |

> 也可以在某個視窗，透過「`Win + <滑鼠中鍵按下>`」來切換浮動狀態。
