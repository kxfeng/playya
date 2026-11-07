# 小熊拼图书

给两三岁小朋友玩的拼图游戏，单个 HTML 文件，支持添加到 iPad 主屏幕全屏玩、断网也能玩（PWA）。

- 三个难度：简单 6 片、中等 9 片、难 16 片，每个难度 4 张原创卡通图
- 碎片拖到任意格子附近都会吸附，全部放对后放烟花
- 页面不含文字，适合还不识字的小朋友

## 发布

仓库 Settings → Pages → Build and deployment → Source 选 **Deploy from a branch**，Branch 选 `main` / `(root)`，保存。几分钟后可访问：

https://kxfeng.github.io/playya/

## 装到 iPad

用 Safari 打开上面的地址 → 分享 → 添加到主屏幕。之后从主屏幕图标打开就是全屏，第一次打开后断网也能玩。

## 更新

改完 `index.html` 后，把 `sw.js` 里的 `VERSION` 加一（例如 `pzb-v2`），已安装的设备下次联网打开时会自动更新。
