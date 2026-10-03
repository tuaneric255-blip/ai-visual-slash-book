# CHƯƠNG 11 — SITTING, FLOOR, KNEELING & SQUATTING

## 11.1. Sitting không chỉ là "ngồi xuống"
Ghế, sofa, bậc thang, sàn và mép bàn tạo ra geometry khác nhau. Prompt cần mô tả quan hệ giữa cơ thể và surface.

## 11.2. Chair Sitting
Candidates:
`/chairsit`
`/frontchairsit`
`/sidechairsit`
`/backwardchair`
`/edgechairsit`
`/deepsit`

Cần kiểm tra contact point giữa cơ thể và ghế, chiều cao ghế, chân và perspective.

## 11.3. Torso trong sitting pose
Candidates:
`/forwardleansit`
`/relaxedsit`
`/elbowonknee`

Forward lean có thể đưa khuôn mặt gần camera hơn, nên dễ làm perspective thay đổi nếu framing/camera không được khóa.

## 11.4. Legs
Candidates:
`/legcrosssit`
`/anklecrosssit`
`/legsapartsit`
`/onelegextended`

Leg crossing cần được đánh giá anatomy và occlusion, không chỉ aesthetic.

## 11.5. Context Sitting
`/sofasit`
`/floorsit`
`/stairsit`
`/benchsit`
`/desksit`
`/windowsit`
`/bededge`

Đây có thể là composite semantics vì pose và object/environment được gói chung.

## 11.6. Kneeling & Squatting
Các tư thế thấp làm thay đổi trọng tâm, joint angles và camera relationship. Khi test cần tránh crop khiến reviewer không thấy contact với mặt đất.

### Tóm tắt chương
Sitting/floor pose phải được mô tả bằng body mechanics + surface relationship. Đây là nhóm cần test anatomy nghiêm ngặt vì occlusion và contact artifacts xuất hiện nhiều.
