# GĐ5 — Transaction & Concurrency

> **Thời lượng:** 2 tuần · **Phụ thuộc:** GĐ3 (proxy), GĐ4 (JPA)
> **Đầu ra:** đặt hàng an toàn khi nhiều request đồng thời; có test 50 request song song chứng minh.

**Trạng thái:** ⬜ chưa bắt đầu

---

## Chia việc giữa 2 repo

| Ở đây (`java-backend-lab`) | Ở `shop-api` |
|---|---|
| Đa luồng **thuần Java**: Thread, `synchronized`, `volatile`, `ReentrantLock`, `AtomicInteger`, `ConcurrentHashMap`, thread pool | Isolation level, propagation, pessimistic/optimistic lock trên DB thật |
| Mục tiêu: thấy race condition xảy ra trong bộ nhớ JVM | Mục tiêu: thấy race condition xảy ra giữa nhiều request/transaction |

Câu hỏi chung của cả giai đoạn: **dữ liệu có còn đúng khi nhiều luồng/request chạy cùng lúc không?**

Lưu ý: `synchronized` chỉ khóa trong **một** JVM — chạy 2 instance app là vô dụng. Đây là lý do phải học thêm lock ở tầng DB.

---

## Checklist hoàn thành

<!-- Copy checklist GĐ5 từ docs/roadmap.pdf vào đây, tick dần -->

- [ ]

---

## Nhật ký

| Ngày | Chủ đề | Đã làm | Thời gian | Vướng gì |
|---|---|---|---|---|
| | | | | |

## Thí nghiệm

| # | Giả thuyết (ghi TRƯỚC khi chạy) | Kết quả thật (chạy ≥ 5 lần) | Cách sửa | Kết quả sau sửa |
|---|---|---|---|---|
| 1 | | | | |

> Bug concurrency không xảy ra mỗi lần chạy. Luôn chạy lặp nhiều lần và ghi lại số lần sai / tổng số lần.

## Điều mới hiểu ra

## Bẫy mình đã dính

## Câu hỏi còn vướng (mang đi hỏi mentor)

-
