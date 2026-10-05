# CHƯƠNG 32 — TIME, WEATHER & MOTIVATED LIGHT

## 32.1. Time-of-day là gói tín hiệu
`/sunrise` · `/goldenhour` · `/bluehour` · `/midday` · `/sunset` · `/night`

Mỗi từ có thể ảnh hưởng đồng thời color, shadow direction, sky, exposure và scene activity.

## 32.2. Golden Hour
`/goldenhour`

Không nên định nghĩa đơn giản là "ảnh màu vàng". Reviewer cần nhìn source direction, shadow length/softness, warm low-angle illumination và context.

## 32.3. Blue Hour
`/bluehour`

Thường liên quan giai đoạn chạng vạng với ambient sky cool hơn và practical lights có thể nổi bật. Đây vẫn là visual cue cần test.

## 32.4. Midday
`/midday`

Kỳ vọng sun elevation cao hơn, shadow ngắn/cứng hơn trong điều kiện trời quang. `/midday /goldenhour` là conflict rõ về time/light direction.

## 32.5. Weather
`/overcast` · `/rainy` · `/foggy` · `/snowy` · `/stormlight`

Weather thay đổi cả visibility, contrast, surface wetness và atmospheric depth.

## 32.6. Motivated lighting
Nếu scene có cửa sổ, biển neon hoặc lamp, lighting direction nên có quan hệ hợp lý với source. "Motivated" là logic, không chỉ việc source xuất hiện trong frame.

### Tóm tắt chương
Time/weather slash là composite visual directions. Cần tách các dấu hiệu quan sát được để test thay vì chấm theo màu tổng thể.
