---
Title: VSCode C++
tags: computer
---
# 用 VSCode 寫 C/C++ 教學

- 同步發布於 https://hackmd.io/@liaojason2/vscodecppwindows

## VSCode 安裝
- [前往 VSCode 網站下載安裝檔](https://code.visualstudio.com/)
![](https://i.imgur.com/PH6FOvN.png)
- 下載後開啟安裝程式
![](https://i.imgur.com/voEpVYS.jpg)
- 同意使用者條款
![](https://i.imgur.com/mXOVHIS.jpg)
- 選擇下面的勾勾
![](https://i.imgur.com/XuIuhXa.jpg)
- 確認安裝
![](https://i.imgur.com/7acp0rC.jpg)
- 安裝完成，會自動打開 VSCode
![](https://i.imgur.com/CMYnoQ9.jpg)
- 進入 Extenion
![](https://i.imgur.com/IHotSkV.jpg)
- 安裝 C/C++
![](https://i.imgur.com/PRhX65n.jpg)
- 安裝 C++ Intellisense
![](https://i.imgur.com/f5YgDH5.jpg)

## MinGW 安裝
- [進入 MinGW 下載頁面選取 mingw-get-setup.exe (檔案會自動下載)](https://zh-tw.osdn.net/projects/mingw/releases/68260)
![](https://i.imgur.com/iQX86Gm.jpg)
- 開啟下載下來的程式，選擇下一步</br>
![](https://i.imgur.com/4NaWJd6.jpg)
- 選擇安裝位置後繼續 (與描述檔有關，除非你知道怎麼弄否則不要動)
![](https://i.imgur.com/gEoE7YR.jpg)
- 安裝畫面</br>
![](https://i.imgur.com/h2GcYTj.jpg)
- 安裝完後會啟動 MinGW Installer Manager，找到 mingw32-gcc-g++-bin 點取左方窗格，選擇 Mark for Installation
![](https://i.imgur.com/8XHfFuj.jpg)
- 選左側 All Packages，找到 mingw32-gdb-bin 點取左方窗格，選擇 Mark for Installation
![](https://i.imgur.com/VDEuDnY.jpg)
- 選擇 Installation --> Apply Change
![](https://i.imgur.com/EJWDEhB.jpg)
- 點選 Apply</br>
![](https://i.imgur.com/rRpfnKk.jpg)
- 安裝中，安裝完成後點選 Close</br>
![](https://i.imgur.com/J9Aq2Gd.jpg)
- 開啟檔案總管 --> 電腦 --> 內容
![](https://i.imgur.com/EfaLPFX.jpg)
- 選取左側進階系統設定
![](https://i.imgur.com/oJSvCZw.jpg)
- 選擇環境變數</br>
![](https://i.imgur.com/AtPQmFO.jpg)
- 在下面的系統變數找到 Path</br>
![](https://i.imgur.com/VBFVONm.jpg)
- 新增 C:\MinGW\bin 點選確定</br>
![](https://i.imgur.com/YvtKYnt.jpg)

## 開始撰寫 C/C++
 
- 在桌面上隨意新增資料夾</br>
![](https://i.imgur.com/Dcp8Qrq.jpg)
- [進入 repository 主頁](https://github.com/liaojason2/vscode-cpp-for-windows)，選擇 Clone or Download --> Download ZIP
- 或在終端機輸入 `git clone https://github.com/liaojason2/vscode-cpp-for-windows.git`
![](https://i.imgur.com/C1S8tnc.jpg)
- 在剛剛在桌面上的資料夾中新增 .vscode 資料夾
![](https://i.imgur.com/2zdy42E.jpg)
- 解壓縮後從下載下來的東西加入畫面中(畫面的四個檔案)
![](https://i.imgur.com/BcY9RcU.jpg)
- 在桌面上對資料夾點選右鍵，選擇以 Code 開始</br>
![](https://i.imgur.com/1skI6aw.png)
- 點選資料按鈕新增檔案，取完檔名後開始輸入程式
![](https://i.imgur.com/xmqmfvg.jpg)
- 輸入 `Ctrl+Shift+B` 進行編譯
![](https://i.imgur.com/vtZkxvr.jpg)
- 輸入 Ctrl+Shift+\` 開啟終端機
![](https://i.imgur.com/bQCwKAh.jpg)
- 輸入 `./<檔名>.exe`+`Enter`執行程式
![](https://i.imgur.com/MCajNUu.jpg)

## 注意事項
- .vscode 必須與要編譯的檔案在同一個資料夾或是任一上層目錄
- vscode 必須以資料夾方式開啟才能編譯，即使是只寫一個檔案也一樣




    
