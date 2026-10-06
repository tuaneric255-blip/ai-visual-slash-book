# CHƯƠNG 49 — COMPOSABLE SLASH GRAMMAR

## 49.1. Từ Slash Dictionary sang Slash Language
Một thư viện mạnh không cần tạo một lệnh riêng cho mọi hình ảnh có thể tưởng tượng. Thay vào đó, các slash nguyên tử được ghép thành visual instruction có cấu trúc.

Mô hình nền:
**SUBJECT → BODY STATE → POSE/GESTURE → ORIENTATION → CAMERA → FRAMING → OPTICS/FOCUS → LIGHT → ENVIRONMENT → STYLE/EFFECT**

Ví dụ:
`/stand /stepforward /wormseye /fullbody /foreshortening`

## 49.2. Atomic, Modifier, Composite và Recipe
- **Atomic Slash:** một ý nghĩa tương đối đơn nhất: `/sit`, `/kneel`, `/profile`.
- **Modifier Slash:** thay đổi atomic instruction: `/lookback`, `/chinhand`, `/onekneeup`.
- **Composite Semantic Slash:** mang nhiều thuộc tính nhưng vẫn tự hiểu được: `/seoulstreetlook`.
- **Recipe:** tổ hợp nhiều slash có mục tiêu production cụ thể.

## 49.3. Vì sao không tạo slash cho mọi pose?
Nếu `/chairslouch` có thể biểu diễn bằng `/sit /slouch /armchair`, canonical dictionary nên ưu tiên primitive có khả năng tái sử dụng. `/chairslouch` có thể xuất hiện ở Recipe/Combination Index.

## 49.4. Canonicalization rule
Chỉ tạo canonical entry riêng khi candidate:
1. có semantic meaning đủ rõ;
2. không thể biểu diễn tốt bằng tổ hợp primitive hiện có;
3. có giá trị tái sử dụng;
4. vượt qua evidence gate.

## 49.5. Order không phải syntax cứng
Slash order giúp con người đọc logic; không được tuyên bố model có parser chính thức theo thứ tự này.

### Tóm tắt chương
Slash Dictionary cung cấp từ vựng; Composable Slash Grammar cung cấp cách ghép thành ngôn ngữ hình ảnh.
