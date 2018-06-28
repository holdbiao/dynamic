1.热更新 browser-sync

// --files 路径是相对于运行该命令的项目（目录） 
browser-sync start --server --files "css/*.css, *.html"
// 如果你的文件层级比较深，您可以考虑使用 **（表示任意目录）匹配，任意目录下任意.css 或 .html文件。 
browser-sync start --server --files "**/*.css, **/*.html"



2.koala  预编译软件

css要求：

1.使用flex，注意兼容（kaola里可以设置）

2.书写顺序为影响回流和重绘的写在前面
3.用最少的代码完成布局（使用伪元素）

3.
使用koala设置scss，browser-sync热更新


