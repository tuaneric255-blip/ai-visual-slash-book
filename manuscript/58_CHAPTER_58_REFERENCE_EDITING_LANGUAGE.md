# CHƯƠNG 58 — REFERENCE & EDITING LANGUAGE

## 58.1. Reference có nhiều loại
Identity reference, product reference, style reference, composition reference và environment reference không nên bị trộn thành một khái niệm.

## 58.2. Lock vocabulary
Các khái niệm thực hành: `/sameperson`, `/sameproduct`, `/sameoutfit`, `/samebackground`, `/samecomposition`. Đây là semantic shorthand hoặc author-defined macro tùy cách triển khai, không phải native command.

## 58.3. Edit operations
`/replacebackground`, `/removeobject`, `/addobject`, `/recolor`, `/restyle`, `/extendframe`, `/cleanup`.

## 58.4. Change budget
Mỗi edit nên nêu rõ:
- MUST KEEP;
- MUST CHANGE;
- MAY CHANGE;
- MUST NOT ADD.

## 58.5. Identity wording
Không hứa “100% identical” khi hệ thống không bảo đảm pixel/identity determinism. Dùng ngôn ngữ: preserve identity as closely and consistently as possible.

### Tóm tắt chương
Reference editing tốt bắt đầu bằng việc xác định cái gì được đổi và cái gì tuyệt đối phải giữ.
