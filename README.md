# PicoScenes-if
1.简单测量20M的CSI：

export UHD_IMAGES_DIR=/usr/local/share/uhd/images

能够检测到USRP后

maybe需要：（sudo pkill PicoScenes）

PicoScenes "-d debug -i usrp --mode logger --freq 2412 --plot"
