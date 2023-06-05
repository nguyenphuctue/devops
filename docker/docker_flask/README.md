# Sự khác nhau giữa user-defined bridges và the default bridge

1. User-defined bridges cung cấp DNS tự động giữa các container
2. User-defined bridges có tính độc lập tốt hơn. Các container được gắn mạng bridge default có thể bị các container không liên quan kết nối vào. Trong khi user-defined bridges không thể bị các container không liên quan kết nối vào khi nó không tham gia vào mạng.
3. Các container trong mạng user-defined có thể thêm vào hoặc xóa đi một cách nhanh chóng. Trong khi các container trong mạng default bridge cần phải dừng trước khi xóa.
4. Mỗi mạng user-defined có thể được cấu hình tùy chỉnh mà không ảnh hưởng đến các container ngoài mạng.
5. Các container trong mạng default bridge có thể chia sẻ biến môi trường.