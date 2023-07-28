- 👋 Hi, I’m @andikctistian
- 👀 I’m interested in ...
- 🌱 I’m currently learning ...
- 💞️ I’m looking to collaborate on ...
- 📫 How to reach me ...

<!---
andikctistian/andikctistian is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
HTML Result Skip Results Iframe
<!DOCTYPE html>
<html lang="en">
  <!-- Design by foolishdeveloper.com -->
<head>
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Auto slideshow</title>
    <!--Stylesheet-->
    <style media="screen">
      *{
    padding: 0;
    margin: 0;
    box-sizing: border-box;
}
body{
    background-color: #7aacff;
}
.container{
    width: 500px;
    position: absolute;
    transform: translate(-50%,-50%);
    top: 50%;
    left: 50%;
    overflow: hidden;
    border: 10px solid #ffffff;
    border-radius: 8px;
    box-shadow: 10px 25px 30px rgba(0,0,0,0.3);
}
.wrapper{
    width: 100%;
    display: flex;
    animation: slide 16s infinite;
}
@keyframes slide{
    0%{
        transform: translateX(0);
    }
    25%{
        transform: translateX(0);
    }
    30%{
        transform: translateX(-100%);
    }
    50%{
        transform: translateX(-100%);
    }
    55%{
        transform: translateX(-200%);
    }
    75%{
        transform: translateX(-200%);
    }
    80%{
        transform: translateX(-300%);
    }
    100%{
        transform: translateX(-300%);
    }
}
img{
    width: 100%;
}
    </style>
</head>
<body>
    <div class="container">
        <div class="wrapper">
            <img src="https://i.pinimg.com/originals/2b/de/de/2bdede0647e3cdf75b44ea33723201d9.jpg">
            <img src="https://images6.alphacoders.com/462/thumb-1920-462371.jpg">
            <img src="https://images5.alphacoders.com/343/thumb-1920-343645.jpg">
            <img src="https://cdn.wallpapersafari.com/24/98/dwMtqD.jpg">
        </div>
    </div>
</body>
</html>
