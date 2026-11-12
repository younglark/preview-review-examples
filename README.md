# 交互预览验收 · 预制模板

这不是一次性演示，而是可套用的验收包模板：单页里用多个 Tab 组合常见验收场景，用户分别体验并填写，最后一次性「复制全部反馈」。

在线预览：https://younglark.github.io/preview-review-examples/

- [视觉稿](https://younglark.github.io/preview-review-examples/#visual)：在稿上打点标注
- [入场动画](https://younglark.github.io/preview-review-examples/#animation)：可拖动的进度条、倍速、在某一刻评论
- [交互走查](https://younglark.github.io/preview-review-examples/#prototype)：可点击的多屏原型 + 走查清单
- [响应式](https://younglark.github.io/preview-review-examples/#responsive)：375 / 768 / 1280 断点切换，逻辑分区可折叠，逐个给结论
- [总评](https://younglark.github.io/preview-review-examples/#general)：跨场景的整体判断

下载可套用的预览包：[preview-review-examples.zip](https://github.com/younglark/preview-review-examples/raw/main/zips/preview-review-examples.zip)

约定见 skill「交互预览验收包」。反馈 UI 由页面自己渲染；若已安装 grokbot-x，会走 `window.__grokbotXPreview.submitFeedback({ json, files })`，否则降级为复制 JSON。
