# GitNoteBook
### 记录使用git的相关问题和解决方案   
#### 使用git上传代码到指定仓库，如：
git init   
git add .   
git commit -m "上传描述"    
git remote add origin https://github.com/KDDGit/SpringMVC.git   
git push -u origin master   
注：git add 后可选择文件夹，但上传到github打不开；   
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;"上传描述"不可省略   

#### 在git仓库中新建文件夹的两种方式  
第一种：在仓库首页->Create new file->"文件夹"/"文件名"，创建即可。   
第二种：在仓库首页->Upload file->将文件夹拖进来，上传即可。文件夹中需要由内容。  

#### 在git仓库删除文件的方式
第一种：进入文件夹，打开文件，点击垃圾桶图标，删除文件。github不存在空文件夹，文件删除完毕，文件夹就消失了。   
第二种：使用git Bash删除

