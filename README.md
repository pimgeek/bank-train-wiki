# help
银行培训相关维基知识文档库

使用 jekyll 构建

发布方法参考：  
http://blog.nitrous.io/2013/08/30/using-jekyll-plugins-on-github-pages.html

### 编辑方法

签出 master 分支后，运行

bundle exec jekyll serve -H 0.0.0.0

增加维基知识文档就是在 _wiki 目录下增加 md 文件  
文件命名规则：

```
<文档库名>-<文档名>.md
```

增加文件后需要填写文件头部，其中：

- account: 编辑者的 github 账号名
- term: 当前知识文档主要针对哪个概念/术语？
- related-terms: 与当前概念/术语相关的其它概念/术语有哪些？

### 其他参考资料

http://stackoverflow.com/questions/28100220/jekyll-display-collection-by-category
