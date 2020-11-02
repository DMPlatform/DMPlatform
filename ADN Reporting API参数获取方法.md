## 优量汇

请向优量汇对接人申请开通Cruis API或优量汇API权限

如您使用腾讯广告联盟Cruis API，需获取member_id、agid、appid和appkey参数

如您使用腾讯优量汇API，需获取memberid和secret参数

## 百青藤

请向百青藤对接人申请开通Baidu MSSP API权限、获取Access Key参数

## Admob

1. **API KEY**

     - 为获取**API KEY**, 您需要在 [Google Cloud Console](https://console.cloud.google.com/home)创建项目(project)。如果您此前没有创建过project，您将需要花几分钟创建一个新的project并同意 **Terms of Service。**填入项目名后点击 ‘**Create',**  完成项目的设置。
     ![img](https://bytedance.feishu.cn/space/api/box/stream/download/asynccode/?code=1c6b2af280921180c2191640679e4b6c_8f118824ce50c961_boxcnWLzQRsMieYYhHbfZFaEfFd_A8Fumn5q5Lx1XavJMOfs35RScRHsnJtX)

     - 回到首页，找到Getting Started, 您应该选择 “**Enable APIs and get credentials like keys**“:
     ![img](https://bytedance.feishu.cn/space/api/box/stream/download/asynccode/?code=2f66e12830d05b8b4fa82f94e1aa8e89_8f118824ce50c961_boxcniLXZrgTAPfrhmt8nuG5yrc_ybcMBtYfFChAmh6bZtUIKOBaZqV19hRO)

     - 接着，在左侧找到‘**Credentials**‘
     ![img](https://bytedance.feishu.cn/space/api/box/stream/download/asynccode/?code=9b0d063b96b7258fdbda5a80257e631c_8f118824ce50c961_boxcnv05fGtgxtCHvYppNKH5z8c_HVZPknqq9z6d1DcoVucwoI0nmKXhiHdb)

     - 选择 ‘**Create credentials**‘ 并在下拉菜单中选择‘**API Key**‘.
     ![img](https://bytedance.feishu.cn/space/api/box/stream/download/asynccode/?code=932c10b88ce51f1966888af3b749ef03_8f118824ce50c961_boxcncGq59YV6FLskSL6neDUvza_bB7YtvgCB89PB8JkeV8rZhssygLN8bLi)

     - 系统会自动生成一个API Key
     ![img](https://bytedance.feishu.cn/space/api/box/stream/download/asynccode/?code=57f83f0ea583d659c349082d49c6ff45_8f118824ce50c961_boxcngZfXJlr8A8wVDcklcsubte_h8qVnEAoHYPuCQGeBnHFWbSKU5EcRWI7)

     - 后续您仍能通过 **Credentials** 找到 **API Key**:
     ![img](https://bytedance.feishu.cn/space/api/box/stream/download/asynccode/?code=ea6d8f272aff44fa2a674320ec1a79d4_8f118824ce50c961_boxcnTgehHmman1MKpKHJtdE1Vd_WLWp4CbM2K0y6pCPlEi628ShQrIuytP5)

2. **Client ID & Client Secret**

     - 想要获得您的 **Client ID & Client Secret**, 请访问 [Google’s API Manager](https://console.cloud.google.com/apis).
     
     - 选中您在第一步中创建的项目（Project）并选中左侧‘**OAuth consent screen’** tab. 在这个页面填入**Product Name**. 点击 **Save保存**:
     ![img](https://bytedance.feishu.cn/space/api/box/stream/download/asynccode/?code=f72e858906a611c4c2fde1c5c49a2596_8f118824ce50c961_boxcnMtnT0KsHgYJKq2tgz0zQRh_Jh6wXUGI1E7XsjuCK2q76FwhZCvylj0Y)

     - 在左侧侧边栏, 选择 ‘**Dashboard‘,** 选择 ‘**ENABLE APIS AND SERVICES**‘:
     *|*![img](https://bytedance.feishu.cn/space/api/box/stream/download/asynccode/?code=3c822fe093010ed2db663f89b6740813_8f118824ce50c961_boxcn6EZALyNSp1NhHj45DSKlsb_2cf4Cv7RX2gNY1VF61iq37cYvQDuHYvf)

     - 在API列表中搜索Adsense Manegement API，选择‘**Enable**‘ 激活
     *|*![img](https://bytedance.feishu.cn/space/api/box/stream/download/asynccode/?code=aa9f194c50742bf4c87000796b3b9716_8f118824ce50c961_boxcn1voHNwBprvDsT1JuQrmIaf_eeJBBckfYDCkFDW6gv4Mwv95mvQwBgos)
     *|*![img](https://bytedance.feishu.cn/space/api/box/stream/download/asynccode/?code=69390aeea39c4bb2a43333f78045e21f_8f118824ce50c961_boxcn7jtARk7RXiNJym92maNgfc_6M4dXB8eXgfNsSLdlj5mzztwHl1e3dCe)

     - **在左边侧边栏选择Credentials**. 选择 ‘**Create Credentials’** 下拉菜单并选择 ‘**OAuth client ID’**
     *|*![img](https://bytedance.feishu.cn/space/api/box/stream/download/asynccode/?code=2030f77a42fca98cbd6c15646049a480_8f118824ce50c961_boxcnmZUKLO7bNCxoM2Q9enF9me_yjgbI9xMkiTe39vGHu4cRcuMrdygMj9s)

     - 选择 **Web application**, 并填入一个app的名称。需要在**Authorized redirect URI** 填入 https://developers.google.com/oauthplayground . 比如下图:
     *|*![img](https://bytedance.feishu.cn/space/api/box/stream/download/asynccode/?code=c232e56ab9d4eb1c94abe2eb66fa9242_8f118824ce50c961_boxcnfgyJUjqKywRKWA0VgE8BJe_hkyQeTQLDfnKAnc7phGW1qjmtAUWg46F)


     - 点击 ‘**Create**‘ 就会生成 ‘**Client ID**‘ 和‘**Client Secret**‘:
     *|*![img](https://bytedance.feishu.cn/space/api/box/stream/download/asynccode/?code=1e45274cbfa5bc16b3c60bc3ded41b4e_8f118824ce50c961_boxcnlB94N4kgWmnKrXRRcWvFJd_fTxWGSbGg6tdjcW08R4AP42HA4edgyOv)

3. **Refresh Token**

     - 为了获得**Refresh Token**, 您需要到 [**OAuth 2.0 Playground**](https://developers.google.com/oauthplayground/#step1&scopes=https://www.googleapis.com/auth/adwords&url=https://&content_type=application/json&http_method=GET&useDefaultOauthCred=checked&oauthEndpointSelect=Google&oauthAuthEndpointValue=https://accounts.google.com/o/oauth2/auth&oauthTokenEndpointValue=https://www.googleapis.com/oauth2/v3/token&includeCredentials=unchecked&accessTokenType=bearer&autoRefreshToken=unchecked&accessType=offline&forceAprovalPrompt=checked&response_type=code)**.**
     - 点击右上角的设置按钮. 将 **Force  prompt** 置为 NO 并 勾选 **Use your own OAuth credentials**. 输入刚才获得的 **Client ID** 和 **Client Secret:**
     *|*![img](https://bytedance.feishu.cn/space/api/box/stream/download/asynccode/?code=290c025c6fc6fb888059bb5903d30146_8f118824ce50c961_boxcnGb2qtmoJag3mzTsDINkHLe_zGa3a44NVRDBGF1xZdgjwc8QNzhJ53UT)

     - 接着, 在 **Step 1: Select & Authorize APIS**处，选择 ‘[**https://www.googleapis.com/auth/adsense.readonly**](https://www.googleapis.com/auth/adsense.readonly)**’** 并勾选 ‘**Authorize APIs**‘:
     *|*![img](https://bytedance.feishu.cn/space/api/box/stream/download/asynccode/?code=871d945b0079ac7dc81b0d6fee1cbbc6_8f118824ce50c961_boxcnfcWT6hBT8A979DrvVUlwmg_nyroQtH6S9pc67iscgZn8HOHC7Q66ScB)

     - 授予Adsense获取您的Admob账号数据的权限
     - 点击 **Exchange authorization code for tokens，**您将获得您的**Refresh token**:
     *|*![img](https://bytedance.feishu.cn/space/api/box/stream/download/asynccode/?code=1c3361cc1382a1afb5f3163d51eb7e54_8f118824ce50c961_boxcnWI2tbKamAH49aM5OvAgZFd_Ao5DE8SLcj5M7tPZ7NC80nU6seZ0yEhD)

## Unity

**Organization Core ID**

登陆账号后，在“Operate”-“Settings”-“Organization info”中即可找到Organization Core ID

![img](https://bytedance.feishu.cn/space/api/box/stream/download/asynccode/?code=3b92a1c52e956a5c3e8bd48f920218ed_8f118824ce50c961_boxcnfnCawt8WHuWuFAonw0cWue_MwzrrS3Nia2hQSBkSCPV8zfbmLae41Gy)

**API Key**

登陆账号后，在“Operate”-“Ads Data Export”-“API Access”-“Monetization Stats APl Access”中即可找到API Key

![img](https://bytedance.feishu.cn/space/api/box/stream/download/asynccode/?code=01c27fa2128d98d960ebd699dc7e205e_8f118824ce50c961_boxcnxFiRvacv65WVZuSPG8b7Cg_Qkg6cmpyusaEhXRmNQ74KJ8V1FeCYeA6)

## Mintegral

**SKey&Secret**

登陆账号后，在“账户管理”-“接口工具”-“统计接口”中即可找到 Skey和Secret。
