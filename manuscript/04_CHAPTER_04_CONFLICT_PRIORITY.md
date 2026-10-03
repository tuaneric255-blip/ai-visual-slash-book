# CHƯƠNG 4 — CONFLICT, PRIORITY & SEMANTIC LOAD

## 4.1. Khi prompt tự mâu thuẫn
Nhiều thất bại không đến từ việc AI "không hiểu", mà từ việc người dùng đồng thời yêu cầu những kết quả khó cùng tồn tại.

Ví dụ rõ nhất:
`/fullbody /extremecloseup`

Hai slash cùng tranh chấp framing.

## 4.2. Conflict theo biến
Có thể phân conflict thành:
- **Framing:** full body vs extreme close-up.
- **Camera/Lens cue:** 85mm portrait aesthetic vs fisheye.
- **Time/Light:** midday vs golden hour.
- **Pose/Action:** static rigid pose vs dynamic running.
- **Composition:** centered symmetry vs aggressive off-center asymmetry khi cả hai được yêu cầu tuyệt đối.
- **Scene:** mutually exclusive environments nếu không có ý định composite.

## 4.3. Hard conflict và soft conflict
**Hard conflict** là hai yêu cầu gần như loại trừ nhau.

**Soft conflict** là hai direction vẫn có thể kết hợp nhưng làm tăng độ mơ hồ. Ví dụ cinematic + UGC không nhất thiết bất khả thi, nhưng cần giải thích yếu tố nào cinematic và yếu tố nào giữ chất UGC.

## 4.4. Semantic Load
Mỗi modifier thêm một yêu cầu. Khi prompt chứa quá nhiều control, mô hình có thể:
- bỏ qua một số chỉ dẫn;
- trộn các thuộc tính;
- thay đổi những thứ không được yêu cầu;
- ưu tiên style mạnh hơn geometry;
- tạo output đẹp nhưng lệch mục tiêu.

Do đó, **ít nhưng rõ** thường hữu ích hơn **nhiều nhưng cạnh tranh**.

## 4.5. Priority bằng cấu trúc
Thay vì lặp từ khóa, hãy tổ chức prompt:

**MUST PRESERVE**
identity, product geometry, logo.

**MUST CHANGE**
camera viewpoint to low angle.

**MAY VARY**
minor natural fabric movement.

Cấu trúc này không bảo đảm tuyệt đối, nhưng làm ý định dễ đọc và dễ debug hơn.

## 4.6. Debug bằng phương pháp loại trừ
Khi một recipe thất bại:
1. quay về subject + một control;
2. kiểm tra control;
3. thêm từng lớp;
4. xác định bước bắt đầu gây lệch;
5. sửa conflict hoặc viết lại bằng natural language.

Đây cũng chính là logic của Isolation Test trong phòng lab.

## 4.7. Khi nào bỏ slash và viết thành câu?
Nếu slash quá mơ hồ, có nhiều nghĩa hoặc thường xuyên bị bỏ qua, hãy mở rộng nó thành Prompt Foundation.

Slash là giao diện nhanh; natural language là công cụ làm rõ.

### Tóm tắt chương
Prompt Engineering không phải nghệ thuật chất thêm từ khóa. Nó là quản trị constraint: biết biến nào đang bị điều khiển, mức ưu tiên nào quan trọng và lúc nào cần giảm semantic load.
