# login README.md

## 파일 정보
html 파일 경로: ./login.html<br>
css 파일 경로: ./login.css<br><br>

## HTML 파일
form, fieldset, legend 등을 사용하여 큰 틀을 잡고 <br>
input, label, button 으로 로그인창을 구현,<br>
 ul, li 로 회원가입, 아이디,비밀번호 찾기 링크를 생성.<br><br>

## CSS 파일
CSS 파일에서 색상, 글꼴, 레이아웃 등의 스타일이 지정.<br><br>

### 스타일 요소

#### fieldset, legend
- 로그인 영역을 구분하기 위해 fieldset, legend를 사용후 보이지 않게 설정.
```
fieldset {
  border: none;
  margin: 0;
  padding: 0;
}
legend {
  overflow: hidden;
  position: absolute !important;
  clip: rect(0, 0, 0, 0);
  clip-path: inset(50%);
}
```


#### width값
- `ul`태그를 제외한 나머지 배경을 담당하는 부모태그는 `width: auto;`를 부여 하여 <br>`padding`과`margin`으로 너비를 지정.<br>
`form`태그에는 `display: table;`을 지정해주어 너비를 설정.

#### position
- `label`과 `input`태그는 `display: inline-block;`속성을 부여해 가로로 정렬.
- `button`태그는 `fieldset` 바깥 `div`에 부모를 지정한후 `absolute`로 위치를 지정.
- `ul`태그엔 `display: inline;`를 부여해 가로로 배열 후 중앙 정렬.

## 결과물

![image](https://github.com/dongapple/home-work/assets/74224516/6912f137-5987-4aa8-84d7-290d7e9e0a05)
