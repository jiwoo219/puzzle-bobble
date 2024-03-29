# puzzle-bobble

이 프로젝트는 puzzle-bobble이라는 실제 존재하는 게임을 C++과 OpenGL을 활용해 구현한 프로젝트입니다.<br/>
puzzle-bobble 링크: https://www.crazygames.com/game/puzzle-bobble

<p align="center">
<img src=https://github.com/jiwoo219/puzzle-bobble/assets/78020027/e42e1fc9-a40a-4cf7-97e1-218613673bcb width="60%" height="60%"/>
</p>

## 게임 방식

1. **게임 화면**: 처음에는 게임 화면에 아무 버블이 없고 화면아래에는 버블 발사대가 있습니다.
2. **조작**: 플레이어는 아래에 위치한 발사대에서 버블을 발사하여 판상의 버블들을 맞춰야 합니다. 발사대에서 발사된 버블은 위로 향해 날아가며 왼쪽 오른쪽 벽에 부딪힐 경우 반사됩니다. 플레이어는 좌우로 이동하며 발사 각도를 조절할 수 있습니다. 
3. **맞추기**: 버블을 발사하여 판상의 동일한 색상의 버블들을 맞추면, 그 버블들은 터지며 점수를 얻습니다. 만약 버블들이 터진 후에 다른 버블들이 떨어져 내려와서 연쇄적으로 터지면 추가 점수를 얻을 수 있습니다.
4. **게임 오버**: 판상의 버블들이 화면 아래로 내려오면서 발사대 까지 다가오면 게임 오버가 됩니다.

## 구현 모습
<p align="center">
<img src=https://github.com/jiwoo219/puzzle-bobble/assets/78020027/7f80d93c-8fde-4a5d-b431-0d2dd76366e3 width="45%" height="45%"/>
<img src=https://github.com/jiwoo219/puzzle-bobble/assets/78020027/b0b8bc6b-013d-4450-9084-8eb48660a85e width="45%" height="45%"/>
</p>
