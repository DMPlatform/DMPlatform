## 优量汇

请向优量汇对接人申请开通Cruis API或优量汇API权限

如您使用腾讯广告联盟Cruis API，需获取member_id、agid、appid和appkey参数

如您使用腾讯优量汇API，需获取账户id和密钥secret参数

请注意：Cruis API将在2021年2月28日下线，请在此之前联系优量汇对接人申请开通优量汇Reporting API，完成Cruis API功能和服务的迁移及替换

## 快手联盟

请向快手联盟对接人申请开通快手Reporting API权限、获取Access Key和Security Key参数

## 百青藤

请向百青藤对接人申请开通Baidu MSSP API权限、获取Access Key参数

## Admob

1. **API KEY**

     - 为获取**API KEY**, 您需要在 [Google Cloud Console](https://console.cloud.google.com/home)创建项目(project)。如果您此前没有创建过project，您将需要花几分钟创建一个新的project并同意 **Terms of Service。**填入项目名后点击 ‘**Create',**  完成项目的设置。
     ![img](https://i.loli.net/2020/11/08/rpKZY64ac3UA9og.png)

     - 回到首页，找到Getting Started, 您应该选择 “**Enable APIs and get credentials like keys**“:
     ![2.png](https://i.loli.net/2020/11/08/YhWvXdLcBMimpg3.png)

     - 接着，在左侧找到‘**Credentials**‘
     ![image.png](https://i.loli.net/2020/11/08/yBqGwsdTc9uFVC5.png)

     - 选择 ‘**Create credentials**‘ 并在下拉菜单中选择‘**API Key**‘.
     ![image.png](https://i.loli.net/2020/11/08/avkGUyZFonxrROH.png)

     - 系统会自动生成一个API Key
     ![image.png](https://i.loli.net/2020/11/08/6f1poytmF8czdvI.png)

     - 后续您仍能通过 **Credentials** 找到 **API Key**:
     ![image.png](https://i.loli.net/2020/11/08/Q64neEHI9NucrOm.png)

2. **Client ID & Client Secret**

     - 想要获得您的 **Client ID & Client Secret**, 请访问 [Google’s API Manager](https://console.cloud.google.com/apis).
     
     - 选中您在第一步中创建的项目（Project）并选中左侧‘**OAuth consent screen’** tab. 在这个页面填入**Product Name**. 点击 **Save保存**:
     ![image.png](https://i.loli.net/2020/11/08/cBTvyJxSDHpsU4O.png)

     - 在左侧侧边栏, 选择 ‘**Dashboard‘,** 选择 ‘**ENABLE APIS AND SERVICES**‘:
     ![image.png](https://i.loli.net/2020/11/08/r7q1t4SUgIcJVDn.png)

     - 在API列表中搜索Adsense Manegement API，选择‘**Enable**‘ 激活
     ![image.png](https://i.loli.net/2020/11/08/unxj3rvEqJX69HT.png)
     ![image.png](https://i.loli.net/2020/11/08/cF2QkWXN1OYuoBh.png)

     - **在左边侧边栏选择Credentials**. 选择 ‘**Create Credentials’** 下拉菜单并选择 ‘**OAuth client ID’**
     ![image.png](https://i.loli.net/2020/11/08/RU9aXF4joBSM5d3.png)

     - 选择 **Web application**, 并填入一个app的名称。需要在**Authorized redirect URI** 填入 https://developers.google.com/oauthplayground . 比如下图:
     ![image.png](https://i.loli.net/2020/11/08/F2dMZ5hWPOXJS3x.png)

     - 点击 ‘**Create**‘ 就会生成 ‘**Client ID**‘ 和‘**Client Secret**‘:
     ![image.png](https://i.loli.net/2020/11/08/Zt4uzsWYVpTRSqc.png)

3. **Refresh Token**

     - 为了获得**Refresh Token**, 您需要到 [**OAuth 2.0 Playground**](https://developers.google.com/oauthplayground/#step1&scopes=https://www.googleapis.com/auth/adwords&url=https://&content_type=application/json&http_method=GET&useDefaultOauthCred=checked&oauthEndpointSelect=Google&oauthAuthEndpointValue=https://accounts.google.com/o/oauth2/auth&oauthTokenEndpointValue=https://www.googleapis.com/oauth2/v3/token&includeCredentials=unchecked&accessTokenType=bearer&autoRefreshToken=unchecked&accessType=offline&forceAprovalPrompt=checked&response_type=code)**.**
     - 点击右上角的设置按钮. 将 **Force  prompt** 置为 NO 并 勾选 **Use your own OAuth credentials**. 输入刚才获得的 **Client ID** 和 **Client Secret:**
     ![image.png](https://i.loli.net/2020/11/08/Zt4uzsWYVpTRSqc.png)

     - 接着, 在 **Step 1: Select & Authorize APIS**处，选择 ‘[**https://www.googleapis.com/auth/adsense.readonly**](https://www.googleapis.com/auth/adsense.readonly)**’** 并勾选 ‘**Authorize APIs**‘:
     ![image.png](https://i.loli.net/2020/11/08/53fw17ZIisdRPXY.png)

     - 授予Adsense获取您的Admob账号数据的权限
     - 点击 **Exchange authorization code for tokens，**您将获得您的**Refresh token**:
     ![image.png](https://i.loli.net/2020/11/08/7d958IxEunRzGK4.png)

## Unity

**Organization Core ID**

登陆账号后，在“Operate”-“Settings”-“Organization info”中即可找到Organization Core ID

![image.png](https://i.loli.net/2020/11/08/PmDQ3XGUWEef4cn.png)

**API Key**

登陆账号后，在“Operate”-“Ads Data Export”-“API Access”-“Monetization Stats APl Access”中即可找到API Key

![image.png](https://i.loli.net/2020/11/08/ThVf41MD3OZ6njC.png)

## Sigmob

请向Sigmob对接人申请开通Sigmob Reporting API权限、获取Public Key和Secure Key参数

## Mintegral

**SKey&Secret**

登陆账号后，在“账户管理”-“接口工具”-“统计接口”中即可找到 Skey和Secret

![image.png](https://i.loli.net/2020/11/08/fyKB4Zu3i7ajQHm.png)
