# Github_pictures

将本地的图片推到GitHub上再引用,适合推文件

在你要上传的文件夹上右键——git cmd（出现了很多黄色的字母就改文件夹右键，例如可以进去下一层的文件夹）

(https://icode.best/i/17648143906863)
到“9.接下来依次输入以下代码即可完成其他剩余操作：

git add * （注：别忘记后面的.，此操作是把Test文件夹下面的文件都添加进来）

git commit -m “提交信息” （注：“提交信息”里面换成你需要，如“first commit”）”

停止
(后面接https://zhuanlan.zhihu.com/p/54924115)

第六步：在命令窗口中输入 git pull
然后，回车。等几秒钟。

第七步：在命令窗口中输入 git push
然后回车，等几秒钟。

第八步：在命令窗口中输入 git status -sb
如果显示如下图，就说明成功了，本地仓库与远程仓库完全一致


注：Please enter a commit message to explain why this merge is necessary, especially if it merges an updated upstream into a topic branch

It's not a Git error message, it's the editor as git uses your default editor. 

To solve this:

-press "i" (i for insert)

-write your merge message

-press "esc" (escape)

-write ":wq" (write & quit)

-then press enter

