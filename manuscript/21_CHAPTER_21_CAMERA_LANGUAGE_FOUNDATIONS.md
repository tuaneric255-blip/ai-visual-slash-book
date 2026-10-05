# CHƯƠNG 21 — CAMERA LANGUAGE FOUNDATIONS

## 21.1. Camera language là vị trí của người xem
Trong hình ảnh tạo sinh, các từ như low angle, top-down hay over-the-shoulder nên được hiểu trước hết là mô tả **viewpoint**. Chúng không chứng minh rằng một máy ảnh vật lý đã được mô phỏng chính xác.

## 21.2. Eye Level
`/eyelevel`

Camera/viewpoint gần mức mắt hoặc trục nhìn tự nhiên của subject. Đây là baseline hữu ích khi test các angle khác.

## 21.3. Low Angle
`/lowangle`

Viewpoint đặt thấp hơn subject và hướng nhìn lên. Cần đánh giá bằng perspective cues, horizon/background relationship và tỷ lệ tương đối trong frame.

**Behavioral evidence:** NOT YET TESTED.

## 21.4. High Angle
`/highangle`

Viewpoint cao hơn subject, hướng nhìn xuống. Không nên mặc định diễn giải thành "yếu đuối"; đó là possible communication effect trong một số context, không phải định nghĩa camera.

## 21.5. Top Down / Overhead
`/topdown` · `/overhead`

Hai từ có thể overlap mạnh. Database cần test xem có đủ khác biệt thực dụng để giữ hai canonical entries hay nên canonicalize một và dùng alias.

## 21.6. Worm's-eye / Ground-level
`/wormseyeview` · `/groundlevel`

Đây là các viewpoint cực thấp. Cần phân biệt "camera thấp" với việc subject chỉ đứng trên nền thấp.

## 21.7. Dutch Angle
`/dutchangle`

Trục camera/frame bị nghiêng. Reviewer phải nhìn horizon/vertical cues thay vì chỉ cảm giác "dynamic".

## 21.8. Camera angle vs subject angle
Subject có thể quay three-quarter trong khi camera vẫn eye-level. Hai biến phải tách:
- camera elevation/orientation;
- subject orientation.

### Tóm tắt chương
Camera angle là geometry của viewpoint. Communication effect là lớp diễn giải thứ hai và phải phụ thuộc context.
