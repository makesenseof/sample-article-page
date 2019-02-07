<!DOCTYPE html>

<html>

<head>

      <meta charset="utf-8">

      <title> Your title here  </title>

      <style>

      #menu{

        background-color: gray;

        height:100px;

        width:100%;

        border-radius: 20px;


      }

      #home{

        border-radius: 20px;


      }

      #ts{

        position: absolute;
        left: 1000px;

        width: 200px;

        color: black;

        font-size: 30px;

        text-align: center;

        background-color: white;

        border-bottom-right-radius: 25px;

        border-bottom-left-radius: 25px;

        padding-left: 15px;

      }

      #a1{

        background-color: black;

        color: white;

        text-align: center;

        font-size: 30px;

        position: absolute;
        left: 1310px;
        top: 62px;

        height: 35px;
        width: 50px;

        border-bottom-left-radius: 10px;

        border-top-left-radius: 10px;


      }

      #a2{

        background-color: black;

        color: white;

        text-align: center;

        font-size: 35px;

        position: absolute;
        left: 1365px;
        top: 62px;

        height: 35px;
        width: 50px;

        border-bottom-right-radius: 10px;

        border-top-right-radius: 10px;

      }

      #font{

        font-size: 45px;

        color: black;

        font-family: monospace;

        position: absolute;
        left: 820px;
        top: 52px;

      }

      #c1{

        background-color: white;

        border: 3px solid black;

        border-radius: 10px;

        position: absolute;
        left: 980px;
        top: 60px;

        height: 35px;
        width: 60px;

      }

      #c2{

        background-color: rgb(249 , 242 , 226);

        border: 3px solid rgb(84 , 49 , 24);

        border-radius: 10px;

        position: absolute;
        left: 1050px;
        top: 60px;

        height: 35px;
        width: 60px;

      }

      #c3{

        background-color: rgb(74 , 74 , 77);

        border: 3px solid rgb(215 , 215 , 216);

        border-radius: 10px;

        position: absolute;
        left: 1120px;
        top: 60px;

        height: 35px;
        width: 60px;

      }

      #c4{

        background-color: rgb(18 , 18 , 18);

        border: 3px solid rgb(176 , 176 , 176);

        border-radius: 10px;

        position: absolute;
        left: 1190px;
        top: 60px;

        height: 35px;
        width: 60px;

      }

      #make{

        font-size: 60px;

        position: absolute;
        left: 300px;
        top: 10px;

        font-family: cursive;

        color: white;




      }

      #sense{

        font-size: 50px;

        position: absolute;
        left: 450px;
        top: 20px;

        font-family: cursive;

        color: white;

      }

      #of{

        font-size: 40px;

        position: absolute;
        left: 580px;
        top: 30px;

        font-family: cursive;

        color: white;

      }

      body{

        background-color: white;

      }

      h1{

        text-align: center;

        font-size: 40px;

        position: relative;
        top: 10px;

      }

      article{

        line-height: 1.5;

        position: absolute;
        top: 120px;

        background-color: black;

        color: white;

        margin: auto;

        font-size: 30px;

        border-radius: 20px;

        width: 99%;

        font-family: palatino;

        text-align: center;

      }



      </style>





</head>


<body>

<div id = "menu">

<img onclick="myFunction()" id = "home" border="0" alt="Go To Home" src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcTek9c0UWQLsoy8B3QX_mpf6ECtUAxNTh1LNzUHonucNLguGdrg" height="100" >



<span id = "ts">Text   Settings .</span>

<span id = "a1">A</span>

<span id = "a2">A</span>

<span id = "font">Font</span>

<span id = "c1"></span>

<span id = "c2"></span>

<span id = "c3"></span>

<span id = "c4"></span>

<span id = "make">Make</span>

<span id = "sense">Sense</span>

<span id = "of"> Of      . . .</span>




</div>


<article id = "content">

  <h1>Playful spirit</h1>




  In the first, Feynman flaunted his rough edges and eccentricities, and much of the book is hilarious. (One story sees him bungling a sprinkler experiment in the cyclotron laboratory at Princeton University in New Jersey, shattering glass tubes and flooding the space with water.)</br></br> The chronicles of Feynman’s Los Alamos days are exceptionally funny, such as his removal of the secret contents of physicist Edward Teller’s locked desk drawer after Teller told him it was impenetrable. However, the book shows its age in disturbingly sexist sections such as “You just ask them?”, about his predatory behaviour towards women.</br></br>
  His relationships with women were complicated. In What Do You Care, he explained how he encouraged his younger sister Joan, now an acclaimed astrophysicist, to go into science. And he recounted how many of his attitudes had been shaped by his love for his first wife, Arline, who died of tuberculosis in 1945, a few years after they married. Those stories were mostly written during the final stages of Feynman’s life, after he had undergone treatment for cancer. By that point he had undoubtedly become more cognizant of his legacy.



</article>

<script src="https://ajax.googleapis.com/ajax/libs/jquery/2.1.4/jquery.min.js"></script>

<script>


var cone = function(){

$("article").css("background-color", "white");

$("article").css("color", "black");

$("body").css("background-color" , "black");

}

var ctwo = function(){

$("article").css("background-color", "rgb(249 , 242 , 226)");

$("article").css("color", "rgb(84 , 49 , 24)");

$("body").css("background-color" , "black");

}

var cthree = function(){

$("article").css("background-color", "rgb(74 , 74 , 77)");

$("article").css("color", "rgb(215 , 215 , 216)");

$("body").css("background-color" , "rgb(249 , 242 , 226)");

}

var cfour = function(){

$("article").css("background-color", "rgb(18 , 18 , 18)");

$("article").css("color", "rgb(176 , 176 , 176)");

$("body").css("background-color" , "white");

}


$("#c1").on("click" , function(){

cone();

})

$("#c2").on("click" , function(){

ctwo();

})

$("#c3").on("click" , function(){

cthree();

})

$("#c4").on("click" , function(){

cfour();

})

$("#home").on("click" , function(){

cfour();

})

function myFunction() {
  location.replace("https://makesenseof.github.io/")
}

</script>


</body>



</html>
