# 学习计划板 · Learning OS

**在线体验 → https://3280053419w-cloud.github.io/study-website-contest/**

把一年的学习排成一条看得见的线：年历、每日时光轴、四条学习线、40 张国标（GB/T）机械制图练习图纸、
年热力图、复盘墙。纯前端零依赖，数据只存在你自己的浏览器里，断网可用。

这个仓库是 **1024 造物挑战的参赛版产物**（首次打开带一份示范数据，横幅上写着，一键可清空）。
正式站是不带示范数据的空白模板版：<https://3280053419w-cloud.github.io/study-website/>

## 三个值得一看的点

1. **首屏背景**是一段手写的 WebGL CRT 着色器（片元着色器逐字移植，零依赖、带降级）。
2. **中间那块会转的玻璃棱镜**是纯 CSS 3D —— 六面玻璃、双描边色散、面内 SVG，没有 Three.js。
3. **一套源码出三种产物**：计划数据空白 / 是否带 40 张图纸 / 首访是否铺示范，
   由构建脚本强制切轴并做门禁校验。

## 制作过程

整个站点（HTML / CSS / JS / 验收脚本）都是在 WorkBuddy 对话里写出来的。
过程记录、踩过的坑、怎么验证的，都写在 [workbuddy.md](workbuddy.md)。

## 本仓库是什么

`dist/` 的产物直接放在根目录（GitHub Pages 用 main 分支根目录发布）：

```
index.html      页面骨架
styles.css      全部样式
main.js         全部逻辑（零依赖 IIFE）
assets/dxf/     40 张 GB/T 练习图纸（DXF + 无损 WebP 预览）
fonts/          本地字体
```

源码与验收脚本在另一个仓库：<https://github.com/3280053419w-cloud/study-website>

---

*没有账号、没有服务端、没有埋点。你的计划只留在你打开它的那台设备上。*
