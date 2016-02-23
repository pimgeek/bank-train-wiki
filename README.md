# help
银行培训相关维基知识文档库汇总

使用 jekyll 构建

发布方法参考：  
http://blog.nitrous.io/2013/08/30/using-jekyll-plugins-on-github-pages.html

### 编辑方法

签出 master 分支后，运行

bundle exec jekyll serve -H 0.0.0.0

增加维基知识文档库名就是在 _repos 目录下增加 md 文件  
文件命名规则：

```
<编辑者名>-<维基知识文档库名>.md
```

增加文件后需要填写文件头部，其中：

- account: 编辑者的 github 账号名
- desc: 维基知识文档库描述
- created: 工程创建时间
- updated: 工程最后提交时间
- last-commit: 最后一次 commit 的 id
- type: 知识文档库类型（基础 common , 信贷 credit , 风险 risk 等等）
- alternative: 是否有替代方案
- skills: 编辑此文档需要的技能
- threads: 隶属于哪条主线，例如：属于 bank-train 就写 [banktrain]
- design-usage: 对这项知识库的设想的用途

### 其他参考资料

http://stackoverflow.com/questions/28100220/jekyll-display-collection-by-category
