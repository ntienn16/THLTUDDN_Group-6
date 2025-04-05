# THLTUDDN_Group-6
Demo Bus Ticketing
## Giới thiệu:
Đây là bản demo giao diện tĩnh được xây dựng bằng ngôn ngữ HTML cho một ứng dụng đặt vé xe bus trực tuyến. Bản demo này tập trung vào việc thể hiện luồng người dùng và các màn hình chính của ứng dụng, bao gồm các chức năng cơ bản như đăng nhập, đăng ký, lấy lại mật khẩu, tìm kiếm chuyến xe, đặt chỗ và thanh toán trực tuyến.

**Lưu ý quan trọng:**
* Đây là **giao diện tĩnh** được tạo bằng HTML và CSS. **Không có chức năng backend hoặc tương tác dữ liệu thực tế** trong bản demo này.
* Các chức năng như xử lý đăng nhập, đăng ký, tìm kiếm dữ liệu chuyến xe, xử lý đặt chỗ và thanh toán **chưa được triển khai** và chỉ được thể hiện dưới dạng các trang giao diện.
## Các Chức Năng Demo:
1.  **Đăng Nhập (login.html)**
    * Giao diện cho người dùng đã có tài khoản đăng nhập bằng email/facebook và mật khẩu.
    * Có liên kết đến trang đăng ký và trang lấy lại mật khẩu.
2.  **Đăng Ký Tài Khoản (register.html)**
    * Giao diện cho người dùng mới tạo tài khoản bằng cách nhập các thông tin cá nhân (ví dụ: tên, email/số điện thoại, mật khẩu).
    * Có nút để chuyển về trang đăng nhập.
3.  **Lấy Lại Mật Khẩu (forgot_password.html)**
    * Giao diện cho người dùng quên mật khẩu, thường yêu cầu nhập email/số điện thoại để khôi phục.
    * Có thể có các bước xác minh (ví dụ: gửi mã OTP).
4.  **Tìm Chuyến Xe (find_trip.html)**
    * Giao diện cho phép người dùng tìm kiếm chuyến xe bằng cách chọn:
        * Điểm đi.
        * Điểm đến.
        * Ngày đi.
        * (Tùy chọn) Thời gian đi.
    * Hiển thị danh sách các chuyến xe khả dụng dựa trên tiêu chí tìm kiếm (dữ liệu chuyến xe là tĩnh và chỉ mang tính minh họa).
5.  **Đặt Chỗ (booking.html)**
    * Giao diện hiển thị thông tin chi tiết của một chuyến xe đã chọn (ví dụ: giờ khởi hành, giá vé, nhà xe, số ghế còn trống).
    * Cho phép người dùng chọn số lượng hành khách và vị trí ghế (chỉ là giao diện chọn ghế tĩnh).
    * Hiển thị tổng tiền dự kiến.
    * Có nút để chuyển sang trang thanh toán.
6.  **Quản Lý Vé Xe (Bookings history)**
    * Thư mục này chứa các trang liên quan đến quản lý vé:
        * **Xem Lại Lịch Sử Đặt Vé (Bookings history.html):**
            * Giao diện hiển thị danh sách các vé đã đặt trong quá khứ, bao gồm thông tin chi tiết như mã vé, thông tin chuyến xe, trạng thái thanh toán, ngày đặt.
            * Có thể có các bộ lọc hoặc chức năng tìm kiếm lịch sử.
        * **Hủy Vé Chưa Thanh Toán:**
            * Giao diện hiển thị danh sách các vé đã đặt nhưng chưa được thanh toán.
            * Cho phép người dùng chọn và hủy các vé này. Có thể có bước xác nhận hủy.
        * **Chi Tiết Vé:**
            * Giao diện hiển thị thông tin chi tiết của một vé cụ thể khi người dùng nhấp vào một vé trong lịch sử hoặc danh sách vé chưa thanh toán.
            * Bao gồm đầy đủ thông tin chuyến đi, thông tin hành khách, trạng thái thanh toán và có thể có nút để xem mã QR hoặc tùy chọn hủy (tùy thuộc vào trạng thái vé).
  7.  **Thanh Toán Online (Payment)**
    * Giao diện cho phép người dùng chọn phương thức thanh toán (ví dụ: thẻ tín dụng, ví điện tử, chuyển khoản ngân hàng). (Payment information)
    * Có nút "Thanh Toán" để hoàn tất giao dịch (chức năng thanh toán thực tế không được triển khai). (Payment methods)
    * Sau khi "thanh toán", có thể chuyển đến trang thông báo đặt vé thành công. (Ticket information)

## Cách Sử Dụng:
1.  Tải xuống và giải nén các file `Log, Register.rar`, `Search Trip-Reserve Vehicle.rar`, `Booking-Ticket.rar`. 
3.  Mở file `Login.html` (hoặc bất kỳ file HTML nào bạn muốn xem) bằng trình duyệt web của bạn (Google Chrome, Mozilla Firefox, Safari, v.v.).
4.  Điều hướng đến các trang (thông qua các liên kết giả định trong giao diện) để hình dung luồng người dùng cho việc đăng nhập, tìm kiếm, đặt chỗ, thanh toán và **quản lý vé**.
5.  Trong thư mục `Booking history`, mở các file HTML để xem giao diện cho lịch sử đặt vé và hủy vé chưa thanh toán.
