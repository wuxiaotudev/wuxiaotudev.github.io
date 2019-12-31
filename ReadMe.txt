
1. 下载 安装 nodes
  https://nodejs.org/en/

2. 安装hexo
  npm install -g hexo-cli
  npm install hexo --save

3. 克隆分支hexo到本地
  git clone -b hexo_branch https://github.com/wuxiaotudev/wuxiaotudev.github.io.git

4. 推送到指定分支
  git add .
  git commit -m "XXX"
  git push origin hexo_branch

// 创建新的博客文件
hexo_blog/source/创建一个xxx.md

// 生在静态博客文件 
hexo g

// 推到github上去
hexo d

// 本地运行
hexo s

// 清除
hexo clean
