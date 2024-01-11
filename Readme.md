## Dayz模组开发入门指南

> 视频教程：

### 准备工作

1. 系统环境和工具
   - Win操作系统，40~50G磁盘空间
   - Dayz游戏本体
   - Dev开发工具包

     [Mikero's Tools - Downloads (bytex.digital)](https://mikero.bytex.digital/Downloads)
   - (可选)GMIP图像编辑工具和插件

     [GIMP - Downloads](https://www.gimp.org/downloads/)

     [gruppe-adler/paa-gimp-plugin: A GIMP plug-in for the paa file format (github.com)](https://github.com/gruppe-adler/paa-gimp-plugin)
   - (可选)一个文本编辑器

     [Visual Studio Code - Code Editing. Redefined](https://code.visualstudio.com/)
2. 一点点英语基础
3. 耐心和时间，以及最重要的热爱

### 模组开发流程

1. Steam安装Dayz Tools
2. Setting设置P盘驱动
3. 加载P驱动
4. 导出原版文件
5. 编写模组
6. 打包模组
7. 测试模组
8. 签名模组
9. 发布/更新模组

### 模组结构

```md
📦@modname ---模组包
 ┣ 📂addons ---模组文件
 ┃ ┣ 📜xxx.pbo
 ┃ ┗ 📜xxx.pbo.sign
 ┗ 📂keys ---模组签名
   ┗ 📜key
```

###
