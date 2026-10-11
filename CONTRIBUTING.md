# Hướng dẫn đóng góp

Cảm ơn bạn đã quan tâm đến dự án!

## Cách báo lỗi (Issue)
1. Vào tab **Issues**, bấm **New issue**.
2. Đặt tiêu đề ngắn gọn, rõ vấn đề.
3. Mô tả: các bước tái hiện lỗi, kết quả mong đợi, kết quả thực tế,
   hệ điều hành và phiên bản trình biên dịch.

## Cách gửi Pull Request
1. Fork repository về tài khoản của bạn.
2. Tạo nhánh mới: `git checkout -b feature/ten-tinh-nang`
3. Sửa code, kiểm tra build chạy đúng.
4. Commit theo quy tắc bên dưới.
5. Push nhánh lên fork và mở Pull Request vào nhánh `main`.
6. Mô tả rõ thay đổi và liên kết tới Issue liên quan (nếu có).

## Quy tắc đặt tên commit
Dùng dạng: `<loại>: <mô tả ngắn>`

Các loại thường dùng:
- `feat`: thêm tính năng
- `fix`: sửa lỗi
- `docs`: thay đổi tài liệu
- `refactor`: cải tổ code

Ví dụ: `docs: add build instructions to README`