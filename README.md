# privoxy2direct

从
[dnsmasq-china-list](https://github.com/felixonmars/dnsmasq-china-list/)
和你的定制的文件中创建privoxy的action文件来加快网络连接。
配置privoxy使其直连在dnsmasq-china-list中的域名。

generate privoxy action from
[dnsmasq-china-list](https://github.com/felixonmars/dnsmasq-china-list/)
and your custom file to accelerate connection.
configure privoxy to connect to the domain in dnsmasq-china-list directly.

## 用法

下载或更新dnsmasq-china-list配置文件（需要wget）。
```bash
./update_dnsmasq-china-list
```

生成并且安装privoxy的action。
如果添加`CUSTOM_DOMIN`参数，把`CUSTOM_DOMIN`追加到`custom.txt`。
```bash
./privoxy2direct [CUSTOM_DOMIN]
./privoxy2direct .jandan.net
```

## usage

download or update dnsmasq-china-list conf files (require wget).
```bash
./update_dnsmasq-china-list
```

generate and install privoxy action. if `CUSTOM_DOMIN` is passed, add `CUSTOM_DOMIN` to `custom.txt`.
```bash
./privoxy2direct [CUSTOM_DOMIN]
./privoxy2direct .jandan.net
```
