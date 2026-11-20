# 基本内容
## 登录
- 通过官网下载，同步会下载GitBash
- 在gitbash面板用（$ git config --global user.name "NAME"）等语句进行账户关联
## 基本流程
- git clone：克隆仓库到本地，建立gitbash面板和GitHub仓库之间的联系便于后续文件推送
- cd：后面加具体仓库或文件夹名称，后续会把新文件推送到这里
- echo：创建文件(echo加文件内容加大于号加文件名称)
- git add：将改动的文件暂存
- git commit -m：在本地保存提交这个文件
- git push：把文件推送到GitHub仓库中（这一步会出现二者的请求关联界面，推送成功就会在gitbash面板提示并且可以在仓库中看到这个文件）
## 什么是Git
Linus自己用C语言写的一个分布式版本控制系统（分布式没有中央服务器，参与的每个人移动端都有一个完整的版本库，不需要联网操作，并且因此可以实现多设备共同改动文件后期合并，提高效率），本质是系统不是语言也不是app，下载时会同时下载一个GitBash，gitbash可以进行编码操作且可以远程传送到GitHub仓库，这个相当于编码软件，只拥有一个黑色界面框。

# hello.md推送流程
- 克隆仓库（用clone这个，后面加仓库地址）
- 进入仓库文件（用cd加文件或仓库名称Tasks）
- 创建文件（echo "#Hello Andrew-725" >hello.md）
- 暂存文件（用add把文件暂存到本地）
- 提交文件到本地（git commit -m"新增hello.md文档"）
- 推送文件到Tasks仓库（git push）
- 关联认证（自动出现面板要求认证关联，输入GitHub账号密码后关联成功）
- 推送成功，文件出现在GitHub仓库中

