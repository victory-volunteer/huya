# huya
项目介绍：首先需要拿到主页面的页面源代码, 找到iframe；然后从iframe的页面源代码中拿到m3u8文件的地址；下载第一层m3u8文件(第一层只放了一个地址) -> 下载第二层m3u8文件(视频存放路径，通过请求第一层的地址得到)；下载所有ts视频 ；利用ffmpeg合并所有ts文件为一个mp4文件。
