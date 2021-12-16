# Crashdump là gì?
Crashdump là tệp có phần mở rộng `.log` và chứa thông tin quan trọng được sử dụng để xác định, tái tạo và sửa lỗi. Chúng chứa các thông tin con người có thể đọc được về sự cố và cũng có thể xem được các thông tin một cách trực quan tại trang web [Crash Archive (Kho lưu trữ sự cố)](https://crash.pmmp.io/) của PocketMine

# Khi nào Crashdump file được tạo ra?
Crashdump file được tạo ra khi máy chủ gặp các sự cố như:
- Plugin bị lỗi
- Hết bộ nhớ do không đủ hoặc bộ nhớ bị rò rỉ
- Các lỗi trong PocketMine-MP không thể khôi phục được

# Crashdump file có thể chứa các thông tin gì?
- Thông báo lỗi, tên tệp, số dòng và loại lỗi
- Dấu vết của lỗi, giúp xác định vị trí xảy ra sự cố
- Một đoạn mã xung quanh địa điểm xảy ra sự cố, giúp xác định nơi xảy ra sự cố
- Thông tin về phiên bản hệ điều hành và phần cứng của bạn (chẳng hạn như kiểu CPU)
- Danh sách các plugin được cài đặt trên máy chủ
- Phiên bản PocketMine-MP mà bạn đang sử dụng
- Nội dung của tệp pocketmine.yml và server.properties (thông tin nhạy cảm như mật khẩu RCON sẽ ẩn đi)

# Crashdump file được tạo ra ở đâu?
Crashdump file được tạo trong bên trong thư mục `crashdumps` (Thư mục `crashdumps` nằm bên trong thư mục có chứa `PocketMine-MP.phar`)
