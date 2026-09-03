# DÀN Ý BÁO CÁO ĐỀ TÀI CAMPUSMATCH

**Đề tài:** Xây dựng ứng dụng kết nối và ghép đôi sinh viên trong khuôn viên đại học (CampusMatch)

---

# LỜI MỞ ĐẦU

## LỜI CẢM ƠN

## LỜI CAM ĐOAN

## MỤC LỤC

## DANH MỤC HÌNH ẢNH

## DANH MỤC BẢNG BIỂU

## DANH MỤC TỪ VIẾT TẮT

---

# CHƯƠNG 1: TỔNG QUAN VỀ ĐỀ TÀI

## 1.1. Giới thiệu đề tài

- Giới thiệu hệ thống CampusMatch.
- Bối cảnh kết nối sinh viên trong môi trường đại học.
- Nhu cầu tìm kiếm bạn bè, bạn học và giao lưu.
- Ý tưởng xây dựng nền tảng kết nối dành riêng cho sinh viên.

## 1.2. Lý do chọn đề tài

- Nhu cầu kết nối và giao lưu của sinh viên.
- Hạn chế của các nền tảng kết nối hiện nay.
- Khó xác định người dùng có thực sự là sinh viên.
- Khó tìm kiếm người có cùng trường, ngành học và sở thích.
- Nhu cầu xây dựng môi trường kết nối phù hợp với sinh viên.

## 1.3. Mục tiêu đề tài

- Xây dựng hệ thống CampusMatch.
- Hỗ trợ sinh viên tạo và quản lý hồ sơ cá nhân.
- Hỗ trợ tìm kiếm và đề xuất sinh viên phù hợp.
- Hỗ trợ Like/Pass và tạo Match.
- Hỗ trợ trò chuyện giữa các sinh viên đã Match.
- Hỗ trợ Block/Report nhằm đảm bảo an toàn.
- Hỗ trợ Quản trị viên quản lý và thống kê hệ thống.

## 1.4. Phạm vi đề tài

### 1.4.1. Phạm vi chức năng

- Quản lý tài khoản.
- Quản lý hồ sơ.
- Quản lý sở thích.
- Đề xuất và Matching.
- Trò chuyện.
- Báo cáo và xử lý vi phạm.
- Thống kê hệ thống.

### 1.4.2. Phạm vi đối tượng

- Khách.
- Sinh viên.
- Quản trị viên.
- Các hệ thống/dịch vụ bên ngoài có liên quan.

## 1.5. Đối tượng sử dụng hệ thống

### 1.5.1. Khách (Guest / Sinh viên chưa đăng nhập)

- Người dùng truy cập hệ thống nhưng chưa xác thực tài khoản.
- Chỉ được sử dụng các chức năng công khai:
  - Đăng ký.
  - Đăng nhập.

### 1.5.2. Sinh viên (Student)

- Người dùng đã đăng nhập thành công.
- Kế thừa toàn bộ quyền của Khách.
- Được sử dụng các chức năng cốt lõi:
  - Quản lý hồ sơ.
  - Quản lý sở thích.
  - Xem đề xuất.
  - Like/Pass.
  - Match.
  - Chat.
  - Block/Report.

### 1.5.3. Quản trị viên (Admin)

- Quản lý người dùng.
- Xử lý báo cáo vi phạm.
- Khóa/xóa tài khoản.
- Xem thống kê hệ thống.

### 1.5.4. Hệ thống bên ngoài

- Mail Server.
- Dịch vụ gửi thông báo.
- Dịch vụ lưu trữ hình ảnh.

## 1.6. Ý nghĩa của đề tài

- Ý nghĩa thực tế.
- Ý nghĩa trong học tập.
- Khả năng ứng dụng và phát triển.

## 1.7. Cấu trúc đồ án

- Giới thiệu nội dung chính của từng chương.

---

# CHƯƠNG 2: KHẢO SÁT VÀ THU THẬP THÔNG TIN

## 2.1. Khảo sát nhu cầu sinh viên

- Nhu cầu tìm kiếm bạn bè.
- Nhu cầu tìm bạn học.
- Nhu cầu giao lưu và kết nối.
- Nhu cầu tìm người có cùng sở thích.

## 2.2. Khảo sát các phương thức kết nối hiện nay

- Mạng xã hội.
- Nhóm lớp/nhóm trường.
- Ứng dụng hẹn hò.
- Các nền tảng tìm bạn học.

## 2.3. Phân tích những khó khăn của phương pháp hiện tại

- Khó xác thực người dùng.
- Khó tìm người phù hợp.
- Thiếu thông tin về trường/ngành học.
- Khó kiểm soát hành vi vi phạm.
- Thiếu môi trường kết nối dành riêng cho sinh viên.

## 2.4. Quy trình nghiệp vụ thực tế

Mô tả quy trình kết nối sinh viên:

**Đăng ký → Xác thực → Tạo hồ sơ → Xem đề xuất → Like/Pass → Match → Chat**

## 2.5. Giải pháp đề xuất

- Xây dựng hệ thống CampusMatch.
- Xác thực người dùng.
- Quản lý hồ sơ sinh viên.
- Đề xuất sinh viên phù hợp.
- Cơ chế Like/Pass và Match.
- Trò chuyện.
- Block/Report.
- Quản trị và thống kê.

## 2.6. Yêu cầu hệ thống

### 2.6.1. Yêu cầu chức năng

- Quản lý tài khoản và hồ sơ.
- Đề xuất và Matching.
- Trò chuyện.
- Báo cáo và xử lý vi phạm.
- Thống kê hệ thống.

### 2.6.2. Yêu cầu phi chức năng

- Bảo mật.
- Hiệu năng.
- Tính ổn định.
- Khả năng mở rộng.
- Tính dễ sử dụng.

## 2.7. Cấu trúc đồ án

- Tóm tắt nội dung và sự liên kết giữa các chương.

---

# CHƯƠNG 3: PHÂN TÍCH VÀ THIẾT KẾ HỆ THỐNG

## 3.1. Liệt kê Tác nhân và Ca sử dụng

### 3.1.1. Khách

- UC1 – Đăng ký.
- UC2 – Đăng nhập.

### 3.1.2. Sinh viên

- Các Ca sử dụng từ UC3 trở đi liên quan đến chức năng chính của hệ thống.
- Quản lý hồ sơ.
- Quản lý sở thích.
- Đề xuất và Matching.
- Trò chuyện.
- Block/Report.

### 3.1.3. Quản trị viên

- Quản lý người dùng.
- Xử lý báo cáo.
- Khóa/xóa tài khoản.
- Thống kê hệ thống.

### 3.1.4. Hệ thống bên ngoài

- Mail Server.
- Dịch vụ thông báo.
- Dịch vụ lưu trữ hình ảnh.

## 3.2. Ma trận phân tích yêu cầu

Xây dựng bảng:

**Khó khăn → Giải pháp → Yêu cầu chức năng → Tác nhân → Ca sử dụng → Input → Output**

## 3.3. Sơ đồ luồng dữ liệu và phân rã tiến trình

### 3.3.1. Sơ đồ luồng dữ liệu mức 0

- Mô tả luồng dữ liệu tổng quát giữa các tác nhân và hệ thống CampusMatch.

### 3.3.2. Sơ đồ luồng dữ liệu mức 1

Phân rã hệ thống thành 5 tiến trình:

| Tiến trình | Tên tiến trình | Kho dữ liệu liên quan |
|---|---|---|
| **1.0** | **Quản lý tài khoản & hồ sơ** | TAI_KHOAN, HO_SO, SO_THICH |
| **2.0** | **Đề xuất & Matching** | LIKE, MATCH |
| **3.0** | **Trò chuyện** | CHAT |
| **4.0** | **Báo cáo & Xử lý vi phạm** | REPORT, TAI_KHOAN |
| **5.0** | **Thống kê hệ thống** | TAI_KHOAN, HO_SO, LIKE, MATCH, CHAT, REPORT |

### 3.3.3. Chi tiết các tiến trình

#### Tiến trình 1.0 – Quản lý tài khoản & hồ sơ

- Đăng ký tài khoản.
- Đăng nhập.
- Cập nhật hồ sơ.
- Quản lý sở thích.

#### Tiến trình 2.0 – Đề xuất & Matching

- Xem danh sách đề xuất.
- Thực hiện Like/Pass.
- Kiểm tra Like hai chiều.
- Tạo Match.

#### Tiến trình 3.0 – Trò chuyện

- Xem danh sách cuộc trò chuyện.
- Gửi tin nhắn.
- Nhận tin nhắn.
- Lưu trữ lịch sử trò chuyện.

#### Tiến trình 4.0 – Báo cáo & Xử lý vi phạm

- Sinh viên gửi báo cáo.
- Quản trị viên xem báo cáo.
- Xử lý báo cáo.
- Khóa/xóa tài khoản vi phạm.

#### Tiến trình 5.0 – Thống kê hệ thống

- Tổng hợp dữ liệu người dùng.
- Thống kê Like/Match.
- Thống kê hoạt động trò chuyện.
- Thống kê báo cáo vi phạm.
- Xuất báo cáo cho Quản trị viên.

## 3.4. Sơ đồ Ca sử dụng

### 3.4.1. Sơ đồ Ca sử dụng tổng quát

- Toàn bộ tác nhân và Ca sử dụng.

### 3.4.2. Sơ đồ Ca sử dụng quản lý tài khoản

- Đăng ký.
- Đăng nhập.

### 3.4.3. Sơ đồ Ca sử dụng quản lý hồ sơ

- Xem hồ sơ.
- Cập nhật hồ sơ.
- Quản lý sở thích.

### 3.4.4. Sơ đồ Ca sử dụng Đề xuất & Matching

- Xem danh sách đề xuất.
- Like.
- Pass.
- Xử lý Match.

### 3.4.5. Sơ đồ Ca sử dụng Trò chuyện

- Xem danh sách Match.
- Gửi/nhận tin nhắn.

### 3.4.6. Sơ đồ Ca sử dụng Báo cáo & Quản trị

- Báo cáo vi phạm.
- Chặn người dùng.
- Quản lý người dùng.
- Xử lý báo cáo.
- Thống kê hệ thống.

## 3.5. Đặc tả các Ca sử dụng

- Bảng đặc tả chi tiết từng Ca sử dụng.
- Mỗi Ca sử dụng gồm:
  - Tên Ca sử dụng.
  - Mã Ca sử dụng.
  - Tác nhân chính.
  - Mô tả.
  - Tiền điều kiện.
  - Hậu điều kiện.
  - Luồng chính.
  - Luồng thay thế/ngoại lệ.

### 3.5.1. UC1 – Đăng ký

### 3.5.2. UC2 – Đăng nhập

### 3.5.3. UC3 – Cập nhật hồ sơ

### 3.5.4. UC4 – Xem hồ sơ

### 3.5.5. UC5 – Quản lý sở thích

### 3.5.6. UC6 – Xem danh sách đề xuất

### 3.5.7. UC7 – Like/Pass

### 3.5.8. UC8 – Xử lý Match

### 3.5.9. UC9 – Xem danh sách Match

### 3.5.10. UC10 – Nhắn tin

### 3.5.11. UC11 – Chặn người dùng

### 3.5.12. UC12 – Báo cáo vi phạm

### 3.5.13. UC13 – Quản lý người dùng

### 3.5.14. UC14 – Xử lý báo cáo

### 3.5.15. UC15 – Thống kê hệ thống

> Nếu nhóm hiện tại đã chốt số lượng/mã UC khác thì giữ đúng danh sách UC thực tế của nhóm, không tự đổi mã.

## 3.6. Sơ đồ Phân tích

### 3.6.1. Sơ đồ phân tích UC Đăng ký

### 3.6.2. Sơ đồ phân tích UC Đăng nhập

### 3.6.3. Sơ đồ phân tích UC Matching

### 3.6.4. Sơ đồ phân tích UC Chat

### 3.6.5. Sơ đồ phân tích UC Báo cáo

## 3.7. Sơ đồ Tuần tự

### 3.7.1. Sơ đồ tuần tự Đăng ký/Đăng nhập

### 3.7.2. Sơ đồ tuần tự xử lý Matching

### 3.7.3. Sơ đồ tuần tự Nhắn tin

### 3.7.4. Sơ đồ tuần tự Báo cáo vi phạm

## 3.8. Sơ đồ Lớp

### 3.8.1. Sơ đồ lớp tổng quát

### 3.8.2. Mô tả các lớp chính

- User.
- StudentProfile.
- Interest.
- Swipe/Like.
- Match.
- Message/Chat.
- Report.
- Notification.
- Các lớp liên quan khác.

## 3.9. Sơ đồ Hoạt động và Giao diện

Mỗi Ca sử dụng quan trọng gồm:

**Sơ đồ hoạt động + mô tả + giao diện tương ứng**

### 3.9.1. Đăng ký

### 3.9.2. Đăng nhập

### 3.9.3. Cập nhật hồ sơ

### 3.9.4. Xem hồ sơ

### 3.9.5. Quản lý sở thích

### 3.9.6. Xem danh sách đề xuất

### 3.9.7. Like/Pass

### 3.9.8. Xử lý Match

### 3.9.9. Xem danh sách Match

### 3.9.10. Nhắn tin

### 3.9.11. Chặn người dùng

### 3.9.12. Báo cáo vi phạm

### 3.9.13. Quản lý người dùng

### 3.9.14. Xử lý báo cáo

### 3.9.15. Thống kê hệ thống

---

# CHƯƠNG 4: XÂY DỰNG VÀ TRIỂN KHAI HỆ THỐNG

## 4.1. Công cụ và môi trường phát triển

- Ngôn ngữ lập trình.
- IDE.
- Framework.
- Công cụ quản lý cơ sở dữ liệu.
- Công cụ xây dựng sơ đồ.

## 4.2. Kiến trúc hệ thống

- Mô hình kiến trúc.
- Client.
- Server.
- Database.
- Các dịch vụ bên ngoài.

## 4.3. Thiết kế cơ sở dữ liệu

### 4.3.1. Sơ đồ ERD

- Sơ đồ quan hệ thực thể của CampusMatch.

### 4.3.2. Danh sách các bảng

- TAI_KHOAN.
- HO_SO.
- SO_THICH.
- LIKE.
- MATCH.
- CHAT.
- REPORT.
- Các bảng liên quan khác.

### 4.3.3. Chi tiết các bảng

- Tên thuộc tính.
- Kiểu dữ liệu.
- Khóa chính.
- Khóa ngoại.
- Ràng buộc dữ liệu.

## 4.4. Xây dựng giao diện

- Giao diện Đăng ký.
- Giao diện Đăng nhập.
- Giao diện Hồ sơ.
- Giao diện Matching.
- Giao diện Chat.
- Giao diện Report.
- Giao diện Admin.

## 4.5. Xây dựng các chức năng chính

- Quản lý tài khoản.
- Quản lý hồ sơ.
- Matching.
- Chat.
- Block/Report.
- Quản trị và thống kê.

## 4.6. Tích hợp các dịch vụ bên ngoài

- Email.
- Thông báo.
- Lưu trữ hình ảnh.
- Các dịch vụ khác nếu có.

---

# CHƯƠNG 5: CÁC VẤN ĐỀ PHÁT SINH VÀ GIẢI PHÁP KHẮC PHỤC

## 5.1. Vấn đề về xác thực người dùng

- Tài khoản giả.
- Email không hợp lệ.
- Spam đăng ký.

## 5.2. Vấn đề về Matching

- Đề xuất chưa chính xác.
- Thiếu dữ liệu sở thích.
- Số lượng người dùng ít.

## 5.3. Vấn đề về Chat

- Mất kết nối.
- Đồng bộ tin nhắn.
- Độ trễ khi gửi/nhận.

## 5.4. Vấn đề về bảo mật và quyền riêng tư

- Bảo vệ thông tin cá nhân.
- Bảo vệ mật khẩu.
- Phân quyền người dùng.
- Bảo vệ dữ liệu.

## 5.5. Vấn đề về hiệu năng

- Số lượng người dùng tăng.
- Quá tải máy chủ.
- Tối ưu truy vấn cơ sở dữ liệu.

## 5.6. Kiểm thử hệ thống

### 5.6.1. Kiểm thử chức năng

### 5.6.2. Kiểm thử tích hợp

### 5.6.3. Kiểm thử hiệu năng

## 5.7. Đánh giá kết quả

- Các chức năng đã hoàn thành.
- Các yêu cầu đã đáp ứng.
- Những điểm còn hạn chế.

## 5.8. Kết luận

- Tổng kết quá trình thực hiện đề tài.

## 5.9. Hướng phát triển

- Cải thiện thuật toán Matching.
- Ứng dụng AI trong đề xuất.
- Mở rộng tính năng tìm bạn học.
- Phát triển thêm tính năng gọi video.
- Mở rộng hệ thống cho nhiều trường đại học.

---

# TÀI LIỆU THAM KHẢO

- Giáo trình và tài liệu môn học.
- Tài liệu kỹ thuật của các công nghệ sử dụng.
- Các nguồn tài liệu tham khảo khác.

# PHỤ LỤC

- Code chương trình.
- Bảng dữ liệu.
- Hình ảnh giao diện.
- Các sơ đồ UML.
- Các nội dung bổ sung khác.
