# CHƯƠNG 30 — DIRECTIONAL & EFFECT LIGHTING

## 30.1. Side Light
`/sidelight`

Key illumination chủ yếu đến từ một phía, giúp reveal form/texture tùy subject.

## 30.2. Backlight
`/backlight`

Nguồn sáng chính/đáng kể từ phía sau subject. Exposure và fill quyết định subject trở thành silhouette hay vẫn giữ detail.

## 30.3. Rim / Edge Light
`/rimlight` · `/edgelight`

Highlight dọc contour giúp separation. Hai candidate có thể overlap và cần canonicalization sau test.

## 30.4. Top / Under Light
`/toplight` · `/underlight`

Direction cực rõ; underlight dễ tạo appearance phi tự nhiên nếu scene không có motivated source.

## 30.5. Silhouette
`/silhouette`

Silhouette là kết quả exposure/contrast, không chỉ "backlight". Subject shape phải đọc được.

## 30.6. Volumetric / God Rays
`/volumetriclight` · `/godrays`

Cần medium/particles/atmospheric scattering cue. Không nên dùng chỉ để thêm "cinematic glow" vô nghĩa.

## 30.7. Practical Light
`/practicallight`

Nguồn sáng nhìn thấy trong scene: lamp, sign, candle... Việc nguồn sáng xuất hiện không bảo đảm nó thực sự "motivate" toàn bộ lighting, nên review phải xem quan hệ giữa source và illumination.

### Tóm tắt chương
Directional/effect lighting nên được đánh giá bằng nguồn, hướng và kết quả trên form. Hiệu ứng đẹp không thay thế logic ánh sáng.
