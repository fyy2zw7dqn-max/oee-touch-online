# OEE 触摸端（前端在线版）

OEE 触摸电脑界面重构 1.3 的纯前端在线演示，使用内置 mock 演示数据，无需后端。

## 公网访问地址

https://fyy2zw7dqn-max.github.io/oee-touch-online/

## 本地预览

```bash
node ../deploy/serve.cjs --root .
# 然后浏览器打开 http://localhost:8088/
```

## 更新上线

修改 `index.html` / `guide-video.mp4` 后：

```bash
git add -A
git commit -m "更新说明"
git push
```

GitHub Pages 会自动重新构建并上线（约 1–2 分钟生效）。
