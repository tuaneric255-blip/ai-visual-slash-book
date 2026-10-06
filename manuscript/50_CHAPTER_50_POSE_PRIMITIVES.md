# CHƯƠNG 50 — POSE PRIMITIVES: BODY STATE, SUPPORT & WEIGHT

## 50.1. Body State
Candidate primitives:
`/stand` · `/sit` · `/kneel` · `/crouch` · `/squat` · `/recline` · `/lie` · `/prone` · `/supine`.

## 50.2. Leg configuration
`/crosslegged` · `/onekneeup` · `/kneehug` · `/legsextended` · `/onelegextended` · `/legscrossed` · `/kneestogether` · `/kneesapart`.

## 50.3. Support
`/handsupport` · `/elbowsupport` · `/walllean` · `/chairlean` · `/backlean` · `/forwardlean`.

## 50.4. Weight
`/weightshift` · `/hipshift` · `/contrapposto` · `/widebase` · `/balancedstance`.

## 50.5. Ground relationship
Pose review phải kiểm tra contact points, center of mass và support logic. Một pose đẹp nhưng cơ thể không có điểm đỡ hợp lý là anatomy/physics failure.

## 50.6. Combination examples
`/sit /crosslegged`
`/sit /onekneeup /chinhand`
`/kneel /forwardlean /handsupport`
`/prone /elbowsupport /feetup`

### Tóm tắt chương
Primitive mô tả trạng thái cơ thể trước khi thêm biểu cảm, camera hoặc style.
