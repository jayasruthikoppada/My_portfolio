# My_portfolio
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Jaya Sruthi Koppada - Portfolio</title>
    <style>
        * {
            box-sizing: border-box;
            margin: 0;
            padding: 0;
        }

        body {
            font-family: 'Times New Roman', sans-serif;
            background-color: #1b1b2f; /* Modern dark theme */
            color: #e0e0e0;
            line-height: 1.7;
        }

        header {
            text-align: center;
            padding: 30px;
            background-color: #162447;
            border-bottom: 1px solid #1f4068;
        }

        header h1 {
            font-size: 2.9em;
            color: #ffbe33;
        }

        header p {
            font-size: 1.2em;
            color: #a3d8f4;
        }

        .content {
            padding: 25px;
        }

        .section {
            margin-bottom: 50px;
            background: #1f4068;
            padding: 20px;
            border-radius: 10px;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.5);
        }

        .section h2 {
            text-align: center;
            color: #ffbe33;
            margin-bottom: 20px;
        }

        .about-me {
            display: flex;
            align-items: center;
            justify-content: space-between;
        }

        .about-me img {
    width: 300px;
    height: 300px;
    border-radius: 0.5%;
    border: 1px solid white;
    object-fit: cover;
    <! --animation: swing 8s infinite ease-in-out; -->
    margin-top: -50px; /* Adjust the value as needed */
}


        .skills {
            display: grid;
            grid-template-columns: repeat(4, 1fr);
            gap: 10px;
        }

        .skill {
            background: #162447;
            padding: 20px;
            border-radius: 5px;
            text-align: center;
            border: 2px solid #1f4068;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.5);
        }

        .slideshow-container {
            position: relative;
            max-width: 90%;
            margin: auto;
            overflow: hidden;
            border-radius: 10px;
        }

        .slide {
            display: none;
            text-align: center;
        }

        .slide img {
            width: 50%;
            height: auto;
            border-radius: 5px;
        }

        .prev, .next {
            cursor: pointer;
            position: absolute;
            top: 50%;
            width: auto;
            padding: 10px;
            margin-top: -22px;
            color: #ffffff;
            font-weight: bold;
            font-size: 18px;
            background-color: rgba(0, 0, 0, 0.5);
            border-radius: 0 3px 3px 0;
            user-select: none;
            transform: translateY(-50%);
        }

        .next {
            right: 0;
            border-radius: 3px 0 0 3px;
        }

        .prev {
            left: 0;
            border-radius: 3px 0 0 3px;
        }

        .dots {
            text-align: center;
            margin-top: 10px;
        }

        .dot {
            cursor: pointer;
            height: 15px;
            width: 15px;
            margin: 0 2px;
            background-color: #bbb;
            border-radius: 50%;
            display: inline-block;
            transition: background-color 0.6s ease;
        }

        .active, .dot:hover {
            background-color: #717171;
        }

        .contact-icons {
            display: flex;
            justify-content: center;
            gap: 20px;
            margin-top: 20px;
        }

        .contact-icons a {
            color: #a3d8f4;
            text-decoration: none;
            font-size: 2em;
        }

        .contact-icons a:hover {
            color: #e43f5a;
        }
        
			
        footer {
            text-align: center;
            padding: 15px;
            background-color: #1f4068;
            color: #ffffff;
        }

        footer a {
            color: #a3d8f4;
            text-decoration: none;
        }

        /* Animation Keyframes */
        @keyframes swing {
            0% {
                transform: rotate(5deg);
            }
            50% {
                transform: rotate(-5deg);
            }
            100% {
                transform: rotate(5deg);
            }
        }

    </style>
	
</head>
<body>

<header>
    <h1>Jaya Sruthi Koppada</h1>
    <p>Bioinformatician | Data Scientist | Research Enthusiast</p>
</header>

<div class="content">
    <div class="section about-me">
        <div>
            <h2>About Me</h2>
            <p>Hi, I'm Jaya Sruthi Koppada, You can call me Jaya, /ˈjīə/. I recently finished my Masters in Bioinformatics from Indiana University(December 2024), boasting a strong GPA of 3.7/4.0. I am a Bioinformatician with expertise in next-generation sequencing, data analysis, and bioinformatics workflows. I have two years experience as a Research Associate focused in developing pipeline in applying NGS to Early Onset Alzheimer's disease patients dataset. </p>
      <p> In addition, my role as a Teaching Assistant enabled me to refine my ability to communicate complex concepts effectively, particularly in Clinical Decision Support Systems and Electronic Health Records. With a dual background in bioinformatics and chemistry, I bring a multidisciplinary approach to solving biological challenges. I have contributed to several academic projects, including genome assembly, pathway enrichment analysis, and applying machine learning to biological datasets. My technical expertise spans Python, R, MySQL, and workflow automation tools like Snakemake, which I leverage to streamline data analysis pipelines. Proficient in data visualization, I excel at presenting insights using Matplotlib, ggplot2, and Tableau, ensuring that complex data becomes actionable and understandable.</p>
        <p>Driven by curiosity and a passion for discovery, I aim to bridge the gap between biological research and computational innovation. My focus lies in leveraging data-driven approaches to advance personalized medicine and uncover new insights into disease mechanisms. I am committed to continuous learning and thrive in collaborative environments that challenge me to grow professionally and intellectually.</p>
        </div>
        <img src="https://i.postimg.cc/Y24nCs4p/IMG-9182.jpg" alt="Jaya Sruthi Koppada">
    </div>

      <div class="section">
        <h2>Technical Skills</h2>
        <div class="skill-category">
            <h3>Programming Languages</h3>
            <div class="skills">
                <div class="skill">
                 
                    Python
                </div>
                <div class="skill">
                    R
                </div>
                <div class="skill">
                    MySQL
                </div>
            </div>
        </div>
<h3>Data Visualizations</h3>
            <div class="skills">
                <div class="skill">
                 
                    Power BI
                </div>
                <div class="skill">
                    Tableau
                </div>
        </div>
			  <div class="skill-category">
            <h3>Web Technologies</h3>
            <div class="skills">
                <div class="skill">
                   
                    HTML
                </div>
                <div class="skill">
                  
                    CSS
                </div>
            </div>
        </div>

        <div class="skill-category">
            <h3>Databases</h3>
            <div class="skills">
                <div class="skill">
                    BLAST
                </div>
                <div class="skill">
                 
                    GenBank
                </div>
                <div class="skill">

                    Cytoscape
                </div>
                <div class="skill">
                  
                    GWAS Catalog
                </div>
            </div>
        </div>

        <div class="skill-category">
            <h3>Other Skills</h3>
            <div class="skills">
                <div class="skill">
                    
                    Windows
                </div>
                <div class="skill">
                    Unix/Linux
                </div>
                <div class="skill">
                   
                    Machine Learning
                </div>
            </div>
        </div>
    </div>

    <div class="section">
        <h2>Certificates & Licenses</h2>
        <div class="slideshow-container">
            <div class="slide">
                <img src="https://i.postimg.cc/jSXFhHXC/2024-hipaa-privacy-and-security-jaya-sruthi-koppada-1-page-0001.jpg" alt="HIPAA Certificate">
            </div>
            <div class="slide">
                <img src="https://i.postimg.cc/sXSPTyrK/citi-Completion-Certificate-12905003-60307208-1-page-0001.jpg" alt="CITI Program Certificate 1">
            </div>
            <div class="slide">
                <img src="https://i.postimg.cc/ncV7DqC3/citi-Completion-Certificate-12905003-60307210-2-page-0001.jpg" alt="CITI Program Certificate 2">
            </div>
            <div class="slide">
                <img src="https://i.postimg.cc/tJvgPZMc/citi-Completion-Certificate-12905003-60307209-page-0001.jpg" alt="CITI Program Certificate 3">
            </div>

            <a class="prev" onclick="changeSlide(-1)">&#10094;</a>
            <a class="next" onclick="changeSlide(1)">&#10095;</a>
        </div>
        <div class="dots">
            <span class="dot" onclick="currentSlide(1)"></span>
            <span class="dot" onclick="currentSlide(2)"></span>
            <span class="dot" onclick="currentSlide(3)"></span>
            <span class="dot" onclick="currentSlide(4)"></span>
        </div>
    </div>
    </div>
</div>
    <div class="section">
        <h2>Let's connect :)</h2>
        <p>Email: sruthikoppada@gmail.com</p>
        <p>Phone: +1 (317) 912-8735</p>
        <p><a href="https://linkedin.com/in/jaya-sruthi-koppada">LinkedIn</a></p>
        <p><a href="https://github.com/jaya-sruthi-koppada">GitHub</a></p>
    </div>
</div>
<footer>
    <p>&copy; 2024 Jaya Sruthi Koppada. All Rights Reserved.</p>
</footer>

<script src="https://kit.fontawesome.com/a076d05399.js" crossorigin="anonymous"></script>
<script>
    let slideIndex = 1;
    showSlides(slideIndex);

    function changeSlide(n) {
        showSlides(slideIndex += n);
    }

    function currentSlide(n) {
        showSlides(slideIndex = n);
    }

    function showSlides(n) {
        let i;
        const slides = document.getElementsByClassName("slide");
        const dots = document.getElementsByClassName("dot");
        if (n > slides.length) {slideIndex = 1}
        if (n < 1) {slideIndex = slides.length}
        for (i = 0; i < slides.length; i++) {
            slides[i].style.display = "none";
        }
        for (i = 0; i < dots.length; i++) {
            dots[i].className = dots[i].className.replace(" active", "");
        }
        slides[slideIndex-1].style.display = "block";
        dots[slideIndex-1].className += " active";
    }

</script>

</body>
</html>


