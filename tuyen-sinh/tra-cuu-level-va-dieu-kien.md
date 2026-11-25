# Các level và điều kiện vào từng level

> Bảng tra nhanh: mỗi level nghĩa là gì, cần gì trước khi vào, ai hoặc cái gì đặt level đó. Bộ level mặc định khi đưa vào dùng; quản trị có thể đổi tên hoặc thêm level.

| Mã | Tên | Nhóm | Cần có trước khi vào | Ai đặt |
|---|---|---|---|---|
| L1 | Có SĐT | Đang chăm | Chọn được khi tạo cơ hội | Người tạo cơ hội; import; đường tạo tự động |
| L2 | Đã tương tác | Đang chăm | Chọn được khi tạo cơ hội | Người dùng |
| L2A | Không phù hợp / sai số | Đã đóng | Chọn một lý do trong danh mục. Cơ hội còn khoản thu thì không đóng sang L2A được, phải qua L7 | Người dùng |
| L2B | Quan tâm | Đang chăm | Không | Người dùng |
| L2C | Tiềm năng tương lai | Đang chăm | Xác nhận năm học nhập học | Người dùng |
| L3 | Hẹn tham quan / test | Đang chăm | Năm học nhập học, lớp dự tuyển, chương trình, và ít nhất một lịch hẹn tham quan hoặc test còn hợp lệ. Chọn được khi tạo cơ hội (kèm lịch hẹn) | Người dùng |
| L4 | Đã đến trường | Đang chăm | Năm học nhập học, lớp dự tuyển, chương trình | Người dùng tự chọn khi phụ huynh đã đến |
| L4A | Test không đạt | Đang chăm | Chương trình có test đầu vào; có lần test còn hiệu lực với kết quả không đạt | Hệ thống, khi ghi kết quả test |
| L4B | Test đạt, chưa chốt | Đang chăm | Chương trình có test đầu vào; có lần test còn hiệu lực với kết quả đạt | Hệ thống, khi ghi kết quả test |
| L5 | Đặt cọc | Đang chăm | Có khoản thu hợp lệ, hoặc đủ phí mà chưa ký hợp đồng | Hệ thống theo thu phí; lên tay có cảnh báo và lý do |
| L6 | Nhập học chính thức | Thành công | Đủ các đợt nhập học và đã ký hợp đồng nếu chương trình yêu cầu | Hệ thống theo thu phí; lên tay có cảnh báo và lý do |
| L7 | Rút phí | Đã đóng | Chọn một lý do rút trong danh mục | Hệ thống khi hoàn hết hoặc huỷ ghi danh cuối; trưởng nhóm, kế toán, quản trị chuyển tay |

## Khi nào phải ghi lý do

| Thao tác | Kiểu lý do |
|---|---|
| Chuyển sang L2A, L7 | Chọn trong danh mục lý do của level, ghi thêm chú thích nếu muốn |
| Lùi level, mở lại cơ hội đã đóng, lên tay Đặt cọc hay Nhập học, sửa hoặc huỷ kết quả test | Gõ lý do tự do, bắt buộc |
| Một lần đổi thuộc nhiều trường hợp trên | Chỉ một ô lý do |

## Con số cần nhớ

| Mục | Giá trị |
|---|---|
| Số lần test đầu vào tối đa của một cơ hội | 3, quản trị đổi được; lần đã huỷ không tính. Vượt thì hệ thống hỏi lại |
| Năm học | Từ 01/8 năm N tới 31/7 năm N+1, ghi "N–N+1" |
| Nhắc lập lại phiếu thu đã huỷ | Sau 1 ngày làm việc, quản trị đổi được |

> **Phần mềm hiện tại:** khi chuyển sang L3, phần mềm đang kiểm chương trình và lịch hẹn, chưa kiểm năm học nhập học và lớp dự tuyển.

__Liên quan:__ [Bộ level và hành trình của một cơ hội](./bo-level-va-hanh-trinh-co-hoi.md) · [Đổi level theo tiến trình chăm sóc](./doi-level.md) · [Khi không đổi được level](./su-co-doi-level.md)
