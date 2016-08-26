
    调用手机拨号界面：
    <a href="tel:110"></a>  
    
    在cordova中所有的URL Schemes 都是服从于白名单的，所以a tel 在这无法正常使用。解决方法是在项目config.xml中添加

    <access origin="tel:*" launch-external="yes" />
    
    
