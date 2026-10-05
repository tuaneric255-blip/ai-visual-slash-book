# CHƯƠNG 27 — CAMERA RECIPES & DEBUGGING

> Các tổ hợp dưới đây là hướng thiết kế để test, không phải cam kết VERIFIED.

## 27.1. Leadership Full-body
`/fullbody /lowangle /frontview`

Sau khi geometry ổn mới thêm light/style.

## 27.2. Natural Portrait
`/mediumshot /eyelevel /threequarterview`

## 27.3. Beauty Detail
`/closeup /eyelevel /85mm /shallowdof`

Lens/DOF là aesthetic cues; không tuyên bố physical simulation.

## 27.4. Street Depth
`/fullbody /eyelevel /35mm /leadinglines`

## 27.5. Architecture Hero
`/lowangle /wideangle /twopointperspective`

Cần review vertical distortion và geometry.

## 27.6. Product Hero
`/threequarterview /closeup /shallowdof`

Product geometry/label phải được khóa riêng.

## 27.7. Debug order
1. subject/reference;
2. framing;
3. orientation;
4. camera elevation;
5. perspective/lens cue;
6. focus;
7. composition;
8. lighting;
9. style.

### Tóm tắt chương
Camera recipe tốt có thứ tự kiểm soát. Khi fail, tháo từng lớp thay vì thêm prompt.
