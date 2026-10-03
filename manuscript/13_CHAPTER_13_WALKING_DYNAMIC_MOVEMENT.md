# CHƯƠNG 13 — WALKING & DYNAMIC MOVEMENT

## 13.1. Từ pose tĩnh sang chuyển động
Movement prompt phải mô tả được trạng thái của cơ thể trong một thời điểm có thể quan sát. Từ "dynamic" tự nó quá rộng; direction tốt hơn chỉ ra loại chuyển động, hướng và phase.

## 13.2. Walking vocabulary
Candidates:
`/walk` · `/slowwalk` · `/casualwalk` · `/confidentwalk` · `/powerwalk` · `/catwalk` · `/runwaywalk` · `/citywalk` · `/crosswalk` · `/walktowardcamera` · `/walkaway` · `/walksideways` · `/walklookback` · `/walkandtalk` · `/handsinpocketwalk` · `/bagcarrywalk` · `/coatmotionwalk` · `/longstride` · `/midstep`.

## 13.3. Phase matters
Một ảnh walking có thể bắt ở heel strike, mid-step hoặc toe-off. Nếu cần visual consistency, mô tả phase bằng natural language tốt hơn chỉ dựa vào slash.

## 13.4. Dynamic actions
Candidates:
`/running` · `/jogging` · `/sprinting` · `/jumping` · `/landing` · `/spinning` · `/turning` · `/reaching` · `/stretching` · `/bending` · `/lunging` · `/throwing` · `/catching` · `/pushing` · `/pulling` · `/climbing`.

## 13.5. Motion cue vs motion blur
Một body pose có thể truyền đạt chuyển động dù ảnh sắc nét. Motion blur là một visual effect riêng. Không nên mặc định ghép `/motionblur` vào mọi action.

## 13.6. Test movement
Review:
- body phase có hợp lý?
- trọng tâm có hỗ trợ chuyển động?
- limbs có đúng hướng?
- contact với mặt đất/vật thể có logic?
- clothing/hair motion có hỗ trợ hay phá identity?
- camera/framing có vô tình thay đổi?

### Tóm tắt chương
Movement cần action + direction + phase. Slash là shorthand; natural-language expansion giúp kiểm soát những chi tiết chuyển động mà một từ đơn không biểu đạt hết.
