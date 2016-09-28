# cluster_tools
[说明]

  集群工具  ssh免密码   文件同步    时间同步 等等   没事自己搞着玩   目前准备打包centos 6 下的rpm包
  
[ssh免密码工具]

  目的：
  
    管理集群时，配置master与node实现ssh免密码。
    
  工具名称:
  
    ssh-skip-pwd
    
  语言:python
  
  使用方法:
  
    ssh-skip-pwd  -u <username>  -p <password>  -f  <hostlist>
    
  参数解释:
  
    u:  准备做免密码的用户;
    
    f:  hostlist文件  里面时host列表
    文件内容实例:
      hostname1(ip1)
      hostname2(ip2)
      hostname3(ip3)
      hostname4(ip4)
    
    p:  password 用户密码,要求所有机器上用户密码一致.
    

