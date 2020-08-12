# CSS 공부내용 정리

css 강의 보면서 공부한 내용 정리  

* 고정위치 - position : fixed
* 마진겹침 - 태그간 마진 겹치는 현상
* 문자정렬 - text-align : center or justifiy ...
* 박스모델 - margin, padding
* 박스사이징 - box-sizing : border-box or content-box ...
* 부모자식선택자 - tag1 tag2, tag1 > tag2
* 상대위치정적위치 - position : relative, static
* 상속 - css 프로퍼티중에 부모로 부터 자식으로 상속되는 프로퍼티가 있음
* 서체 - font-family, font-size, font-weight, line-height, font
* 웹폰트 - 웹폰트사용법
* 인라인vs블럭레벨 - 인라인태그와 블럭레벨 태그의 차이
* 절대위치 - position : absolute
* flex 기본 - flex 레이아웃의 기본 구조, 부모(container)와 자식(item)이 기본구조
* flex-grow&flex-shrink : flex레이아웃 자식에서 flex-basis, flex-grow, flex-shrink 속성 사용법

* flex_holy_grail_layout
* [flex 기타속성](https://codepen.io/enxaneta/pen/adLPwv)
* 미디어쿼리 기본
* 미디어쿼리 응용
* float 기본
* float holy grail layout
* 멀티컬럼(다단)
* 배경 - background 관련 속성
* 필터 - 명도, 채도, 흐림등 각종 효과 , [예제사이트](https://codepen.io/search/pens?q=filter)
* 변형 - 포토샵 처럼 컨텐츠에 왜곡, 회전등의 각종 효과
* 전환(transition) - 부드러운 효과 전환에 사용되는 기능 [trasition timing function](https://matthewlein.com/tools/ceaser)
* link와 import
* 코드경량화 - [clean-css-online](http://adamburgess.github.io/clean-css-online/), [clean-css](https://github.com/jakubpawlowicz/clean-css) [clean-css-util](https://github.com/jakubpawlowicz/clean-css-cli)
* preprocessor - css의 부족한 기능(중첩 등..)을 preprocessor가 보충한다. preprocessor가 인식 할수있는 스타일 파일을 컴파일하여 순수한 css로 만든다.   
 [less](http://lesscss.org/), [sass](https://sass-lang.com/), [stylus](https://stylus-lang.com/), [preprocessor 도구 비교](https://csspre.com/compile/)
 * [fontello](http://fontello.com/) - 특정한 문자를 특정한 이미지로 표현하는 방식(벡터방식의 이미지를 추가할 수 있는 방식).  svg 파일을 이용한 Custom 폰트를 작성한다.
 * [Unicode table](https://unicode-table.com/en/)
 * [Icon](https://thenounproject.com/)
 * 표준 벡터이미지는 svg이다.

```
    //선택자 설명
    //class의 이름이 icon-로 시작하는 모든 before에 대해서, class의 이름이 icon-을 포함하는 모든 before에 대해서
    [class^="icon-"]:before, [class*=" icon-"]
```