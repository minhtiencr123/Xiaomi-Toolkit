# Xiaomi Toolkit for Android

Xiaomi Toolkit là ứng dụng hỗ trợ thiết lập và tối ưu thông báo trên điện thoại Xiaomi, đặc biệt là máy sử dụng ROM nội địa Trung Quốc (MIUI/HyperOS), hoạt động thông qua Shizuku và không yêu cầu root.

Ứng dụng phù hợp với các máy Xiaomi nội địa cần cài Google Play, xử lý ứng dụng Trung Quốc và cải thiện độ ổn định của thông báo.

English summary: Xiaomi Toolkit helps fix notification issues on Xiaomi phones running MIUI/HyperOS using Shizuku, without root.


## Chức năng

### Setup

Hỗ trợ thiết lập máy mới hoặc máy vừa khôi phục cài đặt gốc:

* Chuyển ngôn ngữ máy sang tiếng Việt.
* Kiểm tra Google Play Store trước khi cài đặt.
* Cài đặt các thành phần Google Play cần thiết.
* Gỡ các ứng dụng Trung Quốc được hỗ trợ.
* Khởi động lại máy sau khi hoàn tất.

Nếu máy đã có Google Play, ứng dụng sẽ tự nhận diện và bỏ qua bước cài đặt.

### Tối ưu thông báo

Bảo vệ các ứng dụng quan trọng khỏi các cơ chế hạn chế chạy nền của Xiaomi/HyperOS.

Có thể tối ưu cho:

* Google Play Services
* Gmail
* Messenger
* Zalo
* Ứng dụng ngân hàng
* Các ứng dụng khác được hỗ trợ

Tùy phiên bản MIUI/HyperOS, ứng dụng sẽ áp dụng các thiết lập liên quan đến Doze, Data Saver, chạy nền, ưu tiên thông báo và các cơ chế quản lý ứng dụng của Xiaomi.

Danh sách ứng dụng đã được bảo vệ sẽ được giữ lại khi chạy tối ưu lần sau.

### Tùy chọn hệ thống

Một số tùy chọn bổ sung:

* Thông báo trên màn hình khóa.
* Tối ưu quản lý pin và mạng.
* App Freezer.
* Giảm cơ chế ép ứng dụng ngủ trên hệ thống.
* Tối ưu hoặc đóng băng TikTok và Telegram.
* Khôi phục các tùy chọn đã thay đổi.

Một số tùy chọn có thể không hoạt động trên mọi phiên bản MIUI/HyperOS.

### Kiểm tra và sửa lỗi

Kiểm tra nhanh tình trạng hệ thống, bao gồm:

* Ứng dụng cần thiết.
* Ứng dụng hệ thống và ứng dụng có thể gây ảnh hưởng.
* Google Play.
* Cài đặt liên quan đến thông báo.
* Danh sách ứng dụng được bảo vệ.
* Một số thiết lập tối ưu khác.

Nếu phát hiện lỗi, ứng dụng có thể cung cấp thao tác sửa tương ứng.

### Pin

Phân tích mức sử dụng pin dựa trên dữ liệu BatteryStats của thiết bị.

Có thể xem:

* Mức tiêu thụ pin từ lần rút sạc gần nhất.
* Phân bổ mức sử dụng pin.
* Top 7 ứng dụng tiêu thụ pin.
* Thời gian màn hình sáng và tắt.
* Theo dõi mức hao pin trong một khoảng thời gian do người dùng bắt đầu.

## Cách sử dụng

### Máy mới cài ROM hoặc khôi phục cài đặt gốc

Nên thực hiện theo thứ tự:

1. Bật **USB debugging** theo hướng dẫn trong ứng dụng.
2. Kích hoạt **Shizuku**.
3. Vào **Setup** và thực hiện các bước thiết lập cần thiết.
4. Cài Google Play nếu máy chưa có.
5. Gỡ các ứng dụng Trung Quốc không cần thiết.
6. Khởi động lại máy.
7. Cài Gmail, Messenger, Zalo và các ứng dụng cần nhận thông báo.
8. Vào **Tối ưu** và thực hiện các nhóm tối ưu cần thiết.
9. Vào **Kiểm tra** để kiểm tra lại trạng thái hệ thống.

Sau khi tối ưu xong, có thể tắt USB debugging nếu không còn sử dụng.

### Máy đang sử dụng bình thường

Nếu máy đã có Google Play và tiếng Việt, không cần chạy Setup.

Chỉ cần:

**Shizuku → Tối ưu → Kiểm tra**

Nếu chỉ gặp vấn đề thông báo, ưu tiên sử dụng mục **Bảo vệ thông báo**.

Các nút có biểu tượng `i` có phần giải thích chức năng tương ứng.

## Yêu cầu

* Điện thoại Xiaomi.
* MIUI hoặc HyperOS.
* Shizuku.
* Một số chức năng yêu cầu quyền ADB/Shizuku hoạt động bình thường.
* Không yêu cầu root.

Hiệu quả và các tùy chọn có thể khác nhau tùy model máy và phiên bản MIUI/HyperOS.

## Lưu ý

Xiaomi Toolkit thực hiện các thay đổi ở cấp hệ thống thông qua Shizuku/ADB. Người dùng nên đọc mô tả của từng chức năng trước khi thực hiện.

Không phải tất cả thiết lập đều tồn tại hoặc hoạt động giống nhau trên mọi phiên bản MIUI/HyperOS.

Ứng dụng không đảm bảo mọi thiết bị Xiaomi sẽ có cùng kết quả sau khi tối ưu.

Nếu Shizuku mất kết nối, hãy kích hoạt lại Shizuku trước khi sử dụng các chức năng cần quyền hệ thống.

## Tải xuống

APK và thông tin thay đổi của từng phiên bản được đăng tại mục **Releases** của repository.

Hãy sử dụng bản phát hành mới nhất nếu không có yêu cầu sử dụng một phiên bản cụ thể.

## Ủng hộ tác giả

Xiaomi Toolkit được phát triển và cung cấp miễn phí.

Nếu ứng dụng hữu ích với bạn, một chút ủng hộ sẽ giúp tác giả có thêm động lực để tiếp tục duy trì và phát triển dự án.
