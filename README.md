# 惠园三维校园与 B3 车库方案

对外经济贸易大学惠园校园的三维近似展示，以及求索楼 B3 停车库的方案示意。

- 直接以 `index.html` 作为静态网站首页，无需构建和服务器端程序。
- 程序、校园轮廓数据、样式和贴图均已内置，不依赖 ChatGPT 登录或外部组件下载。
- 支持旋转缩放、校园视角切换、示意车位选择及充电桩显示切换。

## 资料精度

校园建筑高度与立面为近似重建。B3 的 102 个车位容量参考 2025 年校方停车公告。
B3 内部布局、尺寸、柱网、坡道、设备区与充电桩位置均为方案假设，尚未以实际图纸核实。
充电候选点用于演示，不代表已经实施或已进行选址优化求解。

## 资料来源

- [学校地图](https://www.uibe.edu.cn/xywh/xxdt/index.htm)
- [求索楼地下三层建设说明](https://jjc.uibe.edu.cn/zhxx/31208.htm)
- [2025 年停车容量公告](https://110.uibe.edu.cn/tzgg/aee483226af6438a99651141d55f7780.htm)
- 校园轮廓数据 © OpenStreetMap contributors，按 ODbL 使用；三维库 Three.js 按 MIT 许可使用。

## GitHub Pages

在仓库 Settings → Pages 选择 Deploy from a branch，以 `main` 分支根目录发布。
`.nojekyll` 用于直接发布已生成的静态文件。
