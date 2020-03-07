
# luci-app-ssr-plus

This is a backup repoistory of luci-app-ssr-plus from Lean's OpenWrt project package.

Lean's OpenWrt source:

<https://github.com/coolsnowwolf/lede/>

Source from tree: 2915c44a11ca0ee40b51ff5d9c18a0da1951e170

Lean's luci-app-ssr-plus source (history):

<https://github.com/coolsnowwolf/lede/tree/2915c44a11ca0ee40b51ff5d9c18a0da1951e170/package/lean/luci-app-ssr-plus>

# 加入lean原版建议重新fork源码 

## 说明
   源码来源：https://github.com/coolsnowwolf

#### 建议搭配opentomato  opentomcat  theme，能有最好的显示体验。（兼容所有Argon魔改主题）

theme : https://github.com/Leo-Jo-My/luci-theme-opentomato

theme : https://github.com/Leo-Jo-My/luci-theme-opentomcat

theme : https://github.com/Leo-Jo-My/luci-theme-Butterfly

# luci-app-ssr-plus-Jo
   
## 使用方法
    #下载源码
    
    git clone https://github.com/Leo-Jo-My/luci-app-ssr-plus-Jo package/luci-app-ssr-plus-Jo
 
    git clone https://github.com/Leo-Jo-My/my package/my  #依赖包
    
    git clone https://github.com/Leo-Jo-My/luci-theme-Butterfly package/luci-theme-Butterfly #主题包
    
    git clone https://github.com/Leo-Jo-My/luci-theme-opentomato package/luci-theme-opentomato #主题包
    
    git clone https://github.com/Leo-Jo-My/luci-theme-opentomcat package/luci-theme-opentomcat  #主题包

    make menuconfig
    #编译
    make package/luci-app-ssr-plus-Jo/{clean,compile} V=s
    
# luci-app-ssr-plus-lean
    
## 原版使用方法
```Brach
    #下载源码
    
    git clone -b lean  https://github.com/Leo-Jo-My/luci-app-ssr-plus-Jo package/lean/luci-app-ssr-plus-lean
    
    git clone https://github.com/Leo-Jo-My/luci-theme-Butterfly package/luci-theme-Butterfly #主题包
    
    git clone https://github.com/Leo-Jo-My/luci-theme-opentomato package/luci-theme-opentomato #主题包
    
    git clone https://github.com/Leo-Jo-My/luci-theme-opentomcat package/luci-theme-opentomcat  #主题包
 
    make menuconfig
    #编译
    make package/luci-app-ssr-plus-lean/{clean,compile} V=s

