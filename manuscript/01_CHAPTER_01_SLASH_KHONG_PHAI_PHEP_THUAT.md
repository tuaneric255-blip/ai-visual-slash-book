# CHƯƠNG 1 — SLASH KHÔNG PHẢI PHÉP THUẬT

## 1.1. Vì sao một dấu "/" có thể tạo cảm giác như một câu lệnh?

Khi người dùng nhập `/lowangle`, `/softlight` hay `/goldenhour`, điều quan trọng không nằm ở dấu gạch chéo. Phần có giá trị là cụm từ phía sau: nó mang một ý nghĩa thị giác mà mô hình có thể liên hệ với ngôn ngữ, hình ảnh và các mẫu mô tả đã học.

Vì vậy, trong cuốn sách này, slash được xem trước hết là **một giao diện ngôn ngữ ngắn gọn cho ý định thị giác**. Dấu "/" giúp con người nhận diện nhanh một đơn vị điều khiển, dễ ghi nhớ, dễ kết hợp và dễ xây thư viện; nó không tự biến từ phía sau thành một tham số kỹ thuật chính thức.

> **Nguyên tắc:** Slash hữu ích khi nó làm cho ý định thị giác ngắn hơn mà không làm ý nghĩa trở nên mơ hồ hơn.

## 1.2. Semantic Slash

**Semantic Slash** là slash có tên đủ tự mô tả để mô hình có cơ sở diễn giải ngay cả khi chưa được dự án định nghĩa trước.

Ví dụ:

`/lowangle` → gợi ý góc nhìn thấp.

`/fullbody` → gợi ý khung hình toàn thân.

`/softlight` → gợi ý ánh sáng mềm.

`/leadinglines` → gợi ý tổ chức bố cục bằng các đường dẫn thị giác.

Điều này không đồng nghĩa mọi mô hình, mọi phiên bản và mọi ngữ cảnh sẽ phản ứng giống nhau. Semantic Slash tạo ra **kỳ vọng có thể kiểm thử**, không tạo ra sự bảo đảm.

## 1.3. Composite Semantic Slash

Một số slash ghép nhiều ý nghĩa:

`/seoulstreetlook`

Người đọc có thể hình dung đây là một visual direction liên quan đến Seoul, street scene và một kiểu "look". Tuy nhiên, chính vì chứa nhiều thành phần, kết quả có thể biến thiên mạnh hơn `/lowangle`.

Cuốn sách gọi nhóm này là **Composite Semantic Slash**. Khi sử dụng, cần hỏi: slash đang điều khiển địa điểm, thời trang, màu sắc, ánh sáng hay toàn bộ aesthetic? Nếu câu trả lời không rõ, prompt foundation phải làm rõ.

## 1.4. Defined Slash / Author Macro

Giả sử ta quy định:

`/storyvideo` = giữ nhân vật + chia storyboard thành cảnh + tạo chuyển động + duy trì continuity.

Tên `storyvideo` có ý nghĩa ngôn ngữ, nhưng toàn bộ hành vi phía sau là một workflow do tác giả định nghĩa. Đây là **Author Macro**, không phải bằng chứng rằng nền tảng có một command native tên như vậy.

Macro rất hữu ích trong sản xuất vì nó đóng gói quy trình dài. Điều kiện là phải công khai mapping của macro để người khác hiểu và tái tạo được.

## 1.5. Slash, Prompt, Parameter và Native Command khác nhau thế nào?

**Slash** trong hệ thống sách là ký hiệu shorthand.

**Prompt** là toàn bộ chỉ dẫn bằng ngôn ngữ hoặc cấu trúc mà người dùng cung cấp.

**Parameter** là biến được hệ thống/phần mềm thực sự hỗ trợ ở cấp giao diện hoặc API, chẳng hạn một lựa chọn kích thước khi nền tảng cung cấp nó.

**Native Command** là cú pháp được nền tảng chính thức định nghĩa và tài liệu hóa.

Không nên gọi Semantic Slash là Native Command nếu không có tài liệu chính thức chứng minh điều đó. Sự phân biệt này bảo vệ tính chính xác của toàn bộ cuốn sách.

## 1.6. Từ Slash đến hình ảnh

Mô hình làm việc thực tế phức tạp hơn một sơ đồ tuyến tính, nhưng với mục đích học và thiết kế prompt, ta có thể dùng mô hình tư duy:

**SLASH → SEMANTIC CONCEPT → VISUAL ATTRIBUTES → PROMPT INTERPRETATION → VISUAL RESULT**

Ví dụ kỳ vọng với `/lowangle`:

**/lowangle** → góc máy thấp → camera/viewpoint thấp hơn chủ thể + hướng nhìn lên → thay đổi phối cảnh và quan hệ chủ thể/bối cảnh → hình ảnh có dấu hiệu của low-angle view.

Từ "kỳ vọng" là bắt buộc. Bước cuối phải được kiểm tra bằng output thực tế.

## 1.7. Visual Slash Grammar

Một hình ảnh có thể được mô tả bằng các lớp điều khiển:

**[SUBJECT] + [ACTION/POSE] + [FRAMING] + [CAMERA] + [COMPOSITION] + [LIGHT] + [SCENE] + [COLOR] + [STYLE]**

Ví dụ:

`/fullbody /contrapposto /lowangle /leadinglines /goldenhour /seoulstreet`

Không phải càng nhiều slash càng tốt. Mỗi slash thêm vào làm tăng lượng ràng buộc và có thể tạo cạnh tranh ngữ nghĩa.

## 1.8. Slash Conflict

Hai slash có thể xung đột trực tiếp:

`/fullbody /extremecloseup`

Một slash yêu cầu thấy toàn thân; slash kia yêu cầu crop cực gần.

Hoặc:

`/midday /goldenhour`

Hai chỉ dẫn mô tả điều kiện thời gian/ánh sáng khác nhau.

Xung đột cũng có thể tinh tế hơn:

`/85mm /fisheye`

Nếu mô hình diễn giải cả hai như lens aesthetics, hai hướng phối cảnh có thể cạnh tranh.

Do đó, Prompt Engineer không chỉ biết "thêm slash" mà phải biết **slash nào đang điều khiển cùng một biến**.

## 1.9. Một slash đẹp chưa chắc là một slash tốt

Nếu thêm `/leadinglines` khiến ảnh đẹp hơn, điều đó chưa chứng minh slash tạo leading lines. Cần kiểm tra xem cấu trúc đường trong ảnh có thực sự dẫn mắt hay không.

Nếu `/rembrandt` tạo một portrait tối và điện ảnh, điều đó chưa đủ để kết luận ánh sáng Rembrandt xuất hiện. Cần đánh giá pattern ánh sáng và bóng trên khuôn mặt.

Nếu `/contrapposto` tạo một dáng đứng thời trang, cần kiểm tra phân bố trọng lượng, chân thả lỏng, hông và vai đối trọng.

Đây là ranh giới giữa **prompt collection** và **visual prompt engineering**.

## 1.10. Quy tắc kiểm chứng của cuốn sách

Mỗi candidate đi qua:

**Candidate → Professional Definition → Control → Isolated Test → Repeated Runs → Compatibility → Production Test → Human Review → Evidence Status**

Các trạng thái chính:

- **VERIFIED:** có bằng chứng đủ rõ cho hành vi được mô tả trong điều kiện đã test.
- **CONTEXTUAL:** hiệu ứng có ích nhưng phụ thuộc đáng kể vào ngữ cảnh/model/subject.
- **UNSTABLE:** mô hình có dấu hiệu hiểu nhưng tính lặp lại hoặc khả năng kiểm soát còn yếu.
- **REJECTED:** không chứng minh được claim, gây hiểu sai hoặc không tạo khác biệt hữu ích.
- **UNTESTED:** chưa hoàn thành protocol.

## 1.11. Mục tiêu cuối cùng không phải thuộc hàng nghìn slash

Người mới có thể bắt đầu bằng việc copy:

`/fullbody /lowangle /softlight`

Nhưng mục tiêu cao hơn là nhìn một hình ảnh và tự phân tích:

**Subject → Pose → Framing → Camera → Composition → Light → Environment → Color → Style → Message**

Khi đó slash trở thành từ vựng. Người dùng không còn "xin prompt"; họ đang **thiết kế hình ảnh bằng ngôn ngữ**.

### Tóm tắt chương
1. Dấu "/" không phải phép thuật; semantic meaning mới là phần cần nghiên cứu.
2. Semantic Slash khác Author Macro và Native Command.
3. Slash là đơn vị shorthand trong một Visual Grammar lớn hơn.
4. Slash có thể xung đột.
5. Ảnh đẹp không phải bằng chứng.
6. Mọi claim hành vi phải đi qua test.
7. Đích đến là tư duy Visual Prompt Engineer, không phải học thuộc danh sách lệnh.
