# v2ray-vmess-heroku
Hosting 4G Free
V2Ray Heroku
Nếu bạn cần triển khai V2Ray VLESS，thì qua bài viết này vless

Tổng quan
Dự án V2Ray WebSocket trên Heroku phải được sử dụng một cách hợp lý nếu không sẽ bị chặn

Sau khi triển khai, mỗi khi khởi động sẽ tải bản V2Ray mới nhất

Triển khai
Bắt đầu
Fork dự án này qua tài khoản GitHub của bạn（trên PC có thể thấy nút Fork trên cùng bên tay phải, ví dụ tài khoản của bạn tên là example）
Sửa lại tên dự án thành tên bất kỳ không nên chứa hai từ khóa v2ray và heroku（Ví dụ đổi thành demo）
Sửa lại file README.md，đường dẫn TroLyAmazon/v2ray-vmess-heroku bằng đường dẫn của bạn（ví dụ example/demo）
Deploy

Quay lại trang chủ của dự án，bấm vào liên kết để triển khai V2Ray
Đối số
Các đối số sẽ dùng trong quá trình cài đặt。

Đối số	Mặc định	Diễn giải
ID	ad806487-2d26-4636-98b6-ab85cc8521f7	
VMess user ID
AID	64	AlterID，Số từ 0 đến 65535
WSPATH	/	
Truy cập CloudFlare
Hai phương pháp sau có thể kết nối ứng dụng với CloudFlare, từ đó tăng tốc độ ở một mức độ nhất định:

Liên kết tên miền với ứng dụng và kết nối tên miền với CloudFlare
Reverse proxy thông qua CloudFlare worker
Lưu ý
** Xin đừng lạm dụng dự án này, có rất ít dịch vụ miễn phí như Heroku, hãy sử dụng và trân trọng **
Nếu bạn sử dụng tên miền để kết nối với CloudFlare, vui lòng xem xét bật TLS 1.3
Hầu hết các địa chỉ AWS IPv4 đã bị Twitter chặn
