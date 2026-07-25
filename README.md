</DOCTYPE html>
<html>
    <head>
        <meta charset="utf-8"/>
       <title>buscador gogle</title>
       <link rel="stylesheet" href="ESTILOS.CSS"/>
    </head>
    <body>
        <header>
            <nav>
                <ul class="nav-right-section">
                    <li>
                        <a href="">Gmail</a>
                    </li>
                    <li>
                        <a href="">Imagenes</a>
                    </li>
                    <li class="menu-icon">
                        <a href=""></a>
                    </li>
                    <li>
                        <a href="">
                            <img src="https://lh3.googleusercontent.com/ogw/AF2bZyjnvuT06261Ar3rsFQQH2dxMqST3zP3-UhcuOBzn4F5_g=s32-c-mo" alt="foto perfil">
                        </a>
                    </li>
                </ul>
            </nav>
        </header>
        
        <main>
            <section class="main-logo">
                <img src="https://1000marcas.net/wp-content/uploads/2020/02/Google-Logo.png" alt="">
            </section>

            <section class="main-input">
                <div class="main-input-container">
                    <span class="search-icon"></span>
                    <input type="text">
                    <a class="micro-icon" href=""></a>
                </div>
            </section>

            <section class="main-buttons">
                <div>
                    <button>buscar con google</button>
                </div>
                <div> 
                    <button>me siento emocionada</button>
                </div>
            </section> 
        </main>

        <footer>
            <ul class="footer-left">
                <li>
                    <a href="">Sobre Google</a>
                </li>
                <li>
                    <a href="">Publicidad</a>
                </li>
                <li>
                    <a href="">Negocios</a>
                </li>
                <li>
                    <a href="">Cómo Funciona la Búsqueda</a>
                </li>
            </ul>

            <ul class="footer-right">
                <li>
                    <a href=""> Privacidad</a>
                </li>
                <li>
                    <a href="">Condiciones</a>
                </li>
                <li>
                    <a href="">Configuración</a>
                </li>
            </ul>
        </footer>
    </body>
</html>


body{
    margin: 0;
    padding: 0px;
    font-family: Arial, Helvetica, sans-serif;
    font-size: 13px;
}

a{
    text-decoration: none;
    cursor: pointer;
}

header{ 
    width: 100%;
    height: 60px;
}

header nav{
    display: flex;
    justify-content: flex-end;
}

header nav .nav-right-section{
    width: 200px;
    height: auto;
    display: flex;
    justify-content: center;
    list-style: none;
    align-items: center;
}

nav .nav-right-section a{
    margin-right: 10px;
    color: #000001;
}

nav .nav-right-section .menu-icon{
    background-image: url("https://static.thenounproject.com/png/756729-200.png");
    background-repeat: no-repeat;
    background-position: center;
    background-size: contain;
    width: 25px;
    height: 25px;  
}

nav .nav-right-section img{
    border-radius: 50%;
    margin-left: 10px;
}

main{
    /*margin-top: 100px;*/
    text-align: center;
}

main .main-logo{
    width: 530px;
    margin: 0 auto;
    margin-bottom: 35px;
}

main .main-logo img{
    width: 272px;
}

main .main-input{
    width: 530px;
    margin: 0 auto;
    margin-bottom: 35px;
}

main .main-input-container{
    width: 525px;
    border-radius: 100px;
    border: 1px solid #e1e2e6;
    display: flex;
    justify-content: center;
    align-items: center;
}

main .main-input input{
    width: 450px;
    height: 40px;
    border: none;
    outline: none;
}

main .main-input-container:hover{
box-shadow: 0 1px 6px 0 #20212447;
}

main .main-input .search-icon{
    background-image: url("https://e7.pngegg.com/pngimages/886/318/png-clipart-computer-icons-edison-state-community-college-google-search-symbol-magnifying-glass-material-logo-google-logo.png");
    background-repeat: no-repeat;
    background-position: center;
    background-size: contain;
    width: 18px;
    height: 18px;
}

main .main-input .micro-icon{
   background-image: url("https://images.icon-icons.com/2642/PNG/512/google_mic_logo_icon_159335.png");
    background-repeat: no-repeat;
    background-position: center;
    background-size: contain;
    width: 18px;
    height: 18px; 
    cursor: pointer;
}

main .main-buttons div{
    display: inline-block;
}

main .main-buttons button{
    height: 36px;
    background-color: #f8f9fa;
    border: none;
    font-size: 14px;
    color: #3c4043;
    border-radius: 5px;
    padding: 0 15px;
    margin-right: 10px;
}

main .main-buttons button:hover{
    border: 1px solid #dadce0;
    box-shadow: 1px #dadce0;
    color: #202124;
}

footer{
    width: 100%;
    height: 50px;
    position: absolute;
    bottom: 0;
    display: grid;
    grid-template-columns: 1fr 1fr;
    aling-items: center;
    background-color: #f2f2f2;
    border-top: 1px solid #e4e4e4;
}

footer ul{
    margin: 1opx;
    list-style: none;
    display: flex;
    padding-left: 0;
}

footer .footer-left{
    justify-content: left;
}

footer .footer-right{
    justify-content: right;
}

footer ul li a{
    margin: 10px;
    color: #5f6368;
}

