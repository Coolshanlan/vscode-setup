# 教學步驟
- https://medium.com/@c52chungyuny/%E8%B6%85%E7%B0%A1%E5%96%AEvisual-studio-code-c-c-%E8%A8%AD%E5%AE%9A%E6%AD%A5%E9%A9%9F-a360be1487c
- https://blog.csdn.net/itas109/article/details/99699807
# 相關設定
"stopAtEntry": true,

"externalConsole": true,

setting.json  "terminal.integrated.shell.windows": "C:\\User_C\\Git\\bin\\bash.exe" 這行要註解掉

會出現路徑問題是因為bash的路徑跟windows的不一樣(file not found)

發現解決辦法思路:https://ask.csdn.net/questions/774686

有人提到 "如果你使用了bash終端，bash使用的文件分隔符是/，不相容，就會出現此類錯誤"
於是我把bash關掉了
> 修復在git bash 上 $dir path 錯誤
> https://github.com/formulahendry/vscode-code-runner/pull/469

