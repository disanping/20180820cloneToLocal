# 20180820cloneToLocal
github上创建的，拉取到本地

### 如何使用git bash 或命令行从服务器端拉取资源库到本地，并在本地做修改后提交到服务器？

	. 首先要获取线上的库的地址：比如 `https://github.com/disanping/20180820cloneToLocal.git` 格式即为 `https://github.com/用户名/资源库名称.git`
	. 在需要落地的文件夹下使用git bash 并输入`git clone 线上地址库`，比如`git clone  https://github.com/disanping/20180820cloneToLocal.git`
	. 这样在本地就出来一个文件夹了，里面的文件即为线上同步过来的。这时操作就如同在本地修改提交步骤。试着在本地提交，如果线上线下账户未打通，那么push提交时还是报一样的错误
	· 需要注意一个细节:从线上clone下来的库，需要通过`cd 子文件夹`进入到资源库文件夹再做git等其他操作