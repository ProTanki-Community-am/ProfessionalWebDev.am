# ProfessionalWebDev.am
<!DOCTYPE html>
<html lang="ru">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Professional WebDev</title>
    <meta property="og:site_name" content="MiDeev - сайт о созерцании и познании истинности души MiDeev'a">
    <meta property="article:author" content="https://github.com/MiDeev">
    <meta name="description"
        content="Здесь Вы сможете ознакомиться с жизненным путём и самопознанием автора данного сайта - MiDeev'a.">
    <meta property="og:title" content="MiDeev - сайт о жизни автора.">
    <meta property="og:type" content="website">
    <meta property="og:image" content="https://raw.githubusercontent.com/MiDeev/MiDeev-ru/master/MiDeevPre.png">
    <meta property="og:image:secure_url"
        content="https://raw.githubusercontent.com/MiDeev/MiDeev-ru/master/MiDeevPre.png">
    <meta property="og:url" content="https://mideev.ru/">
    <meta property="og:description"
        content="Здесь Вы сможете ознакомиться с жизненным путём и самопознанием автора данного сайта - MiDeev'a.">
    <meta property="url" content="https://mideev.ru/">
    <meta property="name" content="MiDeev - сайт о жизни автора.">
    <meta property="description"
        content="Здесь Вы сможете ознакомиться с жизненным путём и самопознанием автора данного сайта - MiDeev'a.">
    <meta property="image" content="https://raw.githubusercontent.com/MiDeev/MiDeev-ru/master/MiDeevPre.png">
    <meta itemprop="url" content="https://mideev.ru/">
    <meta itemprop="name" content="MiDeev - сайт о жизни автора.">
    <meta itemprop="description"
        content="Здесь Вы сможете ознакомиться с жизненным путём и самопознанием автора данного сайта - MiDeev'a.">
    <meta itemprop="image" content="https://raw.githubusercontent.com/MiDeev/MiDeev-ru/master/MiDeevPre.png">
    <meta content="#ff4444" data-react-helmet="true" name="theme-color" />
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css" integrity="sha512-iecdLmaskl7CVkqkXNQ/ZH/XLlvWZOJyj7Yy7tcenmpD1ypASozpmT/E0iPtmFIB46ZmdtAc9eNBvH0H/ZpiBw==" crossorigin="anonymous" referrerpolicy="no-referrer" />
    <link rel="icon" href="logo.png">
    <link rel="stylesheet" href="bg.css">
    <link rel="stylesheet" href="style.css">
    <link rel="stylesheet" href="silka.css">
    <link rel="stylesheet" href="svg.css">
    <link rel="icon" type="image/png" sizes="32x32" href="pa3os.gif">
  
    
    <style>
        #home:before {
            position: absolute;
            content: "";
            width: 100%;
            border-bottom: 3px solid #f52;
            border-radius: 2px;
            transition: width 0.3s ease-in-out, left 0.3s ease-in-out;
            left: 0%;
            bottom: 25px;
        }

        #menu>li>#home {
            color: #fff;
        }

    </style>
</head>



</body>
</html>


<body>
    <div class="navbar">
         <img src="logo.png" class="logo-img" alt="Logo">
        <input type="checkbox" id="checkbox">
        <nav>
            <span id="log">ProfessionalWebDev.am</span>
            <ul id="menu">
                <li><a id="Գլխավոր" href="#">Գլխավոր</a></li>
                <li><a id="ProTanki Community AM" href="https://protanki-community-am.github.io/ProTanki.Community.AM/">ProTanki Community AM</a></li>
                <li><a id="նախագծի մասին" href="Project.html">նախագծի մասին</a></li>
                <li><a id="Discord" href="https://discord.gg/gJfDX6nD">Discord</a></li>
                <li><a id="captcha" href="Captcha.html">Captcha</a></li>
            </ul>

            <div class="pc">
                <div class="pb" id="mb"></div>
            </div>

            <label for="checkbox">
                <svg class="menu-icon ham hamRotate ham8" viewBox="0 0 100 100" width="80"
                    onclick="this.classList.toggle('active')">
                    <path class="line top"
                        d="m 30,33 h 40 c 3.722839,0 7.5,3.126468 7.5,8.578427 0,5.451959 -2.727029,8.421573 -7.5,8.421573 h -20" />
                    <path class="line middle" d="m 30,50 h 40" />
                    <path class="line bottom"
                        d="m 70,67 h -40 c 0,0 -7.5,-0.802118 -7.5,-8.365747 0,-7.563629 7.5,-8.634253 7.5,-8.634253 h 20" />
                </svg>
            </label>
        </nav>
    </div>

    <div class="welcome">Professional WebDev<br>
        <div class="bord">Scoial Links</div>
    </div>

    <div class="main">
        <div class="sites">
            <div class="welcome">ProfesionalWebDev<br>
                <div class="bord">Social Links</div>
            </div>
            <div class="links">
                <div class="yt">
                    <a href="https://youtube.com/@Professional1297">YouTube</a>
                </div>
                <div class="gh">
                    <a href="https://github.com/ProTanki-Community-am">GitHub</a>
                </div>
                <div class="dc">
                    <a href="https://discord.gg/gJfDX6nD">Discord</a>
                </div>
                <div class="vk">
                    <a href="https://vk.com/id785725619">VK</a>
                </div>
                <div class="tg">
                    <a href="https://web.telegram.org/a/#-1926947977">Telegram</a>
                </div>
            </div>
        </div>
    </div>

  
           
   

    <div class="copyright">© 2023 ProfessionalWebDev</div>

    <script>
        window.onscroll = function () { scroll() };

        function scroll() {
            let winScroll = document.body.scrollTop || document.documentElement.scrollTop;
            let height = document.documentElement.scrollHeight - document.documentElement.clientHeight;
            let scrolled = (winScroll / height) * 100;
            document.getElementById("mb").style.width = scrolled + "%";
        }
        
    </script>

</body>

</html>
