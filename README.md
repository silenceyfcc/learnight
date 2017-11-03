# git 学习

## 一、安装git
#### sudo apt get install git  //Ubuntu


## 二、全局配置git 
#### git config --global user.name("silenceyfcc")  
#### git config --global user.email("sielnceyfcc@126.com")
### 查看配置
#### git config user.name
#### git config user.email 或 git config --list

## 三、创建版本库
#### 1、mkdir fielsname;
#### 2、cd filesname;
#### 3、git init;  //创建git仓库 

## 四、操作
#### git add filesname
#### git commit -m "描述"
#### git reflog 返回修改日志
#### git reset --hard HEAD(可以直接写HEAD的号码)
 

## 远程仓库
#### 1、创建SSH key
#### ssh-keygen -t rsa -C "silenceyfcc@126.com" 

#### 2、添加远程库
#### git remote add origin git@github.com:silenceyfcc/xx.git 
#### git push -u origin master

#### 3、克隆到本地
#### git clone git@github.com:silenceyfcc/xx.git 