<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Pet-project</title>
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Roboto+Mono:ital,wght@0,500;0,700;1,300&display=swap" rel="stylesheet">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/modern-normalize/1.0.0/modern-normalize.min.css">
    <link rel="stylesheet" href="/css/style.css">
    <style>
        html, body, div, span, applet, object, iframe,
h1, h2, h3, h4, h5, h6, p, blockquote, pre,
a, abbr, acronym, address, big, cite, code,
del, dfn, em, img, ins, kbd, q, s, samp,
small, strike, strong, sub, sup, tt, var,
b, u, i, center,
dl, dt, dd, ol, ul, li,
fieldset, form, label, legend,
table, caption, tbody, tfoot, thead, tr, th, td,
article, aside, canvas, details, embed, 
figure, figcaption, footer, header, hgroup, 
menu, nav, output, ruby, section, summary,
time, mark, audio, video {
  margin: 0;
  padding: 0;
  border: 0;
  font-size: 100%;
  font: inherit;
  vertical-align: baseline;
}
  ​
article, aside, details, figcaption, figure, 
footer, header, hgroup, menu, nav, section {
  display: block;
}
  ​
body {
  line-height: 1;
}
  ​
ol, ul {
  list-style: none;
}
  ​
blockquote, q {
  quotes: none;
}
  ​
blockquote:before, blockquote:after,
q:before, q:after {
  content: '';
  content: none;
}
  ​
table {
  border-collapse: collapse;
  border-spacing: 0;
}
header{
  background-color: #e4d9e6;
  width: 100%;
  height:  100px;
}
.logo_name{
  font-family: 'Roboto Mono', monospace;
  font-size: 50px;
  color: #51524f;
  padding-top: 12px;
  padding-left: 70px;
  padding-bottom: 12px;
}
/* .menu {
	width: 100%;
	display: table;
}
.menu ul {
	display: table-row;
}
.menu li {
	display: table-cell;
	position: relative;
	background: #e4d9e6;
}
.menu li a {
	display: block;
	padding: 15px 15px;
	color: #51524f;
	text-align: center;
  font-family: 'Roboto Mono', monospace;
  text-decoration: none;
}
.menu-caret:after {
	display: inline-block;
	width: 0;
	height: 0;
	margin-left: .255em;
	vertical-align: .255em;
	content: "";
	border-top: 3px solid;
	border-right: 3px solid transparent;
	border-bottom: 0;
	border-left: 3px solid transparent;
}
.menu ul li:hover, .menu a:hover {
	background: #e4d9e6;
  color: rgb(161, 161, 161);
}
.menu li:hover ul  {
	display: block;
	position: absolute;
	top: 100%;
	left: 0px;
	background: #e4d9e6;
	margin: 0;
	padding: 10px 20px;
	width: 150px;
	z-index: 9999;
}
.menu ul ul  {
	display: none;
}
.menu ul ul li  {
	display: block;
	background: #e4d9e6;
	padding: 5px 0;
}
.menu ul ul li a  {
	display: block;
	padding: 0;
	background: #e4d9e6;
	text-align: left;
}
main{
  height: 500px;
  background-color: rgb(201, 186, 100);
  display: flex;
  color: black;
} */
/* .burger-menu_button {
  position: fixed;
  top: 10px;
  right: 10px;
  z-index: 30;
  width: 80px;
  height: 80px;
  border-radius: 50%;
  background-color: rgba(255, 255, 255, 0.5);
  -webkit-transition: 0.4s;
  -moz-transition: 0.4s;
  -o-transition: 0.4s;
  transition: 0.4s;
}
.burger-menu_button:hover .burger-menu_lines {
  filter: brightness(0.7);
}

.burger-menu_button:hover {
  background-color: rgba(255, 255, 255, 0.7);
}

.burger-menu_lines::before,
.burger-menu_lines::after,
.burger-menu_lines {
  position: absolute;
  width: 50px;
  height: 3px;
  background-color: #BB1E99;
  -webkit-transition: 0.4s;
  -moz-transition: 0.4s;
  -o-transition: 0.4s;
  transition: 0.4s;
}
.burger-menu_lines {
  top: 50%;
  left: 50%;
  transform: translate(-50%, -50%);
}
.burger-menu_lines::before {
  content: '';
  top: -12px;
}
.burger-menu_lines::after {
  content: '';
  top: 12px;
}


.burger-menu_active .burger-menu_lines {
  background-color: transparent;
}
.burger-menu_active .burger-menu_lines::before {
  top: 0;
  transform: rotate(45deg);
}
.burger-menu_active .burger-menu_lines::after{
  top: 0;
  transform: rotate(-45deg);
}

.burger-menu_nav {
  padding-top: 120px;
  position: fixed;
  top: 0;
  z-index: 20;
  display: flex;
  flex-flow: column;
  height: 100%;
  background-color: #F9AFE9;
  overflow-y: auto;
  right: -100%;
  -webkit-transition: 0.8s;
  -moz-transition: 0.8s;
  -o-transition: 0.8s;
  transition: 0.8s;
}
.burger-menu_active .burger-menu_nav {
  right: 0;
  -webkit-transition: 0.4s;
  -moz-transition: 0.4s;
  -o-transition: 0.4s;
  transition: 0.4s;
}
.burger-menu_link {
  padding: 18px 35px;
  font-family: 'Roboto', sans-serif;
  font-size: 18px;
  text-decoration: none;
  text-transform: uppercase;
  letter-spacing: 5px;
  font-weight: 400;
  color: #BB1E99;
  border-bottom: 1px solid #fff;
}
.burger-menu_link:first-child {
  border-top: 1px solid #fff;
}
.burger-menu_link:hover {
  filter: brightness(0.9);
}
.burger-menu_overlay {
  display: none;
  position: fixed;
  top: 0;
  left: 0;
  width: 100vw;
  height: 100vh;
  z-index: 10;
}
.burger-menu_active .burger-menu_overlay {
  display: block;
  background-color: rgba(0, 0, 0, 0.5);
} */
.menu-bar {
  position: absolute;
  right: 10px;
  top: 10px;
  width: 50px;
  height: 50px;
  cursor: pointer;
}
.menu-bar span, .menu-bar span:before, .menu-bar span:after {
  width: 100%;
  position: absolute;
  height: 10px;
  background:#51524f;
  display: block;
  transition: .3s;
  border-radius: 5px;
}
.menu-bar span:before{
content: "";
top: -20px;
transition: top 300ms 300ms, transform 300ms cubic-bezier(0.23, 1, 0.32, 1);
}
.menu-bar span{
top: 20px;
}
.menu-bar span:after{
content: "";
bottom: -20px;
transition: bottom 300ms 300ms, transform 300ms cubic-bezier(0.23, 1, 0.32, 1);
}

.menu-bar span.active:before{
content: "";
top: 0px;
transform: rotate(45deg);
transition: top 300ms, transform 300ms 300ms cubic-bezier(0.68, -0.55, 0, 1.55);
}
.menu-bar span.active:after{
content: "";
bottom: 0;
transform: rotate(-45deg);
transition: bottom 300ms, transform 300ms 300ms cubic-bezier(0.68, -0.55, 0, 1.55);
}
.menu-bar span.active{
  background: rgba(255, 255, 255, 0); 
}
ul{
list-style: none;
}
.menu{
width: 300px;
height: auto;
background: #e4d9e6;;
color: #ccc;
padding: 10px;
position: fixed;
left: -320px;
transition: left 500ms cubic-bezier(0.68, -0.55, 0.265, 1.55);
}
.menu.animate{
left: 0;
}
@media(max-width: 380px){
.menu{
width: 220px;
}
}
section {
  display: flex;
  align-items: center;
  justify-content: center;
  height: 100vh;
  font-family: sans-serif;
  font-size: 72px;
  text-transform: uppercase;
  color: #000;
}

#section-1 {
  background-image: url(/image/section_1.jpg);
  background-attachment: fixed;
  background-size: cover;
  color: #51524f;
  text-shadow: 4px 4px 6px #fff;
  font-family: 'Roboto Mono', monospace;
}

#section-2 {
 background-color: rgba(218, 188, 212, 0.952); 
 color: #fff;
}

#section-3 {
 background-image: url(/image/section_3.jpg) ; 
  background-size: cover;
  color: rgb(113, 153, 125);
  text-shadow: 4px 4px 3px rgb(105, 124, 87);
}

#section-4 {
 background-color: rgb(248, 170, 229); 
 color: #fff;
}

#section-5 {
 background-image: url(/image/section_5.jpg);
  background-attachment: fixed;
  background-size: cover;
  color: #dfa0ff;
  text-shadow: 0px 0px 15px #a9a9e4;
}

    </style>
</head>
<body>
 <header >
     <div class="logo_name">
            <p>flowers.</p>
     </div>
            <!-- <div class="menu">
                <ul>
                    <li><a href="#">news</a></li>
                    <li><a href="#">history</a></li>
                    <li><a href="#">memetic movement</a></li>
                    <li><a href="#">types of memes</a></li>
                    <li><a href="#">religious memes</a></li>
                    <li>
                        <a class="menu-caret" href="#">looking for memes?</a>
                        <ul>
                            <li><a href="tel:0963848058">my phone number</a></li>
                            <li><a href="mailto:tanyaignat1811@gmail.com">mail</a></li>
                            <li><a href="https://www.instagram.com/tanyaihnatenkoo/">instagram</a></li>
                            <li><a href="#">telegram</a></li>
                            <li><a href="#">click here</a></li>
                        </ul>
                    </li>
                </ul>
            </div> -->
        </header>
        <main>
            <div class="menu-bar">
                <span></span>
            </div>
            <div class="menu">
                    <ul>
                        <li><a href="#section-1" class="burger-menu_link">section 1</a></li>
                        <li><a href="#section-2" class="burger-menu_link">section 2</a></li>
                        <li><a href="#section-3" class="burger-menu_link">section 3</a></li>
                        <li><a href="#section-4" class="burger-menu_link">section 4</a></li>
                        <li><a href="#section-5" class="burger-menu_link">section 5</a></li>
                    </ul> 
                </div>
            </div>
               <section id="section-1">section 1</section>
               <section id="section-2">section 2</section>
               <section id="section-3">section 3</section>
               <section id="section-4">section 4</section>
               <section id="section-5">section 5</section>
        </main>
        <footer></footer>
        <script>
            document.querySelector('.menu-bar').addEventListener('click', function(){
    document.querySelector('.menu-bar span').classList.toggle('active');
    document.querySelector('.menu').classList.toggle('animate');
    
})
    </script>
</body>
</html>
