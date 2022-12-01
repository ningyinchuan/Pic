- 防火墙

  ```shell
  # 查看防火墙状态
  systemctl status firewalld
  # 查看规则
  firewall-cmd --zone=public --list-ports
  # 开放端口
  firewall-cmd --zone=public --add-port=80/tcp --permanent
  # 删除端口
  firewall-cmd --zone=public --remove-port=80/tcp --permanent
  # 配置生效
firewall-cmd --reload
  ```
  
  

