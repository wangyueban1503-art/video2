# video2 - 静态视频播放站点 (docs)

把视频文件放到本目录的 videos 子目录后，访问仓库的 GitHub Pages 即可播放。

推荐流程：

1. 上传视频到 docs/videos/video.mp4（文件名可自定义，但需更新 docs/index.html 中的 source 路径）。
2. 若文件 <= 100MB，可直接通过 GitHub 网页或 git push 上传到仓库。
3. 若文件 > 100MB，请使用外部托管并在 docs/index.html 中将 <code>source src</code> 改为外部 URL（例如 CDN、S3、Cloudflare R2、YouTube、Bunny等）。

示例 git 上传命令：

git clone https://github.com/wangyueban1503-art/video2.git
cd video2
mkdir -p docs/videos
cp /path/to/your/video.mp4 docs/videos/video.mp4
git add docs/videos/video.mp4
git commit -m "Add video file"
git push
