
> 注：当前项目为 Serverless Devs 应用，由于应用中会存在需要初始化才可运行的变量（例如应用部署地区、服务名、函数名等等），所以**不推荐**直接 Clone 本仓库到本地进行部署或直接复制 s.yaml 使用，**强烈推荐**通过 `s init ` 的方法或应用中心进行初始化，详情可参考[部署 & 体验](#部署--体验) 。

# nas-manaer 帮助文档
<p align="center" class="flex justify-center">
    <a href="https://www.serverless-devs.com" class="ml-1">
    <img src="http://editor.devsapp.cn/icon?package=nas-manager&type=packageType">
  </a>
  <a href="http://www.devsapp.cn/details.html?name=nas-manager" class="ml-1">
    <img src="http://editor.devsapp.cn/icon?package=nas-manager&type=packageVersion">
  </a>
  <a href="http://www.devsapp.cn/details.html?name=nas-manager" class="ml-1">
    <img src="http://editor.devsapp.cn/icon?package=nas-manager&type=packageDownload">
  </a>
</p>

<description>
管理阿里云的Nas, 使用Kodbox进行可视化管理
</description>

<codeUrl>

- [:smiley_cat: 代码](https://github.com/devsapp/nas-manager)

</codeUrl>
<preview>



</preview>


## 前期准备

使用该项目，您需要有开通以下服务：

<service>



| 服务 |  备注  |
| --- |  --- |
| 函数计算 FC |   |
| 文件存储 NAS |   |

</service>

推荐您拥有以下的产品权限 / 策略：
<auth>
</auth>

<remark>



</remark>

<disclaimers>

免责声明：   
免责声明：

1. 该项目的软件部分由开源社区贡献，阿里云仅提供了算力及存储支持；

</disclaimers>

## 部署 & 体验

<appcenter>
   
- :fire: 通过 [Serverless 应用中心](https://fcnext.console.aliyun.com/applications/create?template=nas-manager) ，
  [![Deploy with Severless Devs](https://img.alicdn.com/imgextra/i1/O1CN01w5RFbX1v45s8TIXPz_!!6000000006118-55-tps-95-28.svg)](https://fcnext.console.aliyun.com/applications/create?template=nas-manager) 该应用。
   
</appcenter>
<deploy>
    
- 通过 [Serverless Devs Cli](https://www.serverless-devs.com/serverless-devs/install) 进行部署：
  - [安装 Serverless Devs Cli 开发者工具](https://www.serverless-devs.com/serverless-devs/install) ，并进行[授权信息配置](https://docs.serverless-devs.com/fc/config) ；
  - 初始化项目：`s init nas-manager -d nas-manager `
  - 进入项目，并进行项目部署：`cd nas-manager && s deploy - y`
   
</deploy>

## 应用详情

<appdetail id="flushContent">

## 前期准备

使用该项目，您需要有开通以下服务：

| 服务 | 备注 |
| --- | --- |
| 函数计算 FC |  |
| 文件存储 NAS |  |


推荐您拥有以下的产品权限 / 策略：

## 应用介绍文档

### 应用详情

使用阿里云函数计算部署开源大模型应用，提供兼容openai规范的接口和[ChatGPT-Next-Web](https://github.com/Yidadaa/ChatGPT-Next-Web)客户端.
![image.png](https://intranetproxy.alipay.com/skylark/lark/0/2023/png/13970/1693222399152-69e625af-13c9-4d4a-8d68-2b0475921622.png#clientId=u0542e5c1-914e-4&from=paste&height=730&id=ue7c46bb6&originHeight=1460&originWidth=2986&originalType=binary&ratio=2&rotation=0&showTitle=false&size=3207417&status=done&style=none&taskId=ud6ce1730-09f2-407c-8443-9a4723f48ea&title=&width=1493)
![image.png](https://intranetproxy.alipay.com/skylark/lark/0/2023/png/13970/1693221028075-582cc6e4-9728-4703-bde7-911bc3c6b00a.png#clientId=ude024fc4-380f-4&from=paste&height=893&id=u2439d332&originHeight=1786&originWidth=3580&originalType=binary&ratio=2&rotation=0&showTitle=false&size=5320998&status=done&style=none&taskId=u534cd37f-6b4a-4a56-bce5-ad6906be4db&title=&width=1790)

## 使用文档
### 函数计算应用中心部署方案
#### 选择应用模版
登录到阿里云函数计算控制台->应用->创建应用
选择nas-manager应用模板点击"立即创建"




</appdetail>

## 使用文档

<usedetail id="flushContent">

### 常见问题

</usedetail>


<devgroup>


## 开发者社区

您如果有关于错误的反馈或者未来的期待，您可以在 [Serverless Devs repo Issues](https://github.com/serverless-devs/serverless-devs/issues) 中进行反馈和交流。如果您想要加入我们的讨论组或者了解 FC 组件的最新动态，您可以通过以下渠道进行：

<p align="center">  

| <img src="https://serverless-article-picture.oss-cn-hangzhou.aliyuncs.com/1635407298906_20211028074819117230.png" width="130px" > | <img src="https://serverless-article-picture.oss-cn-hangzhou.aliyuncs.com/1635407044136_20211028074404326599.png" width="130px" > | <img src="https://serverless-article-picture.oss-cn-hangzhou.aliyuncs.com/1635407252200_20211028074732517533.png" width="130px" > |
| --------------------------------------------------------------------------------------------------------------------------------- | --------------------------------------------------------------------------------------------------------------------------------- | --------------------------------------------------------------------------------------------------------------------------------- |
| <center>微信公众号：`serverless`</center>                                                                                         | <center>微信小助手：`xiaojiangwh`</center>                                                                                        | <center>钉钉交流群：`33947367`</center>                                                                                           |
</p>
</devgroup>
