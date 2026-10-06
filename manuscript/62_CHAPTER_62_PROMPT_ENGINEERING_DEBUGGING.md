# CHƯƠNG 62 — PROMPT ENGINEERING & DEBUGGING

## 62.1. Khi Slash không hoạt động
Không kết luận ngay rằng model “không hiểu”. Có thể slash bị conflict, bị instruction khác override, semantic quá rộng hoặc output variance.

## 62.2. Debug ladder
1. Giảm về baseline.
2. Test một slash.
3. Kiểm tra semantic effect.
4. Thêm layer thứ hai.
5. Kiểm tra conflict.
6. Lock biến không liên quan.
7. Lặp nhiều run.
8. Human review.

## 62.3. Failure classes
NO EFFECT · PARTIAL EFFECT · WRONG EFFECT · OVERRIDE · MORPHING · ANATOMY FAILURE · TEXT FAILURE · IDENTITY DRIFT · PRODUCT DRIFT.

## 62.4. Prompt expansion
Slash là shorthand. Khi cần kiểm soát cao, mở rộng slash thành natural-language foundation cụ thể.

## 62.5. Evidence rule
Một output đẹp không chứng minh slash hoạt động. Cần control, isolated test, provenance và review.

### Tóm tắt chương
Debugging là cầu nối giữa ngôn ngữ slash tiện dụng và prompt engineering có kiểm chứng.
