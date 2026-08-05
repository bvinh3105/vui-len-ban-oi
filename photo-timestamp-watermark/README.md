# Photo Timestamp Watermark

Tool web tĩnh chèn watermark ngày giờ + địa chỉ lên ảnh hàng loạt, phong cách iOS Photos location stamp.

**Live:** https://bvinh3105.github.io/vui-len-ban-oi/photo-timestamp-watermark/

## Tính năng

- Upload nhiều file, nhiều thư mục, kéo thả cùng lúc
- Ngày + giờ bắt đầu + khoảng cách giây → tự sinh timestamp tuần tự có jitter tự nhiên
- 5 định dạng ngày, 4 vị trí đặt text, cỡ chữ điều chỉnh, shadow bật/tắt
- Preview trực tiếp dòng đầu
- Xử lý client-side hoàn toàn — ảnh không đi đâu
- Tải hàng loạt dưới dạng ZIP (STORE mode, không nén JPEG)
- Light/Dark theme

## Cách dùng

1. Nhập ngày, giờ bắt đầu, khoảng cách giây
2. Nhập các dòng địa chỉ (mỗi dòng một dòng)
3. Chọn vị trí, cỡ chữ, có/không shadow
4. Kéo thả ảnh hoặc chọn file/thư mục
5. Bấm **Xử lý tất cả** → **Tải ZIP**

## Chạy local

Chỉ cần mở `index.html` bằng trình duyệt bất kỳ. Không cần server, không dependency.
