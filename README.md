# Slider2023
이미지 슬라이드 애니메이션 효과를 구현했습니다.

css로 이미지가 보이는 영역, 움직이는 영역, 개별적인 이미지의 영역의 크기를 부여했습니다. <br>
보여지는 영역을 제외하고는 보여지지 않게 하기 위해 `overflow: hiddem` 을 사용했습니다. <br>
script 태그에서 javascript, jQuert, GSAP 라이브러리를 사용해서 구현했습니다.

## SliderEffect

**sliderEffect01** : https://dongjin6539.github.io/web2023/javascript/slider/sliderEffect01.html <br>
- 이미지가 fadeIn, fadeOut인 fade 애니메이션 효과를 구현했습니다.
- setInterval() 메서드를 사용해서 duration 효과를 줬습니다.

**sliderEffect02** : https://dongjin6539.github.io/web2023/javascript/slider/sliderEffect02.html <br>
- 이미지가 오른쪽에서 왼쪽으로 슬라이드하는 애니메이션 효과를 구현했습니다.
- setInterval() 메서드를 사용해서 duration 효과를 줬습니다.

**sliderEffect03** : https://dongjin6539.github.io/web2023/javascript/slider/sliderEffect03.html <br>
- 이미지가 아래에서 위로 슬라이드하는 애니메이션 효과를 구현했습니다.
- setInterval() 메서드를 사용해서 duration 효과를 줬습니다.

**sliderEffect04** : https://dongjin6539.github.io/web2023/javascript/slider/sliderEffect04.html <br>
- 이미지가 오른쪽에서 왼쪽으로 연속적으로 슬라이드하는 애니메이션 효과를 구현했습니다.
- setInterval() 메서드를 사용해서 duration 효과를 줬습니다.
- firstElementChild.cloneNode(true) 메서드를 사용해서 이미지를 복사했습니다.
- appendChild() 메서드를 사용해서 복사한 이미지를 붙여넣었습니다.

**sliderEffect05** : https://dongjin6539.github.io/web2023/javascript/slider/sliderEffect05.html <br>
- 이미지가 아래에서 로 연속적으로 슬라이드하는 애니메이션 효과를 구현했습니다.
- setInterval() 메서드를 사용해서 duration 효과를 줬습니다.
- firstElementChild.cloneNode(true) 메서드를 사용해서 이미지를 복사했습니다.
- appendChild() 메서드를 사용해서 복사한 이미지를 붙여넣었습니다.

**sliderEffect06** : https://dongjin6539.github.io/web2023/javascript/slider/sliderEffect06.html <br>
- 이미지 슬라이드 부분에 버튼과 닷 메뉴를 활성화 시키는 효과를 구현했습니다.
- 버튼과 닷 메뉴를 클릭했을 때 이미지가 해당하는 index 값에 이동하도록 구현했습니다.

**sliderEffect07** : https://dongjin6539.github.io/web2023/javascript/slider/sliderEffect07.html <br>
- 이미지 슬라이드 부분에 버튼과 썸네일을 활성화 시키는 효과를 구현했습니다.
- 버튼과 썸네일을 클릭했을 때 이미지가 해당하는 index 값에 이동하도록 구현했습니다.
