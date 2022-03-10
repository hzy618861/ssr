● html模板<!--vue-ssr-outlet--> 不能有空格
● vue-server-renderer插件调用createRenderer方法传入html模板，调用renderToString传入vm实例进行编译转换，将转换的结果替换<!--vue-ssr-outlet-->返回完整html给浏览器，生成的页面节点data-server-rendered：true
● createRenderer传入第二个配置参数，可以向模板传递动态数据，模板中通过{{}}进行读取，三个大括号可以进行标签原文输出

### server entry(服务端入口)  client entry(客户端入口)
jin  
