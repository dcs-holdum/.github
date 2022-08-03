# ATTENDANCE

## Command

- `$attendance check`

  - 위 커멘드로 현제 현황 체크
  - `<TIME> <STREAK> <EARN> <USERNAME>`

- `$attendance stamp`

  - 위 커멘드 출석 가능함
  - 출석시 1000 코인을 얻음
  - 출석을 연속으로 할 시 +1000 코인을 더 얻고, 한번이라도 빼먹으면 초기화 됨

## API

- Check
  - 현재 현황 체크
  - `GET /attendance/check/:userId`

- Attendance
  - 출석하기
  - `POST /attendance/stamp/:userId`
