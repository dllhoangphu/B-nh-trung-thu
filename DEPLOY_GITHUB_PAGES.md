# Hướng dẫn deploy trang web lên GitHub Pages

## 1. Đẩy mã nguồn lên GitHub
- Nếu chưa có repository, tạo một repository mới trên GitHub.
- Kết nối thư mục dự án với repository:
  ```bash
  git init
  git remote add origin https://github.com/<tên-tài-khoan>/<ten-repo>.git
  git add .
  git commit -m "Initial commit"
  git push -u origin main
  ```

## 2. Bật GitHub Pages
- Truy cập repository trên GitHub.
- Vào mục **Settings** → **Pages**.
- Ở phần **Source**, chọn branch là `main` và folder là `/ (root)`.
- Nhấn **Save**.

## 3. Truy cập trang web
- Sau vài phút, GitHub sẽ cung cấp một đường link dạng:
  `https://<tên-tài-khoan>.github.io/<ten-repo>/`
- Truy cập link này để xem trang web của bạn.

---
Nếu cần hỗ trợ chi tiết hơn, hãy gửi link repository hoặc hỏi thêm nhé!