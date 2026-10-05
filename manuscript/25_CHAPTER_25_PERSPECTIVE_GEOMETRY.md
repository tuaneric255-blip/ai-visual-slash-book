# CHƯƠNG 25 — PERSPECTIVE & GEOMETRY

## 25.1. Perspective không chỉ là lens
Perspective trong hình ảnh chịu ảnh hưởng mạnh bởi vị trí camera so với scene. Trong prompt generation, lens cue và camera distance thường bị model gộp thành một aesthetic package.

## 25.2. One-point Perspective
`/onepointperspective`

Các đường chính hội tụ về một vanishing point. Hữu ích cho corridor, street, architecture và centered composition.

## 25.3. Two-point Perspective
`/twopointperspective`

Thường thấy khi nhìn một corner/object với hai nhóm cạnh hướng tới hai vanishing points.

## 25.4. Three-point Perspective
`/threepointperspective`

Thêm vertical convergence, thường xuất hiện ở viewpoint rất cao/thấp của architecture.

## 25.5. Forced Perspective
`/forcedperspective`

Sử dụng quan hệ scale/distance để tạo illusion. Đây là composite visual technique và dễ gây geometry artifacts.

## 25.6. Foreshortening
`/foreshortening`

Một phần cơ thể/object hướng về camera có thể trông lớn/ngắn tương đối do perspective. Với people imagery, anatomy review đặc biệt quan trọng.

## 25.7. Orthographic / Isometric
`/orthographic` · `/isometric`

Đây là visual projection cues quan trọng cho technical/product illustration. Không nên tuyên bố engineering accuracy nếu chỉ dựa vào generated image.

### Tóm tắt chương
Perspective slash cần được đánh giá bằng geometry cues, không phải mood. Technical-looking output không tự động trở thành technical evidence.
