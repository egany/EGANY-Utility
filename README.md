# EGANY-Utility
EGANY Utility là bộ tiện ích mở rộng cho quản trị website trên các nền tảng Bizweb, Haravan và Shopify.

Version 1.0 hiện chỉ mới hỗ trợ người dùng trên nền tảng Bizweb.

## Các tính năng nổi bật hiện có:

1. Chỉnh sửa nội dung mô tả của Sản Phẩm và Bài Viết trực tiếp ngoài giao diện người dùng, mà không cần truy cập vào trang quản trị

2. Thêm / Xoá / Sửa trường thông tin bổ sung (MetaField) cho loại dữ liệu Sản Phẩm (product) và Khách Hàng (customer)
- Loại dữ liệu Con Số
- Loại dữ liệu Ngày Tháng
- Loại dữ liệu Văn Bản (có trình chỉnh sửa và format dữ liệu trực tiếp)

3. Thêm và xoá tag hàng loạt vào sản phẩm, khách hàng chỉ trong 1 click chuột

.. và những tính năng khác đang chờ cập nhật từ phản hồi của người dùng... 

## Lưu ý:
- Click vào biểu tượng của tiện ích mở rộng này để sử dụng!

## Mặc định các giao diện của EGANY đều được hỗ trợ đầy đủ tính năng
Nếu bạn *không sử dụng giao diện của EGANY* có thể xem hướng dẫn bên dưới để cấu hình cho giao diện của mình chạy được *chế độ chỉnh sửa trực tiếp*.

## Hướng dẫn bật chế độ chỉnh sửa nội dung Sản Phẩm và Bài Viết:
Mở mã nguồn của giao diện từng file và điều chỉnh như bên dưới:

## Đối với product.bwt
```
<div id="egany-content-edit" data-id="{{product.id}}" >
  {{product.content}}
</div>
```
## Đối với article.bwt 
```
<div id="egany-content-edit" data-id="{{article.id}}" data-item="article" data-blog="{{blog.id}}" >
  {{article.content}}
</div>
```
