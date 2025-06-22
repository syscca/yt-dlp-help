# yt-dlp-help
yt-dlp实践使用方法

yt-dlp --cookies cookies.txt -f "bv*[vcodec^=avc1][height<=1080]+ba[ext=m4a]/b" --remux-video mp4 -o "VOXY 2023/%(title)s.%(ext)s" --download-archive downloaded.txt --limit-rate 2M "https://www.youtube.com/playlist?list=PLkStjK0RCu757iKkxqy5xbTwaUzppVw1p"
