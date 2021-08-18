#  前置基础知识
借用了一下网上找的一张图比较清晰。如有侵权联系删除。
[![WsUHBV.png](https://z3.ax1x.com/2021/07/23/WsUHBV.png)](https://imgtu.com/i/WsUHBV)
1、"navigationStyle": "custom", 配置之后整体的导航栏就消失了，页面会顶到状态栏， 整体的高度就是 （状态栏高度 + 导航栏高度）
> 导航栏高度 = 胶囊高度 +（高度差）x  2, 高度差可以通过胶囊到顶部的距离，减去状态栏的高度获取得到; 状态栏高度: statusBarHeight 可以通过wx.getSystemInfo 获取；胶囊高度：可以通过wx.getMenuButtonBoundingClientRect 获取。
### 点击查看 [getSystemInfo](https://developers.weixin.qq.com/miniprogram/dev/api/base/system/wx.getSystemInfo.html)

### 点击查看 [getMenuButtonBoundingClientRect](https://developers.weixin.qq.com/miniprogram/dev/api/ui/menu/wx.getMenuButtonBoundingClientRect.html)


# 最后感谢[lingxiaoyi](https://github.com/lingxiaoyi/navigation-bar) 大佬的组件
> 在其基础上把它掏空整理出的清晰点，可以更好的往里加自己的东西，引入即用。