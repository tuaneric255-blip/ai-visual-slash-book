# CHƯƠNG 15 — COUPLE & GROUP POSE

## 15.1. Từ pose cá nhân sang relationship geometry
Khi có hai người trở lên, composition không còn chỉ là tổng các pose cá nhân. Khoảng cách, hướng nhìn, overlap và hierarchy tạo ra quan hệ thị giác.

## 15.2. Couple vocabulary
Candidates:
`/sidebyside` · `/facingeachother` · `/backtoback` · `/walkingtogether` · `/sittingtogether` · `/talkingpose` · `/laughingtogether` · `/lookingatcamera` · `/lookingateachother` · `/oneforwardoneback`.

## 15.3. Group vocabulary
Candidates:
`/teamlineup` · `/staggeredgroup` · `/semicircle` · `/triangleformation` · `/groupwalk` · `/teamdiscussion` · `/teamcelebration` · `/groupcandid` · `/presentationgroup` · `/workshopgroup`.

## 15.4. Hierarchy
Group image cần trả lời:
Ai là focal subject? Có leader không? Hay mọi người ngang hàng?

Hierarchy có thể được tạo bằng position, scale, focus, lighting hoặc gesture.

## 15.5. Identity collisions
Trong group generation, model có thể trộn facial traits hoặc wardrobe. Vì vậy review identity phải theo từng subject, không chỉ nhìn tổng thể.

## 15.6. Occlusion
Một formation đẹp nhưng che mặt, tay hoặc product của người khác có thể không dùng được trong production.

### Tóm tắt chương
Couple/group pose là bài toán relationship geometry + hierarchy + identity + occlusion. Đây là lớp giao giữa Pose và Composition.
