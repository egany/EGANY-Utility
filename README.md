# EGANY-Utility
EGANY Utility là bộ tiện ích mở rộng cho quản trị website trên các nền tảng Bizweb, Haravan và Shopify.

# Để có thể chỉnh sửa trực tiếp nội dung của Sản Phẩm và Bài Viết:
Trong mã nguồn của giao diện trước khi in Content ra nên thêm đoạn
* Đối với product.bwt
<div id="egany-content-edit" data-id="{{product.id}}" >
  {{product.content}}
</div>
* Đối với article.bwt 
<div id="egany-content-edit" data-id="{{article.id}}" data-item="article" data-blog="{{blog.id}}" >
  {{article.content}}
</div>
