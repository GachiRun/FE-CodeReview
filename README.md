# FE-CodeReview를 통한 코드 컨벤션
## 📌 Code Convention

1. grid/flex 사용 시 웬만하면 `gap`을 사용하자. 혹시나 간격이 다를 경우에만 `margin` 사용을 허가한다.
2. margin/padding은 무조건 축약형으로 사용하자.
3. css의 순서는 반드시 아래와 같이 진행한다.

| 순서 | 속성 |
| --- | --- |
| 1 | content (내용) |
| 2 | display (요소의 노출여부/표현방식) |
| 3 | list-style |
| 4 | position (위치/좌표) |
| 5 | float |
| 6 | clear |
| 7 | width / height (크기/여백) |
| 8 | padding / margin |
| 9 | color / font (글자/정렬) |
| 10 | text-decoration |
| 11 | text-align / vertical-align |
| 12 | white-space |
| 13 | other text |
| 14 | border / background (윤곽/배경) |
   
4. 한 묶음의 컨테이너 사용 시 또는 코드가 길어질 시 닫는 태그 옆에 `// detailed-info` 와 같은 주석을 추가한다.
5. css 파일은 기능별로 뭉쳐서 하나씩 사용한다.
6. `border: none` 대신에 `border : 0`을 사용한다. 
