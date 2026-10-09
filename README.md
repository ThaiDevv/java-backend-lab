# java-backend-lab

Nơi học, thử sai và ghi chép theo lộ trình **Java Backend với Spring Boot** (8 giai đoạn, ~15 tuần).

Project thực hành xuyên suốt nằm ở repo riêng: [shop-api](https://github.com/ThaiDevv/shop-api).

> **Vì sao tách 2 repo?** Repo này là "phòng thí nghiệm": được phép viết code sai để tái hiện lỗi, commit thẳng `main`.
> `shop-api` là project làm như đi làm thật: chỉ merge qua Pull Request, dùng làm portfolio.

---

## Tiến độ

Trạng thái: ⬜ chưa bắt đầu · 🟨 đang học · ✅ đạt đầu ra

| GĐ | Chủ đề | Làm ở đâu | Đầu ra (đạt mới qua) | Trạng thái |
|---|---|---|---|---|
| 0 | Setup & công cụ: Git, Maven, IDE, Docker, Postman | [gd0-setup](gd0-setup/NOTES.md) + `shop-api` | Repo chuẩn; app Spring Boot rỗng kết nối DB chạy bằng Docker | ⬜ |
| 1 | Java Core: OOP, exception, equals/hashCode, Collections, Java 8+ | [gd1-java-core](gd1-java-core/NOTES.md) | Giải thích được HashMap, vì sao key nên immutable | ⬜ |
| 2 | SQL nền: JOIN, subquery, window function, CTE, chuẩn hóa, ACID | [gd2-sql](gd2-sql/NOTES.md) | ERD project, bảo vệ được từng quyết định thiết kế | ⬜ |
| 3 | Spring Core & REST API | `shop-api` | CRUD API chuẩn, lỗi thống nhất, có test | ⬜ |
| 4 | JPA/Hibernate & SQL hiệu năng | `shop-api` | Không còn N+1; index chứng minh bằng EXPLAIN | ⬜ |
| 5 | Transaction & Concurrency | [gd5-concurrency](gd5-concurrency/NOTES.md) + `shop-api` | Đặt hàng an toàn khi đồng thời, test 50 request song song | ⬜ |
| 6 | Hệ thống & vận hành: HTTP client, scheduled, Security, profile, Flyway, Actuator, logging | `shop-api` | Phân quyền, tách môi trường, job ngầm, gọi service ngoài có timeout | ⬜ |
| 7 | Mở rộng: JVM/GC, memory leak, partitioning/sharding, trigger, HATEOAS | [gd7-advanced](gd7-advanced/NOTES.md) | Hiểu khái niệm và tradeoff, có thí nghiệm minh họa | ⬜ |

Thứ tự: GĐ0 → (GĐ1 ∥ GĐ2) → GĐ3 → GĐ4 → GĐ5 → GĐ6 → GĐ7

---

## Cấu trúc

```
java-backend-lab/
├── gd0-setup/          # Ghi chú Git, Maven, Docker, IDE
├── gd1-java-core/      # Maven project thuần Java + learning tests (tự tạo)
├── gd2-sql/            # schema/, queries/, ERD
├── gd5-concurrency/    # Thí nghiệm đa luồng thuần Java
├── gd7-advanced/       # GC, memory leak, partitioning...
├── interview/          # Tự trả lời câu hỏi phỏng vấn từng GĐ
└── docs/               # roadmap.pdf
```

GĐ3, GĐ4, GĐ6 làm trực tiếp trên `shop-api`; ghi chú và thí nghiệm nằm ở `shop-api/docs/`.

---

## Quy tắc tự học

1. **Mỗi ngày ít nhất 1 commit**, message theo [Conventional Commits](https://www.conventionalcommits.org/): `docs:`, `test:`, `feat:`, `fix:`, `refactor:`, `chore:`.
2. **Ghi `NOTES.md` ngay khi học**, không dồn cuối tuần. Viết bằng lời của mình — không viết lại được bằng lời của mình nghĩa là chưa hiểu.
3. **Thí nghiệm: đoán trước, chạy sau.** Ghi giả thuyết trước khi chạy; chỗ đoán sai là chỗ học được nhiều nhất.
4. **Câu hỏi phỏng vấn: tự trả lời trước, xem đáp án sau.** Chỉ qua GĐ mới khi mọi câu của GĐ hiện tại đạt 🟢.
5. **Hết mỗi GĐ:** cập nhật bảng tiến độ ở trên, rồi gửi mentor review.
