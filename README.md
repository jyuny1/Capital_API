Capital_API
===========

使用Java JNA和SWT去界接群益報價API的範例

1.使用必要條件<br/>
　a.需有群益帳戶<br/>
　b.有開通報價API，並下載那API相關DLL檔<br/>

2.使用方法<br/>
　a.將群益帳號密碼輸入到SKQuoteLib_SWT_Example的身分證字號和密碼。<br/>
　b.將那SKQuoteLib.dll複製到這專案目錄下。<br/>
　c.如果那SKQuoteLib.dll為32位元，請用32位元版的SWT和JDK，若64位元，則用64位元版的SWT和JDK。<br/>
　　目前是使用32位元。<br/>
　d.執行那SKQuoteLib_SWT_Example.java，就會登入並取得Server端時間，按下接收報價就會取得台指期跟領先指的報價。<br/>
　e.要結束請先按結束連線再關閉。<br/>