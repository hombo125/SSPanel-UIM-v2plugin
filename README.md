## 更新安装脚本测试版本
脚本不再从github拉取docker-compose.yml,而是自己生成，添加自定义镜像，默认是我提供的升级版镜像
## 更新镜像（测试）
升级核心,原镜像hulisang/v2ray_v3:go还可以使用

## 增加自定义DNS，增加数据库连接
在脚本中选择即可，测试通过

## 支持对接SSRPanel
欢迎测试

教程写在了wiki里

使用方法：

```
mkdir v2ray-agent  &&  \
cd v2ray-agent && \
curl https://raw.githubusercontent.com/hulisang/v2ray-sspanel-v3-mod_Uim-plugin/dev/install.sh -o install.sh && \
chmod +x install.sh && \
bash install.sh
```
path极力不推荐使用/v2ray了（大家懂的）



感恩原作者rico辛苦付出
本人仅做备份和后续维护
caddy镜像更新支持tls1.3
