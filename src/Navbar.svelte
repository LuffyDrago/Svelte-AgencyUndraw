    <body>
        <header>
            <a class="logo" href="/">DesignA.</a>
            <nav>
                <ul class="nav__links">
                    <li><a href="/">Home</a></li>
                    <li><a href="/">About</a></li>
                    <li><a href="/">Blog</a></li>
                    <li><a href="/">Portflio</a></li>
                    <li><a href="/">Services</a></li>
                </ul>
            </nav>
            <a class="cta" href="/">Contact Us</a>
            <p class="menu cta">Menu</p>
        </header>
        <div class="overlay">
            <!-- <a class="close">&times;</a> -->
            <div class="overlay__content">
                <a href="/">Services</a>
                <a href="/">Projects</a>
                <a href="/">About</a>
            </div>
        </div>
       
    </body>
<style>
   
header {
  display: flex;
  justify-content: space-between;
  align-items: center;
  padding: 30px 10%;
  /* background-color: #000; */
}


.logo {
  cursor: pointer;
}

.nav__links a,
.cta,
.overlay__content a {
  font-size: 12px;
  font-weight: 500;
  color: #8c8c8c;
  text-decoration: none;
}

.nav__links {
  list-style: none;
  display: flex;
}

.nav__links li {
  padding: 0px 20px;
}

.nav__links li a {
  transition: color 0.3s ease 0s;
}

.nav__links li a:hover {
  color: #000;
}

.cta {
  padding: 10px 20px;
  background-color: #eeedf2;
  color: #606182;
  border: none;
  text-transform: uppercase;
  border-radius: 3px;
  cursor: pointer;
  transition: background-color 0.3s ease 0s;
}

.cta:hover {
  background-color: #565786;
  color: #fff;
}

/* Mobile Nav */

.menu {
  display: none;
}

.overlay {
  height: 100%;
  width: 0;
  position: fixed;
  z-index: 1;
  left: 0;
  top: 0;
  background-color: #24252a;
  overflow-x: hidden;
  transition: width 0.5s ease 0s;
}

/* .overlay--active {
  width: 100%;
} */

.overlay__content {
  display: flex;
  height: 100%;
  flex-direction: column;
  align-items: center;
  justify-content: center;
}

.overlay a {
  padding: 15px;
  font-size: 36px;
  display: block;
  transition: color 0.3s ease 0s;
}

.overlay a:hover,
.overlay a:focus {
  color: #0088a9;
}
/* .overlay .close {
  position: absolute;
  top: 20px;
  right: 45px;
  font-size: 60px;
  color: #edf0f1;
} */

@media screen and (max-height: 450px) {
  .overlay a {
    font-size: 20px;
  }
  /* .overlay .close {
    font-size: 40px;
    top: 15px;
    right: 35px;
  } */
}

@media only screen and (max-width: 800px) {
  .nav__links,
  .cta {
    display: none;
  }
  .menu {
    display: initial;
  }
}

</style>