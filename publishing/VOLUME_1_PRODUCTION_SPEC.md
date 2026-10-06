# VOLUME 1 — PRODUCTION SPEC

## 1. Mục tiêu
Tập 1 là visual field handbook thực chiến. Người đọc phải có thể đi theo nhịp:
**xem → nhận ra thay đổi → đọc slash → hiểu cơ chế → copy → kết hợp → tự kiểm tra.**

Không biến sách thành giáo trình toàn chữ. Không dùng ảnh đẹp ngẫu nhiên để minh họa cho một behavioral claim.

## 2. Ba cấu trúc hình chuẩn

### A. CONTROL → SLASH RESULT
Dùng cho một slash cần cho thấy hiệu ứng riêng.

| CONTROL | SLASH RESULT |
|---|---|
| ảnh baseline | ảnh test |
| CONTROL | `/lowangle` |

Ngay dưới pair:
- **Quick meaning:** 1–2 câu.
- **What changed:** đúng biến slash cần tác động.
- **What stayed:** subject/identity/outfit/scene/light… nếu được khóa.
- **Prompt foundation:** natural-language expansion.
- **Evidence badge:** VERIFIED / CONTEXTUAL / UNSTABLE / REJECTED / UNTESTED.

### B. REFERENCE → APPLIED RESULT
Dùng cho reference/editing. Trình bày ảnh reference bên trái và output bên phải. Ghi rõ MUST KEEP / MUST CHANGE.

### C. FINAL RESULT + SLASH STACK
Dùng cho combination/recipe. Ảnh final lớn. Slash stack đặt ngay dưới ảnh, ví dụ:
`/sit /onekneeup /chinhand /highangle /fullbody`
Sau đó dùng legend nhỏ để chỉ layer của từng slash.

## 3. Quy tắc evidence
- TEST EVIDENCE và DOCUMENTATION ILLUSTRATION phải khác badge.
- Composite board không phải atomic evidence.
- Không tự ghi model/version/run count/date nếu provenance không tồn tại.
- Ảnh failure chỉ được gọi là failure evidence khi là original output của run đã đăng ký.

## 4. Diagram rule
Chuỗi có trình tự, phân cấp, vòng lặp hoặc quan hệ nhiều node phải chuyển thành figure SVG/HTML.
Không để pipeline dài dạng chữ có mũi tên chạy xuyên trang.
Không biến mọi danh sách thành infographic.

## 5. Human-writing rule
Biên tập loại:
- câu mở đầu/kết luận lặp công thức;
- “không chỉ… mà còn…” nếu không thực sự cần;
- các đoạn nhắc lại định nghĩa vừa nói;
- bullet đồng dạng chỉ để kéo dài;
- câu khẳng định mơ hồ kiểu “điều quan trọng là…”;
- kết chương máy móc.

Ưu tiên:
- câu ngắn, có chủ ngữ và nhận định rõ;
- ví dụ ngay sau khái niệm khó;
- nhận xét thực hành;
- giới hạn/ngoại lệ;
- thuật ngữ nhất quán;
- không kéo dài chương để đủ trang.

## 6. Publishing pipeline
MANUSCRIPT → HUMAN EDIT → VISUAL STRUCTURE AUDIT → FIGURE/SVG → HTML PRINT MASTER → PDF.
DOCX là editorial/review master, không phải giới hạn thiết kế cuối cùng.
