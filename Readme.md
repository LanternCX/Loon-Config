# Loon 配置文件

参考自 [【iOS去开屏广告】LOON喂饭级说明书](https://idcflare.com/t/topic/36816)，针对平常写码的场景做了修改

主要实现功能：

- 基于节点名称的地区节点分类
- 可莉去广告全家桶（[插件中心](https://hub.kelee.one/)）
- Github、Telegram、流媒体、AI 服务规则分流

## Quick Start

1. 打开LOON → 配置 → 编辑 → 从URL下载：

  ```url
  https://raw.githubusercontent.com/LanternCX/Loon-Config/refs/heads/main/loon.lcf
  ```

2. 仪表 → 节点，添加订阅
3. 配置 → 勾选 脚本、复写、MitM，MitM选择证书管理安装证书；
4. 通用 → 关于本机 → 拉到最下面 证书信任设置 → 打开LOON的证书信任开关
5. 参照 [可莉推荐的Loon功能配置图](https://raw.githubusercontent.com/luestr/ProxyResource/main/Tool/Loon/Lcf/zh-CN/Resource/ConfigDiagram.png)，以便正确配置Loon的各项功能