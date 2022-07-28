# MONEY

MONEY 는 `원` 으로 계산되며, 돈을 얻는 방식은 여러가지 입니다.
커멘드(`$`) 를 사용할 시 계속해서 800 원씩 나갑니다.

## Command

- `$money check`
  - 현재 돈 확인

## API

- Check
  - `GET /money/check/:userId`

- Earn
  - `POST /money/get/:amount/:userId`

- Lose
  - `POST /money/lose/:amount/:userId`

