# Đố vui giơ ngón tay

Trò chơi trắc nghiệm cho học sinh tiểu học. Học sinh chọn đáp án bằng cách giơ ngón tay trước camera:

| Số ngón | Đáp án |
|---|---|
| 1 | A |
| 2 | B |
| 3 | C |
| 4 | D |

Chỉ giơ từ 1 đến 4 ngón; xòe cả 5 ngón là không hợp lệ (trò chơi sẽ đọc "Không phù hợp, mời chọn lại đáp án"). Giữ tay yên khoảng 1,5 giây để chốt đáp án.

## Tính năng
- Giao diện đổi màu và hình trang trí theo từng câu hỏi
- Giáo viên tự soạn câu hỏi (nút "Soạn câu hỏi"), lưu trên trình duyệt
- Nhận diện ngón tay bằng MediaPipe Hands, camera hiển thị trong ô tròn ở giữa màn hình
- Có thể bấm vào đáp án hoặc nhấn phím 1-4 nếu không dùng camera

## Chạy trên GitHub Pages
1. Tạo repository mới và tải `index.html` cùng `README.md` lên.
2. Vào **Settings > Pages**, ở mục **Branch** chọn `main` và thư mục `/ (root)`, rồi bấm **Save**.
3. Sau 1-2 phút, mở đường dẫn `https://<tên-tài-khoản>.github.io/<tên-repo>/`.

GitHub Pages dùng `https` nên trình duyệt cho phép bật camera. Máy cần có Internet để tải thư viện nhận diện tay.

## Chỉnh sửa
- Câu hỏi mẫu: biến `SAMPLE` trong `index.html`
- Thời gian giữ tay: biến `HOLD` (mili giây)
