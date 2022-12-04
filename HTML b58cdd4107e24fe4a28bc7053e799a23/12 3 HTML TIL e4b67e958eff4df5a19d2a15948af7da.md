# 12.3 HTML TIL

```html
<!doctype html>
<html>
  <head>
    <title> HTML 주요 태그 정리</title>
    <meta charset="utf-8">
  </head>
  <body>
    <div>안녕하세요. div입니다</div>

    <h1>h1</h1>
    <h2>h2</h2>
    <h3>h3</h3>
    <h6>h6</h6>

    <img src="apple.png" alt=" 애플로고 ">.     <!--닫는 태그가 없다. 소스는 경로 알트는 불러오지 못할 시 입력-->

    <h2>input test</h2>
    <input type="text" placeholder="이름입력"> <!--문자열 입력-->
    
    
    <input type="button" value="눌러보세요" ><br>
    
    
    <input type="checkbox" id="agree"><br>

    <label for="agree">약관에 동의 하십니까?</label><br>

    <input type="password" name="" id="" placeholder="비밀번호"><br><!--placeholder인풋 상자 안에 이름생성-->

    <input type="number" name="" id=""><br><!--숫자만 입력하게 해줌-->

    <label for="man">남성</label>
    <input type="radio" name="gender" id="man" checked><br><!--checked는 디폴트값을 지정해준다-->

    <label for="woman">여성</label>
    <input type="radio" name="gender" id="woman"><!--동그란 버튼생성 name은 두 개이상 만들 시 양자택일 하게 해준다.-->

    <h2>button test</h2>
    <button type="submit">버튼 태그 입니다.</button><br>
    <input type="button" name="" id="">

    <h2>a tag</h2>
	      <a href="http://naver.com" target="_blank">네이버</a><!--_blank 새 페이지에서 열기-->
	
	    <h2>span tag</h2>
	    <h3>안녕하세요. <span style="color: blue"> 고상현입니다.<span/></h3><!-- Css를 사용하기 위한 형식-->
	
	    <h3>안녕하세요. <div style="color: blue"> 고상현입니다.</div></h3><!--div 태그는 디폴트로 한 줄을 모두 사용-->

    
    <h2>ul,ol,li</h2>
	    <ul >
	      <li>num1</li>
	      <li>num2</li>
	      <li>num3</li>
	    </ul>

    
	    <ol>
	      <li>num1</li>
	      <li>num2</li>
	      <li>num3</li>
	    </ol>

    
    <h2>form tag</h2>
	    <form action="day1 HW.html" method="get" target="_self">
	    <input type="text" name="user-id" placeholder="아이디">
	    <input type="password" name="user-password" placeholder="비밀번호">
	    <button type="submit">로그인하기</button>
	    <button type="reset">리셋</button></form>
  </body>
</html>
```

## 오늘 연습한 HTML 태그

### H[1~6]

```html
<h1>h1</h1>
<h2>h2</h2>
<h3>h3</h3>
<h6>h6</h6>

글자의 크기가 조절할 수 있다.
```

### div

```html
<div>안녕하세요. div입니다</div>

div 태그를 사용하여 각각의 블록(공간)을 알맞게 배치하고 CSS를 활용하여 스타일을 적용할 수 있다.
```

### img

```html
<img src="apple.png" alt=" 애플로고 ">.     

닫는 태그가 없다. 
src(소스)는 이미지의 경로 
alt(알트)는 불러오지 못할 시 보여지는 텍스트나 이미지
```

### input & label

```html
<h2>input test</h2>
    <input type="text" placeholder="이름입력"> 
    
    
    <input type="button" value="눌러보세요" ><br>
    
    
    <input type="checkbox" id="agree"><br>

    <label for="agree">약관에 동의 하십니까?</label><br>

    <input type="password" name="" id="" placeholder="비밀번호"><br>

    <input type="number" name="" id=""><br>

    <label for="man">남성</label>
    <input type="radio" name="gender" id="man" checked><br>

    <label for="woman">여성</label>
    <input type="radio" name="gender" id="woman">

입력값을 받게 해주는 태그
type에는 text, button, checkbox, number,radio가 있다.
placeholder는 input 상자에 내용을 보여준다 ex) 아이디, 비밀번호
name은 2개 이상의 input을 동일 name으로 묶어줌
id는 label과 input을 하나로 묶어줌 
label은 input에 라벨을 붙여준다고 생각하면 됨 

```

### button

```html
<button type="submit">버튼 태그 입니다.</button>

버튼을 만들어주는 태그
input의 button과 다른 점은?
```

### a

```html
<a href="http://naver.com" target="_blank">네이버</a>]

a는 불러올 링크나 페이지를 설정할 수 있고 
target은 _blank & _self로 지정가능

```

### ul & ol & li

```html
<ul >
	      <li>num1</li>
	      <li>num2</li>
	      <li>num3</li>
	    </ul>

    
	    <ol>
	      <li>num1</li>
	      <li>num2</li>
	      <li>num3</li>
	    </ol>

ul은 순서가 없는 태그
ol은 순서가 있는 태그
```

### form

```html
 <form action="day1 HW.html" method="get" target="_self">
	    <input type="text" name="user-id" placeholder="아이디">
	    <input type="password" name="user-password" placeholder="비밀번호">
	    <button type="submit">로그인하기</button>
	    <button type="reset">리셋</button></form>
```