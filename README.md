【概念】

構想是電子商務的一環，類似POST機器應用，讓消費者在商城消費完可於購物車結帳

【主要功能】

結算金額、消費券使用、活動日期折扣

【框架】

Django → HTML (UI) → AJAX →  Django(View) →   Python (Object)    →    HTML (UI)

         訪問網頁    傳遞值     傳回Sever    物件初始化(計算、結帳)   結帳完成畫面
         
         
         
         
【工程】                                單元測試

Python (Object) ： 完成度80%               無

HTML(購物車一覽) ：

HTML(結帳端)     ：

Django(架構)     ：



【考量規劃】

MySQL-周年慶資訊只單純存在物件，如果有類似會員制勢必要用到DB，Sqlite也是個好選項

CI-完整的單元測試



【Python (Object) 】

初始化後類似台POST機器可不斷運行，

考量資源有效利用下，還沒考量到就讓他一直跑。

目前是結算一次就初始化一次。

程式碼地方覺得仍有許多可以優化。



【HTML(購物車一覽)】


【HTML(結帳端)】


【Django(架構)】
