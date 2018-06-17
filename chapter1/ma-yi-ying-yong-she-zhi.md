**蚂蚁金服应用设置**

我们为您开通后台之后，您可以我们平台配置你的蚂蚁应用信息。  完成配置之后，你邀请公司的支付流水直接走你的支付宝后台。由蚁蚂金服为你返佣结算 （最终解释权归蚁蚂金服所有）。

1. **如何配置应用信息**

进入后台，系统&gt;蚂蚁金服应用&gt;添加![](/assets/import.png)注意应用类型选择，如果您应用是用于物业缴费那么请选择物业缴费 ， 其它参数的需要在蚂蚁金服申请了应用之后获得，下面我会再进行介绍。 ![](/assets/import2.png)

**2.申请蚂蚁金服应用 **

进入蚂蚁金服务的官网 ： [https://open.alipay.com/platform/home.htm](https://open.alipay.com/platform/home.htm)

物业缴费相关： [https://open.alipay.com/platform/banner.htm?page=tenement](https://open.alipay.com/platform/banner.htm?page=tenement)

中小学缴费相关：[https://open.alipay.com/platform/banner.htm?page=edu](https://open.alipay.com/platform/banner.htm?page=edu)

进入官网后登陆 , 选择开发者中心，创建应用

![](/assets/import3.png)

![](/assets/import4.png)应用的名称和图标你可以根据自己的需要填写 （比如，物业相关的应用，填写XX物业缴费 。 中小学的应用可以写XX小中学费 ， 名称之后也可以改）。 ![](/assets/import6.png)

创建完成之后，给应用添加能力。

![](/assets/import7.png)如果是物业相关应用，请添加如下功能（这样才能正常使用）：

![](/assets/import9.png)如果是中小学缴费应用，请添加如下功能

![](/assets/import90.png)添加完功能之后，给应用设置回调地址（应用信息）。 这里很重要，应用网关和授权回调地址一定不能填错，否则无法完成支付流程。（无论是中小学还是物业应用，这里的地址填写都一样）

应用网关：https://service.boxphp.me/api/openapi/gateway

授权回调地址：https://service.boxphp.me/admin/home/auth ![](/assets/import12.png)

![](/assets/import12.png)

![](/assets/import12.png)



