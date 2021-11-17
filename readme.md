#### 安装部署

```
pip install supervisor

echo_supervisord_conf > supervisord.conf

mkdir $WORKPATH/conf.d $WORKPATH/log

## 更改supervisord.conf和conf.d/project_name.conf相关配置

supervisord -c supervisord.conf  ## 可配置开机自启动
```
