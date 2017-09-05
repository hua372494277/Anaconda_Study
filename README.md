# Anaconda_Study
* Download Anaconda and install it
* Add channels    
    \# 如果需要安装很多package添加Anaconda的TUNA镜像   
    conda config --add channels https://mirrors.tuna.tsinghua.edu.cn/anaconda/pkgs/free/    
    \# TUNA的help中镜像地址加有引号，需要去掉    
    \# 设置搜索时显示通道地址    
    conda config --set show_channel_urls yes   
    
    conda config --show     
    

…or create a new repository on the command line

echo "# Anaconda_Study" >> README.md
git init
git add README.md
git commit -m "first commit"
git remote add origin https://github.com/hua372494277/Anaconda_Study.git
git push -u origin master

…or push an existing repository from the command line

git remote add origin https://github.com/hua372494277/Anaconda_Study.git
git push -u origin master

…or import code from another repository

You can initialize this repository with code from a Subversion, Mercurial, or TFS project.
