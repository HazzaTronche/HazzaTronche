body {
    font-family: 'Imprima', sans-serif;

    font-size: 12px;
    max-width: 960px;
    margin: auto;
}

#header-main { 
    display: grid;
    grid-template-columns: 70% 30%;
    margin-top: 3em;
}

/* section {
    margin: auto 1em 1em 1em;
} */

/* article {
    margin: auto 1em 1em 1em;
} */

.banner {
    background-color: #000000;
    padding: 10px;
    margin-top: 30px;
    
}

.banner h1 {
    font-size: 36px;
}

h1 {
    color: #658cae;
    font-size: 36px
    
}

h2 {
    color: #000000;
    font-size: 28px
}

h3 {
    color: #a777c9;
    font-size: 18px
}

header {
    margin: 0px 50px 0px 20px;
    padding: 0px 0px 0px 30px;
}

#header-blurb {
    padding-right: 70px;
}

#header-contact {
    background-color: #2b5173;
    padding: 5px 5px 20px 20px;
    max-width: 180px;
}

#header-contact a {
    text-decoration: none;
    font-size: 11px;
    color: rgb(255, 255, 255)
}

#header-contact a:hover {
    color: #159376;
}

#header-contact i {
    color: rgb(255, 255, 255)
    
}

p {
    font-size: 12px;
    font-family: 'Open Sans', sans-serif;
}

.highlight {
    color: #a777c9;
    font-weight: bold;
}

img {
    max-width: 300px;
    max-height: 400px;
    margin: auto;
}

.project {
    display: grid;
    grid-template-columns: 50% 50%;
    margin-top: 60px;

}

/* h1 {
    font-size: 3em;
    letter-spacing: .6em;
    padding-top: 1em;
    padding-bottom: 1em;
} */

/* h2 {
    font-size: 1.5em;
    padding-bottom: 1em;
}

h3 {
    font-size: 1em;
    padding-bottom: 1em;
} */
/* 
main { 
    display: grid;
    grid-template-columns: 40% 60%;
    margin-top: 3em;
} */

ul {
    list-style: none; /* Remove default bullets */
    padding: 0px 15px 15px;
  }

ul li::before {
    content: "\2022";
    color: #a777c9;
    font-weight: bold; /* If you want it to be bold */
    display: inline-block; /* Needed to add space between the bullet and the text */
    width: 1em; /* Also needed for space (tweak if needed) */
    margin-left: -1em; /* Also needed for space (tweak if needed) */
}


main {
    padding: 0px 40px 40px 40px; 
}

#mainLeft {
    border-right: 1px solid lightgray;
}

.link-btn {
    background-color: #a777c9;
    padding: 10px;
    margin: 5px;
    margin-top: 40px;
    text-decoration: None;
    color:rgb(67, 66, 66);
}

.link-btn:hover {
    background-color: #1e6554;
    color: white;
}








<html>

	<head>
		<link href="style.css" rel="stylesheet">
		<title>Harry Tronche - Portfolio</title>
        <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/5.15.4/css/all.min.css">
        <link rel="preconnect" href="https://fonts.googleapis.com">
        <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
        <link href="https://fonts.googleapis.com/css2?family=Imprima&family=Open+Sans:wght@400;700&display=swap" rel="stylesheet">
    </head>

	<body>
		
            
		<h1 class="banner">Harrison Keith Tronche</h1>
        <header id="header">	
            <section id="header-main">
                <article id="header-blurb">
                <h2>
                Up and Coming Software Engineer  
                </h2>
                    <p>
                        My goal is to make a gazillion dollars and buy everything lol xd              </p>
                </article>
                <article id="header-contact">
                    <h2>Socials</h2>
                        <p>
                            <i class="fa fa-envelope" aria-hidden="true"></i>
                            <a href="mailto:your-harrytronchesemail@gmail.com">harrytronchesemail@gmail.com</a>
                        </p>
                        <p>
                            <i class="fab fa-github" aria-hidden="true"></i>
                            <a href="github.com/gh-HazzaTronche">HazzaTronche</a>
                        </p>
                        <p>
                            <i class="fab fa-linkedin" aria-hidden="true"></i>
                            <a href="https://www.linkedin.com/in/your-link">Your name on LinkdIn</a>
                        </p>
                </article>
            </section>
		</header>

        <h2 class="banner">My Projects</h2>
        <main>
        <article class="project">
            <img src="images/image1.png">
            <div>
                <h3>
                    [PROJECT TITLE]
                </h3>
                <p>
                    [PROJECT DESCRIPTION] Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.
                </p>
                <span class="highlight">Technology</span>
                <ul>
                    <li>Technology 1 (eg. Python)</li>
                    <li>Technology 2 (eg. Flask)</li>
                    <li>Technology 3 (eg. Azure Cognitive Services)</li>
                </ul>

                <a class="link-btn" href="">See it Live</a>
                <a class="link-btn" href="">GitHub Repo</a>
                
            </div>
        </article>

        <!-- Add more articles here -->
       
		</main>
	</body>
</html>

