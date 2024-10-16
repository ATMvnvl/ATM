## Tìm hiểu về Networking
### Mô hình OSI && TCP/IP

OSI - Open Systems Interconnection (OSI): Mô hình kết nối các hệ thống mở là một khung khái niệm chia các chức năng truyền thông mạng thành 7 lớp.

TCP/IP - Transmission Control Protocol/Internet Protocol: Giao thức điều khiển truyền nhận/ Giao thức liên mạng. Đây là bộ các giao thức truyền thông được dùng để kết nối các thiết bị mạng trên internet với nhau.

Mô tả các tầng OSI và TCP/IP

![alt text](osi_tcp.jpg)

#### Mô hình OSI 

Tóm tắt ngắn gọn mô hình OSI gồm 7 tầng:

+ Tầng Application: gần với con người là nơi ứng dụng tương tác với mạng như: email, web,...
+ Tầng Presentation: chịu trách nhiệm chuyển đổi định dạng mã hóa và nén dữ liệu
+ Tầng Session: quản lý các phiên kết nối
+ Tầng Transport: đảm bảo dữ liệu truyền tin cậy và toàn vẹn giữa hai điểm cuối dùng giao thức udp hoặc tcp
+ Tầng Network: định tuyến và truyền dữ liệu giữa các mạng sử dụng ip
+ Tầng Data link: thực hiện các liên kết kiểm soát lỗi và lưu lượng sử dụng địa MAC
+ Tầng Physical: truyền tín hiệu điện sóng radio hoặc Wifi ethernet, bluetooth 

