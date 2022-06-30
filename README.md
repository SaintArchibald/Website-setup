# Website-setup
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My Website</title>
    <link rel="stylesheet" type="text/css" href="css/style.css">
</head>
<body>
    <header id="main-header">
        <div class="cointainer">
            <h1> My Website</h1>
        </div>
    </header>

    <nav id="navbar">
        <div class="cointainer">
            <ul>
                <li> <a href="#">Home</a></li>
                <li> <a href="#">about</a></li>
                <li> <a href="#">services</a></li>
                <li> <a href="#">Contact</a></li>
            </ul>
        </div>
    </nav>

    <section id="showcase">
        <div class="cointainer">
            <h1> Grows with your child  </h1>
        </div>
    </section>

<div class="cointaner">
    <section id="main">
        <h1> welcome</h1>
        <p>Grows with your child from forward-facing harness (22-65 lb) to highback booster (40-100 lb) to backless booster (40-100 lb) - No-Rethread Simply Safe Adjust Harness System allows the headrest and harness to adjust together in one motion
            Grows with your child from forward-facing harness (22-65 lb) to highback booster (40-100 lb) to backless booster (40-100 lb) - No-Rethread Simply Safe Adjust Harness System allows the headrest and harness to adjust together in one motion
            Grows with your child from forward-facing harness (22-65 lb) to highback booster (40-100 lb) to backless booster (40-100 lb) - No-Rethread Simply Safe Adjust Harness System allows the headrest and harness to adjust together in one motion
        </p>
    </section>
    
    <aside id="sidebar">
        <p>Grows with your child from forward-facing harness (22-65 lb) to highback booster (40-100 lb) to backless booster (40-100 lb) - No-Rethread Simply Safe Adjust Harness System allows the headrest and harness to adjust together in one motion</p>
    </aside>
</div>
<footer id="main-footer">
    <p>copyright &copy; 2017 My website </p>
</footer>
</body>
</html>

STYLE.CSS LAYOUT 

*{margin: 0;
padding: 0;
box-sizing: border-box;
}
body{ 
    background-color: #f4f4f4;
    color:#555;
    font-family: 'Courier New', Courier, monospace;
    font-size: 16px;
    line-height: 1.6em;
    margin: 0;
}

.cointaner{
    width: 80%;
    margin: auto;
    overflow: hidden;
}

#main-header{
    padding: 20px;
    background-color: coral;
    color: #fff;
}

#navbar{
    background-color: #333;
    color: #fff;
}

#navbar ul{
    padding: 0;
    list-style: none;
}

#navbar li{
    display: inline;
}

#navbar a{
    text-decoration: none;
    font-size: 18px;
    padding-right: 15px;
}

#showcase{
    background-image: url(../css/bunny.jpg);
    background-position: center right;
    height: 225px;
    margin-bottom: 30px;
    text-align: center;
}

#showcase h1{
    color: #fff;
    font-size: 50px;
    line-height: 1.6m;
    padding-top: 30px;
}

#main{
    float: left;
    width: 70%;
    padding:0 30px;
    box-sizing: border-box;
}

#main{
    float: right;
    width: 30%;
    background: #333;
    color: #fff;
    padding:10px;
    box-sizing: border-box;
}

#main-footer{
background: #333;
color: #fff;
text-align: center;
margin-top: 40px ;
}

@media (max-width= 600px){
    #main {
        width: 100%;
        float: none;
    }
    #sidebar {
        width: 100%;
        float: none;
    }
}
/* CENTER CSS CONTENT 
.contaner{
    width: 100px;
    height: 600pxpx;
    border: 2px solid red;
    display: flex;
    flex-direction: column;
    align-items: center;
    justify-content: center;
}
.box{
    width: 100px;
    height: 100px;
    border: 2px solid black;
}
*/
