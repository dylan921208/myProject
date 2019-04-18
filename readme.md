## 一个用于自动登录的测试前端请求的demo
> * node test.js
> * 适用于vue-admin 
> * ui：element-ui
## 规则:
 ```
   /**
   * 1、用户名：自定义     密码统一为：12345678a  
   * 2、登录页用户名输入框加入属性name="username"； 密码输入框属性name="password"
   * 3、定义查询的路由列表
   *  BaseUrl: 基础域名
   * urlList：url：路由路径 ； click：点击对象 btn按钮下标，是否有tab（下一页）
   */
   let urlList = [
    { url: 'contract', click: [{ btn: 0, tab: false},{btn: 1, tab: true}],},
    { url: 'diamond', click: [{btn: 0, tab: true}], }, 
    { url: 'audit', click: [{btn: 0}],  }, 
    { url: 'account' },
    { url: 'userIndex' }
    ]
    ```
  

