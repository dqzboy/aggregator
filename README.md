# aggregator
One-stop Proxies Crawling and Aggregation Platform

## 使用流程如下：

- 1、启用Actions，如下图：
![image](https://github.com/user-attachments/assets/e85790b6-ce0f-4b5c-a68e-efeac6540367)

- 2、创建gist并获取到`username/gist_id`（记得保存，稍后要用），打开 [gist.github.com](https://gist.github.com)，随便创建一个，内容随便填，如图所示
![image](https://github.com/user-attachments/assets/6b2d8d31-1dcb-4ca0-b983-c68cd31b52e2)

- 3、回到 [Sign in to GitHub](https://github.com/settings/tokens?type=beta) 点击Generate new token按钮创建 PAT。名字随便填，过期时间选得久一点，重要的是在Account permissions里授予Gists的读写权限，创建好后复制生成的token稍后用
![image](https://github.com/user-attachments/assets/0bd567ae-2517-4245-ba19-5e753d67e762)
![image](https://github.com/user-attachments/assets/555baca1-4531-4d85-82d0-e91806e5a3c4)
![image](https://github.com/user-attachments/assets/214c99ca-1715-4076-b230-62972eb82dd3)

- 4、到仓库页面的Settings里设置环境变量，变量名为`GIST_LINK`和`GIST_PAT`，值分别为第4和5两步获取到的内容
![image](https://github.com/user-attachments/assets/91edee9f-33d2-4404-9abc-427a5dcb541a)
![image](https://github.com/user-attachments/assets/0a9d9455-82fc-48d4-b057-248d6fe3012b)

- 5、手动运行测试是否能够正常执行并成功推送到gist
![image](https://github.com/user-attachments/assets/f0c23028-e2cd-4c94-ba0a-994f3dd6eb4c)

> 如果你看到类似以下内容，说明你跑成功了（也可以到刚刚新建的gist里查看内容）
![image](https://github.com/user-attachments/assets/0331648e-aa8b-4713-a117-c9407939f46c)

- 6、添加订阅到你的翻墙软件里，添加不了的可以先订阅转换一下
![image](https://github.com/user-attachments/assets/1d48dc17-3fae-4492-ae0a-09912deb7a54)
