# CHƯƠNG 10 — STANDING POSE: HỆ TỪ VỰNG DÁNG ĐỨNG

## 10.1. Neutral Standing
Neutral standing là baseline quan trọng vì nó tạo control để so sánh các pose khác. Cơ thể đứng tự nhiên, không cố tạo đường cong hoặc gesture mạnh.

Candidate vocabulary:
`/neutralstand` · `/relaxedstand` · `/straightstand`

**Evidence:** NOT YET TESTED đối với hành vi slash cụ thể.

## 10.2. Weight Shift
Nhóm này thay đổi trọng lượng và trục:
`/weightononeleg`
`/hipshift`
`/onelegforward`
`/kneebend`
`/anklecross`

Khi test, cần full body và feet visible.

## 10.3. Contrapposto
`/contrapposto`

Prompt Foundation:
Natural contrapposto standing pose, body weight supported primarily by one leg, opposite leg relaxed, subtle pelvic shift, shoulders and torso naturally counterbalanced.

Điểm cần kiểm tra:
weight-bearing leg, relaxed leg, pelvis, shoulders, spine.

**Evidence:** NOT YET TESTED.

## 10.4. Structured / Power Stance
Candidates:
`/powerstance`
`/widestance`
`/squarestance`
`/shouldersquare`

Nhóm này cần tránh biến "power" thành một kết luận tâm lý tuyệt đối. Reviewer trước hết kiểm tra stance geometry.

## 10.5. Leaning
Candidates:
`/walllean`
`/sidelean`
`/backlean`
`/shoulderlean`

Lean cần có điểm tựa hợp lý. Nếu body nghiêng mà environment không hỗ trợ, output có thể trông mất trọng lực.

## 10.6. Fashion Standing
Candidates:
`/scurvepose`
`/hippop`
`/toepoint`
`/shoulderdrop`
`/shoulderturn`
`/waisttwist`
`/overtheshoulder`

Các nhãn "feminine" hay "masculine" nếu dùng trong taxonomy chỉ mô tả convention phổ biến trong fashion imagery, không phải quy tắc ai được phép dùng pose nào.

## 10.7. Hand-supported Standing
Candidates:
`/handonhip`
`/onehandpocket`
`/bothhandspockets`
`/armscrossed`
`/jacketgrip`
`/cuffadjust`
`/watchcheck`

Các slash này đồng thời tác động arm/hand gesture, vì vậy cần tag chéo thay vì tạo duplicate canonical entries.

## 10.8. Cách chọn standing pose theo mục tiêu
Professional portrait → stance rõ, ít gesture thừa.
Fashion → silhouette, line, asymmetry và garment display.
KOC/Product → tay phải phục vụ product visibility.
Lifestyle → weight distribution tự nhiên, tránh cảm giác "đứng chụp hình" quá mức.
Group → ưu tiên quan hệ giữa các người hơn pose cá nhân phức tạp.

### Tóm tắt chương
Standing Pose Library phải được tổ chức theo cơ chế: neutral, weight shift, contrapposto, structured stance, leaning, fashion line và hand-supported stance. Mỗi slash cụ thể vẫn phải đi qua Lab trước khi có badge VERIFIED.
