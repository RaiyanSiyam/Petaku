<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Kitty Food</title>
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link rel="stylesheet" href="C:\Users\raiya\OneDrive\Desktop\New folder\main1.css">
</head>
<body>
  
        <div class="wrap">
            <header>
                <div class="header-left">
                    <a href="#">
                        <img src="C:\Users\raiya\OneDrive\Desktop\New folder\petaku1.png" alt="PEtaku Logo">
                    </a>
                    <div class="divider hide-mobile"></div>
                    <a href="#" class="home hide-mobile"><h3>Home</h3></a>
                </div>
    
                <nav>
                    <a href="#" class="menu-open hide-desktop">
                        <img src="menu.svg" alt="Open menu">
                    </a>
                    <ul>
                        <li class = "hide-desktop">
                            <a href="#" class="menu-close">
                                <img src="close.svg" alt="Close menu">
                            </a>
                        </li>
                        <li><a href="#">Our Food</a></li>
                        <li><a href="#">Doctors</a></li>
                        <li><a href="#">Toys</a></li>
                        <li><a href="#">FAQ</a></li>
                    </ul>
                </nav>
            </header>
    
            <main>
                <h1>Your pet will go <img src="bonkers.svg" alt="Text that says bonkers"></h1>
                <p class="subhead" style ="font-family: 'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif;">
                   <h3>..Your one stop solution for all the problems 
                    you face with you pets.</h3> 
                    
                </p>
                <a href="#" class="primary-cta">Get Bonkers</a>
            </main>
    
            <div class="cat-container">
                <div class="cat">
                    <img src="cat.png" alt="Cat illustration">
                    <div class="inner-circle"></div>
                    <div class="outer-circle"></div>
                </div>
            </div>
        </div>
    
        <script> 

            const menu = document.querySelector('nav ul');
            const menuBtn = document.querySelector('.menu-open');
            const closeBtn = document.querySelector('.menu-close');

            menuBtn.addEventListener('click', ()=>{
                menu.classList.add('open')
            } )
            closeBtn.addEventListener('click', ()=>{
                menu.classList.remove('open')
            } )


        </script>
        
    

</body>
</html>
