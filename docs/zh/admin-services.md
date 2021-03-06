# 服务启停

使用由Websoft9提供的 Odoo 部署方案，可能需要用到的服务如下：

## Linux

### Odoo

```shell
sudo systemctl start odoo
sudo systemctl stop odoo
sudo systemctl restart odoo
sudo systemctl status odoo
```

### Nginx

```shell
sudo systemctl start nginx
sudo systemctl stop nginx
sudo systemctl restart nginx
sudo systemctl status nginx
```

### PostgreSQL

```shell
sudo systemctl start postgresql
sudo systemctl stop postgresql
sudo systemctl restart postgresql
sudo systemctl status postgresql
```

## Windows

如果您使用的是 Windows系统，Odoo 服务重启两种方式：

*  方式1: 【开始】>【管理工具】>【服务】，找到 odoo-server，便可以完成**重启/停止/暂停**等操作
*  方式2: 【开始】>【运行】，输入`cmd`，打开命令操作窗口
   ```
   net start odoo-server-12.0 #启动服务
   net stop odoo-server-12.0 #停止服务
   ``` 