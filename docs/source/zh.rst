中文说明
-------

介绍
^^^^^

欢迎上车。 我的名字是 Ernest，我是一名专业的软件工程师和解决方案专家，我已经做了 15 年以上的开发人员。 如果您在中国大陆旅行或逗留，我会在这里帮助您摆脱互联网限制和审查制度。

Awesome VPN 不与行业的全球领导者竞争，例如 Nord VPN 和 Express VPN。 它只是专注于如何处理好中国奇怪的网络政策，这样我们才能让您免受GFW的封锁。 如果您正在或计划留在中国，那么Awesome VPN 将是您的最佳选择。


独家特点
^^^^^^^

#. 平民价格享受专线的稳定和速度，全网独家；
#. 自动更换入口地址，确保稳定；
#. 所有连接方式全程强制进行加密，确保安全；
#. 使用无地址连接，确保长期稳定连接；
#. 无需安装APP或插件，确保易用；


如何支付
^^^^^^^^

* 方法一：申请Paypal账户并绑定信用卡
您只需要有一张VISA或MASTER颁发的信用卡即可完成支付；

* 方法二：请拥有信用卡的朋友代付
请你的一位已经拥有信用卡的朋友代为支付；

* 方法三：在Fiverr等网站找一位值得信任的商家代付

  * 在Upwork、Freelancer、Fiverr找一位值得信任的商家或自由职业者代付；
  * 例如：`推荐商家 <https://gitee.com/geek_tank/gitree/>`_
  * 请告知你的服务商需要付款的Paypal账户：**@orezm**
  * 注意：请谨慎选择为你服务的商家，Awesome VPN不为任何第三方主体的行为及其后果承担负责或作担保；


简易使用说明（PAC方式）
^^^^^^^^^^^^^^^^^^^^

* 这是全网最简单的联网方式；按照本指引只需一步即可完成配置，无需下载软件或插件；
* 准备：请确保您的浏览器支持设置自定义代理，推荐下载并安装Firefox（火狐浏览器）；
* Firefox官网下载链接：`点击这里 <https://www.mozilla.org/zh-CN/firefox/>`_
* 操作步骤：

  * 第一步：打开Firefox浏览器，将下面链接复制到自动代理配置中，点击确定即可完成设置；
  * 没有第二步

.. code:: txt

  https://www.orezm.com/basic.pac
  

* 详细说明：

  #. 打开Firefox，点击主菜单按钮并点击设置或首选项（见附图一）；
  #. 滚动至设置页面底部并点击“网络设置”右侧的设置按钮（见附图二）；
  #. 复制或输入PAC地址并点击确定（见附图三）；
  
* 完成设置后，即可通过Firefox访问国际互联网，其它应用仍保持原有联网方式，互不影响；
* PAC方式适用于电脑端（PC/Mac）的浏览器联网使用，如需手机使用请使用VPN方式联网；
* PAC为您的浏览器自动配置HTTPS代理服务器并使用SSL全程加密，因此您无须担心数据泄露；
* 附图：

  * 附图1
  .. image:: ../../docs/assets/step1.png

  * 附图2
  .. image:: ../../docs/assets/step2.png

  * 附图3
  .. image:: ../../docs/assets/step3.png


如何使用VPN方式进行联网
^^^^^^^^^^^^^^^^^^^^^

* Awesome VPN的联网方式使用思科标准，同时适用于iOS, Android, Windows, Mac；
* 准备：下载并安装AnyConnect软件

  * iOS，可以从大陆App Store直接下载
  * 安卓，`点击下载 <https://github.com/orezm/avc/releases/download/downloads/AnyConnect.apk>`_
  * Mac，`点击下载 <https://github.com/orezm/avc/releases/download/downloads/anyconnect-macos-4.10.01075-predeploy-k9.dmg>`_
  * Windows，`点击下载 <https://github.com/orezm/avc/releases/download/downloads/anyconnect-win-4.10.01075-predeploy-k9.zip>`_

* 操作步骤：

  * 第一步：打开Awesome VPN官网并登录，查看并复制您的AnyConnect专属连接地址；`点击这里登录 <https://www.orezm.com/my>`_
  * 第二步：打开AnyConnect软件，填写连接地址，点击连接按钮；

* 下载AnyConnect软件时，请注意版本号不应低于7.10；
* 大陆的iOS的App Store可以直接下载到最新版本的AnyConnect；
* Google Play或三星应用商店可以直接下载到最新版本的AnyConnect；
* 大陆品牌的应用商店也可以获取AnyConnect，但应特别注意版本；


如何使用Socks方式进行联网
^^^^^^^^^^^^^^^^^^^^^^^

* 仅限有经验的用户操作使用；
* 全程使用TLS加密，请务必确保您使用的客户端支持TLS连接；
* 推荐使用Clash客户端软件；
* 准备：下载并安装Clash：

  * Windows：Clash for Windows `点击下载 <https://github.com/orezm/avc/releases/download/downloads/anyconnect-win-4.10.01075-predeploy-k9.zip>`_
  * Mac：ClashX `点击下载 <https://github.com/orezm/avc/releases/download/downloads/ClashX.dmg>`_

* 操作步骤：

  * 第一步：打开Awesome VPN官网并登录，查看并复制您的Socks专属连接地址；`点击这里登录 <https://www.orezm.com/my>`_
  * 第二步：下载Clash配置模板 `点击下载 <https://github.com/orezm/avc/releases/download/downloads/config.yaml>`_
  * 第三步：使用任意纯文本编辑软件打开配置模板；
  * 第四步：将<server>替换为您的Socks连接地址；
  * 第五步：将<username>替换为您的用户名；
  * 第六步：将<password>替换为您的密码；
  * 第七步：打开Clash for Windows或ClashX，导入配置文件；
  * 第八步：本地代理地址127.0.0.1:7890


如何使用IPv6进行联网
^^^^^^^^^^^^^^^^^^
（即将发布）


如何使用专线流量
^^^^^^^^^^^^^^
* 在PAC联网方式中，将PAC地址更换为账户信息中的Standard地址即可享受专线流量；
* 在VPN联网方式中，将连接地址更新为账户信息中的Standard地址即可享受专线流量；
* 专线流量不支持Socks联网方式；


什么是专线流量
^^^^^^^^^^^^^

专线是指用户专用的跨国数据线路，通常用于中国大陆与国外两点之间的直接通信。区别于Internet，专线属于内网通讯，流量不经过审查，同时两点之间的线路经过特殊挑选和优化，因此延迟低、速度快并且稳定。

专线适用于跨国企业、外贸企业、使领馆等对联网的稳定性及速度有较高要求的单位或个人。

Awesome VPN在提供非常充足的基础流量之余，为每个基础版账户提供10G专线流量，为每个标准版账户提供30G专线流量，满足用户的各种需求。


账户信息说明
^^^^^^^^^^^

* Verification status：您的账户是否通过邮箱验证；
* Valid：您的账户有效期；
* Quota：您本月的流量额度，以“总额度/专线流量额度”的格式显示；
* Transferred：您本月的已用额度，以“总额度/专线流量额度”的格式显示；
* PAC Urls:您的PAC地址，其中Basic表示基础流量，Standard表示专线流量；
* AnyConnect Servers:您的AnyConnect连接地址，其中Basic表示基础流量，Standard表示专线流量；
* Socks Servers:您的Socks连接地址；

*(自豪地使用 Google 翻译)*
