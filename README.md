# 리액트에 구글 웹폰트 적용

[구글 웹폰트 사이트 이동](https://fonts.google.com/)</br>

- public폴더 안쪽의 index.html의 head안에 삽입하는 방식

```html
<head>
	<meta charset="utf-8" />
	<link rel="icon" href="%PUBLIC_URL%/favicon.ico" />
	<meta name="viewport" content="width=device-width, initial-scale=1" />
	<link rel="preconnect" href="https://fonts.googleapis.com" />
	<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin />
	<link
		href="https://fonts.googleapis.com/css2?family=Rubik+80s+Fade&display=swap"
		rel="stylesheet"
	/>
	<title>React App</title>
</head>
```

- scss파일 안쪽에 삽입하는 방식

```css
@import url('https://fonts.googleapis.com/css2?family=Rubik+80s+Fade&display=swap');
```
