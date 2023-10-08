# 前言

基于ARL的二开，在原来的基础上优化一些细节，添加了Oneforall和两款未授权扫描插件FindJsInfo、PackerFuzzer和xray。



# 前端

因ARL的前端已经打包好，无法再次进行二开，故需要对前端进行重构，使用的是vue-element-admin后台模版，前后端修改、添加功能一共历时两个月。

目前已在用，子域名的搜索范围比原来的广泛，且优化了一些功能，减少无用数据入库。



# 效果

## 主页

显示数据详情

![image-20230830171826597](https://xingheimg.oss-cn-guangzhou.aliyuncs.com/img/202308301718667.png)

## SRC
各大SRC厂商的收录准则
![image](https://github.com/xinghe0/ARL2/assets/65886247/36241aba-bade-45a6-ba9c-8aaac67865d4)


## 任务

管理任务，扫描器的入口

![image-20230830172154015](https://xingheimg.oss-cn-guangzhou.aliyuncs.com/img/202308301721069.png)

## 详情

项目的具体情况，例如子域名数和漏洞等情况

![image-20230830172538399](https://xingheimg.oss-cn-guangzhou.aliyuncs.com/img/202308301725451.png)

## 指纹

![image-20230830173239339](https://xingheimg.oss-cn-guangzhou.aliyuncs.com/img/202308301732382.png)

剩下的功能和arl无二致，主要是一些功能的增强和细节的优化，总体来说还是蛮吃服务器配置，但是效果相比原来好许多，重构前端后，可随意增加功能插件（页面也好看了许多）



# 后续

后续会添加其他的实用功能，主当src漏洞挖掘的主力工具。

