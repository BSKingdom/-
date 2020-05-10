<!doctype html>
<html>
<head>
<meta charset="utf-8">
<title>无标题文档</title>
	<style type="text/css">
	html,body{
	height: 100%;
	display: flex;
	align-items: center;
	justify-content: center;
	background: linear-gradient(lightpink, white);
}

.heart {
	display: grid;
	grid-template-columns: repeat(9, 1fr);
	grid-gap: 2px;
}

.heart > * {
	width: 1em;
	height: 1em;
	border-radius: 0.1em;
	font-size: 30px;
}

.heart dot{
	background: red;
	filter: opacity(0); 
	animation: animation 5s ease-out infinite;
}

.heart span {
	background-color: transparent;
}

.heart dot:nth-of-type(2n) {
	animation-delay: 0.2s;
}

.heart dot:nth-of-type(3n) {
	animation-delay: 0.3s;
}

.heart dot:nth-of-type(4n) {
	animation-delay: 0.4s;
}

.heart dot:nth-of-type(5n) {
	animation-delay: 0.5s;
}

.heart dot:nth-of-type(6n) {
	animation-delay: 0.6s;
}

.heart dot:nth-of-type(7n) {
	animation-delay: 0.7s;
}

.heart dot:nth-of-type(8n) {
	animation-delay: 0.8s;
}

.heart dot:nth-of-type(9n) {
	animation-delay: 0.9s;
}

.heart dot:nth-of-type(10n) {
	animation-delay: 1.0s;
}

.heart dot:nth-of-type(11n) {
	animation-delay: 1.1s;
}

@keyframes animation{
	0% {
		filter: opacity(0);
		transform: translateY(-10em);
	}

	25%, 75% {
		filter: opacity(1);
		transform: translateY(0);
	}

	100% {
		filter: opacity(0);
		transform: translateY(10em);
	}
}
</style>
	
</head>

<body>
	<p>祝母亲节日快乐</p>
	<div class="heart">
  <!-- line 1 -->
  <span></span>
  <dot></dot>
  <dot></dot>
  <span></span>
  <span></span>
  <span></span>
  <dot></dot>
  <dot></dot>
  <span></span>

  <!-- line 2 -->
  <dot></dot>
  <dot></dot>
  <dot></dot>
  <dot></dot>
  <span></span>
  <dot></dot>
  <dot></dot>
  <dot></dot>
  <dot></dot>

  <!-- line 3 -->
  <dot></dot>
  <dot></dot>
  <dot></dot>
  <dot></dot>
  <dot></dot>
  <dot></dot>
  <dot></dot>
  <dot></dot>
  <dot></dot>
  <!-- line 4 -->
  <dot></dot>
  <dot></dot>
  <dot></dot>
  <dot></dot>
  <dot></dot>
  <dot></dot>
  <dot></dot>
  <dot></dot>
  <dot></dot>

  <!-- line 5 -->
  <span></span>
  <dot></dot>
  <dot></dot>
  <dot></dot>
  <dot></dot>
  <dot></dot>
  <dot></dot>
  <dot></dot>
  <span></span>

  <!-- line 6 -->
  <span></span>
  <span></span>
  <dot></dot>
  <dot></dot>
  <dot></dot>
  <dot></dot>
  <dot></dot>
  <span></span>
  <span></span>

  <!-- line 7 -->
  <span></span>
  <span></span>
  <span></span>
  <dot></dot>
  <dot></dot>
  <dot></dot>
  <span></span>
  <span></span>
  <span></span>

  <!-- line 8 -->
  <span></span>
  <span></span>
  <span></span>
  <span></span>
  <dot></dot>
  <span></span>
  <span></span>
  <span></span>
  <span></span>
</div>
</body>
</html>
