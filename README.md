<!-- snippet -->

redoing code so as to learn a different way

nav {
    display: flex;
    justify-content: space-between;
    flex-wrap: wrap;
    position: relative;
    color: white;
    top:0;

}

li {
    display: flex;
    position: relative;
    left: 80%;
    padding: 20px;
    font-size: 25px;
    float: left;    
}
nav ul li a {
    text-decoration: none;
    color: white;
    position: relative;
    top: -15px;
}
nav ul li a:hover {
    text-decoration: none;
    color: rgb(96, 114, 221);
}



<nav>
                <ul>
                    <li class="projects">
                        <a href="#projects-&-applications">PROJECTS & APPLICATIONS</a>
                    </li>
                    <li class="about">
                        <a href="#about-me">ABOUT ME</a>
                    </li>
                    <li class="reach">
                        <a href="#reach-out">REACH OUT</a>
                    </li>
                </ul>
            </nav>
            <section>
                <p class="greeting">Hi. My name is Bryan McGrath. <br>I'm a Full Stack Web Developer.
                <p>
            </section>
            <article class="second-page">
            </article>
        </section>