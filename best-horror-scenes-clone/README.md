# BestHorrorScenes Clone Coding

header + main

- 페이지의 영역이 크게 왼쪽과 오른쪽으로 이분된다. 왼쪽은 header 영역, 오른쪽은 main 영역으로 분리했다.

<br>

header의 미디어쿼리

- 창의 width 값이 최소 945px 까지는 header 영역을 position: fixed로 고정을 시켰다. header의 width 값과 main 영역의 padding-left 값을 같게 420px로 고정했다. 창의 width를 줄이더라도 945px 까지는 header 영역의 너비는 420px로 보존되고 main 영역만 줄어드는 효과를 얻을 수 있다.

- 그러다가 창의 width 값이 945px 보다 작아지면 header 영역을 position: display로 바꾼다. 바꾸지 않고 그대로 position: fixed로 둔다면 header영역은 고정된채로 main영역과 겹쳐져 버린다. 겹치지 않고 header 아래에 main이 올 수 있도록 header 영역의 position을 display로 바꾼다.

<br>

header의 자식 요소 h1 태그

- header의 'BEST HORROR SCENES' h1 태그 값의 경우에는 창의 width가 945px까지는 font-size를 4rem으로 유지했다. 그리고 945px보다 작아지면 770px 까지는 font-size를 3rem으로 수정했다. 770px 보다 작아지면 2rem으로 바꿨다. 창의 크기가 줄어들면 font-size도 작아지도록 했다.

<br>

header의 자식 요소들 배치

- header 영역의 h1 태그를 포함한 문구들은 display: flex, flex-direction: column, justify-content: space-between 속성들을 통해 세로 방향으로 일렬로 서로 간격을 두고 정렬되게 했다. 그리고 margin-left 값을 두어서 왼쪽에 바짝 붙어있지 않고 여백을 유지하도록 했다.

https://besthorrorscenes.com/

