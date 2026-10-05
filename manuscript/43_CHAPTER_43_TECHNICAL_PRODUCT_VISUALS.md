# CHƯƠNG 43 — TECHNICAL PRODUCT VISUALS

## 43.1. Technical-looking không đồng nghĩa technically correct
AI có thể tạo hình rất giống sơ đồ kỹ thuật nhưng invent component. Sách phải tách **visual semantics** khỏi **engineering correctness**.

## 43.2. Exploded View
`/explodedview`

Các component được tách theo trục/quan hệ để thể hiện cấu tạo. Test visual semantics có thể đánh giá spacing, assembly relationship và readability; không được xác nhận component là thật nếu không có source.

## 43.3. Cutaway
`/cutaway`

Một phần outer shell được loại bỏ để thấy bên trong. Cần reference kỹ thuật nếu accuracy quan trọng.

## 43.4. Cross Section
`/crosssection`

Mặt cắt cho thấy internal layers/structure. Với product thật, generated internals không phải dữ liệu kỹ thuật.

## 43.5. X-ray / Transparent Shell
`/xrayview` · `/transparentshell`

Đây là explanatory visual styles, không phải imaging/engineering evidence.

## 43.6. Blueprint / Diagram
`/blueprint` · `/technicaldiagram` · `/schematic`

Typography, dimensions và callouts do AI sinh phải được kiểm tra; không dùng generated dimensions làm thông số sản phẩm.

### Tóm tắt chương
Technical Product Visuals có thể giải thích ý tưởng rất tốt, nhưng accuracy phải đến từ dữ liệu kỹ thuật thật.
