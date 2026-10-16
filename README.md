# Đội tuyển Văn — V3 (bản lưu cục bộ)

## Mở ứng dụng
1. Giải nén `DOITUYENVAN_V3.zip`.
2. Mở `index.html` bằng trình duyệt hiện đại (Chrome/Edge khuyến nghị).
3. Ứng dụng mở trực tiếp, không cần đăng nhập, không cần cấu hình Supabase.

## Lưu trữ và riêng tư
- Dữ liệu thành viên, điểm danh, buổi sinh hoạt, tình huống và nhật ký được lưu bằng `localStorage` trên trình duyệt hiện tại.
- Không có đồng bộ đám mây; các thiết bị khác không tự thấy dữ liệu của thiết bị này.
- Vào **Quản lý & dữ liệu → Xuất bản sao JSON** để sao lưu thường xuyên. Cất tệp sao lưu ở nơi an toàn.
- Khi chuyển thiết bị/trình duyệt, mở ứng dụng trên thiết bị mới và dùng **Nhập bản sao JSON**.
- Xóa dữ liệu website/trình duyệt có thể làm mất dữ liệu cục bộ. Hãy sao lưu trước khi xóa cache/dữ liệu trang.

## Chức năng
- Quản lý hồ sơ và trạng thái thành viên; tìm kiếm, lọc, nhập danh sách.
- Điểm danh theo buổi, tạo và chốt buổi.
- Theo dõi tình huống/yêu cầu và trạng thái xử lý.
- Nhật ký hoạt động, xuất CSV, sao lưu/nhập JSON.
- Giao diện sáng/tối và tối ưu responsive.

## Lưu ý
Bản này được chuyển sang chế độ lưu cục bộ để dễ mở và không phụ thuộc Supabase. Nó không phải hệ thống đăng nhập bảo mật: người có quyền truy cập trình duyệt/hồ sơ người dùng trên thiết bị có thể xem dữ liệu. Tránh lưu thông tin nhạy cảm.
