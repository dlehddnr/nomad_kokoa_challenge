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

### Fluid layouts with Flexbox
- 플렉스는 부모클래스에만 적용하면 자식컨텐츠에 적용된다.
- justify-content : 수평, align-items : 수직
- flex direction을 column으로 주면 두개가 반대로 된다.
- flex : wrap 을 사용하면 폭을 유지하기 위해 밑으로 떨어뜨린다. 
- flex는 default로 no-wrap! 그래서 창을 줄이면 폭을 줄인다.

### pseudo-selector
- without class name or id, 가상셀렉터임.
- input[type="submit"], input[required = "required"] 같은걸 사용
- :first-child, :nth-child(), :last-child 같은걸로 순서로 선택 할 수 있다.
- TIP : nth-child(2n) 이라고 하면 매 2의 배수 상자를 선택함 (ex 3n 4n  다 가능)

### Elements States with CSS
- active, focus, visited, hover
- :hover    =>  박스위에 올려지면 효과 나타남
- :active   =>  클릭할 때 효과 나타남
- :focus    =>  탭으로 focus되면 효과 나타남 or Somebody selects or activates a form or link
- :focus    =>  input에서 많이쓰고 내가 글을 쓰고있을 때 작동한다.

### Transition
- 이동, 변경 을 멋지게 보여주는 효과.
- 트랜지션 : 무엇변경, 시간설정, 애니메이션설정
- 한개이상의 설정값을 바꾸고 싶다면 무엇변경 칸에 all 로 적는다.
- 트랜지션은 active, focus, visited, hover 가 적용될때 실행된다.

### Transformations
- transformations 는 elements들이 변하는 효과이다.
- rotate, scale 등등이있다.

### Animation
- @keyframes 으로 css파일에 애니메이션인것을 알려줄수있다.
- 구조 : @keyframes 이름 { from{} to{}}
- from to 대신 % 로 여러단계로 구분가능하다.

### Media Queries
- 브라우저가 큰지 작은지 알아내는 방법.
- 예시 : @media screen and (최소) - (최대){}
  

# 오답노트
## Day 2
- Q . Can I create my own meta tag?
- [x] A . Yes, meta tags are just information so I can put whatever I want 
  
## Day 3
- Q . What is the order for the border shortcut property?
-  [x] A . <border-style> <color> <border-width>

- Q . 'position:absolute' looks for the closest 'relative' parent ?
- A . True

## Day 4
- Q . With flex-direction:column, align-items moves the items ?
-  [x] A . Horizontally

- Q . :focus happens on inputs when ?
-  [x] A . I'm writing on them

## Day 5
- Q . What is the correct way of writing a transition property?
-  [x] A . transition: margin-right 4s ease-in-out;

- Q .  I can rotate elements using 'deg'?
-  [x] A . True

- Q .  I can rotate elements using 'turn'?
-  [x] A . True

- Q .  I can only transform blocks but not inlines 
-  [x] A . False