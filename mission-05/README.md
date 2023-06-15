# sprite 과제

 ### [배포 URL]

  * **URL** : https://github.com/dongapple/home-work.git
  * **계정** : dongapple

  ***
  ### [기술]

  <img src="https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=HTML5&logoColor=white">
   <img src="https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white">

  ***
  ### [파일]
  
  * sprite.html
  * sprite.css
  * reset.css
  * rank.png

  
  html : 
`section`, `ol`, `<a>`

css : `~::before`, `background-position:()`, `display: flex;`


reset.css는 속성을 초기화 해주기 위해 사용.
```	
    margin: 0;
	padding: 0;
	border: 0;
	font-size: 100%;
	font: inherit;
	vertical-align: baseline;
  ```
  body<br> 
  └&nbsp;section<br>
   ├&nbsp;h2<br>
   ├&nbsp;ol<br>
   │&nbsp;└&nbsp;li<br>
   │ └a<br>
   └a


순서를 가지기 떄문에 `ol`태그를 사용해 순서를 지정해줌.<br>

`li`안에 `a`태그를 입력하여 모든 아이템에 링스 속성을 부여.<br>

`ol`태그의 스타일은 숨기고 `counter-increment: index;` 와 `::before`가상 선택자를 사용해 `ol`의 순서를 꾸며줌.<br>

`.sprite`를 사용해 `a`태그의 백그라운드 이미지를 일괄적으로 설정해줌.

`a`태그에 클래스를 각각 부여해 css 가 중복 적용되는것을 배제함.

`더보기`버튼을 스크린 리더가 순서대로 읽을 수 있도록 맨 아래 배치 후 `position: absolute;`를 활용해 맨 위쪽으로 끌어 올림.

***
### [결과]

`결과` <br>

![image](https://github.com/dongapple/home-work/assets/74224516/d9e6dca3-d548-4e7f-8695-c0d9a98c249f)


<br>

`a태그 영역` <br>

![image](https://github.com/dongapple/home-work/assets/74224516/57ff371d-2de7-42a9-aec8-6d433cd88809)
