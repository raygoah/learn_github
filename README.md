# learn_github
## 本機
* 設定帳戶，讓 Git 知道這台電腦做的修改要連結到哪一個使用者 (設定一次即可)
```  
  $ git config --global user.name "Your Name"
  $ git config --global user.email "Email"
```
* 檢查目前的設定
```
  $ git config --list
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
  $ git commit -m "Commit Message"
```
## 遠端
* 設定 github username
```
  $ git config --global user.username <github username>
```
* 連結本機和 github 上的 repository

```
  $ git remote add origin <remote address>
```
* 將本機的檔案 push 到 github 上

```
   $ git push -u origin master
   or
   $ git push origin master
   $ git checkout master
   $ git branch -u origin/master
```
## Reference
* [Git 與 Github 版本控制基本指令與操作入門教學](https://blog.techbridge.cc/2018/01/17/learning-programming-and-coding-with-python-git-and-github-tutorial/)
