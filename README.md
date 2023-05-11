# livros-css
0122
header {
	background: #BBBBBB;
}

.caixa {
	width: 940px;
	position: relative;
	margin: 0 auto;
}

nav {
	position: absolute;
	top: 220px;
	right: 0;
}

nav li {
	display: inline;
	margin: 0 0 0 45px;
}

nav a {
	text-transform: uppercase;
	color: black;
	font-weight: bold;
	font-size: 30px;
	text-decoration: none;
}

.produtos {
	width: 940px;
	margin: 0 auto;
	padding: 100px;
}

.produtos li {
	display: inline-block;
	text-align: center;
	width: 30%;
	vertical-align: top;
	margin: 0 1.5%;
} 

.produtos h2 {
	font-size: 20px;
	font-weight: bold;
}

.produtos p {
	font-size: 15px;
	font-weight: bold;
}

@media screen and (max-width: 768px) {
	.caixa {
		width: 90%;
	}

	nav {
		position: static;
		margin-top: 20px;
	}

	.produtos {
		padding: 50px;
	}

	.produtos li {
		width: 48%;
		margin: 0 1%;
	}
}

@media screen and (max-width: 480px) {
	.caixa {
		width: 90%;
	}

	.produtos {
		padding: 30px;
	}

	.prod
