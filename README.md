# BIODATA BINTANG

<html>
    <head>
        <title>BIODATA</title>
        <style>
            * {
                box-sizing: border-box; 
            }
            body {
                width: 100%;
                overflow-x: hidden;
                background-color: white;
            }
            h1.judul {
                color: black; 
                font-family: 'Times New Roman'; 
                font-size: 20px; 
                text-align: left;
                vertical-align: left;
            }
            p.isi{
                color: black; 
                font-family: 'Times New Roman'; 
                font-size: 15px; 
                text-align: left;
            }
            ul.menu {
                list-style-type: none;
                margin: 0;
                padding: 0;
                overflow: hidden;
                background-color: grey;
            }
            li.menu {
                float: left;
            }
            li a.menu {
                display: block;
                color: white;
                text-align: center;
                padding: 14px 16px;
                text-decoration: none;
                font-size: 15px;
                font-family: 'Times New Roman';
            }
            li a:hover.menu {
                background-color: white;
            }
            .kotak-1 {
                width: 100%; 
                margin: 0; 
                padding: 20px; 
                background-color: white; 
                color: black; 
                text-align: center; 
                font-size: 24px; 
                vertical-align: center;
                border-radius: 10px;
                font-family: 'Times New Roman';
                
            }
            .gambar-1 {
                float: center;
                padding: 15px;
            }
            .main {
                display: flex;
                justify-content: left;
            }
            .gambar-2{
                border-radius: 50%;
                object-fit: cover;
                padding: 10px;
                display: flex;
                justify-content: left;
            }
            ul.projects {
                float: center;
                color: black;
                text-align: justify;
                font-size: 15px;
                font-family: 'Times New Roman', Times, serif;
            }
            li.projects {
                float: left;
            }
            li a.projects{
                color: black;
                text-align: justify;
                font-size: 15px;
                font-family: 'Times New Roman', Times, serif;
            }
            li a:link{
                color: black;
            }
            li a:visited{
                color: black;
            }
            html{
                scroll-behavior: smooth;
            }
            .kontak {
                margin: 5px;
                display: flex;
                justify-content: left;
            }
            #home{}
            #personal{}
            #projects{}
            #contact{}
        </style>
    </head>
    <body>
        <div class="kotak-1">
            <a class="gambar-1" href="#home">
                <img src=".\Biodata.png" alt="Biodataku" width="175px">
            </a>
            <ul class="menu">
                <li class="menu"><a class="menu" href="#personal">Biodata</a></li>
                <li class="menu"><a class="menu" href="#projects">Projects</a></li>
                <li class="menu"><a class="menu" href="#contact">Sosial Media</a></li>
            </ul>
        </div>
        <h1 class="judul" id="personal">Biodata</h1>
        <div class="main">
            <img src=".\WhatsApp Image 2022-10-30 at 23.42.48.jpeg" alt="Aku" class="gambar-1" width="230px" height="240px">
        </div>  
        <p class="isi">Nama Lengkap: Achmad Bintang Pamungkas</p>
        <p class="isi">Tanggal Lahir: 21 Maret 2022</p>
        <p class="isi">Tempat Lahir: Surakarta, Jawa Tengah, Indonesia</p>
        <p class="isi">Hobi: Olahraga</p>
        <h1 class="judul" id="projects">Projects</h1>
        <ul class="projects">
            <li><a href="./Biodata html.html">Html Biodata</a></li>
            <li><a href="./Form Pemesanan Jasa.html">Html Pemesanan Jasa</a></li>
        </ul>
        <h1 class="judul" id="contact">Sosial Media</h1>
        <div class="kontak">
        <a class="kontak" href="https://wa.me/6285729955389">
            <img src="https://w7.pngwing.com/pngs/922/489/png-transparent-whatsapp-icon-logo-whatsapp-logo-whatsapp-logo-text-trademark-grass-thumbnail.png" alt="WhatsApp" width="35px">
        </a>
        <a class="kontak" href="https://www.instagram.com/wobintang/">
            <img src="https://w7.pngwing.com/pngs/722/1011/png-transparent-logo-icon-instagram-logo-instagram-logo-purple-violet-text-thumbnail.png" alt="Instagram" width="35px">
        </a>
        </div>
    </body>
</html>

