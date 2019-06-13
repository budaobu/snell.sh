
Debian & Ubuntu 运行

```
wget --no-check-certificate -O snell.sh https://raw.githubusercontent.com/budaobu/snell.sh/master/snell.sh
chmod +x snell.sh
./snell.sh
```

Centos & RedHat 运行

```
wget --no-check-certificate -O snell.sh https://raw.githubusercontent.com/budaobu/snell.sh/master/snell.centos.sh
chmod +x snell.sh
./snell.sh
```

首次安装默认端口号13254，可在配置文件中修改

```
vi /etc/snell/snell-server.conf
systemctl restart snell
```


查看运行状态：

```
systemctl status snell
```

卸载方法：

```
wget --no-check-certificate -O uninstall-snell.sh https://raw.githubusercontent.com/budaobu/snell.sh/master/uninstall-snell.sh
chmod +x uninstall-snell.sh
./uninstall-snell.sh
```
