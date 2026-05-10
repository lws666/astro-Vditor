# astro-Vditor
一个基于Vditor富文本编辑器的顶目，我的博客是Mizuki，其他astro博客请自行修改Frontmatter部分

# 部署
先fork本项目，然后在cloudflare pages里选择你fork的项目即可完成部署
需要添加一个变量来设置你的访问密码 ADMIN_PASSWORD
构建命令设置为 sed -i "s/\[\[ADMIN_PASSWORD\]\]/$ADMIN_PASSWORD/g" index.html

# 配置
USER 填你的github用户名
REPO 填你博客的仓库名
PATH 填你博客文篇的路径
TOKEN 填你github的token(只要repo权限就行)


# 开发
你们可以拿去二次开发，本项目为ai生成，我开发这个项目是给不会ssr模式的小白用的
