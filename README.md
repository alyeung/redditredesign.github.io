<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <meta http-equiv="X-UA-Compatible" content="ie=edge">
  <link rel="stylesheet" href="reddit.css">
  <title>HTML Stucture</title>
</head>

<header>
  <div>
    <img src="reddit2.jpg" alt="">

 </div>

</header>

<body>

  <div id="container">
  <form>
  <label for="username">Username:</label>
  <input type="text" id="username" name="username">
  <label for="password">Password:</label>
  <input type="password" id="password" name="password">
  <div id="lower">
  <input type="checkbox"><label for="checkbox">Keep me logged in</label>
  <input type="submit" value="Login">
  </div>
  </form>
  </div>

<div id="mySidenav" class="sidenav">
  <a href="javascript:void(0)" class="closebtn" onclick="closeNav()">&times;</a>
  <a href="file:///Users/nelly2121/Desktop/Fewd/13_starter_interactions/interactions_pt_1/reddit%20redesign/hot_reddit">Hot</a>
  <a href="file:///Users/nelly2121/Desktop/Fewd/13_starter_interactions/interactions_pt_1/reddit%20redesign/rising_reddit">Rising</a>
  <a href="file:///Users/nelly2121/Desktop/Fewd/13_starter_interactions/interactions_pt_1/reddit%20redesign/controversial_reddit">Controversial</a>
  <a href="file:///Users/nelly2121/Desktop/Fewd/13_starter_interactions/interactions_pt_1/reddit%20redesign/subbreddits_reddit">Subreddits</a>
</div>

<div id="main">

<span style="font-size:30px;cursor:pointer" onclick="openNav()">&#9776;</span>
</div>

<script>
function openNav() {
    document.getElementById("mySidenav").style.width = "250px";
    document.getElementById("main").style.marginLeft = "250px";
    document.body.style.backgroundColor = "white";
}

function closeNav() {
    document.getElementById("mySidenav").style.width = "0";
    document.getElementById("main").style.marginLeft= "0";
    document.body.style.backgroundColor = "white";
}
</script>

<article>

  <a href="https://i.imgur.com/Ns7St4t.gif">
  <img border="0" alt="reddit" src="benwyatt.gif" width="100" height="100">
  <h1>Ben Wyatt is woke AF</h1>
      <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Eius soluta incidunt, eum quos consequuntur aliquam nobis velit mollitia iste, natus ex repellendus delectus quisquam et quae, in atque a. Perspiciatis excepturi ipsum temporibus, eius odit deleniti quasi voluptates eaque aliquam, iste consequatur repudiandae illo a. Voluptates eligendi reiciendis corporis itaque soluta fugit atque quaerat ipsum reprehenderit sapiente, voluptatem repellat eveniet fuga natus tempore modi vero distinctio nulla accusantium recusandae, omnis.</p>
      <link rel="stylesheet" type="text/css" href="style.css">
        <script type="text/javascript" src="reddit_pseudo.js"></script>
        <div class="box">
            <label for="qty"><abbr title="Quantity">Votes</abbr></label>
            <input id="qty" value="0" />
            <button id="up" onclick="modify_qty(upVote)">upvote</button>
            <button id="down" onclick="modify_qty(downVote)">downvote</button>

        </div>

        <h2>submitted by H2daizzo</h2>


<a href="https://imgur.com/5oCLk">
<img border="0" alt="reddit" src="breakingbad.jpg" width="100" height="100">
<h1>My wife made this awesome cake for my birthday today!</h1>
    <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Eius soluta incidunt, eum quos consequuntur aliquam nobis velit mollitia iste, natus ex repellendus delectus quisquam et quae, in atque a. Perspiciatis excepturi ipsum temporibus, eius odit deleniti quasi voluptates eaque aliquam, iste consequatur repudiandae illo a. Voluptates eligendi reiciendis corporis itaque soluta fugit atque quaerat ipsum reprehenderit sapiente, voluptatem repellat eveniet fuga natus tempore modi vero distinctio nulla accusantium recusandae, omnis.</p>
    <link rel="stylesheet" type="text/css" href="style.css">
      <script type="text/javascript" src="reddit_pseudo.js"></script>
      <div class="box">
          <label for="qty"><abbr title="Quantity">Votes</abbr></label>
          <input id="qty" value="0" />
          <button id="up" onclick="modify_qty(upVote)">upvote</button>
          <button id="down" onclick="modify_qty(downVote)">downvote</button>

      </div>

      <h2>submitted by randzy</h2>


<a href "https://i.redd.it/cu2u53gnhsg01.jpg">
<img border="0" alt="reddit" src="netflix.jpg" width="100" height="100">
  <h1>New image from Netflix's Post-Apocalyptic Zombie thriller 'Cargo'</h1>
   <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Eius soluta incidunt, eum quos consequuntur aliquam nobis velit mollitia iste, natus ex repellendus delectus quisquam et quae, in atque a. Perspiciatis excepturi ipsum temporibus, eius odit deleniti quasi voluptates eaque aliquam, iste consequatur repudiandae illo a. Voluptates eligendi reiciendis corporis itaque soluta fugit atque quaerat ipsum reprehenderit sapiente, voluptatem repellat eveniet fuga natus tempore modi vero  distinctio nulla accusantium recusandae, omnis.</p>
   <link rel="stylesheet" type="text/css" href="style.css">
    <script type="text/javascript" src="reddit_pseudo.js"></script>
    <div class="box">
        <label for="qty"><abbr title="Quantity">Votes</abbr></label>
        <input id="qty" value="0" />
        <button id="up" onclick="modify_qty(upVote)">upvote</button>
        <button id="down" onclick="modify_qty(downVote)">downvote</button>

      </div>

     <h2>submitted by unclecharlie_423</h2>


<a href="https://i.imgur.com/RFovKuM.jpg">
<img border="0" alt="reddit" src="dragonbones.jpg" width="100" height="100">
  <h1>Dragon bones by Stefan Koidl, digital, 2018.</h1>
    <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Eius soluta incidunt, eum quos consequuntur aliquam nobis velit mollitia iste, natus ex repellendus delectus quisquam et quae, in atque a. Perspiciatis excepturi ipsum temporibus, eius odit deleniti quasi voluptates eaque aliquam, iste consequatur repudiandae illo a. Voluptates eligendi reiciendis corporis itaque soluta fugit atque quaerat ipsum reprehenderit sapiente, voluptatem repellat eveniet fuga natus tempore modi vero  distinctio nulla accusantium recusandae, omnis.</p>
    <link rel="stylesheet" type="text/css" href="style.css">
    <script type="text/javascript" src="reddit_pseudo.js"></script>
    <div class="box">
        <label for="qty"><abbr title="Quantity">Votes</abbr></label>
        <input id="qty" value="0" />
        <button id="up" onclick="modify_qty(upVote)">upvote</button>
        <button id="down" onclick="modify_qty(downVote)">downvote</button>

      </div>


      <h2>submitted by 2fistedmario</h2>

    <a href="https://i.redd.it/6zjt6aslndo01.jpg">
    <img border="0" alt="reddit" src="puppy.jpg" width="100" height="100">
  <h1>Look who i found today</h1>
     <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Eius soluta incidunt, eum quos consequuntur aliquam nobis velit mollitia iste, natus ex repellendus delectus quisquam et quae, in atque a. Perspiciatis excepturi ipsum temporibus, eius odit deleniti quasi voluptates eaque aliquam, iste consequatur repudiandae illo a. Voluptates eligendi reiciendis corporis itaque soluta fugit atque quaerat ipsum reprehenderit sapiente, voluptatem repellat eveniet fuga natus tempore modi vero  distinctio nulla accusantium recusandae, omnis.</p>
     <link rel="stylesheet" type="text/css" href="style.css">
     <script type="text/javascript" src="reddit_pseudo.js"></script>
     <div class="box">
         <label for="qty"><abbr title="Quantity">Votes</abbr></label>
         <input id="qty" value="0" />
         <button id="up" onclick="modify_qty(upVote)">upvote</button>
         <button id="down" onclick="modify_qty(downVote)">downvote</button>

       </div>


       <h2>submitted by mrswoopie957</h2>


</article>

<footer>
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.7.0/css/font-awesome.min.css">
  <a href="https://www.reddit.com/r/facebook/" class="fa fa-facebook"></a>
  <a href="https://twitter.com/reddit?ref_src=twsrc%5Egoogle%7Ctwcamp%5Eserp%7Ctwgr%5Eauthor" class="fa fa-twitter"></a>
  <a href="https://www.reddit.com/r/Instagram/" class="fa fa-instagram"></a>

<hr/>


  <p><a href="">Use of this site constitutes acceptance of our User Agreement and Privacy Policy. © 2018 reddit inc. All rights reserved.

REDDIT and the ALIEN Logo are registered trademarks of reddit inc.</a></p>
</footer>


</body>
</html>
