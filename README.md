# MOGUTest
创建tableview 和自定义cell，然后自定义control 用来展示内容。以block回调的形式将点击index返回到控制便于操作跳转详情页之类。 
利用gcd多线程请求数据，提高cpu利用率,下载完成后主线程更新UI,防止数据加载过程中UI阻塞,当然如果加载图片或者文字很多，具体优化可以参考YYkit之类
