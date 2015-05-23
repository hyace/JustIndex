###JustIndex

JustIndex仅仅是静态网页，用来作为技术站点的快速索引。

####建立步骤

#####首先
创建了JustIndex 的git项目，push到github。

#####其次
创建新的branch
    git checkout --orphan gh-pages
gh-pages是固定的分支名。

#####再次
在项目下添加编辑好的index.html文件。

#####add commit push
    git add index.html
    git commit -a -m "create a new branch."
    git push origin gh-pages

#####访问
可以通过`[username].github.io/[projectname]`来访问此页面，比如我的这个网页就是[http://hyace.github.io/JustIndex/](http://hyace.github.io/JustIndex/)。
