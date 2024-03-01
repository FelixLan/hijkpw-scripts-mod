本脚本是备份自网络跳越hijk大佬的脚本修改，

修改了原脚本中与hijk.art绑定的域名IP检测，

以备原网站不能访问的情况。

hostip修改版是将官方脚本的 hijk.art/host.php 网址进行替换成别的域名IP检测API；

hostip去除版是将官方脚本的 hijk.art/host.php 网址进行剔除并换成其他代码；

脚本修改尚有不足，请不要将此脚本用于开发环境，感谢提供修改意见的群友，谢谢！

## V2ray
```
注意，脚本不适用最新版，原因是脚本在安装v2ray过程中，第822行默认从（https://github.com/v2fly/v2ray-core/releases/）抓取最新版本。解压后cp到对应位置，目前的最新版本为v5.1.0。该版本解压后，没有v2ctl文件，copy失败后，导致脚本意外终止，请作者予以修正。

脚本未修正前的临时解决方法：
wget https://raw.githubusercontent.com/daveleung/hijkpw-scripts-mod/main/v2ray_mod1.sh
chmod a+x v2ray_mod1.sh
vi v2ray_mod1.sh
（将822行中的${NEW_VER}修改为v4.45.2）
./v2ray_mod1.sh     
```

【3】V2ray带伪装一键脚本CentOS版

hostip修改版
```
bash <(curl -Ls https://raw.githubusercontent.com/daveleung/hijkpw-scripts-mod/main/centos_install_v2ray2_mod1.sh)
```

hostip去除版
```
bash <(curl -Ls https://raw.githubusercontent.com/daveleung/hijkpw-scripts-mod/main/centos_install_v2ray2_mod2.sh)
```

【4】V2ray带伪装一键脚本Ubuntu版

hostip修改版
```
bash <(curl -Ls https://raw.githubusercontent.com/daveleung/hijkpw-scripts-mod/main/ubuntu_install_v2ray2_mod1.sh)
```

hostip去除版
```
bash <(curl -Ls https://raw.githubusercontent.com/daveleung/hijkpw-scripts-mod/main/ubuntu_install_v2ray2_mod2.sh)
```

【5】V2ray多合一脚本

hostip修改版
```
bash <(curl -Ls https://raw.githubusercontent.com/daveleung/hijkpw-scripts-mod/main/v2ray_mod1.sh)
```

hostip去除版
```
bash <(curl -Ls https://raw.githubusercontent.com/daveleung/hijkpw-scripts-mod/main/v2ray_mod2.sh)
```

## Xray

【1】Xray一键脚本

hostip修改版
```
bash <(curl -Ls https://raw.githubusercontent.com/daveleung/hijkpw-scripts-mod/main/xray_mod1.sh)
```

hostip去除版
```
bash <(curl -Ls https://raw.githubusercontent.com/daveleung/hijkpw-scripts-mod/main/xray_mod2.sh)
```

## Trojan

【1】Trojan一键脚本

hostip修改版
```
bash <(curl -Ls https://raw.githubusercontent.com/daveleung/hijkpw-scripts-mod/main/trojan_mod1.sh)
```

hostip去除版
```
bash <(curl -Ls https://raw.githubusercontent.com/daveleung/hijkpw-scripts-mod/main/trojan_mod2.sh)
```

【2】Trojan-Go一键脚本

hostip修改版
```
bash <(curl -Ls https://raw.githubusercontent.com/daveleung/hijkpw-scripts-mod/main/trojan-go_mod1.sh)
```

hostip去除版
```
bash <(curl -Ls https://raw.githubusercontent.com/wixfreto/hijkpw-scripts-mod/main/trojan-go_mod2.sh)
```
