这是 arduino-start-esp32c3 (中文版)的书籍编写草稿

#### 构建方法

先做好空目录等模板，并在git初始化

然后在gitbook里面，选择从git仓库导入书籍

简单配置一下即可

#### 可能用得上的命令

批量创建单页文件

`for i in $(seq -w 1 20); do touch "$i.md"; done`

#### 编写过程

上一本书是在obsidian里面编写的，可以查看markdown格式预览的效果，并用到了4个obsidian的插件：

更好的导出pdf
pandoc插件
粘贴图片时自动重命名
快速浏览文件

启用插件后简单配置一下