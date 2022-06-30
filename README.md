# springBoot_scaffold


接口访问测试  
使用postman 访问链接(get/post...)http://localhost:8080/user/test.do  


#### 构建工程项目步骤  
1. 选择spring web、jdbc、jdbc api、mysql、mybatis
2. 修改pom.xml
3. 在resource创建generator文件夹、然后在里面创建ggeneratorConfif.xml
4. 删除原来的application 创建application.yml 编辑内容
5. 添加maven启动类 ，对mybatis进行逆向编译
6. 编辑启动类 加上mappingscan("com.eexample.dao")
7. 添加usercontroller 加上test.do接口
8. 启动服务 使用postman测试接口 返回数据