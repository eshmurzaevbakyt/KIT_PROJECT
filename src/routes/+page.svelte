<body>
	<header>
        <div class="logo" href="#ll">IW</div>
        <div class="menu">
		<div class="menu-items">
            <nav>
            <a class="menu-item" href="About"><span>A</span><span>b</span><span>o</span><span>u</span><span>t</span></a>
            <a class="menu-item" href="Vitamins"><span>V</span><span>i</span><span>t</span><span>a</span><span>m</span><span>i</span><span>n</span><span>s</span></a>
            <a class="menu-item" href="https://www.drugwatch.com/testosterone/"><span>M</span><span>e</span><span>d</span><span>i</span><span>c</span><span>a</span><span>t</span><span>i</span><span>o</span><span>n</span><span>s</span></a>
            <a class="menu-item" href="https://www.muscleandstrength.com/workouts/muscle-strength-full-body-workout-routine"><span>T</span><span>&</span><span>M</span><span>S</span><span>e</span><span>s</span><span>s</span><span>i</span><span>o</span><span>n</span></a>
           <a class="menu-item" href="Contacts">Contacts</a>
           <a class="menu-item" href="News">News</a>
        </nav>
           <button class="hamburger">
            <div class="bar"></div>
           </button>
		</div>
    </div>
	</header>
    <nav class="mobile-nav">
        <a href="#">About</a>
        <a href="#">Vitamins</a>
        <a href="#">Medications</a>
        <a href="#">T&M Session</a>
    </nav>
	<main>
        <section class="hero">
            <h1>Enhancing Well-being with High-Quality Health Products</h1>
            <h2>Explore our carefully curated selection of medicines and vitamins, complemented by empowering courses and training programs, to aid you on your journey towards a healthier, more fulfilling life.</h2>
            <a class="learn-button" href="#benefits">Learn More</a>
            <!-- <a class="learn-button" href="javascript:void(0);" onclick="toggleCompanyInfo()">Learn More</a> -->
            <!-- <a class="buy-button" href="#buy">Buy</a> -->
        <!-- <div id="company-info" style="display: none;">
            <h3>About Our Company</h3>
            <p>At Instinctive Wellness Co, we're on a mission to reawaken the primal instincts within every modern man. We understand that in today's fast-paced world, men often find themselves disconnected from their inner strength, vitality, and purpose. That's why we've dedicated ourselves to providing a comprehensive solution to empower you to become the predator you were meant to be.</p>
        </div>         -->
        <!-- <script>
            function toggleCompanyInfo() {
                var companyInfo = document.getElementById("company-info");
                if (companyInfo.style.display === "none" || companyInfo.style.display === "") {
                    companyInfo.style.display = "block";
                } else {
                    companyInfo.style.display = "none";
                }
            }
        </script> -->
        </section>


	</main>
	<footer>
		(c) 2023 Instinctive Wellness Co.
	</footer>
    <!-- <script>
        function toggleMenu() {
            var menu = document.querySelector('.hamburger');
            menu.classList.toggle('show');
        }
    </script> -->
    <script src="./assets/main.js"></script>
</body>

<style>
    * {
    margin: 0px;
    padding: 0px;
    box-sizing: border-box;
}

body {
    height: 100%;
}

header {
    background-color: black;
    color: white;
    padding: 10px;
    display: flex;
    gap: 100px;
    font-size: 25px;
    flex-direction: row;
    justify-content: space-between;
    align-items: center;
}

footer {
    background-color: black;
    align-content: center;
    color: white;
    padding: 10px;
}

.hero {
    display: flex;
    flex-direction: column;
    justify-content: center;
    align-items: center;
    height: 100vh;
    color: white;
    background-image: linear-gradient(rgba(0, 0, 0, 0.5), rgba(0, 0, 0, 0.5)), url('https://secretcompass.com/wp-content/uploads/2018/01/Jungle-Rot.jpg');                
    background-size: cover;
    background-position: center;
}

.img-header {
    display: flex;
    flex-direction: column;
    justify-content: center;
    align-items: center;
    height: 100px;
    max-width: 900px;
}

.hero h1 {
    font-size: 40px;
    font-family: 'Arial', sans-serif; 
    text-align: center; 
    margin-bottom: 30px;
}

.hero h2 {
    font-size: 18px;
    color: white;
    text-align: center;
    align-self: center;
    margin-bottom: 30px;
    display: block;
    max-width: 400px;
}


.hero div {
    font-size: 28px;
    padding: 40px 20px 40px 20px;
}

.menu-items {
        display: flex; 
        padding: 0px 20px;
        gap: 20px; 
    }

    .menu-item {
        text-decoration: none;
        color: #fff;
        font-size: 16px;
        position: relative;
    }
    .menu-item span {
        transition: background-color 0.3s;
    }
    .menu-item:hover span {
    background-color: #fff;
    color: #444;
    }

    .learn-button {
        padding: 10px 20px; 
        background-color: #333;
        color: #fff;
        border: none; 
        border-radius: 5px;
        font-size: 16px;
        text-decoration: none;
        margin-right: 10px;
    }
    .learn-button:hover {
    background-color: #555;
    }

    /* .buy-button {
        padding: 10px 20px; 
        background-color: #333;
        color: #fff;
        border: none; 
        border-radius: 5px;
        font-size: 16px;
        text-decoration: none;
    }
    .buy-button:hover {
    background-color: #555;
    } */


#company-info h3 {
        color: #fff;
        margin-bottom: 10px;
    }

    #company-info p {
        color: #fff;
        display: block;
        max-width: 400px;
        margin: 0 auto;
    }

    .content { 
        margin-top: 80px;
    }
    .burger-menu {
    display: none;
    cursor: pointer;
}

.burger-menu div {
    width: 30px;
    height: 3px;
    background-color: white;
    margin: 6px 0;
    transition: 0.4s;
}

.menu {
    display: flex;
    gap: 100px;
}

.menu-items {
    display: flex;
    gap: 20px;
}

.hamburger {
    position: relative;
    display: block;
    width: 35px;
    cursor: pointer;

    appearance: none;
    background: none;
    outline: none;
    border: none;
}

.hamburger .bar, .hamburger:before, .hamburger:after {
    content: '';
    display: block;
    width: 100%;
    height: 5px;
    background-color: #fff;
    margin: 6px 0px;
    transition: 0.4s;
}

.hamburger.is-active:before {
    transform: rotate(-45deg) translate(-8px, 6px);
}

.hamburger.is-active:after {
    transform: rotate(45deg) translate(-9px, -8px);
}

.hamburger.is-active .bar {
    opacity: 0;
}

.mobile-nav {
    position: fixed;
    top: 0;
    left: 100%;
    width: 100%;
    min-height: 100vh;
    display: block;
    z-index: 98;
    background-color: #12002F;
    padding-top: 120px;
    transition: 0.4s;
}

.mobile-nav.is-active {
    left: 0; 
}

.mobile-nav a {
    display: block;
    width: 100%;
    max-width: 200px;
    margin: 0 auto 16px;
    text-align: center;
    padding: 12px 16px;
    background-color: #1f103F;

    color: #fff;
    text-decoration: none;
}

.mobile-nav a:hover {
    background-color: #24104f;

}

@media (min-width: 768px) {
    .mobile-nav {
        display: none;
    }

    .hamburger {
        display: none;
    }
}
</style>