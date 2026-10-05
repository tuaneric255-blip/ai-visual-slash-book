# CHƯƠNG 22 — VIEW & SUBJECT ORIENTATION

## 22.1. Front View
`/frontview`

Subject orientation hướng trực diện tương đối với camera. Với product, "front" cần xác định mặt chính/label side.

## 22.2. Side View
`/sideview`

Profile hoặc lateral orientation. Người và sản phẩm có tiêu chí side-view khác nhau.

## 22.3. Three-quarter View
`/threequarterview`

Góc giữa front và side, thường cho thấy đồng thời mặt trước và một mặt bên. Đây là candidate mạnh cho portrait/product nhưng vẫn cần test model behavior.

## 22.4. Back View
`/backview`

Camera nhìn phần sau subject. Với fashion, back view hữu ích để show garment construction; với person identity, face evidence sẽ giảm.

## 22.5. Over-the-shoulder
`/overtheshoulder`

Viewpoint sử dụng shoulder/upper body foreground để hướng nhìn tới subject hoặc scene phía trước. Không nên nhầm với `/overshoulderlook`, là head/pose direction.

## 22.6. POV
`/pov`

Point-of-view imagery cố tạo cảm giác camera ở vị trí người quan sát/nhân vật. Đây là composite concept; cần mô tả hands/body/environment nếu chúng quan trọng.

## 22.7. Reverse angle
Trong storyboard/video, reverse angle liên quan continuity giữa hai hướng camera. Đây không chỉ là một aesthetic still-image cue.

### Tóm tắt chương
Orientation mô tả mặt nào của subject hướng về camera; camera angle mô tả camera đứng ở đâu. Tách hai lớp giúp prompt chính xác hơn.
