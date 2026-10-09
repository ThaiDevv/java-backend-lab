# schema/

DDL và ERD cho dữ liệu của `shop-api`.

## Quy ước

- Đánh số theo thứ tự chạy: `01_create_tables.sql`, `02_constraints.sql`, `03_seed_data.sql`.
- Mỗi file chạy lại được nhiều lần (dùng `DROP ... IF EXISTS` hoặc `CREATE ... IF NOT EXISTS`) — tiện khi phải reset dữ liệu để làm lại thí nghiệm.
- ERD xuất ra ảnh `erd.png` (dbdiagram.io / draw.io) và **giữ cả file nguồn** (`erd.dbml` hoặc `erd.drawio`) để sửa sau.

> Sang GĐ6, schema chính thức sẽ chuyển thành migration Flyway trong `shop-api`.
> Thư mục này giữ lại làm nơi nháp và thử thiết kế.
