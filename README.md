# While
test
<!DOCTYPE html>
<head>
    <title>Home</title>
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link href='https://unpkg.com/boxicons@2.1.4/css/boxicons.min.css' rel='stylesheet'>
    <link rel="stylesheet" href="landing1.css">
</head>
<body>
    <header>
        <h3>Mobile</h3>
        <ul id="menu">
            <li><a href="">Home</a></li>
            <li><a href="">About</a></li>
            <li><a href="">Contact</a></li>
            <li><a href="">Gallery</a></li>
            <li><a href="">Service</a></li>
        </ul>
        <ul id="icon">
            <li><a href=""><i class='bx bx-user'></i></a></li>
            <li><a href=""><i class='bx bxl-facebook'></i></a></li>
            <li><a href=""><i class='bx bxl-twitter'></i></a></li>
            <li><a href="#navmenu" id="navmenu"><i class='bx bx-menu'></i></a></li>
        </ul>
    </header>


    <section id="container">
        <div class="content">
            <h2 class="text"><span>Explore</span><br>The Mobile</h2>
            <p>Lorem ipsum dolor sit, amet consectetur adipisicing elit. Ab, cum?</p>
            <button class="btn">Shop Now</button>
            <button class="btn">Order Now</button>
        </div>
    </section>

    <script>
let menu = document.querySelector("#navmenu");
let nav = document.querySelector("#menu");

menu.onclick = () => {
   menu.classList.toggle('bx-x');
    nav.classList.toggle('open');

}
    </script>










    </body>
    </html>
