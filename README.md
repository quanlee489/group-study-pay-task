========================================================================
TÊN DỰ ÁN: GROUPSTUDY PAY & TASK - HỆ THỐNG QUẢN LÝ CÔNG VIỆC VÀ TÍNH TOÁN QUỸ NHÓM
========================================================================

1. THÔNG TIN CHUNG
- Cuộc thi: Sáng tạo dành cho thanh thiếu niên, nhi đồng
- Tác giả / Nhóm thực hiện: Lê Đình Anh Quân
                            Vương Thị Khánh Trang
- Giáo viên hướng dẫn: Cô Lê Thị Hồng Hạnh
                       Cô Nguyễn Thị Hạnh

2. GIỚI THIỆU DỰ ÁN
GroupStudy Pay & Task là ứng dụng web trợ lý tiện ích giúp các nhóm học sinh, sinh viên quản lý công việc và tài chính nhóm một cách minh bạch, tiện lợi. 

Các tính năng chính:
- Quản lý công việc: Giao việc cho từng thành viên, đặt hạn chót (deadline), theo dõi tiến độ hoàn thành trực quan.
- Quản lý Thu/Chi: Ghi nhận lịch sử nộp quỹ, ứng tiền chi tiêu của từng cá nhân.
- Tự động chia tiền sòng phẳng: Hệ thống tự tính toán trung bình chi tiêu và đưa ra số tiền chính xác từng người cần nộp thêm hoặc nhận lại.
- Tích hợp VietQR: Tự động tạo mã QR chuyển khoản ngân hàng chính xác số tiền cần nộp.
- Hỗ trợ Progressive Web App (PWA): Có thể cài đặt trực tiếp về màn hình điện thoại/máy tính và hoạt động tốt ngay cả khi mất kết nối mạng (Offline).

3. ĐƯỜNG LINK TRẢI NGHIỆM TRỰC TUYẾN
- Link Web App: https://quanlee489.github.io/group-study-pay-task/
- Mã nhóm trải nghiệm nhanh: S7942D

4. CÔNG NGHỆ SỬ DỤNG
- Frontend: HTML5, CSS3, JavaScript (ES6), Material Icons.
- Offline & PWA: Web App Manifest, Service Worker Caching.
- Backend & Database: Google Apps Script (GAS) đóng vai trò RESTful API kết nối cơ sở dữ liệu Google Sheets.
- Tích hợp bên thứ ba: VietQR API (Tạo mã quét ngân hàng tự động).

5. CẤU TRÚC THƯ MỤC MÃ NGUỒN (SOURCE CODE)
- index.html      : Giao diện chính người dùng (UI) và toàn bộ logic xử lý phía Frontend.
- manifest.json   : Cấu hình PWA (tên ứng dụng, biểu tượng icon, màu giao diện).
- sw.js           : Service Worker xử lý bộ nhớ đệm (Cache) giúp ứng dụng chạy Offline.
- Code.gs         : Mã nguồn xử lý phía Backend (Google Apps Script) kết nối cơ sở dữ liệu.
- README.txt      : File hướng dẫn và thông tin dự án.

6. HƯỚNG DẪN KHỞI CHẠY (DÀNH CHO GIÁM KHẢO)
- Cách 1 (Nhanh nhất): Bấm trực tiếp vào Đường link trải nghiệm trực tuyến ở Mục 3 bằng trình duyệt Chrome/Safari trên điện thoại hoặc máy tính.
- Cách 2 (Chạy local): Giải nén thư mục dự án -> Nhấp đôi chuột vào file `index.html` để mở và sử dụng trực tiếp trên trình duyệt web mà không cần cài đặt phần mềm phụ trợ.

========================================================================
Cảm ơn Ban Giám khảo đã xem xét sản phẩm dự thi của chúng em!
========================================================================
