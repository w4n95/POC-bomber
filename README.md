# POC-bomber
POC bomber 是一款漏洞检测工具，旨在利用大量POC快速发现目标脆弱性，节省人工检测漏洞的时间   
                                  
本项目收集互联网已知危害性大的漏洞POC并集成在 POC bomber 武器库中，利用大量POC对单个或多个目标进行模糊测试，以此快速获取目标服务器权限，适合红蓝对抗或hvv中红队快速找到突破口进入内网

支持weblogic，struct2，tp5，redis未授权访问等易受攻击组件的漏洞检测，支持单个目标检测和批量检测，支持多线程并能够在当前目录生成漏洞报告

## 用法      
      python3 poc_bomber.py 

配置文件:  /inc/config.py

目录结构:
       
      +--------- poc_bomber.py (启动 POC-bomber)
      | 
      +--------- inc(存放支撑 POC-bomber 框架运行的核心文件)
      |
      \--------- pocs(POC存放列表)----------- framework(存放框架漏洞POC)
                                      |
                                      |------ middleware(中间件漏洞POC)
                                      |
                                      |------ ports(常见端口漏洞,主机服务漏洞POC)
                                      |
                                       \----- webs(常见web页面漏洞POC)
      
      
## Screenshots    
![image](https://user-images.githubusercontent.com/71172892/143585798-9d7e505d-42f0-4b8f-ae0c-fd400466f2b5.png)
![image](https://user-images.githubusercontent.com/71172892/143586027-5e54e484-edc7-4551-a536-4f005efa5048.png)      

项目持续更新中，欢迎各位师傅贡献POC共筑网络安全！  
有问题欢迎issues留言: https://github.com/tr0uble-mAker/POC-bomber/issues    
联系: 929305053@qq.com    
