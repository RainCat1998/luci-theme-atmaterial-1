# luci-theme-atmaterial-color

Based on [Advanced Tomato Material Theme for OpenWrt]([https://github.com/openwrt-develop/luci-theme-atmaterial](https://github.com/openwrt-develop/luci-theme-atmaterial)

Thanks to [Mrbai98](https://github.com/Mrbai98)/**[luci-theme-atmaterial](https://github.com/Mrbai98/luci-theme-atmaterial)** for modification.

# Updates

1. Change repository name to luci-theme-atmaterial-color.

2. Fix the wrong color of "Logout" tap at the bottom.

# Screenshot

![image](https://raw.githubusercontent.com/SDNGer/luci-theme-atmaterial/master/screenshot/20190818145642.png)

# How to use

```batch
    cd package
    git clone https://github.com/RainCat1998/luci-theme-atmaterial-color.git
    
    #change directory name
    mv luci-theme-atmaterial-color/ luci-theme-atmaterial/
   
    make menuconfig
    #choose Luci->Theme->luci-theme-atmaterial as module
    
    make package/luci-theme-atmaterial/{clean,compile} V=s
```
