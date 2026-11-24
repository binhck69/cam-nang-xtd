# Tính lại level khi chưa khớp thu phí

> Khi phiếu thu đã lưu mà level chưa đổi theo, bạn yêu cầu hệ thống tính lại level từ dữ liệu thu phí hiện có.

__Khi nào dùng:__ khung trạng thái cơ hội báo "Chưa lên L5 — phiếu chưa ghi nhận"; hoặc cơ hội đủ phí và đã ký hợp đồng mà vẫn ở L5.

__Trước khi bắt đầu:__ dữ liệu thu phí (phiếu thu, ký hợp đồng) đã được kế toán ghi đúng.

## Các bước

1. Mở cơ hội, tìm khung «Trạng thái cơ hội».
2. Bấm «Thử ghi nhận phiếu lại».
   → *Kết quả:* một trong các thông báo:

| Thông báo | Nghĩa |
|---|---|
| "Đã lên L5." | Cơ hội đã ở Đặt cọc. Tiếp theo: ký hợp đồng để lên L6 |
| "Đã lên L6." | Cơ hội đã Nhập học. Tiếp theo: bàn giao Hành chính |
| "Phiếu chưa ghi nhận vào cơ hội." | Level chưa đổi. Kiểm lại số tiền rồi thử lại; vẫn lỗi thì báo quản trị |
| "Chưa thực hiện được" | Lỗi khi tính lại; thử lại sau, vẫn lỗi thì báo quản trị |

## Luật tính lại

- Tính lại dùng đúng luật tự đổi level theo thu phí: chỉ tiến, phí kiểm tra không tính. Xem [Level và thu phí khớp nhau thế nào](./level-va-thu-phi.md).
- Tính lại **không** đưa cơ hội lên lại level đã bị lùi bằng tay, trừ khi có khoản thu mới sau lần lùi đó.
- Không có gì mới thì level không đổi và không ghi lịch sử.

> **Phần mềm hiện tại:** đặc tả cho mọi vai bấm tính lại level. Phần mềm đang cần quyền lập phiếu thu, mặc định chỉ kế toán; người khác thấy nút bị tắt và nhờ kế toán.

__Liên quan:__ [Soát cơ hội lệch thu phí](./soat-co-hoi-lech-thu-phi.md) · [Lùi level, đóng hoặc mở lại cơ hội](./lui-dong-mo-lai-co-hoi.md)
