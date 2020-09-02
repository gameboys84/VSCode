# VSCode
当githubusercontent无法访问时，可以手动更新VSCode.cs



### 访问githubusercontent的方法

登录任何一个可以通过域名查IP的网站，比如[查询网](https://www.ip138.com/), 然后输入无法访问的域名即可



1. 如果想直接拿结果，也可以直接复制以下内容到hosts

```
151.101.76.133    raw.githubusercontent.com
151.101.76.133    gist.githubusercontent.com
151.101.76.133    cloud.githubusercontent.com
151.101.76.133    camo.githubusercontent.com
151.101.76.133    avatars0.githubusercontent.com
151.101.76.133    avatars1.githubusercontent.com
151.101.76.133    avatars2.githubusercontent.com
151.101.76.133    avatars3.githubusercontent.com
151.101.76.133    avatars4.githubusercontent.com
151.101.76.133    avatars5.githubusercontent.com
151.101.76.133    avatars6.githubusercontent.com
151.101.76.133    avatars7.githubusercontent.com
151.101.76.133    avatars8.githubusercontent.com
```

151.101.76.133   对应的是香港地区



2. 然后在命令行输入，执行后生效

   - Windows

     hosts所在目录： ```C:/windows/system32/drivers/etc/hosts```，需要管理员权限才能保存

     ```
     ipconfig /flushdns
     ```

   - Mac

     hosts所在目录： ```/etc/hosts```， 修改和保存都需要权限，最好的办法是先在其它地方新建一个hosts文件，然后覆盖过去，会要求输入密码

     ```
     sudo killall -HUP mDNSResponder
     ```

3. 如果还不能访问可以重启下相应软件再试下











