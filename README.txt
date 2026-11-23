HSK6 Luyện viết — bộ file web cài được (PWA)
Các file: index.html, manifest.json, sw.js, icon-192/512.png, icon-maskable-192/512.png, apple-touch-icon.png, favicon.ico
Đưa TẤT CẢ file trong thư mục này lên cùng một chỗ (cùng thư mục gốc) của hosting HTTPS:
 - GitHub Pages / Netlify / Cloudflare Pages / Vercel đều được (miễn phí).
Cài đặt: Android/Chrome -> menu ⋮ -> "Cài đặt ứng dụng"; iPhone/Safari -> Chia sẻ -> "Thêm vào MH chính".
Lần sau sửa index.html: đổi VERSION trong sw.js (vd hsk6-viet-v2) để máy người dùng nhận bản mới.
Lưu ý: service worker chỉ chạy trên https:// hoặc http://localhost, không chạy khi mở file bằng file://.
