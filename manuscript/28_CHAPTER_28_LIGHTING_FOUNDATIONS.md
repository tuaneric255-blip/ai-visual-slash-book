# CHƯƠNG 28 — LIGHTING FOUNDATIONS

## 28.1. Light không chỉ là mood
Ánh sáng quyết định visibility, form, texture, separation và contrast. Mood là kết quả có thể xuất hiện, không phải định nghĩa duy nhất.

## 28.2. Các biến nền tảng
Khi phân tích light, hãy hỏi:
- Direction: ánh sáng đến từ đâu?
- Size/softness: shadow edge cứng hay mềm?
- Intensity: quan hệ sáng tối?
- Contrast ratio: key/fill khác nhau thế nào?
- Color: neutral/warm/cool/mixed?
- Motivation: nguồn sáng có hợp scene?
- Specularity: vật liệu phản xạ ra sao?

## 28.3. Soft Light
`/softlight`

Shadow transition mềm hơn, thường liên quan apparent source size lớn hơn so với subject. Behavioral slash effect vẫn phải test.

## 28.4. Hard Light
`/hardlight`

Shadow edge rõ hơn, specular/contrast có thể mạnh hơn tùy material và fill.

## 28.5. Natural / Window Light
`/naturallight` · `/windowlight`

"Natural" là khái niệm rộng; window light cụ thể hơn về motivated source.

## 28.6. Key, Fill, Back
`/keylight` · `/filllight` · `/backlight`

Đây là functional roles. Một light có thể đóng vai key hoặc back tùy vị trí và exposure.

### Tóm tắt chương
Lighting cần được đọc bằng direction, softness, intensity, ratio, color và motivation. Từ mood chỉ là lớp sau.
