# N1 历年研习室 · 听力资源

为 https://Subterranean-Sun.github.io/n1-study/ 提供 32 套整卷 MP3，保留 audio/YYYY_MM.mp3 路径，由主站播放器按各题时间段定位。

## 日常更新

修改这个独立在线副本后，提交并推送 main 分支，GitHub Actions 会自动发布新版本。Pages 设置采用 GitHub Actions；.nojekyll 保留，网站直接运行原生 HTML/CSS/JavaScript。

手动运行 Pages 工作流时，restore_snapshot 默认为 false，会发布当前 main。只有明确需要恢复最初的完整快照时才勾选它；恢复会替换当前站点内容。

已发布内容保存在 Git 仓库与 Pages，原件和恢复快照保存在 Releases。Actions 的 Pages artifact 只用于传输：成功部署后自动删除，未成功的传输包保留一天。

当前资源约 813 MB，Pages 单站发布体积须低于 1 GB。接近 900 MB 时，为新增录音建立另一资源站，保留本仓库已有路径。
