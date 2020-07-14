## 加密文件夹
在某个文件夹下添加 .password 文件，里面写入密码，即可加密该文件夹。注意文件必须以 UTF8NoBOM 编码，且密码前后不能有空格或空行，Windows 下可通过以下方式生成：

在待加密文件夹下按住 Shift 键的同时，鼠标右击文件夹空白处，选择 在此处打开 Powershell 窗口(S)，接着执行以下命令，其中 1234 便是密码。

'1234' | Out-File -FilePath .password -Encoding ascii -NoNewline


## 获取 refresh_token
进入 该网址（世纪互联版点我），点击其中的 Get a refresh_token，在打开的微软账号登录页面中，填写你的 OneDrive 账号和密码，完成登录。
