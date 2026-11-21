# Lịch tập – cách có file APK

1. Tạo repo mới trên GitHub (ví dụ `lich-tap`), tải toàn bộ thư mục này lên nhánh `main`
   (nhớ giữ cả thư mục ẩn `.github`).
2. Vào tab **Actions** → workflow **Build APK** sẽ tự chạy (khoảng 5–8 phút).
   Nếu chưa chạy: chọn workflow → **Run workflow**.
3. Khi xong, vào **Releases** của repo → tải `app-debug.apk` ngay trên điện thoại → mở file để cài.
   (Cho phép "Cài đặt ứng dụng không rõ nguồn" cho trình duyệt nếu máy hỏi.)
4. Lần đầu mở app, bấm **Cho phép** khi được hỏi quyền thông báo.

Sửa giao diện/tính năng: chỉ cần sửa `www/index.html`, commit lên GitHub → APK mới được build lại.
