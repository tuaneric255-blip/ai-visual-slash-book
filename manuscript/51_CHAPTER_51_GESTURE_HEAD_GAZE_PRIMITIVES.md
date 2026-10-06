# CHƯƠNG 51 — GESTURE, HEAD & GAZE PRIMITIVES

## 51.1. Hands
Candidates:
`/chinhand` · `/cheekhand` · `/handsinpocket` · `/armscrossed` · `/handonhip` · `/handsbehind` · `/handsforward` · `/pointing` · `/presenting` · `/reaching`.

## 51.2. Head
`/headtilt` · `/lookback` · `/headturnleft` · `/headturnright` · `/chinup` · `/chindown`.

## 51.3. Gaze
`/lookcamera` · `/lookaway` · `/lookup` · `/lookdown` · `/lookleft` · `/lookright`.

Head direction và gaze direction không phải một biến. Một người có thể quay đầu sang trái nhưng mắt nhìn lại camera.

## 51.4. Expression
`/neutralexpression` · `/softsmile` · `/happysmile` · `/thoughtful` · `/surprised` · `/tiredlook`.

Expression entry phải mô tả facial cues quan sát được và tránh gán tâm lý quá mức.

## 51.5. Combination
`/sit /onekneeup /chinhand /lookcamera /softsmile`

Natural-language expansion:
Subject seated with one knee raised; elbow resting near the raised knee; cheek lightly supported by one hand; head neutral; eyes looking toward camera; subtle closed-mouth smile.

### Tóm tắt chương
Gesture, head, gaze và expression là các layer độc lập. Tách chúng làm tăng khả năng kiểm soát pose.
