本篇将介绍不同ADN Reporting API参数获取方法，包括优量汇、快手联盟、百青藤、admob、unity、sigmob、mintegral和自定义adn。

## 优量汇
1、权限：添加前请确保您的账号已拥有「优量汇API」权限
2、必填参数：
![image](https://github.com/DMPlatform/DMPlatform/assets/26924924/33220836-6ff7-4501-b055-4d4a2aa4f7a0)
- 账号名称：用于区分您在该广告网络下的不同账号，平台不做正确性校验
- 报表API权限：打开后，GroMore可拉取API数据，建议打开
- 账户id：对应“ID”，可在优量汇后台获取
- Secret：对应“我的密钥”，可在优量汇后台获取
![image](https://github.com/DMPlatform/DMPlatform/assets/26924924/cb25842b-fa45-4a80-b2e4-1bddad2458bf)
- 广告网络ID：如为自定义ADN接入，需填写


## 快手联盟
1、权限：添加前请确保您的账号已拥有「快手API」权限
2、必填参数：
- 账号名称：用于区分您在该广告网络下的不同账号，平台不做正确性校验
- 报表API权限：打开后，GroMore可拉取API数据，建议打开
- Access Key：线下获取
- Security Key：线下获取
- 广告网络ID：如为自定义ADN接入，需填写

## 百青藤
1、权限：添加前请确保您的账号已拥有「百度API」权限
2、必填参数：
- 账号名称：用于区分您在该广告网络下的不同账号，平台不做正确性校验
- 报表API权限：打开后，GroMore可拉取API数据，建议打开
- Access Key：可在百青藤后台「账号管理-API管理」获取
- 私钥：与“公钥”一同生成
![image](https://github.com/DMPlatform/DMPlatform/assets/26924924/2f271fe7-1a78-4631-9652-d67b19bf5f33)
- 广告网络ID：如为自定义ADN接入，需填写

  
## Admob
1、权限：添加前请确保您的账号已拥有「Admob API」权限
2、必填参数：
- 账号名称：用于区分您在该广告网络下的不同账号，平台不做正确性校验
- 报表API权限：打开后，GroMore可拉取API数据，建议打开
- API Key：可在「Credentials」获取，操作步骤如下
- Client ID & Client Secret：可在「Credentials」获取，操作步骤如下
- Refresh Token：可在「Credentials」获取，操作步骤如下
- 广告网络ID：如为自定义ADN接入，需填写
  
 **API KEY**
  - Step 1：在 [**Google Cloud Console**](url:https://console.cloud.google.com/home) 创建/选择一个项目(project)
  - Step 2：从首页 -> Getting Started -> Enable APIs and get credentials like keys，进入「APIs & Services」
  - Step 3：从Credentials -> CREATE CREDENTIALS -> API key，自动生成一个API key
  - Step 4：后续则可通过「Credentials」找到API Key
<figure>
<img src="https://github.com/DMPlatform/DMPlatform/assets/26924924/27a334f9-1b89-4a95-95cb-b578eb28c3c4" width=450/>
<img src="https://github.com/DMPlatform/DMPlatform/assets/26924924/dce8bef9-77e3-48df-982c-15c92598aea1" width=500/>   
</figure>


**Client ID & Client Secret**
  - Step 1：选中一个项目(project)，从OAuth consent screen进入，填入Product Name
  - Step 2：从Dashboard -> ENABLE APIS AND SERVICES进入，搜索Adsense Manegement API，点击“ENABLE”激活
    ![image](https://github.com/DMPlatform/DMPlatform/assets/26924924/5d2ad7c8-0719-4b3e-8f15-76a4a43468ed)![image](https://github.com/DMPlatform/DMPlatform/assets/26924924/311bddca-6842-4a85-828c-141aebdb276d)
  - Step 3：从Credentials -> CREATE CREDENTIALS -> OAuth client ID进入，选择“Web application”、填入“APP名称“和“Authorized redirect URI”，即可生成Client ID & Client Secret
    ![image](https://github.com/DMPlatform/DMPlatform/assets/26924924/3db818cb-e020-468b-bde9-665d8e3a6119)![image](https://github.com/DMPlatform/DMPlatform/assets/26924924/c469840d-94df-4afb-964b-4d2383bf3db4)


 **Refresh Token**
  - Step 1：进入[OAuth 2.0 Playground](url：https://developers.google.com/oauthplayground/#step1&scopes=https://www.googleapis.com/auth/adwords&url=https://&content_type=application/json&http_method=GET&useDefaultOauthCred=checked&oauthEndpointSelect=Google&oauthAuthEndpointValue=https://accounts.google.com/o/oauth2/auth&oauthTokenEndpointValue=https://www.googleapis.com/oauth2/v3/token&includeCredentials=unchecked&accessTokenType=bearer&autoRefreshToken=unchecked&accessType=offline&forceAprovalPrompt=checked&response_type=code)，点击右上角的设置按钮，将“Force prompt”设置为“NO”，并勾选“Use your own OAuth credentials”，输入Client ID & Client Secret
  - Step 2：在「Select & Authorize APIS」选择'[(https://www.googleapis.com/auth/adsense.readonly)]'，并勾选 “Authorize APIs”
  - Step 3：授予Adsense获取您的Admob账号数据的权限
  - Step 4：点击“Exchange authorization code for tokens”，获取Refresh token

## Unity
1、权限：添加前请确保您的账号已拥有「Unity API」权限
2、必填参数： 
![image](https://github.com/DMPlatform/DMPlatform/assets/26924924/9482f349-dcdf-4fc3-85f2-a6b571f13fce)
- 账号名称：用于区分您在该广告网络下的不同账号，平台不做正确性校验
- 报表API权限：打开后，GroMore可拉取API数据，建议打开
- Api Key：对应“Monetization Stats APl Access”的值，可在「Ads Data Export-API Access」获取
- Organization Core ID：可在「Settings-Organization info」获取
![image](https://github.com/DMPlatform/DMPlatform/assets/26924924/5dccd8c7-1b4e-475d-a581-e099b9d67b0c)
- 广告网络ID：如为自定义ADN接入，需填写

## Sigmob
1、权限：添加前请确保您的账号已拥有「Sigmob API」权限
2、必填参数：
- 账号名称：用于区分您在该广告网络下的不同账号，平台不做正确性校验
- 报表API权限：打开后，GroMore可拉取API数据，建议打开
- Public Key：可在sigmob后台「账户管理」获取
- Secret Key：可在sigmob后台「账户管理」获取
- 账户ID：对应“开发者ID”，可在sigmob后台「账户管理」获取
  ![image](https://github.com/DMPlatform/DMPlatform/assets/26924924/a05f60f1-e923-4b51-aeee-c4a840660ff9)
- 广告网络ID：如为自定义ADN接入，需填写
  
## Mintegral
1、权限：添加前请确保您的账号已拥有「Mintegral API」权限
2、必填参数：
- 账号名称：用于区分您在该广告网络下的不同账号，平台不做正确性校验
- 报表API权限：打开后，GroMore可拉取API数据，建议打开
- Skey：对应“Skey”，可在「接口工具」获取
- Secret：对应“密钥”，可在「接口工具」获取
  ![image](https://github.com/DMPlatform/DMPlatform/assets/26924924/8a2d05f1-f3e2-46f1-9f66-5f06328e0f50)
- 广告网络ID：如为自定义ADN接入，需填写
## 自定义ADN
通过通过自定义ADN接入的广告网络，需填写广告网络ID，广告网络ID可在GroMore后台-“广告网络” 模块获取
<img width="1185" alt="53df7104a4c0608e54ec6c5ff8d2eaec" src="https://user-images.githubusercontent.com/101794868/159447942-cae77462-d784-4e54-98f0-a2878e2eedfe.png">

