#用户行为分析--前端埋点实现

1.拿到数据：
  （1）用户名
  （2）iP地址，所在省份
  （3）域名
  （4）url
  （5）页面title
  （6）跳入时间
  （7）跳出时间
  （8）上一跳地址
  （9）用户搜索页面上的搜索记录
  （10）用户所使用的操作系统语言（有助于开发对应的语言包）
  
  技术：
   1.前端：js埋点
   2.后端：写入日志文件，通过定时任务，或者队列将数据写入关系型数据库如mysql或者其他大数据平台。
