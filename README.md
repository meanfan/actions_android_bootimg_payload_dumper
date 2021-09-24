# actions_android_bootimg_payload_dumper
利用Github Actions云端解包payload.bin并提取boot.img


## 简介 ##
利用github actions云端自动化提取刷机包payload.bin中的boot.img的脚本。

ROM修改为 Xiaomi MIX4  21.9.22 开发版。

本项目Fork自：https://github.com/yyzq2/actions_android_bootimg_payload_dumper 。

# 使用

首先点击fork这个仓库到你自己的账号下。 

接着，编辑.github/workflows文件夹下的.yml文件，将ROM_URL改成你要提取的刷机包直链地址（最好是官方直链，如miui的官方下载地址），支持zip刷机包（zip里面是payload.bin）。

最后，仅仅需要按下Star小星星按钮，就可以提取刷机包payload.bin中的boot.img

查看进度，在Actions菜单，get_bootimg_from_payload→make→Upload the bootimg to WeTransfer中找到Download link:xxx就是下载地址。

本项目依赖来自：https://github.com/vm03/payload_dumper 感谢。
