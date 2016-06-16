
##### 这个项目仅仅是实现了Xcode Source Editor Extensions的一个概念



> 注意：这个扩展仅仅能转换"love"、"happy"、"graduation"到emojis。

![Emojify hero image](recording.gif)

##### 如何使用

1. 下载Xcode 8
2. 安装additional system components
3. 安装完毕后, 打开terminal，然后执行命令sudo /usr/libexec/xpccachectl
4. 重启电脑，这个只需要一次
5. 使用Xcode 8打开工程，然后运行extension scheme，如果有必须先调整code signing。
6. 当弹出"Choose an app to run"菜单时，选择Xcode 8
7. 这是一个新的Xcode 8会被启动，打开任意源文件，"Emojify"就会在"Editor"菜单出现
8. 选中任意代码，点击菜单执行