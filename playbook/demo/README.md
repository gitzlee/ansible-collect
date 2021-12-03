

### 说明

此 playbook 并无实际用处，仅用作demo测试使用

默认会在目标主机的`/tmp`下新创建文件`demo.conf`，并打印netstat信息

若配置 `netstat: False` 则取消打印 netstat信息


### 使用 

1：修改hosts文件

2：ansible-playbook -i hosts main.yml



ssh连接配置参考

```yaml
ansible_ssh_host # 目标主机地址
ansible_ssh_port # 目标主机端口，默认22
ansible_ssh_user # 目标主机用户
ansible_ssh_pass # 目标主机ssh密码
ansible_sudo_pass # sudo密码
```

