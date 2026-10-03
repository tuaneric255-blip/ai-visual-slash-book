# CHƯƠNG 3 — VISUAL SLASH GRAMMAR: NGỮ PHÁP CỦA MỘT HÌNH ẢNH

## 3.1. Từ danh sách slash đến một câu thị giác
Một prompt hình ảnh tốt không phải là túi từ khóa. Nó là một hệ thống trong đó mỗi chỉ dẫn đảm nhiệm một vai trò. Cách đơn giản để bắt đầu là coi hình ảnh như một câu có ngữ pháp:

**[SUBJECT] + [ACTION/POSE] + [FRAMING] + [CAMERA] + [COMPOSITION] + [LIGHT] + [SCENE] + [COLOR] + [STYLE]**

Không phải prompt nào cũng cần đủ chín lớp. Nguyên tắc là chỉ thêm lớp khi nó phục vụ ý định hình ảnh.

## 3.2. Subject — Ai hoặc cái gì là trung tâm?
Subject có thể là người, sản phẩm, món ăn, không gian, phương tiện hoặc một hệ thống đồ họa. Subject càng cần bảo toàn nhận diện, prompt càng phải nói rõ phần nào được khóa.

Ví dụ:
`adult female reference subject`
`exact reference perfume bottle`

Slash không nên thay thế thông tin nhận diện cốt lõi.

## 3.3. Action / Pose — Chủ thể đang làm gì?
Pose mô tả cơ chế cơ thể; action mô tả hành động.

`/contrapposto` khác `/walking`: một bên chủ yếu điều khiển phân bố trọng lượng trong tư thế đứng, bên kia đưa thêm chuyển động và trạng thái bước.

Khi action thay đổi mạnh, composition và framing thường phải thích nghi theo.

## 3.4. Framing — Người xem được nhìn bao nhiêu?
`/closeup`, `/mediumshot`, `/fullbody` là các chỉ dẫn về phạm vi khung hình. Framing nên được quyết định trước khi thêm chi tiết nhỏ, vì nó xác định lượng thông tin có thể xuất hiện.

Một lỗi phổ biến là yêu cầu `/fullbody` nhưng đồng thời mô tả quá nhiều chi tiết khuôn mặt như thể đang làm beauty close-up. Mô hình phải phân bổ độ phân giải cho toàn khung, vì vậy mục tiêu cần được ưu tiên.

## 3.5. Camera — Người xem đứng ở đâu?
Camera language kiểm soát quan hệ không gian giữa người xem và chủ thể:

`/eyelevel`
`/lowangle`
`/highangle`
`/topdown`

Đây là một lớp khác với framing. Một full-body portrait vẫn có thể được chụp eye-level hoặc low-angle.

## 3.6. Composition — Các phần tử được tổ chức ra sao?
Composition không chỉ là vị trí chủ thể. Nó là quan hệ giữa chủ thể, khoảng trống, đường, khối, chiều sâu và điểm chú ý.

Ví dụ:
`/ruleofthirds`
`/symmetry`
`/leadinglines`
`/negativespace`

Nếu mục tiêu là quảng cáo cần đặt headline bên trái, negative space có thể quan trọng hơn một quy tắc bố cục mang tính trang trí.

## 3.7. Light — Hình khối được nhìn thấy bằng cách nào?
Light ảnh hưởng trực tiếp đến hình khối, vật liệu, độ tương phản và cảm nhận.

`/softlight`
`/hardlight`
`/rimlight`
`/windowlight`

Tên lighting pattern không được đánh đồng với mood. Một ánh sáng đúng kỹ thuật có thể được sử dụng cho nhiều thông điệp khác nhau tùy subject và context.

## 3.8. Scene — Hình ảnh xảy ra ở đâu?
Scene cung cấp context:

`/seoulstreet`
`/cozycafe`
`/modernoffice`
`/rooftop`

City slash nên được coi là visual direction cần kiểm thử, không phải cam kết tái tạo địa lý chính xác.

## 3.9. Color — Hệ màu đang làm nhiệm vụ gì?
Color có thể giúp phân cấp, thống nhất thương hiệu, tạo tương phản hoặc điều chỉnh cảm nhận. Những slash như `/monochromatic` hay `/warmtones` nên được hiểu như direction, sau đó được kiểm tra trong bối cảnh thực tế.

## 3.10. Style — Lớp hoàn thiện, không phải nền móng
`/editorial`, `/cinematic`, `/minimalist` có thể tác động nhiều biến cùng lúc. Vì thế style thường nên đặt sau khi subject, camera, composition và light đã rõ.

## 3.11. Công thức tối giản
Người mới có thể dùng:

**Subject + 3 controls**

Ví dụ:
`reference subject /fullbody /lowangle /softlight`

Sau đó chỉ thêm scene/style nếu thực sự cần.

## 3.12. Công thức production
Một cấu trúc production có thể là:

**LOCKS + SUBJECT + ACTION + FRAMING + CAMERA + COMPOSITION + LIGHT + SCENE + STYLE + OUTPUT CONSTRAINTS**

Trong đó LOCKS mô tả những gì không được thay đổi.

## 3.13. Thứ tự không phải luật tuyệt đối
Visual Slash Grammar là mô hình tư duy, không phải parser chính thức của nền tảng. Mục đích của nó là giúp người dùng phát hiện thiếu biến, thừa biến và xung đột.

### Tóm tắt chương
Một prompt tốt có cấu trúc. Slash chỉ có giá trị khi người dùng biết nó đang điều khiển lớp nào của hình ảnh và nó có cạnh tranh với control khác hay không.
