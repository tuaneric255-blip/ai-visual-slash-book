# CHƯƠNG 9 — POSE ANATOMY: ĐỪNG CHỈ GỌI TÊN DÁNG, HÃY HIỂU CƠ CHẾ CƠ THỂ

## 9.1. Vì sao Pose cần một chương giải phẫu thị giác?
Một slash như `/contrapposto` chỉ hữu ích khi người dùng biết phải quan sát điều gì. Nếu chỉ nhìn "có vẻ thời trang", ta dễ chấp nhận một output sai cơ chế.

Pose Anatomy trong sách không nhằm dạy y khoa. Nó cung cấp ngôn ngữ quan sát để mô tả trọng lượng, trục cơ thể, khớp, hướng và đối trọng.

## 9.2. Weight Distribution
Câu hỏi đầu tiên của standing pose:
**Trọng lượng cơ thể đang đặt ở đâu?**

Các trạng thái thường gặp:
- cân bằng hai chân;
- chủ yếu một chân;
- chuyển trọng lượng khi bước;
- dựa vào tường/ghế/vật thể.

Weight distribution ảnh hưởng trực tiếp đến hip line, knee relaxation và cảm giác tự nhiên.

## 9.3. Pelvis và Shoulder Counterbalance
Khi trọng lượng dồn sang một chân, pelvis thường thay đổi độ nghiêng. Vai và torso có thể counterbalance để cơ thể giữ cân bằng.

Đây là lý do contrapposto không đơn giản là "đẩy hông sang một bên".

## 9.4. Spine & Torso
Các biến cần quan sát:
- upright vs forward lean;
- backward lean;
- side bend;
- torso twist;
- S-curve;
- shoulder rotation.

Khi prompt yêu cầu quá nhiều biến cực đoan cùng lúc, anatomy dễ méo.

## 9.5. Legs & Feet
Chân không chỉ là phần dưới khung hình. Chúng cho biết weight-bearing, hướng chuyển động và stability.

Full-body test phải thấy bàn chân. Nếu crop mất chân, reviewer không thể đánh giá chính xác nhiều standing pose.

## 9.6. Arms & Hands
Tay có thể tạo:
- open/closed silhouette;
- đường chéo;
- frame quanh mặt;
- tương tác với product;
- chỉ hướng chú ý.

Nhưng tay cũng là vùng dễ artifact. Pose test cần tách "pose concept đúng" khỏi "hand rendering lỗi".

## 9.7. Head, Chin & Eye Direction
Một thay đổi nhỏ ở head tilt hoặc eye direction có thể thay đổi communication mà không cần đổi toàn bộ body pose.

Do đó `/lookbackpose`, `/sideglance`, `/chinup` nên được xem là các control riêng thay vì gom thành "pose đẹp".

## 9.8. Silhouette
Một pose tốt cho hình ảnh thương mại thường cần silhouette dễ đọc: tay không dính khó hiểu vào torso, hai chân không chồng thành một khối và sản phẩm không bị che.

Silhouette là tiêu chí hữu ích khi đánh giá output ở kích thước thumbnail.

## 9.9. Pose Mechanism vs Pose Message
Mechanism là cấu trúc có thể quan sát.
Message là cách người xem có thể diễn giải.

Ví dụ:
Mechanism: wide stance + shoulders square.
Possible message: stable, assertive, grounded.
Nhưng message phụ thuộc wardrobe, expression, camera và context.

## 9.10. Pose Test Checklist
Khi review một pose:
1. chân nào chịu lực?
2. pelvis có hợp lý?
3. shoulders có counterbalance?
4. spine có tự nhiên?
5. tay có logic?
6. feet có hỗ trợ stance?
7. silhouette có rõ?
8. anatomy có artifact?
9. pose có đúng định nghĩa?
10. side effects nào xuất hiện?

### Tóm tắt chương
Pose không phải tên gọi thẩm mỹ. Nó là một hệ thống weight, joint, axis, counterbalance và gesture. Hiểu cơ chế giúp viết prompt tốt hơn và chấm test bớt cảm tính.
