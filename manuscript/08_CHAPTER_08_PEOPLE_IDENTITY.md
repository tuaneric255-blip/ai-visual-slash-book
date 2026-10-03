# CHƯƠNG 8 — PEOPLE & IDENTITY: GIỮ ĐÚNG NGƯỜI TRƯỚC KHI LÀM ĐẸP ẢNH

## 8.1. Identity là constraint, không phải style
Khi làm việc với một người tham chiếu, mục tiêu đầu tiên không phải "đẹp hơn" mà là giữ những đặc điểm nhận diện cần thiết ổn định trong khi thay đổi pose, camera, ánh sáng hoặc bối cảnh.

Identity và aesthetic quality phải được đánh giá riêng. Một ảnh đẹp nhưng biến thành một người khác là thất bại nếu bài toán yêu cầu consistency.

## 8.2. Identity Lock gồm những gì?
Tùy workflow, nhóm đặc điểm cần giữ có thể gồm:
- cấu trúc khuôn mặt và tỷ lệ tổng thể;
- mắt, mày, mũi, môi, jawline;
- hairline, kiểu và màu tóc;
- skin tone/texture ở mức phù hợp;
- age appearance;
- tỷ lệ cơ thể tự nhiên;
- các đặc điểm nhận diện ổn định khác có trong reference.

Không nên dùng từ "100% identical" như một cam kết kỹ thuật. Cách viết chính xác hơn là **preserve identity as consistently as the system allows**.

## 8.3. Reference không phải prompt
Reference cung cấp thông tin thị giác; prompt mô tả ý định thay đổi. Hai lớp nên được tách:

**REFERENCE / LOCKS** → cái phải giữ.

**TRANSFORMATION** → cái được thay đổi.

Ví dụ:
Giữ identity + hair + body proportions.
Thay pose → contrapposto.
Thay camera → low angle.
Giữ wardrobe + scene + light.

## 8.4. Identity Drift
Drift có thể biểu hiện qua khuôn mặt, tuổi, tóc, tỷ lệ cơ thể hoặc phong cách retouch. Khi nhiều biến thay đổi cùng lúc, khó xác định nguyên nhân.

Cách debug:
1. quay về reference;
2. chỉ thay một biến;
3. kiểm tra identity;
4. thêm biến tiếp theo;
5. ghi nhận bước bắt đầu drift.

## 8.5. Same Person không đồng nghĩa Same Image
Một bộ city pack có thể giữ cùng người nhưng vẫn cần thay wardrobe, pose, weather hoặc scene. Vì vậy consistency không có nghĩa mọi ảnh phải giống hệt nhau; nó nghĩa các thuộc tính được khóa vẫn nhận diện được xuyên suốt biến đổi.

## 8.6. Group Identity
Khi có nhiều người, bài toán khó hơn: mỗi identity cần được phân biệt và quan hệ vị trí cần ổn định. Prompt nên tránh mô tả mơ hồ như "same people" nếu có thể định danh vai trò: subject A, subject B, left/right hoặc wardrobe marker.

## 8.7. Identity Evidence
Nếu một slash hoặc macro được quảng bá là giúp giữ identity, claim đó phải được test riêng. Việc model tình cờ giữ người giống trong một output không đủ chứng minh slash có tác dụng identity-lock.

### Tóm tắt chương
Identity là một hệ constraint độc lập. Khóa cái cần giữ, cô lập cái cần đổi và đánh giá consistency tách khỏi vẻ đẹp của output.
