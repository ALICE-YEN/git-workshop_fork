###### 12/25-12/26上課筆記&心得 

## 終端機指令

| Windows | MacOS/Linux | 說明 |舉例(window)|
|---------|---------|---------|---------|
| cd 和路徑中間 增加 /d  | cd     | 切換目錄 change directory   | cd /d d:(換成D槽目錄)|
| cd     | pwd    | 顯示目前所在路徑 print working directory |
| dir    | ls     | 列出目前檔案夾的檔案列表  list   |
| md     | mkdir  | 建立新的檔案夾  make dir   |md (名稱)    |
| copy   | cp     | 複製檔案   copy  |copy (想複製檔案/位置) (新檔名/新增位置)|
| move   | mv     | 移動檔案   move  |同上
| del    | rm     | 刪除檔案    remove |delete (刪除位置)|
| cls    | clear  | 清除畫面上的內容    |
|type    | cat    | 尋找顯示檔案內容    |
| cd `..`|        |前一頁|
| cd . > b.txt|        |新增b.txt檔|
| echo   |     |寫入檔案|echo xxx > 1.txt xxx寫入1.txt(覆蓋) echo xxx >> 1.txt 1.txt xxx寫入1.txt(追加最後一行)


參數的意義，不同指令會不一樣，但通常會是這樣   
`-a` ==> all   全部   
`-f` ==> force 強制    
`-r` ==> recursive 遞迴   
`-l` ==> long 查看完整名稱   
**以上參數供Mac/Linux參考**


```
window檔案位置要用\ (/不會有反應)
cd其他用法
https://reurl.cc/6Egp3Z
```
## 常見git指令
|指令|解釋|備註|
|-----|-----|-----|
|git config |設定|位置 D:/git/Git/etc/gitconfig
|git init|初始化|
|git status|狀態|git st|
|git add|將資料存到暫存區|ex:git add. / git add 1.html|
|git commit -m|暫存區資料存到儲存庫|git ci -m|
|git ci -am|同時 add和 commit|要已經add過的檔案|
|git push|傳送到遠端||
|git clone|將github資料下載下來|git clone (網址) 此指令通常只會使用第一次|
|git pull|更新最新的線上版內容|fetch+merge的效果|
|git branch|查看分支|git br (分支名) 建立分支|
|git switch|切換分支|git switch (分支)
|git merge|合併分支|
|git diff|檢視修改的差異||
|git restore --staged |對當前在staging area的檔案的修改回復至前一個狀態|ex: git restore --staged 1.txt|
|git restore|遺棄掉在working directory的修改|ex: git restore 1.txt|
|git log|查看紀錄|



詳細 git操作: 
https://github.com/hellojs-tw/git-101/blob/master/SUMMARY.md
https://gitbook.tw/chapters/github/pull-from-github
```
git log <檔名>  查看特定檔案的紀錄
git log -p test.txt  查看檔案修改細節
git log --grep="delete" 可以針對 commit 訊息做搜尋
git blame test.txt 查看內容是誰編寫的
```

![](https://i.imgur.com/iYbhwu4.png)
![](https://www.git-tower.com/learn/git/ebook/en/command-line/remote-repositories/introduction)

```
參考資料
https://hackmd.io/Ns0AuMFtROOT9E0oSujQ7A?both
```
## 心得
老師上課非常清楚，很扎實，又很有耐心幫忙解決問題，有讓我事半功倍的效果
雖然在講指令的時候，身為windows的使用者的我有一度錯亂，