# Kokoa Talk Challenge in 2 weeks

2주간 코코아톡 클론을 진행하면서 제출사항들을 기록합니다.

## CSS

### CSS 구성
- css 는 두 파트로 구성 되어있는데 selector 파트와 property 파트로 나눈다.

### CSS selector
- h1, div ,span .... everything + id(#) + class(.) 

### CSS 사용
- inline 방식으로 쓰면 그 파일에만 적용되어서 넓게 쓸 수 없다. 비효율적
- external 방식이라면 연결만 하고 css 파일만 수정하면 된다.

### CSS elements
- 많은 elements 들이 박스라는 사실을 기억하자.
- box는 4개의 요소가 있다.
- content padding border margin 으로 이루어져있다.

### Display
- block 은 옆에 아무것도 없다. 크기와 상관 없이 다른것이 옆에 있는것을 허용하지 않는다.
- inline 은 블럭이 서로서로 바로 옆에 있을 수 있다.
- inline-block 은 보더가 겹치지 않으면서도 옆에 있을 수 있다.
- inline 은 width 나 height를 없애버린다 텍스트로 인식해서 컨텐츠의 길이만 존재한다.

### Position
- static : default 값.
- fixed : {top:0 rigth:0} 같은 값을 줘서 위치에 고정시키고 스크롤해도 그자리에 계속 있게한다.
- relatibe : 부모 박스 설정.
- absolute : html 상에서 부모에 해당하는 박스를 찾아서 이에 상응해서 포지션이 결정.



# 오답노트
## Day 2
- Q . Can I create my own meta tag?
- [x] A . Yes, meta tags are just information so I can put whatever I want 
  