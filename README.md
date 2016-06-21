# docker-jenkins


### 运行
```sh
docker run -p 8080:8080 -p 50000:50000 slsay/docker-jenkins
```

### 访问Jenkins
访问需要使用虚拟机IP
```sh
docker-machine ip
```
http://MACHINE_VM_IP:8080/

第一次访问时，需要一个管理员初期化密码,这个密码在控制台能找到
```sh
*************************************************************
*************************************************************
*************************************************************

Jenkins initial setup is required. An admin user has been created and a password generated.
Please use the following password to proceed to installation:

deb78f3410d94ea8930a61f4f9d62e42

This may also be found at: /var/jenkins_home/secrets/initialAdminPassword

*************************************************************
*************************************************************
*************************************************************
```
插件选择推荐的插件就行，实际使用中，按需再装吧。
