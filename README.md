# CSE391 - Nền Tảng Phát Triển Web

## Thông tin sinh viên

| Thông tin        | Chi tiết      |
| ---------------- | ------------- |
| **Họ và tên**    | Hoàng Bảo Nam |
| **Mã sinh viên** | 2451170931    |
| **Lớp**          | K66KTPM2.1    |

---

## Mô tả bài thi

Ứng dụng **Task List** cho phép người dùng quản lý danh sách công việc cá nhân, bao gồm các chức năng:

- Hiển thị danh sách Tasks với thông tin Task, Priority và Status
- Thêm Task mới thông qua form với validation
- Lưu trữ dữ liệu bằng file `data.json`

---

## Cấu trúc thư mục

```
CSE391_Ktra_2451170931_HoangBaoNam_K66KTPM2.1/
├── css_bootstrap/        # Thư viện Bootstrap CSS
├── js_bootstrap/         # Thư viện Bootstrap JS
├── index.html            # Giao diện chính
├── style.css             # CSS tùy chỉnh
├── script.js             # Logic JavaScript
├── data.json             # Dữ liệu giả lập CSDL
└── README.md             # Tài liệu dự án
```

---

## Checklist bài kiểm tra

### Câu 1 — Giao diện HTML/CSS Bootstrap (4 điểm)

- [x] Hiển thị tiêu đề **Task List** và nút **+ Add Task**
- [x] Hiển thị danh sách task với các cột: Task, Priority, Status, Action
- [x] Priority hiển thị đúng màu: `High` (đỏ), `Medium` (cam), `Low` (xanh lá)
- [x] Status hiển thị dạng badge: `To Do`, `In Progress`, `Done`
- [x] Có icon **Edit** và **Delete** cho mỗi task
- [x] Form **Add Task** có ô nhập tên task và chọn Priority (High / Medium / Low)
- [x] Form có nút **Add** và nút đóng **×**
- [x] Giao diện responsive, cơ bản đẹp

### Câu 2 — JavaScript (3 điểm)

- [x] Tạo file `data.json` chứa tối thiểu **5 tasks** đúng cấu trúc JSON _(1 điểm)_
- [x] Validation: Tên Task **không được để trống**
- [x] Validation: Tên Task **không quá 100 ký tự**
- [x] Hiển thị thông báo lỗi rõ ràng khi dữ liệu không hợp lệ _(2 điểm)_

### Câu 3 — ReactJS (3 điểm)

- [ ] Chuyển đổi giao diện Câu 1 sang **ReactJS**
- [ ] Đọc và hiển thị dữ liệu động từ `data.json`
- [ ] Chức năng **Thêm mới** task hoạt động đúng
- [ ] Sử dụng **State / Props** phù hợp
- [ ] Sử dụng **fetch / axios** để truy vấn `data.json`

---

_Bài thi môn CSE391 — Trường Đại học Thủy Lợi, Khoa Công nghệ Thông tin_
