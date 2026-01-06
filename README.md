hugo server -p 3333

Chạy kèm IP LAN (xem bằng điện thoại)
hugo server --bind 0.0.0.0 -p 3333

Set port mặc định luôn trong config Thêm vào hugo.toml:

[server]
  port = 3333


Một số option hay
Lệnh	Tác dụng
hugo server -D	Xem cả bài draft: true
hugo server --disableFastRender	Reload chính xác hơn
hugo server --renderToDisk	Xuất file ra public/ khi dev


build prod
hugo --environment production --minify
