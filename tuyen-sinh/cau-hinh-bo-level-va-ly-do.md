# Cấu hình bộ level và danh mục lý do

> Quản trị thêm, sửa, ngừng dùng level; đặt ngưỡng nguội, ngưỡng đạt test; quản lý danh sách lý do từ chối.

> **Cảnh báo:** thay đổi áp dụng ngay cho mọi người dùng, từ lần đổi level kế tiếp. Không làm đổi level hiện tại hay lịch sử của các cơ hội đã có.

__Khi nào dùng:__ trường cần thêm một bước mới, đổi tên level, chỉnh số ngày nguội, hoặc thêm lý do từ chối.

__Trước khi bắt đầu:__ bạn là quản trị. Trưởng nhóm chỉ xem được trang này.

## Thêm level

1. Vào «Cài đặt», nhóm «Danh mục», mục «Bộ level».
   → *Kết quả:* thấy nhóm «Bộ level chung» và «Level cũ (ngừng dùng)».
2. Bấm «Thêm level», điền:
   - «Mã level»: không đổi được sau khi tạo, không trùng mã đã có (kể cả mã đã ngừng dùng).
   - «Tên», «Bước», «Level chính» (chọn nếu đây là level con), «Màu».
   - Tick nếu cần: «Level dừng», «Bắt buộc lý do», «Tính đăng ký (thành công)», «Chọn được khi tạo cơ hội».
3. Bấm «Lưu level».
   → *Kết quả:* báo "Đã thêm level {mã}".

## Sửa level, ngưỡng nguội, ngưỡng đạt test

- Sửa tên, cờ của level ngay trên dòng level.
- «Ngưỡng nguội (ngày)»: số ngày không tương tác thì cơ hội hiện nhãn nguội. Để 0 hoặc trống là tắt. Xem [Chăm sóc lại cơ hội nguội](./cham-soc-lai-co-hoi-nguoi.md).
- Mục «Ngưỡng đạt test đầu vào»: bật môn và đặt điểm đạt cho từng môn. Xem [Ghi kết quả test đầu vào](./ghi-ket-qua-test-dau-vao.md).

Luật theo đặc tả:

- Level chưa từng được cơ hội nào dùng thì xoá được; level đã dùng chỉ ngừng dùng được.
- Có 6 vai trò cố định: Đã hẹn, Test không đạt, Test đạt, Đặt cọc, Nhập học, Rút. Mỗi vai trò gắn đúng một level đang dùng, theo đúng thứ tự bậc. Level đang gắn vai trò phải chuyển vai trò sang level khác trước khi ngừng dùng.
- Mọi thay đổi ghi vào nhật ký cấu hình: ai sửa, lúc nào, giá trị cũ và mới.

## Danh mục lý do từ chối

1. Vào «Cài đặt», mục «Lý do từ chối».
2. Thêm: gõ vào «Thêm lý do», bấm «Thêm».
3. Tạm không dùng một lý do: bấm «Ẩn» (bấm «Hiện» để dùng lại).
4. Xoá: bấm «Xoá», xác nhận. Lý do đã dùng trên cơ hội không xoá được; báo "Lý do đang dùng trên N cơ hội — ẩn thay vì xoá."
5. Đổi thứ tự bằng mũi tên lên, xuống.

> **Phần mềm hiện tại:**
> - Chưa thấy chỗ gắn 6 vai trò cho level; luật trên phần mềm đang gắn thẳng theo mã L3 tới L7.
> - Đặc tả có danh mục lý do riêng cho từng level cần lý do (L2A, L7); phần mềm dùng chung danh sách «Lý do từ chối», kể cả khi rút.
> - Trưởng nhóm đổi tên level được trên phần mềm; đặc tả chỉ cho quản trị.
> - Chưa thấy chỗ cấu hình số lần test tối đa và số ngày nhắc lập lại phiếu đã huỷ.
> - Mô tả đầu trang «Lý do từ chối» còn nhắc mã level cũ.

__Liên quan:__ [Các level và điều kiện vào từng level](./tra-cuu-level-va-dieu-kien.md) · [Quyền theo vai và phạm vi xem](../bat-dau/tra-cuu-quyen-theo-vai.md)
