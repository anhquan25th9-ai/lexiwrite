# LexiWrite iOS (.ipa) Builder

Bộ mã nguồn đóng gói **LexiWrite v3** thành ứng dụng iOS thật (`.ipa`) kèm biểu tượng bạn đã chọn, biên dịch tự động miễn phí bằng **GitHub Actions** (không cần máy Mac).

## Cách tạo file `LexiWrite.ipa` (3 phút)
1. Giải nén toàn bộ thư mục này.
2. Tạo một Repository mới trên GitHub (Public hoặc Private đều được).
3. Tải toàn bộ các tệp và thư mục bên trong (bao gồm cả thư mục ẩn `.github`) lên Repository đó.
4. Vào tab **Actions** trên GitHub -> chọn workflow **Build LexiWrite iOS IPA** -> chờ khoảng 3-5 phút đến khi có dấu tích xanh.
5. Nhấn vào lần chạy vừa xong -> cuộn xuống mục **Artifacts** -> tải **LexiWrite-IPA** (giải nén sẽ được file `LexiWrite.ipa`).

## Cách cài `LexiWrite.ipa` vào iPhone (từ máy Windows)
- **Cách 1 (Nhanh nhất - Sideloadly):** Tải Sideloadly trên Windows, cắm cáp iPhone, kéo file `LexiWrite.ipa` vào, đăng nhập Apple ID và bấm **Start**. Sau đó trên iPhone vào *Cài đặt -> Cài đặt chung -> Quản lý VPN & Thiết bị* để Tin cậy (Trust).
- **Cách 2 (Tự gia hạn không cần máy tính - SideStore):** Cài SideStore một lần, sau đó nhập `LexiWrite.ipa` trực tiếp trên iPhone và bấm Refresh qua Wi-Fi mỗi 7 ngày.

## Mẹo cập nhật giao diện
Nếu sau này bạn muốn sửa nội dung app, chỉ cần thay thế tệp `www/index.html` rồi đẩy lên GitHub, file `.ipa` mới sẽ tự động được tạo lại.
