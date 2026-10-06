# CHƯƠNG 53 — POSE × CAMERA COMBINATIONS

## 53.1. Combination changes meaning
Cùng một pose nhưng camera khác nhau tạo geometry khác nhau. Cùng một camera nhưng body state khác nhau cũng thay đổi visual result.

## 53.2. Standing
**Neutral full body**
`/stand /frontview /eyelevel /fullbody`

**Low hero**
`/stand /weightshift /lowangle /threequarterview /fullbody`

**Extreme perspective**
`/stand /stepforward /wormseye /fullbody /foreshortening`

## 53.3. Sitting
**Relaxed floor portrait**
`/sit /crosslegged /eyelevel /fullbody`

**High-angle seated**
`/sit /onekneeup /chinhand /highangle /fullbody`

**Foreshortened seated**
`/sit /onelegextended /highangle /foreshortening`

## 53.4. Reclining
`/recline /elbowsupport /threequarterview /fullbody`
`/prone /elbowsupport /closeup`
`/sidelying /cheekhand /eyelevel /fullbody`

## 53.5. Look-back
`/stand /backview /lookback /fullbody`
`/lookback /overtheshoulder /closeup`

## 53.6. Conflict examples
`/fullbody /extremecloseup` → hard framing conflict.
`/frontview /profile` → orientation conflict for one subject.
`/topdown /wormseye` → viewpoint conflict for one camera.

### Tóm tắt chương
Combination recipes nên ghi rõ mỗi slash đang điều khiển biến nào và conflict nào có thể xảy ra.
