# HMER
这个是小学生数学作业检测的代码仓库
是三个小学生


## 相关论文


## 实现方法
计划：把CoMER中的encoder改了，准备用DW-ViT,结构如下图

注意：拼接函数可以考虑torch.cat。DW-ViT的头要改，官方给定的是一个分类头。在改forward过程中要加mask！



# 一些技巧
## 后台挂起
   nohup : http://t.csdn.cn/FrqDm
   
   命令：nohup command > myout.file 2>&1 &
   
   注：退出终端之后用jobs看不到nohup挂起的文件，要用ps/ps-aux
   
   也可以用screen
   
   'screen -R [终端名]'. 新建终端
   
   按'ctrl+a d'终端放到后台. 
   
   'screen -ls'查看终端. 
   
   'screen -r [pid/终端名]'进入之前放在后台的终端.
   
   在新终端里确定不用了，直接输入'exit'删除
 
