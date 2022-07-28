# LEVEL

레벨이 높으면 높을 수록 돈을 받을 때 더 많이 가져갈 수 있습니다.
최초 레벨은 Lv.0 이며 최대 레벨(Lv. 10) 이 되면 커멘드를 칠때 마다 나가는 돈이 없습니다.

## Command

- `$level check`

  - 위 커멘드로 현재 레벨 체크
  - ```
    NOW : <level>
    HISTORY : <TIME> <LEVEL> <SUCSSED> <PERCENTAGE> <SPEND> <UserName>
    ```

- `$level up`

  - 위 커멘드로 레벨 증가를 시킬 수 있음
  - 일정량의 돈 지불
    - 레벨이 오르면 오를 수록 50% 씩 증가
  - 일정량의 확률로 올라감
    - 레벨이 오르면 오를 수록 10% 씩 감소

## API

- Check 
  - `GET /level/check/:userId`

- Level Up
  - `POST /level/up/:userId`
