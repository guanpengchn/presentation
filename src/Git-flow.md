title: Git和Git工作流
speaker: 关鹏
theme: light
transition: slide2
headFiles: /assets/light.css

[slide]

# GitHub和Git工作流
## 关鹏

[slide]

## 目录

- Git简介
- GitHub简介
- Git工作流

[slide]

# Git简介

[slide]

### Git本地指令——基础

```shell
$ git init // 初始化仓库
$ git status // 查看仓库的状态
$ git add [dir/file] // 向暂存区中添加文件
$ git commit // 保存仓库的历史记录
$ git log // 查看提交日志
$ git diff // 查看更改前后的差别
$ git reset [id] // 回溯历史版本
```

![](http://dl2.iteye.com/upload/attachment/0109/0178/291c4dc9-f58f-351e-a39f-fb070f211b32.png)

[slide]

### Git本地指令——分支

[演示工具](http://git-school.github.io/visualizing-git/)

```shell
$ git branch [name] // 显示、创建分支一览表

$ git checkout [name] // 切换分支

$ git merge [name] // 合并分支
```

[slide]

### Git远程指令

[演示工具](http://git-school.github.io/visualizing-git/)

```shell
$ git clone [url] // 获取远程仓库

$ git remote add [key] [value] // 添加远程仓库

$ git push [key] [local]:[remote] // 推送至远程仓库

$ git pull [key] [remote]:[local] // 获取最新的远程仓库分支
```

[slide]

# GitHub简介

[slide]

### 界面和功能

- 个人界面：[阮一峰](https://github.com/ruanyf)
- 项目界面：[ant-design](https://github.com/ant-design/ant-design)
  - Code
  - Issue: [《提问的智慧》](https://github.com/ant-design/ant-design/blob/master/README-zh_CN.md)、[《如何向开源社区提问题》](https://github.com/seajs/seajs/issues/545)、[《如何有效地报告 Bug》](https://www.chiark.greenend.org.uk/~sgtatham/bugs-cn.html)、[《如何向开源项目提交无法解答的问题》](https://zhuanlan.zhihu.com/p/25795393)
  - Pull requests
  - Wiki
-  Insights
  - Star, Watch, Fork
- 内容：[README.md](https://gist.github.com/PurpleBooth/109311bb0361f32d87a2#project-title)、[开源协议](http://www.ruanyifeng.com/blog/2011/05/how_to_choose_free_software_licenses.html)、lint（规范代码格式）、单元测试、持续集成部署
- 其他功能：
  - GitHub Page（静态网页）
  - GitHub API（通过REST API使用GitHub）
  - GitHub Action（持续集成部署）
  - GitHub Gist（代码片段）

[slide]

# Git工作流

[slide]

### Git Flow —— 以发布为中心的开发模式

![](https://upload-images.jianshu.io/upload_images/2062729-b22e35babaac5210.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/914/format/webp)

[slide]

### Git Flow —— 以发布为中心的开发模式

[演示链接](https://github.com/guanpengchn)

- feature、fix等[commit规范](http://www.ruanyifeng.com/blog/2016/01/commit_message_change_log.html)
- review提高代码质量
