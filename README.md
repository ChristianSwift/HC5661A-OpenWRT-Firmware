# Hiwifi HC5661A OpenWRT with SSR firmware
## 固件地址（已带酸酸乳）  
> (！注意！)无特殊要求请下载闪存固件，内存固件在关机或者重启后会重置所有更改
* [闪存固件下载](http://hc5661a.dingcloud.xyz/targets/ramips/mt76x8/openwrt-ramips-mt76x8-hiwifi_hc5661a-squashfs-sysupgrade.bin)  
* [内存固件下载](http://hc5661a.dingcloud.xyz/targets/ramips/mt76x8/openwrt-ramips-mt76x8-hiwifi_hc5661a-initramfs-kernel.bin)  
## 软件源（删除发行版软件源，换为本地址）  
```Shell
src/gz openwrt_core http://hc5661a.dingcloud.xyz/targets/ramips/mt76x8/packages
src/gz openwrt_base http://hc5661a.dingcloud.xyz/packages/mipsel_24kc/base
src/gz openwrt_luci http://hc5661a.dingcloud.xyz/packages/mipsel_24kc/luci
src/gz openwrt_packages http://hc5661a.dingcloud.xyz/packages/mipsel_24kc/packages
src/gz openwrt_routing http://hc5661a.dingcloud.xyz/packages/mipsel_24kc/routing
```
