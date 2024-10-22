# Landing-page
<html>
    <head>
        <title>LANDING PAGE</title>
    <style>
        *
{
    margin: 0;
    padding: 0;
}
body
{
    background: rgba(0, 0, 0, 0.7) url(image/bi.jpg);
    background-size: cover;
    background-blend-mode:darken;
    font-family: Cambria, Cochin, Georgia, Times, 'Times New Roman', serif;
}
.container
{
    display: flex;
    align-items: center;
    justify-content: space-between;
}
.container h1
{
    margin-left: 10px;
    color:rgb(227, 31, 17);
    font-size: 40px;
    padding: 10px;
}
.navbar ul li
{
    display: inline-block;
    padding: 18px;
}
.navbar ul li a
{
    text-decoration: none;
    color: chartreuse;
    padding:4px;
    font-size: 20px;
    font-family: 'Segoe UI', Tahoma, Geneva, Verdana;
    transition: 1.5s;
}
.navbar ul li a:hover
{
    background-color:rgb(131, 77, 182);
}
.content
{
    position: absolute;
    color:white ;
    top: 45%;
    left:13% ;
}
.content h2
{
    font-family: 'Trebuchet MS', 'Lucida Sans Unicode', 'Lucida Grande', 'Lucida Sans';
    font-size: 30px;
    margin-left: 26%;
}
.content h1
{
    font-size: 55px;
    margin-left:20% ;
}
.content p
{
    text-align:center ;
    margin-top: 17px;
    font-size: 20px;
}
    </style>
    </head>
    <body>
        <div class="container">
            <h1>YASHMI ORGANICS</h1>
            <div class="navbar">
                <ul>
                    <li><a href="#">HOME</a></li>
                    <li><a href="#">ABOUT</a></li>
                    <li><a href="#">GALLERY</a></li>
                    <li><a href="#">SERVICE</a></li>
                    <li><a href="#">CONTACT</a></li>                    
                </ul>
            </div>
        </div>
        <div class="content">
            <h2>Get Fresh Organic Products Here</h2>
            <h1>Be healthy with Yashmi</h1>
            <p>
                Organic is something we can all partake of and benefit from. When we demand organic, we are demanding poison
                free food.
            </p>
        </div>
    </body>
</html>
