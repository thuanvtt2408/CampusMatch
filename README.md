# DÀN Ý TỔNG QUÁT BÁO CÁO CAMPUSMATCH

**Đề tài:** Xây dựng ứng dụng kết nối và ghép đôi sinh viên trong khuôn viên đại học (CampusMatch)

---

## PHẦN MỞ ĐẦU

- Lời cảm ơn
- Lời cam đoan
- Mục lục
- Danh mục hình ảnh
- Danh mục bảng biểu
- Danh mục từ viết tắt

---

# CHƯƠNG 1: TỔNG QUAN VỀ ĐỀ TÀI

### 1.1. Giới thiệu đề tài
- Giới thiệu CampusMatch.
- Bối cảnh và nhu cầu kết nối sinh viên.

### 1.2. Lý do chọn đề tài
- Vấn đề thực tế.
- Hạn chế của các nền tảng hiện nay.
- Nhu cầu xây dựng nền tảng kết nối dành cho sinh viên.

### 1.3. Mục tiêu đề tài
- Mục tiêu tổng quát.
- Các mục tiêu cụ thể.

### 1.4. Phạm vi đề tài
- Phạm vi chức năng.
- Phạm vi đối tượng.
- Phạm vi triển khai.

### 1.5. Đối tượng sử dụng hệ thống
- Khách / Sinh viên chưa đăng nhập.
- Sinh viên.
- Quản trị viên.
- Các hệ thống/dịch vụ bên ngoài.

### 1.6. Ý nghĩa của đề tài
- Ý nghĩa thực tế.
- Ý nghĩa học tập.
- Khả năng ứng dụng.

### 1.7. Cấu trúc báo cáo
- Giới thiệu nội dung từng chương.

---

# CHƯƠNG 2: KHẢO SÁT VÀ PHÂN TÍCH YÊU CẦU

### 2.1. Khảo sát nhu cầu người dùng
- Nhu cầu kết nối của sinh viên.
- Nhu cầu tìm bạn, bạn học, giao lưu.

### 2.2. Khảo sát các phương thức hiện tại
- Mạng xã hội.
- Nhóm lớp/nhóm trường.
- Ứng dụng kết nối/hẹn hò.
- Các nền tảng liên quan.

### 2.3. Phân tích vấn đề thực tế
- Các hạn chế.
- Các khó khăn của người dùng.
- Vấn đề xác thực và bảo mật.

### 2.4. Giải pháp đề xuất
- Giới thiệu giải pháp CampusMatch.
- Cách hệ thống giải quyết các vấn đề đã khảo sát.

### 2.5. Phân tích yêu cầu chức năng
- Quản lý tài khoản.
- Quản lý hồ sơ.
- Quản lý sở thích.
- Đề xuất và Matching.
- Trò chuyện.
- Chặn/Báo cáo.
- Quản trị hệ thống.
- Thống kê.

### 2.6. Phân tích yêu cầu phi chức năng
- Bảo mật.
- Hiệu năng.
- Tính ổn định.
- Khả năng mở rộng.
- Tính dễ sử dụng.

### 2.7. Ma trận yêu cầu
- Vấn đề.
- Giải pháp.
- Yêu cầu chức năng.
- Tác nhân.
- Ca sử dụng.
- Input.
- Output.

---

# CHƯƠNG 3: PHÂN TÍCH VÀ THIẾT KẾ HỆ THỐNG

## 3.1. Danh sách Tác nhân

- Khách.
- Sinh viên.
- Quản trị viên.
- Các hệ thống bên ngoài.

## 3.2. Danh sách Ca sử dụng

- Tổng hợp **19 Use Case (UC1–UC19)**.
- Xác định tác nhân chính của từng UC.
- Xác định mối quan hệ giữa các UC nếu có.

## 3.3. Sơ đồ luồng dữ liệu

### 3.3.1. DFD mức 0
- Sơ đồ luồng dữ liệu tổng quát.

### 3.3.2. DFD mức 1
Phân rã thành 5 tiến trình:

- **1.0 – Quản lý tài khoản & hồ sơ**
  - TAI_KHOAN
  - HO_SO
  - SO_THICH

- **2.0 – Đề xuất & Matching**
  - LIKE
  - MATCH

- **3.0 – Trò chuyện**
  - CHAT

- **4.0 – Báo cáo & Xử lý vi phạm**
  - REPORT
  - TAI_KHOAN

- **5.0 – Thống kê hệ thống**
  - TAI_KHOAN
  - HO_SO
  - LIKE
  - MATCH
  - CHAT
  - REPORT

## 3.4. Sơ đồ Use Case

### 3.4.1. Sơ đồ Use Case tổng quát

### 3.4.2. Sơ đồ Use Case phân rã
- Quản lý tài khoản.
- Quản lý hồ sơ.
- Đề xuất & Matching.
- Trò chuyện.
- Báo cáo & Quản trị.

## 3.5. Đặc tả 19 Use Case

- Đặc tả từ **UC1 → UC19**.
- Mỗi UC gồm:
  - Mã UC.
  - Tên UC.
  - Tác nhân chính.
  - Mô tả.
  - Tiền điều kiện.
  - Hậu điều kiện.
  - Luồng chính.
  - Luồng thay thế/ngoại lệ.

## 3.6. Sơ đồ Hoạt động

- Các Activity Diagram tương ứng với những UC/quy trình quan trọng.
- Đảm bảo sơ đồ khớp với đặc tả UC.

## 3.7. Sơ đồ Phân tích

- Robustness Diagram cho các quy trình chính.
- Xác định Actor / Boundary / Control / Entity.

## 3.8. Sơ đồ Tuần tự

- Sequence Diagram cho các quy trình quan trọng.
- Đảm bảo khớp với luồng của Use Case.

## 3.9. Sơ đồ Lớp

- Class Diagram tổng quát.
- Các lớp Entity.
- Các lớp Boundary/Control nếu sử dụng.
- Thuộc tính, phương thức và quan hệ giữa các lớp.

## 3.10. Thiết kế giao diện

- Giao diện Đăng ký.
- Giao diện Đăng nhập.
- Giao diện Hồ sơ.
- Giao diện Matching.
- Giao diện Chat.
- Giao diện Báo cáo.
- Giao diện Admin.
- Các giao diện khác tương ứng với UC.

---

# CHƯƠNG 4: THIẾT KẾ CƠ SỞ DỮ LIỆU VÀ XÂY DỰNG HỆ THỐNG

## 4.1. Kiến trúc hệ thống

- Mô hình kiến trúc.
- Client.
- Server.
- Database.
- Các dịch vụ bên ngoài.

## 4.2. Thiết kế cơ sở dữ liệu

### 4.2.1. Sơ đồ ERD

### 4.2.2. Danh sách bảng

- TAI_KHOAN
- HO_SO
- SO_THICH
- LIKE
- MATCH
- CHAT
- REPORT
- Các bảng liên quan khác.

### 4.2.3. Chi tiết các bảng

- Tên thuộc tính.
- Kiểu dữ liệu.
- Khóa chính.
- Khóa ngoại.
- Ràng buộc.

## 4.3. Công nghệ sử dụng

- Ngôn ngữ lập trình.
- Framework.
- Frontend.
- Backend.
- Database.
- Công cụ phát triển.
- Các dịch vụ bên ngoài.

## 4.4. Xây dựng các chức năng

- Quản lý tài khoản.
- Quản lý hồ sơ.
- Matching.
- Chat.
- Block/Report.
- Quản trị.
- Thống kê.

## 4.5. Xây dựng giao diện

- Các màn hình chính.
- Mô tả giao diện.
- Luồng sử dụng giao diện.

## 4.6. Tích hợp dịch vụ bên ngoài

- Email/OTP.
- Thông báo.
- Lưu trữ hình ảnh.
- Các dịch vụ khác nếu có.

---

# CHƯƠNG 5: KIỂM THỬ, AN TOÀN VÀ ĐÁNH GIÁ HỆ THỐNG

## 5.1. Kiểm thử hệ thống

### 5.1.1. Kiểm thử chức năng

### 5.1.2. Kiểm thử tích hợp

### 5.1.3. Kiểm thử hiệu năng

### 5.1.4. Kiểm thử giao diện

## 5.2. An toàn thông tin

- Bảo mật tài khoản.
- Mã hóa mật khẩu.
- Xác thực người dùng.
- Phân quyền.
- Bảo vệ dữ liệu cá nhân.

## 5.3. Các vấn đề phát sinh

- Vấn đề xác thực.
- Vấn đề Matching.
- Vấn đề Chat.
- Vấn đề hiệu năng.
- Vấn đề bảo mật.

## 5.4. Giải pháp khắc phục

- Giải pháp cho từng vấn đề.
- Các phương án dự phòng.

## 5.5. Đánh giá kết quả

- Những chức năng đã hoàn thành.
- Mức độ đáp ứng yêu cầu.
- Ưu điểm.
- Hạn chế.

---

# KẾT LUẬN VÀ HƯỚNG PHÁT TRIỂN

## 1. Kết luận

- Tổng kết quá trình thực hiện.
- Kết quả đạt được.

## 2. Hạn chế

- Những chức năng chưa hoàn thiện.
- Những vấn đề còn tồn tại.

## 3. Hướng phát triển

- Cải thiện thuật toán Matching.
- Ứng dụng AI.
- Mở rộng tính năng tìm bạn học.
- Phát triển thêm tính năng giao tiếp.
- Mở rộng hệ thống cho nhiều trường đại học.

---

# TÀI LIỆU THAM KHẢO

- Giáo trình.
- Tài liệu môn học.
- Tài liệu kỹ thuật.
- Các nguồn tham khảo.

# PHỤ LỤC

- Code.
- CSDL.
- Hình ảnh giao diện.
- Các sơ đồ.
- Nội dung bổ sung.

# Lưu ý
- In 2 mặt 40 trang, nhớ ghi đóng góp để cho điểm kí tên nhưng chấm trên lớp thì phải cho xem sản phẩm, chia đều để không bị thiếu điểm 
- dùng jira, trello và git 
- Code yếu thì tìm devexpress

