# video2

这是一个用于通过 GitHub Pages 播放本地视频的简单静态站点。上传视频到 `docs/videos/video.mp4`，然后在仓库设置中将 GitHub Pages 来源设置为 `main` 分支下的 `/docs` 目录（Settings -> Pages -> Build from -> main branch /docs folder）。

页面文件已放在 `docs/`，启用 Pages 后访问 URL 形式为:

https://wangyueban1503-art.github.io/video2/

注意：GitHub 对单文件大小有限制（约 100MB）；如需托管更大的视频，请使用外部对象存储或流媒体服务，然后在 docs/index.html 中替换视频来源为外部链接。