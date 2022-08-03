# GAMBLING

## Command

- `$gambling check`
  - 위 커맨드로 도박 전적 확인
  - `<TIME> <MONEY> <EARN> <PERCENTAGE> <USERNAME>`

- `$gambling <money>`

  - 위 커맨드로 `<money>` 만큼의 돈을 자신에게서 빼서, 도박 판에다가 걸음
  - 랜덤한 확률로 이기거나 지게됨
  - 만약 30% 확률로 배팅을 하면..
    - 이겼다면..
      - 배팅한 돈의 170%((100 + (100 - 30))%)
    - 졌다면..
      - 배팅한 돈의 70%((100 - 30)%)

## API

- Check
  - 도박 전적 확인
  - `GET /gambling/check/:userId`

- Gambling
  - 도박 실행
  - `POST /gambling/:money/:userId`
