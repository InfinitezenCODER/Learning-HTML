# Learning-HTML
I am learning these from Shradha Khapra Mam (APNA_COLLEGE).
<br>
Author-InfinitezenCODER
<BR>
<!DOCTYPE html>

<html lang="en" style="
 font-style: oblique">
 
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <titl>MY EXPERIMENTS</titl></title>
</head>
<br>
<body>
<!--This is Paragraph-->
 <a href="/Education.html">Education</a>
<br>
<a href="/Skills.html">Skills</a>
<br>
<a href="/Experience.html">Experience</a>
<br>
<a href="/Control.html">Control</a>   

<header style=" background-color:rgb(152, 221, 244);">
   <h1><b> MY PORTFOLIO </b></h1> 
</header>
<main>
    <section> education: COLLEGE(VSSUT)  SCHOOL(NK NAGAR)</section>
    <section> Languages: Python,C,HTML</section>
    <section> Experience: Fresher</section>
    <article> My Story : "Initialization of Coding in my LIFE."</article>
    <aside>  This is not content-related.</aside> 
    <div>
    A Passionate Coder.
    A Curious Learner.
    A Future Developer.
    </div>
    <div>
    A Marathon Rider.
    A Lover.
    A big Dreamer.
    A Zlatan Ibrahimovic Fan.
    </div>
</main>    
<header style=" background-color:rgb(152, 221, 244);">
<h1><b> MY JEE PREPARATION </b></h1>
</header>
<main>
    <section> coaching: MOTION ONLINE , PHYSICS WALLAH</section>
    <small> Favourite Teacher - Gavesh Bhardwaj, Mohit Sir </small> 
    <img src="https://www.google.com/imgres?q=gb%20sir%20maths&imgurl=https%3A%2F%2Fyt3.ggpht.com%2Fo7I2PDwXhSWf5i4a4pzB72vbW4ym4HvRqaLSYrbFx2a-vNQQkrrvXSSlpMTH_1AdAvITFfonCqQ%3Ds800-c-k-c0x00ffffff-no-rj&imgrefurl=https%3A%2F%2Fwww.speakrj.com%2Faudit%2Freport%2FUCjILZDfCFrqeU1EQrAm_ZPw%2Fyoutube%2Flive&docid=do6yigKhtRNytM&tbnid=uieyUIRaJCCpDM&vet=12ahUKEwj6juyngIiQAxWrZWwGHQQTGKkQM3oECCQQAA..i&w=800&h=800&hcb=2&ved=2ahUKEwj6juyngIiQAxWrZWwGHQQTGKkQM3oECCQQAA" alt="#GB sir" height="150"/>
    <br>
    <section> Subjects: PHYSICS,CHEMISTRY,MATHS</section>
    <small> Favourite Subject - PHYSICS </small>
    <br>
    <section> Rank:  AIR 115k , Percentile: 93 </section>
    <article> My Story : "Never Give Up."</article>
<ol>
     <li>PHYSICS</li>
       <ul>
         <li>Class NOTES</li>
        <li>Rank UP PHYSICS</li>
        <li>HC VERMA</li>
       </ul>
     <li>Mathematics</li>
        <ul>
         <li>Class NOTES</li> 
         <li>Arihant</li>
         <li>Mathongo</li>
        </ul>  
     <li>Chemistry</li>
     <ul>
        <li>Class NOTES</li>
        <li>VK Jaiswal</li>
     </ul>   
    </ol>
</main>
<table>
   <caption><b> Percentile in each subject</b> </caption>
 <thead>
    <tr>
        <th>Subject</th>
        <th>Percentile</th>
    </tr>
 </thead>
 <tbody>
    <tr>
        <td>Physics</td>
        <td>93.64</td>
    </tr>
    <tr>
        <td>Chemistry</td>
        <td>90.23</td>
    </tr>
    <tr>
        <td>Mathematics</td>
        <td>89.56</td>
    </tr>
 </tbody>
</table>
<table>
    <tr>
        <th colspan="2">Informations</th>
    </tr>
    <tr>
        <td>Physics</td>
        <td>93.64</td>
    </tr>
    <tr>
        <td>Chemistry</td>
        <td>90.23</td>
    </tr>
    <tr>
        <td>Mathematics</td>
        <td>89.56</td>
    </tr>

</table>
 
<form action="/action.php">
    <input type="text" placeholder=" Name">
    <input type="password"placeholder="Password">
    <input type="email"placeholder="Email">
    <br>
    <label for="01">
    <input type="radio"value="Undergraduate" name="class" id="01">UG
    <br>
    <label for="02">
    <input type="radio"value="Postgraduate" name="class" id="02">PG
    
</form>


</body>
</html>
<br> <br> <br> <br>
<br>
I am learning Javascript...
<br>
Connect JS to HTML as HTML is already connected to Browser.
<br>

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>
<body></body>
<script src="First.js">
 
</script>
</html>

First.js -

console.log("This is my first  Javascript Program");
let name="InfinitezenCODER";
console.log(name);
x= null;
console.log(x);
y=undefined;
console.log(y);
{
let age=19;
console.log(age);
}
{
let age=20;
console.log(age);
}
const Student=
{
fullNmae : "Swastik",
fan : "Zlatan Ibrahimnovic",
age : 19,
};
console.log(Student.Fan);
console.log(Student["age"]);
Student["age"]= Student["age"]+2;
console.log(Student.age);

console.log(Student.age);
const Profile = 
{
    User_name : "shradhakhapra",
    isFollow : true,
    Posts : 195,
    Followers : 569000 ,
    Following : 4 ,
    Name : "Shradha_Khapra",
    Profession : "Enterpreneur" ,
    Experience : "Ex-Microsoft_DRDO" ,
    Instituition : "Apnacollege" ,
    Moto : "TO EDUCATE SOMEONE IS THE HIGHEST PRIVILEGE" , 
}
console.log (Profile.Name);
console.log (Profile ["Experience"]);

// This Part Will Not be Executed.
/* This Part Will not be Executed. */

//Arithmatic Operators
let a = 2;
let b = 4;

console.log("a+b");
console.log(a+b);
console.log("a+b =", a+b);
console.log("a-b =", a-b);
console.log("a*b =", a*b);
console.log("a/b =", a/b);
console.log("a%b =", a%b);
console.log("a**b =", a**b);
console.log("a++=", a++);
console.log("a=", a);
console.log("++a=", ++a);

//Assignment Operators
let c = 10;
c+=5;
console.log("c+=5 =", c);
c-=5;
console.log("c-=5 =", c);
c**=2;
console.log("c**=2",c);

















