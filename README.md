# EGANY-Utility
EGANY Utility là bộ tiện ích mở rộng cho quản trị website trên các nền tảng Bizweb, Haravan và Shopify.


## Mặc định các giao diện của EGANY đều được hỗ trợ đầy đủ tính năng
Nếu bạn không sử dụng giao diện của EGANY có thể xem hướng dẫn bên dưới để cấu hình cho giao diện của mình chạy được *chế độ chỉnh sửa trực tiếp*.

## Hướng dẫn bật chế độ chỉnh sửa nội dung Sản Phẩm và Bài Viết khi không sử dụng theme EGANY:
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
