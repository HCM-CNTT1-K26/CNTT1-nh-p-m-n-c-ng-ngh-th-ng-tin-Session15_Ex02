# CNTT1-nh-p-m-n-c-ng-ngh-th-ng-tin-Session15_Ex02
### 1. Bảng phân quyền an toàn

| Đối tượng | Quyền hạn | Lý do |
| --- | --- | --- |
| **Ứng viên ngoài** | **Chặn sạch (No Access)** | Cấm tuyệt đối để bảo vệ thông tin nhạy cảm như SĐT, mức lương kỳ vọng. |
| **Trưởng bộ phận** | **Commenter (Chỉ xem và góp ý)** | Cho phép nhận xét, đánh giá nhưng không được sửa trực tiếp bảng gốc hay tải file về máy. |
| **Trưởng phòng HR** | **Editor (Quản lý chính)** | Giữ quyền kiểm soát toàn bộ dữ liệu và phân phối phân quyền. |

---

### 2. Kịch bản xử lý sự cố khi lỡ lộ link Editor

1. **Thu hồi quyền ngay lập tức:** Vào phần quản lý chia sẻ, cắt đứt quyền của liên kết hoặc cá nhân bị lộ, chuyển trạng thái link về dạng **Hạn chế (Restricted)**.
2. **Kiểm tra lịch sử truy cập (Audit Log):** Vào mục hoạt động hoặc console quản trị để check xem đối tượng đó đã kịp bấm nút tải file (`Download`) hay chỉ mới mở xem (`View`).
3. **Chuyển sang chế độ gợi ý (Suggesting Mode):** Dùng chế độ này cho các sếp xem CV để mọi đóng góp đều hiển thị dưới dạng đề xuất, HR duyệt thì mới áp dụng vào file gốc.
