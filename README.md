- š Hi, Iām @veenashre
- š Iām interested in ...
- š± Iām currently learning ...
- šļø Iām looking to collaborate on ...
- š« How to reach me ...

<!---
veenashre/veenashre is a āØ special āØ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
---><!DOCTYPE html>
<html>
<head>
<meta name="viewport" content="width=device-width, initial-scale=1">
<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.7.0/css/font-awesome.min.css">
<link href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.7.0/css/font-awesome.min.css">
<title>Home</title>
<script>
    function search_movie() {
    let input = document.getElementById('searchbar').value
    input=input.toLowerCase();
    let x = document.getElementsByClassName('movie');
      
    for (i = 0; i < x.length; i++) { 
        if (!x[i].innerHTML.toLowerCase().includes(input)) {
            x[i].style.display="none";
        }
        else {
            x[i].style.display="list-item";                 
        }
    }
}</script>
<style>
     #list{
    font-size:  1.5em;
    margin-left: 300px;
    margin: right 0;
   }
   
</style>
</head>
<body>
    <div class= "container">
        <center><h1 style="color:blueviolet">Welcome to the Movie Mania!!!</h1>
            <h2>Search for your favourite movie to know more about it :)</h2>
        <input type="text" placeholder="Search.." name="search" style="width:20%">
        <button type="submit" style="width:5%" ><i class="fa fa-search";></i></button>
        <ol id='list'>
            <li class="movie">Garuda Gamana Vrishabha Vahana</li>
            <li class="movie">Ratnan Prapancha</li>
            <li class="movie">Vikrant Rona</li>
            <li class="movie">Ninna Sanihake</li>
            <li class="movie">Sakath </li>
            <li class="movie">Kurukshetra</li>
            <li class="movie">Roberrt</li>
            <li class="movie">Raajakumara</li>
            <li class="movie">Diyaa</li>
            <li class="movie">K.G.F: Chapter 1 </li>
            <li class="movie">Salaga</li>
        </ol>
          
        <!-- linking javascript -->
        <script src="./movie.js"></script>
    </center>
    </div>
    
</body>
</html>

