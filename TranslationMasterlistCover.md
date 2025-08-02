---
title: "Masterlist Cover"
description: ""
permalink: masterlistcover/
---

<head>
<meta name="viewport" content="width=device-width, initial-scale=1.0">

<style>
body {
background-color: #89AEB2;
}
.grid {
	display: flex;
	justify-content: center;
	margin: auto;
	width: 60vw;
	height: 70vh;
	padding: 1rem;
	border-radius: 10px;
	background: #ffffff;
}

.left-side {
	flex-grow: 3;
	margin-right: 1rem;
}

figure {
	margin: 0;
	}

.title {
	margin: 0.5rem;
	font-size: 2rem;
	font-weight: 700;
}

.right-side {
	flex-shrink: 1;
	display: flex;
	margin-left: 1rem;
	/*width: 500rem;*/
	width: 2300px;
}

.right-side a div {
	height: 70vh;
	padding: 0.2rem;
}

.right-side img, .top-side img {
	border-radius: 10px;
	transition: .4s;
	display: block;
	object-fit: cover;
	max-width: 100%;
    max-height: 100%;
}

.right-side img:hover, .top-side img:hover {
	filter: brightness(55%);
	transition: .4s;
}

.left-side a {
	background-color: #1894A1;
	color: #FFFFFF; 
	display: inline-flex;
    width: auto;
    height: 3.75rem;
    line-height: 3.75rem;
    padding: 0 1.875rem;
    vertical-align: middle;
    font-family: 'Source Sans Pro', sans-serif;
    letter-spacing: 0.05rem;
    padding-left: calc(0.05rem + 1.875rem);
    font-size: 1em;
    font-weight: 400;
    border-radius: 0.5rem;
    transition: transform 0.25s ease, color 0.25s ease, background-color 0.25s ease, border-color 0.25s ease;
}

.top-side {
	display: none;
}

@media only screen and (max-width:900px) {
	.grid {
		display: block;
	}
	.right-side {
	display: none;
	}
 
	.top-side {
	display: block;
	}
	
	.top-side img {
	max-height: 35rem;
	height: 100% !important;
    object-fit: cover;
    object-position: top;
    width: 100% !important;
    border-radius: 10px;
    padding: 0.25rem;
	}
}
</style>
</head>

<body>
<section class="grid">
	<div class="top-side">
	<div><a href="eventscout"><img src="https://esmlmock.carrd.co/assets/images/image03.jpg"></a></div>
	</div>
	<div class="left-side">
		<div class="title">Ensemble Stars Masterlist</div>
		<div class="description">Lorem ipsum dolor sit amet, consectetur adipiscing elit. Donec lacinia pulvinar ex, non lacinia erat placerat vitae. Nam in felis mi. Nulla sit amet fermentum justo. Vivamus molestie ultrices lorem, vel aliquam ligula egestas at. Quisque vitae finibus est. Duis eu mi gravida, rutrum purus vel, ornare urna. Curabitur nunc massa, auctor non eros sit amet, sodales euismod augue.</div>
		<a href="/">About the Masterlist</a>
		<a href="/">About the Contact</a>
	</div>
	<div class="right-side">
		<a href="eventscout"><div><img src="https://esmlmock.carrd.co/assets/images/image03.jpg"></div></a>
		<a href="featureidol"><div><img src="https://esmlmock.carrd.co/assets/images/image01.jpg"></div></a>
	</div>
	<div class="top-side">
		<a href="featureidol"><div><img src="https://esmlmock.carrd.co/assets/images/image01.jpg"></div></a>
	</div>
</section>
</body>