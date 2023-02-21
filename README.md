<!DOCTYPE html>
<html>
<head>
<title>Blog post</title>
</head>
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<style>
* {
  box-sizing: border-box;
}
.row::after {
  content: "";
  clear: both;
  display: table;
}
[class*="col-"] {
  float: left;
  padding: 15px;
}
html {
  font-family: "Times New Roman", serif;
}
.header {
  background-color: #34e5be;
  color: #000000;
  padding: 15px;
}
.menu ul {
  list-style-type: none;
  margin: 0;
  padding: 0;
}
.menu li {
  padding: 8px;
  margin-bottom: 7px;
  background-color: #f00a98;
  color: #ffffff;
}
.menu li:hover {
  background-color: #0099cc;
}

.pc {
max-width:33.33%;
height:auto;
}


[class*="col-"] {
  width: 100%;
}
@media only screen and (min-width: 600px) {
  .col-s-1 {width: 8.33%;}
  .col-s-2 {width: 16.66%;}
  .col-s-3 {width: 25%;}
  .col-s-4 {width: 33.33%;}
  .col-s-5 {width: 41.66%;}
  .col-s-6 {width: 50%;}
  .col-s-7 {width: 58.33%;}
  .col-s-8 {width: 66.66%;}
  .col-s-9 {width: 75%;}
  .col-s-10 {width: 83.33%;}
  .col-s-11 {width: 91.66%;}
  .col-s-12 {width: 100%;}
  .pc {width: 8.33%;}
}
@media only screen and (min-width: 768px) {
  .col-1 {width: 8.33%;}
  .col-2 {width: 16.66%;}
  .col-3 {width: 25%;}
  .col-4 {width: 33.33%;}
  .col-5 {width: 41.66%;}
  .col-6 {width: 50%;}
  .col-7 {width: 58.33%;}
  .col-8 {width: 66.66%;}
  .col-9 {width: 75%;}
  .col-10 {width: 83.33%;}
  .col-11 {width: 91.66%;}
  .col-12 {width: 100%;}
   .pc {width: 12.33%;}
}
@media only screen and (max-width: 600px) {
  .secret {
    display: none;
}
@media print {
  .row::after { display: none; }
  .header { display: none; }
  .menu ul { display: none; }
  .menu li { display: none; }
  .li { display: none; }
  .ul { display: none; }
  .row { display: none; }
  .col-3 col-s-3 menu { display: none; }
}
</style>
</head>
<body>

<div class="header">
  <h1>A blogger's life</h1>
</div>

<div class="row">
  <div class="col-3 col-s-3 menu">
    <ul>
      <li>My weird dreams</li>
      <li>A new path in life</li>
      <li>How I deal with school</li>
      <li>About my friends</li>
    </ul>
  </div>

  <div class="col-6 col-s-9">
    <h1>A new course (BWD) </h1>
    <p>Basic web design is a course that thought me very useful stuff about how to make a website, but sometimes I get really confused and get stuck when doing some works. For example, medias queries was probably for me the hardest topic (I even had to watch A LOT of tutorials and website examples with my friend to do this page properly). But no matter what,I will never give up and learn from my mistakes. </p>
    <p>This course is also really cool because you can use your abilities to make fun things like a puzzles, staff page, scorecards, and many more! I recommend it a 100%! You can find this course at Catholic Virtual if you are interested (there are also other courses). </p>
  </div>

  <div class="secret">
<p> Secret random tip (you will only see this if you are on computer or big screen device!): If you decide to start the course and you need help, ask as much questions as you need!</p>
</div>

<img class="pc", src="https://i.imgur.com/qsjkYW0.png">
<img class="pc", src="https://i.imgur.com/3STnqhJ.png">
</body>
</html>
