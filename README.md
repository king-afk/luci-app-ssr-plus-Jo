
# luci-app-ssr-plus

This is a backup repoistory of luci-app-ssr-plus from Lean's OpenWrt project package.

Lean's OpenWrt source:

<https://github.com/coolsnowwolf/lede/>

Source from tree: 2915c44a11ca0ee40b51ff5d9c18a0da1951e170

Lean's luci-app-ssr-plus source (history):

<https://github.com/coolsnowwolf/lede/tree/2915c44a11ca0ee40b51ff5d9c18a0da1951e170/package/lean/luci-app-ssr-plus>

# luci-app-ssr-plus-Jo

## 说明
   源码来源：https://github.com/coolsnowwolf

#### 建议搭配opentomato  opentomcat  theme，能有最好的显示体验。（兼容所有Argon魔改主题）

theme : https://github.com/Leo-Jo-My/luci-theme-opentomato

theme : https://github.com/Leo-Jo-My/luci-theme-opentomcat
   
## 使用方法
```Brach
    #下载源码
    
    git clone https://github.com/Leo-Jo-My/luci-app-ssr-plus-Jo package/luci-app-ssr-plus-Jo
 
     git clone https://github.com/Leo-Jo-My/my package/my  #依赖包

    make menuconfig
    #编译
    make package/luci-app-ssr-plus-Jo/{clean,compile} V=s
    


