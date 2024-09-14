[figma](https://www.figma.com/design/WyFL7XWV7cFkNfr8Z3MWIZ/Essential-UI---Figma-Ui-Kit-(Community)?node-id=315-449&node-type=CANVAS&t=aoYVhwlPHRYNfVez-0)

## 피드백
- 전체 article로 묶음 -article 무리, 전체는 div container로 하면 더 좋았을 거 같다.
 card클래스명을 준 마크업을 article로..(accessories~view all까지)
- 반응형 잘했다
- l_wrapper는 화면 전체를 감쌀 때 쓰는 것이니.... 클래스명을 다른 것으로 대체하면 좋을 거 같다.
- 버튼 찌그러짐 =>/*너비 높이 설정 필요*/


## 내가 상대방에게 한 피드백
- flex 사용시에 wrapper을 안줘서 창 크기 줄였을 때 안에 contents가 화면에서 overflow된다.
- items 이름이 길어졌을 때를 가정한 반응협 웹이 준비되지 않았다
- count에 margin left를 줘서 배치하는 거 보다 item에 flex-grow:1과 width:0을 줘서 내용 관계 없는 일관된 레이아웃을 유지하는 것이 좋을 거 같아
