# Alexander Burnas

**mailto:** [Google](78burnog@gmail.com)

## Summary.
One year ago, I began to study Web programming on *HTML/CSS/JavaScript*. 
I learn from Timur Semshedinov’s lectures on YouTube, online courses on CourseHunters website and SoloLearn mobile application. 
Also I have an account on `CodeWars`, where I solve programming problems. 
In your courses I want to learn how to create dynamic Web applications in JavaScript. 
In the future I want to become a Web-developer and get a good offer in one of the popular companies.

## Skills
* HTML5/CSS3/JS (Foundation, Bootstrap 4)
* GitHub, Sublime, VS Code
* C++

### My code examples

 **Here’s an example of HTML code**
 
 ```<main class="main">    	
        <section class="big">
            <h2 class="big_furniture">furniture</h2>
            <h2 class="big_d">d</h2>
            <h2 class="big_decor">decor</h2>
        </section>
         <section class="section section_elips">
            <div class="wq">
                <h3 class="grid_1_h3" align="center">wooder - is quality</h3>
                <img class="image_6_2" src="img/pryamougol_17.png" alt="">
                <p align="center">We create unique design objects made of rare wood, specially under the otder. Look at the short video about our work.</p>
            </div>
            <div class="elipsis">
                 <div class="elipsis_3div">
                    <img  src="img/play46.png" alt=""> 
                    <img class="elipsis_img"  src="img/image_6_8.png" alt="">
                    <h5>innovative design</h5>
                 </div>
                 <div class="elipsis_3div play47" >
                    <img   src="img/play47.png" alt=""> 
                    <img class="elipsis_img" src="img/image_6_8.png" alt="">
                    <h5>high-level skills</h5>
                 </div>
                 <div class="elipsis_3div">
                    <img  src="img/play48.png" alt=""> 
                    <img  class="elipsis_img" src="img/image_6_8.png" alt="">
                    <h5>quality products</h5>
                 </div>
            </div>
        </section>
    </main>
    <footer>
        <div>
            <img src="img/DSC_1007_2000.png" alt="">
            <div class="foot_flex ">
            <span class="srift_sp">© 2016 WOODER</span>               
                    <h3 class="logoh3 logo prox_nova_bold foot_pram_h3 ">wooder</h3>
            <div>
                <span class="srift_sp">Designed by </span><span class="viacheslav"> Viacheslav Olianishyn</span></div>
            </div>
            <img class="foot_pram" src="img/pram.png" alt="">
        </div>
    </footer> 
```

**Here’s an example of CSS code**
```
@import url('https://nomail.com.ua/font/Proxima%20Nova');
@import url('https://nomail.com.ua/family/Myriad%20Pro');
@font-face { font-family: 'MyriadPro-Regular';  src: local('MyriadPro-Regular'), url('https://nomail.com.ua/files/woff/17caf3268902de9c59e505297508ecdb.woff') format('woff'); }

* {
-webkit-box-sizing: border-box;
-moz-box-sizing: border-box;
box-sizing: border-box;
}

*{	
	margin: 0 auto;
	padding: 0;
}
.body, .header{	
	max-width: 360px;
    min-width: 1920px;
}
.elipsis{
	display: -webkit-box;
	display: -ms-flexbox;
	display: flex;
	-ms-flex-pack: distribute;
	justify-content: space-around;
}
.elipsis_3div{
	display: -webkit-box;
	display: -ms-flexbox;
	display: flex;
	-webkit-box-orient: vertical;
	-webkit-box-direction: normal;
	-ms-flex-direction: column;
	 flex-direction: column;
	-webkit-box-align: center;
	-ms-flex-align: center;
	 align-items: center;
	 margin-top: 57px;
}
.foot_pram_h3{
	margin: 0 -123px 0 -124px;
}
.foot_pram{
	margin: -32px 832px;
}
.viacheslav{
	font-family: 'Proxima Nova Regular', sans-serif;
    text-transform: unset;
    font-size: 15px;
	color: #5b5b5b;
}

@media screen and (max-width: 70em){	
	.elips_1, .elips_4, .one_01 {
		display: none;
	}
	.logo{
		color: yellow;
	}
	.decor img, .letter_w h2 {
		display: none;
	}
}   
@media screen and (max-width: 50em){	
	#wood_h1{
		font-size: 4em;
		letter-spacing: 10px;
	}
} 
```
**Here’s an example of JS code**
```
var parameters = {
  target: '#myFunction',
  data: [{
    fn: 'sin(x)', 
    color: 'red'
 }],
  grid: true,
  yAxis: {domain: [-1, 1]},
  xAxis: {domain: [0, 2*Math.PI]}
};

function plot() {
  var f = document.querySelector("#function").value;
  var xMin = document.querySelector("#xMin").value;
  var xMax = document.querySelector("#xMax").value;
  var yMin = document.querySelector("#yMin").value;
  var yMax = document.querySelector("#yMax").value;
  var color = document.querySelector("#color").value;
  
  parameters.data[0].fn = f;
  parameters.xAxis.domain = [xMin, xMax];
  parameters.yAxis.domain = [yMin, yMax];
  parameters.data[0].color = color;
  
  functionPlot(parameters);
}
```

### Education
* I have a higher technical education *[National Technical University of Ukraine «Igor Sikorsky Kyiv Polytechnic Institute»](https://kpi.ua/ru)*
* Basic course `Java` (two month)
* Online cource `HTML/CSS` (three month)

### English
My Level `A2`
