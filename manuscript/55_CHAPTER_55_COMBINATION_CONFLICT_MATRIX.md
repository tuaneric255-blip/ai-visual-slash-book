# CHƯƠNG 55 — COMBINATION CONFLICT MATRIX

## 55.1. Hard conflict
Hai instruction không thể cùng đúng trên cùng target/frame:
- `/fullbody + /extremecloseup`
- `/frontview + /profile`
- `/topdown + /wormseye`
- `/midday + /goldenhour` khi cùng mô tả một thời điểm.

## 55.2. Soft conflict
Có thể cùng tồn tại nhưng dễ làm model ưu tiên một phía:
- `/85mm + /wideangle`
- `/symmetry + /copyspaceleft`
- `/lowkey + /purewhite`
- `/shallowdof + /technicaldiagram`.

## 55.3. Contextual conflict
Chỉ conflict trong một số domain:
`/motionblur` có thể tốt cho action campaign nhưng gây hại label legibility trong packshot.

## 55.4. Redundancy
`/topdown + /overhead` có thể dư thừa nếu test cho thấy hai candidate tương đương.
`/rimlight + /edgelight` cần evidence trước canonicalization.

## 55.5. Debugging
Khi tổ hợp fail:
1. xác định target của từng slash;
2. bỏ redundancy;
3. bỏ hard conflict;
4. chạy atomic controls;
5. ghép lại từng layer;
6. ghi nhận slash bị override.

### Tóm tắt chương
Conflict matrix biến slash combination từ mẹo prompt thành một hệ thống có thể debug.
