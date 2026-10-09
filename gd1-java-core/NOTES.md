# GĐ1 — Java Core

> **Thời lượng:** 2 tuần · **Phụ thuộc:** GĐ0 · **Học song song được với GĐ2**
> **Đầu ra:** giải thích được HashMap hoạt động thế nào và vì sao key nên immutable; vẽ được cây exception cho project.

**Trạng thái:** ⬜ chưa bắt đầu

---

## Cách học ở thư mục này: learning tests

Thư mục này sẽ là **một Maven project thuần Java** (không Spring) có JUnit 5 — **bạn tự tạo** (`pom.xml`, `src/main/java`, `src/test/java`).

Gợi ý chia package theo chủ đề:

```
src/test/java/lab/
├── oop/           # overloading vs overriding, composition
├── exception/     # checked vs unchecked, try-with-resources, exception chaining
├── equality/      # equals/hashCode contract, mutable key trong HashMap
├── collections/   # List/Set/Map, fail-fast iterator, Comparable vs Comparator
├── string/        # String pool, immutability, StringBuilder
└── java8/         # lambda, Stream, Optional
```

**Vì sao viết test thay vì `System.out.println`?**
Mỗi test là một *khẳng định* về hành vi Java bạn tin là đúng. Hiểu sai → test fail → bạn buộc phải đi tìm lý do.
Ba tháng sau đọc lại test là nhớ ngay, và chạy lại được để kiểm chứng.

Đặt tên test mô tả hành vi, ví dụ: `mutatedKey_isNoLongerFoundInHashMap()`.

---

## Checklist hoàn thành

<!-- Copy checklist GĐ1 từ docs/roadmap.pdf vào đây, tick dần -->

- [ ]

---

## Nhật ký

| Ngày | Chủ đề | Đã làm | Thời gian | Vướng gì |
|---|---|---|---|---|
| | | | | |

## Thí nghiệm

| # | Giả thuyết (ghi TRƯỚC khi chạy) | Kết quả thật | Đúng/Sai | Test |
|---|---|---|---|---|
| 1 | | | | |

## Điều mới hiểu ra

<!-- Viết bằng lời của mình -->

## Bẫy mình đã dính

## Câu hỏi còn vướng (mang đi hỏi mentor)

-
