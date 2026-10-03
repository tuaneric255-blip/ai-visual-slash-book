# CHƯƠNG 17 — LINES, CURVES & SHAPES

## 17.1. Đường dẫn thị giác
`/leadinglines` hướng tới việc dùng các đường trong scene để dẫn mắt qua frame, thường về focal subject.

Một con đường xuất hiện trong ảnh chưa đủ. Cần đánh giá nó có thực sự tham gia hierarchy hay không.

## 17.2. Diagonal Composition
`/diagonalcomposition`

Đường chéo có thể tạo hướng và movement. Trong fashion/action, diagonal body line có thể kết hợp với environmental lines.

## 17.3. Converging Lines
`/converginglines`

Các đường hội tụ thường liên quan perspective và vanishing point. Đây là vùng giao giữa composition và camera geometry.

## 17.4. S-Curve
`/scurve` có ít nhất hai context:
- body line trong pose;
- đường cong dẫn qua landscape/road/river.

Do đó đây là candidate có tính contextual/composite cao và cần tag theo domain.

## 17.5. C-Curve & Leading Curve
Candidates:
`/ccurve` · `/leadingcurve` · `/curvecomposition`.

Curves có thể tổ chức flow mềm hơn straight diagonal, nhưng communication effect phụ thuộc scene.

## 17.6. Shape-based organization
Candidates:
`/trianglecomposition` · `/lcomposition`.

Shape name nên mô tả geometry quan sát được, không phải ép mọi element thành hình học cứng nhắc.

### Tóm tắt chương
Lines/curves/shapes là công cụ tạo flow. Khi test, phải chỉ ra đường nào, bắt đầu ở đâu, dẫn tới đâu và focal point có được hỗ trợ hay không.
