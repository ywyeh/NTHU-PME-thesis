# 國立清華大學碩博士論文 XeLaTeX 模板（適用於工學院動機系）

## Introduction
本模板魔改了[Dephilia](https://github.com/Dephilia/NTHU-PME-thesis)魔改了[signxer](https://github.com/signxer/nthu-thesis-template-mod)魔改的 [Hao-Wei Lee](https://github.com/HW-Lee/) 修改的 [國立清華大學碩博士論文 XeLaTeX 模板](https://github.com/HW-Lee/nthu-thesis-template)。

簡單來說就是魔改四次的超級魔改版。

以下是原始魔改版留下的話，我覺得很棒必須要推推。

```
👍適配了近幾年來流行的論文格式。

👍替換了學校圖書館給的馬賽克浮水印為高清版本。

👍支援Overleaf直接導入zip，把默認的Compiler設定改成XeLaTeX即可。（強推Overleaf！！！好用！！！）
```

清大的同學們可使用學校信箱(m1xx@nthu.edu.tw)註冊[overleaf](https://www.overleaf.com/login?)，可使用premium的功能。

## 到底改了哪些東西啊

較上個版本又再修改了不少東西，基本上應該已經是ICMEMS實驗室的中文模板了。

1. 邊界調整，輸出時請注意第一章第一頁以後是雙面列印，前面是單面列印(頁面邊界有少許不同)。
2. 封面格式調整，其實還是跟學校模板有一些小差別但反正實驗室同一屆都用一樣的就不會被發現吧(X
3. 目錄羅馬數字編號錯誤問題。
4. 目錄、圖目錄、表目錄格式問題。
5. 新增附錄樣本。
6. 新增中文支援：包含目錄、圖/表目錄、章、節、圖、表、式、演算法、參考文獻、附錄，為ICMEMS實驗室所使用的格式。
7. 新增超連結支援：使用hyperref包(thesis.tex中46行)。<font color="#f00">**請注意：不要拿有新增超連結的檔案去列印，頁數會有羅馬數字，要的話最後上傳學校系統再使用就好**</font>
8. 支援ICMEMS實驗室之引用格式：IEEEtran_rchen模板，非本實驗室建議使用正常IEEEtran模板即可，或是自行魔改XD。

## 老師說他要Word欸

使用adobe的線上工具(目前不用登入就可以使用)：https://www.adobe.com/tw/acrobat/online/pdf-to-word.html

## 圖書館要加密
使用[PDFtk](https://www.pdflabs.com/tools/pdftk-the-pdf-toolkit/)，並參考李吉豪學長的[blog](https://www.dephilia.moe/posts/encrypt-your-pdf/)。

## 提醒一下而已

匯入Overleaf的時候要記得把compiler改成XeLaTeX，不然你永遠無法編譯成功的。

## 說明及版權
請參考原原原作者所提供之 [README](https://github.com/HW-Lee/nthu-thesis-template/blob/master/README.md) 文件。
以及原原原原作者所提供之 [wiki](https://github.com/tzhuan/ntu-thesis/wiki) 文件。
