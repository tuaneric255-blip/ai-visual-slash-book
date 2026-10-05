# CHƯƠNG 37 — CITY SLASH SYSTEM

## 37.1. City slash không phải GPS
`/seoulstreet`, `/tokyonight` hay `/hanoioldquarter` là visual directions. Nếu không khóa landmark/location bằng reference hoặc dữ liệu phù hợp, không nên tuyên bố địa lý chính xác.

## 37.2. Cấu trúc City Pack
Mỗi city pack nên có bốn lớp:
1. **Core city context**
2. **District/location direction**
3. **Time/weather**
4. **Lifestyle/fashion context**

## 37.3. Seoul candidates
`/seoulstreet`
`/seoulstreetlook`
`/seoulnight`
`/seoulneon`
`/myeongdong`
`/gangnamstreet`
`/hongdae`
`/itaewon`
`/seoulcafe`
`/seoulalley`
`/seoulrooftop`
`/seoulspring`

## 37.4. Tokyo candidates
`/tokyostreet`
`/tokyonight`
`/tokyoneon`
`/shibuya`
`/shibuyanight`
`/shinjuku`
`/shinjukunight`
`/harajuku`
`/tokyoalley`
`/tokyorain`
`/tokyosakura`
`/tokyocafe`

## 37.5. Hanoi candidates
`/hanoistreet`
`/hanoioldquarter`
`/hanoiautumn`
`/hanoiwinter`
`/hanoicafe`
`/hanoirain`
`/hanoinight`
`/hanoifrenchquarter`
`/hoankiem`
`/trainstreet`
`/hanoivintage`
`/hanoimorning`

## 37.6. Stereotype control
Wardrobe không tự động biến thành trang phục truyền thống chỉ vì city name. Default city pack nên ưu tiên contemporary context trừ khi user yêu cầu historical/traditional styling.

## 37.7. Test city slash
Review:
- architecture/environment cues;
- signage plausibility;
- climate/time cues;
- unwanted stereotype;
- location hallucination;
- identity/wardrobe drift.

### Tóm tắt chương
City Slash Library là visual-context library, không phải hệ thống xác minh địa điểm. Mỗi pack phải tách core, district, time/weather và lifestyle.
