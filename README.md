# learn_github
* 設定帳戶，讓 Git 知道這台電腦做的修改要連結到哪一個使用者
```  
  $ git config --global user.name "Your Name"
  $ git config --global user.email "Email"
```  
* 建立一個本機的 repository
```
 // create a practice_git dictionary
 $ mkdir practice_git-git
 $ cd hello-git
 // make the practice_git to be a git repository
 $ git init
 // ls (-l: detail，-a: hide）
 $ ls -la
```
* 建立一個新的檔案: ```test.py```
* 檢視檔案狀態
```
  $ git status
```
* 將檔案加入到 git 追蹤的範圍/暫存區
```
  $ git add test.py
```
* commit 檔案進去 repository
```
  $ git commit -m "Init hello.py"
```
