## 📝 오늘 공부한 내용
> useState vs useReducer

## 😲 오늘 깨달은 내용
-  useState와 useReducer 둘 다 상태관리를 위한 훅이지만 useState는 단순한 상태 변경 로직에서 사용하고 useReducer는 상태값 변경을 액션으로 미리 지정하여 정해진 규칙에 따라 상태 변경을 강제할 수 있다.
- 또한 useReducer은 현재 상태를 기반으로 하는 복잡한 로직을 처리할 때도 유리하다.
- 트레이딩 시스템을 만들 때 빠른 로직 속도 때문에 계좌의 포지션 상태 값과 로직 상 상태가 1대1 매칭이 되지 않는 경우가 있었다. (ex. A 롱 포지션: 1개, B 숏 포지션: 0개인 상태가 A1개, 1개에서 줄어든 건지 0개, 0개에서 늘어난 건지 판단 하려면 이전 상태를 알아야함) 
- 따라서 복잡한 상태 관리 로직이 필요 했는데 시스템이 커지다보니 원치 않는 변경도 생기고 까다로웠던 기억이 있다. 만약 useReducer 내부 구성 로직을 알고 있었다면, 설계할 때 편리했을 것 같다는 생각이 들었다.  

## 🥲 오늘 이해못했거나 궁금한 내용
- 없음
   
## 📁 참고한 자료 및 사진 첨부
- ![image](https://github.com/user-attachments/assets/765ab30f-e237-4b65-80fc-7b7354af0692)
- ![image](https://github.com/user-attachments/assets/bf045468-263c-4d3d-be1e-7ce35c6a33ae)
