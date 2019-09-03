## Introduction

This mpv player plugin written in lua script is used to blur any area you slected. And it can adjust blur weight automatically according to the size of the area you selected.

To install it, just download the file to your mpv scripts folder. (That is `~/.config/mpv/scripts/` on Linux)

该mpv播放器插件用来模糊你选定的任意区域。它会根据选区的大小自动调整模糊的程度。

直接下载该文件到mpv的scripts文件夹即可使用。



You may find it useful to cover the built-in subtitle you don't what to see. For example, watching movies to study another language:

你可以用它来遮挡字幕：

![1566729691288](Readme.assets/1566729691288.jpg)



## Usage

By default keyboard button `b` is used to toggle it on/off.  (You can assign another key if you like)

Press key `b` and click on the first corner. Then move mouse to another corner and click again.

默认使用按键 `b` 进行切换。激活的时候用鼠标点击选区的两个对角即可。

![1566728274407](Readme.assets/1566728274407.jpg)

![1566728299409](Readme.assets/1566728299409.jpg)



> https://superuser.com/questions/901099/ffmpeg-apply-blur-over-face

Crop and lavfi setting codes are taken from [here](https://github.com/occivink/mpv-scripts).
