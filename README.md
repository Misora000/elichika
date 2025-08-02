# elichika
A fork of https://github.com/arina999999997/elichika, check out the original.

All this fork did was let you enjoy this game on Windows without any external dependency.

I don't change anything of the server code but provide a patched client apk which connect to http://10.0.2.2:8080/ so that you can play this game by Android emulator such as [BlueStacks](https://www.bluestacks.com/tw/index.html).

Also provide a pre-build server exe which uses `local CDN`. Please get my repack CDN files from [Internet Archive](https://archive.org/details/ll-sifas-local-cdn-data-elichika)

## Installation
- Download and unzip [CDN file](https://archive.org/details/ll-sifas-local-cdn-data-elichika) to the roor of elichika, overwrite the original `static` folder is ok
- Execute elichika.exe
- Install [Game App](https://github.com/Misora000/elichika/releases/download/BlueStacks_Client/LLAS_JP_3.12.0_10.0.2.2_8080_BlueStacks.apk) in BlueStacks


## 中文說明
這個fork提供了一個能直接在Windows用BlueStacks等Android模擬器玩的方案, 因為模擬器是以`10.0.2.2:8080`連到localhost, 原本的apk是連向127.0.0.1:8080無法使用, 所以我patch了一個新的 [APK](https://github.com/Misora000/elichika/releases/download/BlueStacks_Client/LLAS_JP_3.12.0_10.0.2.2_8080_BlueStacks.apk) 讓他連向10.0.2.2:8080  
  
此外, 外部的CDN似乎都失效了, 為了能獨立運作不仰賴他人, 我將server設定成使用local CDN, 你能直接下載編譯好的 [Server執行檔](https://github.com/Misora000/elichika/releases/download/BlueStacks_Client/elichika_win_x64.7z) 與我重新包裝好的 [CDN檔案](https://archive.org/details/ll-sifas-local-cdn-data-elichika), 將CDN檔案解開後覆蓋原本elichika目錄內的static即可啟動elichika.exe, 然後打開BlueStacks安裝APK就能享受遊戲

