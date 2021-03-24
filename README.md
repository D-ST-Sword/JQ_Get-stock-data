# JQ_Get-stock-data(基于聚宽平台的中国股票数据获取)

    运行环境：
    python == 3.6
    
    安装jqdatasdk 工具库
    pip install jqdatasdk
    
    升级工具包
    pip install -U jqdatasdk
    
    登录前必须导入 jqdatasdk // must import jqdatasdk  before sign in
    from jqdatasdk import *
    auth('ID','Password') #ID是申请时所填写的手机号；Password为聚宽官网登录密码，新申请用户默认为手机号后6位
    
    
    

Convenient access to Chinese stock data------Including viewing, obtaining, and briefly formatting for storing.//包括查看，获取，简单的格式化以及存储操作

Many people are very interested in financial quantitative research, but how to obtain the data is indeed a problem. Many platforms at home and abroad have interfaces for downloading financial market data. Here is a sample code based on the JQ platform. Suitable for machine learning, deep learning or simple financial tools for quantitative analysis and research. //很多人对金融量化研究很有兴趣，但是如何获得数据确是一个问题。国内外很多平台都有提供金融市场数据下载的接口，这里提供一个基于JQ平台的示例代码。适合机器学习，深度学习或者简单的金融工具来进行量化分析研究.

JQ platform provides 1 million data requests per day for free. // 聚宽平台免费提供每日100万条数据请求量，只需要简单的去官网注册即可

### If you have already registered a JQ account, please replace the kkkkkk below with your account and password //如果您已经注册了聚宽的账户，请把下面的kkkkkk替换成您的账户和密码
auth('kkkkkk','kkkkkk') 

#### The account number is the mobile phone number filled in at the time of application; the password is the login password of the JQ official website, and the new application user defaults to the last 6 digits of the mobile phone number. //账号是申请时所填写的手机号；密码为聚宽官网登录密码，新申请用户默认为手机号后6位
