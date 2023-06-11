# transition 과제

 ### [배포 URL]

  * **URL** : https://github.com/dongapple/home-work.git
  * **계정** : dongapple

  ***
  ### [기술]

  <img src="https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=HTML5&logoColor=white">
   <img src="https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white">

  ***
  ### [파일]
  
  * transition.html
  * transition.css
  * reset.css

  
  html : 
`article`, `div`, `li`, `<a>`

css : `~:hover`, `transition`, `padding`


reset.css는 속성을 초기화 해주기 위해 사용.
```	
    margin: 0;
	padding: 0;
	border: 0;
	font-size: 100%;
	font: inherit;
	vertical-align: baseline;
  ```
`.ani-article`클래스에 `display: table;`부여해 **넓이** 와 **높이** 모두 자식 요소를 따라가게 함.

`.ani-box`클래스에 **넓이값** 과 **세로값**을 부여해 박스 크기를 지정해줌.<br>
`:hover`선택자와 `transition:`를 사용해 마우스가 호버 되었을 시 크기에 변화를 줌.<br>`overflow:`를 사용하여 박스크기를 넘어가는 내용은 보이지 않게 함

`.ani-link`를 `display: block;`로 설정하고 `padding-left:`을 설정해 **좌,우** 모든 영역에서도 선택 가능 하게 함.

***
### [결과]

`hover before` <br>

![image](https://github.com/dongapple/home-work/assets/74224516/7c690d12-f29f-4089-affa-7758d88ee551)

<br>

`hover affter` <br>

![image](https://github.com/dongapple/home-work/assets/74224516/4ddc61d4-81d7-4951-a584-67763e2d2832)
