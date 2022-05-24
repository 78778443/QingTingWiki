## CLI运行

### 下载命命令

蜻蜓的CLI命令目前仅支持Linux运行,执行如下命令自动下载
```zsh
curl -L http://qingting.starcross.cn/static/files/qingting > /usr/local/bin/qingting && chmod 755 /usr/local/bin/qingting
```

### 写入配置文件

需要你添加配置才可以运行,token在web页面中的个人设置里可以找到;`usce_id`在装备武器列表中的ID列中找到
```zsh
echo  '{"token": "4b2d6574e1xxxxxx8647f23295137b66", "usce_id": "6"}'  > ~/.qingting_config.json
```

### 使用命令：

使用方法非常简单,参考命令如下所示
```zsh
qingting --target 'http://txy8g.songboy.site:10001/'
```

返回信息如下所示

```zsh
添加目标成功,扫描结果请在页面[http://qingting.starcross.cn/target/detail.html?id=35197}]查看
```