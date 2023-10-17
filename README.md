# vue-tea
这是一个vue类茶叶的商城
一、
1.1 克隆下来代码 git clone  https://github.com/cuwecue/vue-tea.git
1.2 在master下创建dev分支并且提交道远程仓库中 
    git branch xxx_dev  创建分支
    git checkout xxx_dev  切换到该分支
    git push origin xxx_dev push到远程仓库
1.3 在develop分支下创建功能分支
二、初始化一个项目
2.1 创建前端项目
    vue create <项目名称>
2.2 创建后端项目
    全局：cnpm（npm) install express-generator -g
    局部：进入目录 express --view=ejs <项目名称>
          cd <项目名称>  
          cnpm(npm) install
          npm run start 启动后端(http://localhost:3000)
三、指定分支克隆代码
    git clone  https://github.com/cuwecue/vue-tea.git 在主分支下克隆的代码
    git clone -b 分支名称 地址 克隆分支代码
常用命令：
① git branch  查看当前所在的分支
② git branch -r  用于查看远程分支（Remote Branches）的列表
 
