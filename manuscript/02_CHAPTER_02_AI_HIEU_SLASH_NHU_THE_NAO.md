# CHƯƠNG 2 — AI HIỂU SLASH NHƯ THẾ NÀO?

## 2.1. Từ từ khóa đến thuộc tính thị giác
Một slash tốt phải có thể mở rộng thành một mô tả thị giác có nghĩa. Nếu không thể giải thích nó bằng ngôn ngữ tự nhiên, khả năng cao slash đang quá mơ hồ hoặc chỉ là một macro chưa được định nghĩa.

Ví dụ:
`/softlight` → nguồn sáng có độ chuyển vùng sáng-tối mềm, bóng ít gắt, chuyển tiếp dịu hơn.

`/negativespace` → dành vùng trống đáng kể quanh hoặc bên cạnh chủ thể để tăng tách biệt, nhịp thở thị giác hoặc chỗ đặt copy.

## 2.2. Prompt Foundation
Mỗi slash trong Dictionary có một **Prompt Foundation**: câu diễn giải tự nhiên dùng để giải thích ý nghĩa cốt lõi.

Prompt Foundation không phải "câu thần chú tốt nhất". Nó là bản mở rộng có thể đọc, kiểm tra và sửa.

Ví dụ:
`/lowangle`

Prompt Foundation:
“Camera positioned below the subject and directed upward, emphasizing the upward viewing perspective while preserving natural subject proportions as far as possible.”

## 2.3. What Changes / What Stays
Một kỹ thuật kiểm soát quan trọng là xác định trước biến nào được phép thay đổi.

Với `/lowangle`:
- **Changes:** camera viewpoint, upward perspective, foreground/background relationship.
- **Stays:** identity, wardrobe, scene, lighting, product geometry - trừ khi chúng chính là biến đang test.

Tư duy này đặc biệt quan trọng khi edit/reference image, bởi một prompt tốt không chỉ nói AI phải thay đổi gì mà còn nói rõ **không được tự ý thay đổi gì**.

## 2.4. Semantic Strength
Cuốn sách sử dụng ba nhóm khái niệm:

**STRONG:** tên slash trực tiếp trùng với một khái niệm thị giác phổ biến, ví dụ `/lowangle`, `/symmetry`, `/softlight`.

**COMPOSITE:** slash ghép nhiều tín hiệu hoặc có biên nghĩa rộng, ví dụ `/seoulstreetlook`, `/heroangle`.

**MACRO:** hành vi do dự án định nghĩa.

Semantic Strength không phải Test Status. Một slash có ý nghĩa ngôn ngữ rất mạnh vẫn có thể UNSTABLE khi chạy trên một model cụ thể.

## 2.5. Tại sao cùng slash có thể ra kết quả khác?
Generative model không phải máy ảnh vật lý nhận một tham số duy nhất. Kết quả chịu ảnh hưởng đồng thời bởi subject, reference, các câu lệnh khác, model/version, chế độ generation/edit, tỉ lệ khung hình và nhiều yếu tố nội bộ mà người dùng không trực tiếp kiểm soát.

Vì vậy cuốn sách luôn ghi **ngữ cảnh test** thay vì biến một quan sát thành quy luật vĩnh viễn.

## 2.6. Từ slash đơn đến hệ thống điều khiển
Hãy coi mỗi slash như một control trong một bảng điều khiển:

Pose: `/contrapposto`
Framing: `/fullbody`
Camera: `/lowangle`
Composition: `/leadinglines`
Light: `/softlight`
Scene: `/seoulstreet`

Khi ghép, nhiệm vụ của Prompt Engineer là đảm bảo mỗi control có vai trò rõ ràng và không tranh chấp cùng một biến.

### Tóm tắt chương
Slash có giá trị khi nó ánh xạ được sang visual attributes, có Prompt Foundation, xác định được What Changes/What Stays và có thể kiểm thử. Semantic Strength mô tả độ rõ nghĩa; Test Status mô tả bằng chứng thực nghiệm - hai thứ không được đánh đồng.
