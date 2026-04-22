### 1. Tại sao thiếu hibernate.dialect lại khiến Hibernate không thể khởi động?

Vì hibernate.dialect giúp mình xem là đang dùng loại Database nào

Là cách chuyển đổi từ HQL sang SQL

Nếu thiếu: 

Hibernate không biết cú pháp SQL cần sinh ra

Không thể mapping dữ liệu

### 2. Thuộc tính nào giúp tự động tạo bảng từ Entity?
Là hibernate.hbm2ddl.auto

