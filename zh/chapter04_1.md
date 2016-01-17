# 基本表达式

在第三章的结尾，我们制作了一个基本的Hello World应用。在其中，我们使用了如下的语法：

```HTML
<h1>{{"Hello World!"}}</h1>

//上方的“{{”和“}}”既是AngularJS的基本表达式

//如果AngularJS被成功的引入，那么最终的页面将不会显示双括号，而是直接显示Hello World.
```

我们可以尝试下将表达式中的内容替换为如下内容，并观察运行的结果：

```HTML
{{ 1+1 }} //网页会显示2

{{ 'a' + 'bc' }} //网页会显示abc
```

从上我们可以看出，双括号内的内容，其实是一个JavaScript表达式，并将表达式进行计算的结果显示在此处。这也是AngularJS最吸引人的特性，因为它还支持将JavaScript中的数据显示在此处（我们将在后面的内容中介绍如何操作）。

并且，如果此处输出的是JavaScript中的变量，此处的显示会**自动**的随JavaScript变量的变化而变化。