# JavaPath — Website hỗ trợ dạy học Lập trình Java

## Cách chạy
1. Giải nén `JavaPath_Website.zip`.
2. Mở thư mục `website_hoc_java`.
3. Nhấp đúp `index.html` để mở bằng Chrome, Edge hoặc Firefox.
4. Không cần cài đặt máy chủ để xem giao diện demo.

## Tệp trong dự án
- `index.html`: cấu trúc trang chủ, khu vực chương học, thực hành và hồ sơ sinh viên.
- `style.css`: giao diện responsive, màu sắc và bố cục.
- `script.js`: dữ liệu chương học, modal lý thuyết/lời giải, đăng nhập demo, tạo bài tập, chọn kiểm tra/thi, chấm điểm mẫu, lưu thông tin cá nhân trên trình duyệt.

## Tính năng demo
- 8 chương Java với phần giới thiệu lý thuyết và đoạn mã minh họa.
- Bài tập được gắn mức độ Dễ, Trung bình, Khó/Nâng cao.
- Xem lời giải tham khảo.
- Chế độ sinh viên: nhập họ tên, MSSV, chọn kiểm tra (1 bài) hoặc thi (2–3 bài), nhập lời giải và nộp.
- Chế độ giáo viên: tạo bài tập kèm input/output mẫu, chọn mức độ/chương, xem danh sách và xóa bài.
- Trang cá nhân: Trương Thanh Phong, ngành Công nghệ thông tin, sở thích đá banh; có thể nhập MSSV và tải ảnh cá nhân.

## Lưu ý kỹ thuật quan trọng
Đây là bản demo frontend chạy trên trình duyệt. Bộ chấm điểm hiện tại chỉ nhận diện một số mẫu mã đơn giản; **không thực sự biên dịch hoặc thực thi Java**. Các test input/output được lưu để minh họa luồng làm bài. Dữ liệu được lưu cục bộ trên trình duyệt, chưa có tài khoản bảo mật, cơ sở dữ liệu dùng chung hay phân quyền phía máy chủ.

Để triển khai thành hệ thống dùng thật, nên bổ sung:
- Backend/API và cơ sở dữ liệu để lưu tài khoản, đề, test và kết quả.
- Xác thực, phân quyền phía máy chủ cho Giáo viên/Sinh viên.
- Trình chạy Java an toàn trong sandbox/container, giới hạn thời gian, bộ nhớ và quyền truy cập.
- Bộ chấm tự động chạy 5 test/bài, 2 điểm/test; tổng điểm cần được quy đổi phù hợp khi đề gồm nhiều bài.
