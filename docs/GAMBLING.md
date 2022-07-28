# GAMBLING

## Command

- `$gambling check`
  - 위 커맨드로 도박 전적 확인
  - `<TIME> <MONEY> <EARN> <PERCENTAGE> <USERNAME>`

- `$gambling <money>`

  - 위 커맨드로 `<money>` 만큼의 돈을 자신에게서 빼서, 도박 판에다가 걸음
  - 랜덤한 확률로 돈이 줄어들거나 많아짐

## API

- Check
  - 도박 전적 확인
  - `GET /gambling/check/:userId`

- Gambling
  - 도박 실행
  - `POST /gambling/:money/:userId`
