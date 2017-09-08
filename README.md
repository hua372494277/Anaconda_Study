# Anaconda_Study
* Download Anaconda and install it     
* Add channels    
    \# 如果需要安装很多packages, 发现conda下载速度经常很慢，因为Anacondaa.org的服务器在国外。      
    \# 添加清华TUNA镜像源有Anaconda仓库的镜像       
    conda config --add channels https://mirrors.tuna.tsinghua.edu.cn/anaconda/pkgs/free/    
    执行完之后，会生成~/.condarc(Linux/Maxc), 或C:\Users\USER_NAME\.condarc文件，记录着对conda的配置，直接手动创建和编辑该文件是一样的。    
    \# TUNA的help中镜像地址加有引号，需要去掉    
    \# 设置搜索时显示通道地址    
    conda config --set show_channel_urls yes   
    \# show所有添加的channels     
    conda config --show     

# 查看已安装的库或查看指定环境中的库     
    \# conda list  或 conda list -n python34   
    \# pip list     
 
#安装各种包之前，创建环境，例如:     
conda create -n python34 python=3.4     

# 查看已安装的环境     
conda info -e  #当前激活的环境会显示有一个星号或括号     

#激活环境     
activate python34     
     
#退出环境     
deactivate python34     
     
#删除一个已有的环境     
conda remove -n python34 --all     
     
#删除环境中的package     
conda remove -n python34 numpy     
     
#搜索package信息     
conda search numpy     

# 安装和更新库     
	pip install scipy     
	pip install scipy --upgrade     
	\# 或者     
	conda install scipy      
	或者   conda  install -n python34 numpy 指定环境安装numpy包     
	conda update scipy     
	或者   conda  update -n python34 numpy     
     
	\# 更新所有库     
	conda update --all     
     
	\# 更新 conda 自身     
	conda update conda     
     
	\# 更新 anaconda 自身     
	conda update anaconda     
 

         
     
