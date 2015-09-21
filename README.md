# DataTaipei
R Client for http://data.taipei/

Linux: [![Travis-ci Status](https://travis-ci.org/TaipeiRHackers/DataTaipei.svg?branch=master)](https://travis-ci.org/TaipeiRHackers/DataTaipei)
Win : [![Build status](https://ci.appveyor.com/api/projects/status/luwh8nnqbu526ejd/branch/master?svg=true)](https://ci.appveyor.com/project/wush978/datataipei/branch/master)
OS X: [![Travis-ci Status](https://travis-ci.org/TaipeiRHackers/DataTaipei.svg?branch=osx)](https://travis-ci.org/TaipeiRHackers/DataTaipei)


## 安裝


```r
library(devtools)
install_github("TaipeiRHackers/DataTaipei")
```

## 功能

- 搜尋台北市政府的開放資料
- 下載台北市政府的開放資料
    - 下載的資料集會透過 [http://data.taipei](http://data.taipei) 提供的功能轉換為表格
    - 編碼在windows 上一律轉換為big-5，在非windows上轉換為utf-8
    - 輸出即為data.table，使用者可以直接從data.table或data.frame出發

## 範例

[DataTaipei應用範例 - 台北市youbike站點資料](http://taipeirhackers.github.io/DataTaipei/youbike.html)

[DataTaipei應用範例 - 台北市天氣資料](http://taipeirhackers.github.io/DataTaipei/weather.html)

[DataTaipei應用範例 - 台北市不動產資料](http://taipeirhackers.github.io/DataTaipei/estate.html)

## 問題回報與建議

如果在使用套件上有任何意見想要告訴我們，請到<https://github.com/TaipeiRHackers/DataTaipei/issues/new>填寫你的意見。

我們很樂意聽到你的任何聲音，包含錯誤、建議、以及你使用套件的愉快經驗。
我們很期待和任何一位使用者合作，將你的經驗加到應用範例，幫助更多的其他使用者。

## License

GPL(>= 2)
