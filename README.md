<DOCTYPE html>
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
            font-family: 'Roboto', sans-serif;
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
        
.navbar {
    position: relative;
    top: 10;
    left: 0;
    width: 100%; /* Ensures it covers full width */
    background-color: #162447;
    font-size: 0.7em;
    padding: 10px;
    display: flex;
    justify-content: right;
    gap: 10px;
    z-index: 9999; /* Ensures it stays above content */
    box-shadow: 0 4px 8px rgba(0, 0, 0, 0.5);
    height: 60px; /* Explicit height */
}

.content {
    padding-top: 60px; /* Ensures content starts below navbar */
}


.navbar a {
    color: white;
    text-decoration: none;
    font-size: 1.2em;
    font-weight: bold;
    padding: 10px 15px;
    transition: 0.3s;
}

.navbar a:hover {
    background-color: #ffbe33; /* Highlight color on hover */
    color: #1b1b2f;
    border-radius: 5px;
}


.content {
            padding-top: 80px;;
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
            align-items: flex;
            justify-content: space-between;
            gap: 60px;
        }

.about-me img {
    width: 500px;
    height: 500px;
    border-radius: 0.5%;
    border: 1px solid white;
    object-fit: cover;
    margin-top: 20px; /* Adjust the value as needed */
}
.Education{
            display: grid;
            grid-template-columns: repeat(2, 1fr);
            gap: 60px;
        }
.type{
            background: #1f4068;
            padding: 10px;
            border-radius: 5px;
            text-align: flex;
            border: 2px solid #1f4068;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.5);
        }
.type:hover {
    background: #ffbe33;
    color: #1b1b2f;
    transform: scale(1.1);
}

.type:hover i {
    color: #1b1b2f;
}

.skills-icons {
    display: flex;
    flex-wrap: wrap;
    gap: 15px;
    justify-content: flex;
}

.skill {
    background: #1f4068;
    padding: 12px 18px;
    border-radius: 8px;
    color: white;
    font-size: 1.0em;
    display: center;
    align-items: flex;
    border: 2px solid #1f4068;
    box-shadow: 0 4px 8px rgba(0, 0, 0, 0.5);
    transition: transform 0.3s ease, background 0.3s ease;
}

.skill i {
    margin-right: 8px;
    font-size: 1.5em;
    color: #ffbe33; /* Highlighted icon color */
}

.skill:hover {
    background: #ffbe33;
    color: #1b1b2f;
    transform: scale(1.1);
}

.skill:hover i {
    color: #1b1b2f;
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
            color: #ffffff;
        }
        .white-link {
    color: white !important; /* Force white color */
    text-decoration: underline !important; /* Remove underline */
}

.white-link:hover {
    color: #ccc !important; /* Light gray on hover */
}

			
        footer {
            text-align: center;
            padding: 15px;
            background-color: #1f4068;
            color: #ffffff;
        }

        footer a {
            color: #ffffff;
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
<nav class="navbar">
    <a href="#about">About Me</a>
    <a href="#education">Education</a>
    <a href="#skills">Technical Skills</a>
    <a href="#certificates">Certificates</a>
    <a href="#contact">Contact</a>
</nav>

<header>
    <h1>Jaya Sruthi Koppada</h1>
    <p>Bioinformatician | Research Enthusiast</p>
</header>

<div class="content">
    <div class="section about-me" id="about">
        <div>
            <h2>About Me</h2>
            <p>Hey there! I'm Jaya Sruthi Koppada, you can call me Jaya (/ˈjīə/). I’m a Bioinformatician and Computational Biologist with a passion for making sense of complex biological data through coding, machine learning, and bioinformatics workflows. I recently completed my Master’s in Bioinformatics at Indiana University (December 2024) with a 3.7 GPA, and I love finding patterns in data that can drive breakthroughs in genomics and medicine. </p>
</p> During my time as a Research Assistant at Indiana University School of Medicine, I worked on next-generation sequencing (NGS) projects, built bioinformatics pipelines, and developed machine learning models in analyzing genomic datasets (turns out, genes can be quite predictable!). I also optimized RNA-Seq, single-cell RNA sequencing, WGS, and WES workflows, improving data processing efficiency because science moves fast, and so should our data! </p>
<p> Before diving into computational biology, I was at Aragen Life Sciences as a Research Associate, where I worked on drug discovery and biomarker identification. I conducted high-throughput screening (HTS) and large-scale compound screening, analyzing dose-response curves and Z’-factor scores (aka, the behind-the-scenes magic of drug development). I also applied machine learning to analyze multi-dimensional assay datasets.
I also enjoyed teaching and mentoring, which I got to do as a Teaching Assistant, helping students navigate Clinical Decision Support Systems (CDSS) and Electronic Health Records (EHRs)—basically, making health data a little less intimidating.
Tech-wise, I’m fluent in Python, R, SQL, and Snakemake, love creating data visualizations in Tableau and Power BI, and have experience with machine learning frameworks like TensorFlow and scikit-learn. My passion? Using data-driven approaches to make personalized medicine smarter and disease research faster.</p>
<p> Outside of bioinformatics, I’m always up for a good fictional, sci-fi or mythological books, binge watching documentories, or exploring new ways to make biological data storytelling more engaging. If you're looking for someone who can code, analyze, and communicate science without making it boring, we should definitely connect! 🚀 </p>
        </div>
        <img src="https://i.postimg.cc/Y24nCs4p/IMG-9182.jpg" alt="Jaya Sruthi Koppada">
    </div>
<div class="section" id="education">
<h2>Education</h2>
    <div class="Education">
        <div class="education-category">
            <h3>Master's</h3>
            <div class="education">
                <div class="type">Bioinformatics (3.7/4.0)
                </div>
                <div class="type">Applied Chemistry (8.6/10)
                </div>
            </div>
        </div>

        <div class="education-category">
            <h3>Bachelor's</h3>
            <div class="education">
                <div class="type">Biotechnology/Microbiology/Chemistry(9.3/10)
                </div>
            </div>
        </div>
    </div>
</div>
 <div class="section" id="skills">
    <h2>Technical Skills</h2>
    <div class="skills-icons">
        <!-- Programming & Scripting -->
        <div class="skill">Python, Bash Scripting, R</div>

        <!-- Data Science & Machine Learning -->
        <div class="skill">Machine Learning, Biomedical Analytics, scikit-learn,  TensorFlow, PyTorch</div>

        <!-- Pipeline Development & Workflow Automation -->
        <div class="skill">Nextflow, Snakemake, WDL, Slurm</div>
        <!-- Data Science & Machine Learning -->
        <div class="skill">Keras, Pandas, NumPy, Seaborn, MATLAB</div>
    

        <!-- Bioinformatics & Genomics -->
        <div class="skill">RNA-Seq, Single-Cell RNA-Seq, Next Generation Sequencing, GWAS</div>
        <!-- Databases & Version Control -->
        <div class="skill">MySQL, PostgreSQL, Git/GitHub, DHIS2</div>
        <!-- Bioinformatics & Genomics -->
        <div class="skill">Genomics, Epigenomics, Spatial Transcriptomics, WGS/WES, Systems Biology </div>

      


        <!-- Computational Environments & Cloud -->
        <div class="skill">Unix/Linux, High-Performance Computing (HPC)</div>
        <div class="skill">Google Cloud Platform (GCP), AWS</div>

        <!-- Data Visualization & Analytics -->
        <div class="skill">Tableau, Power BI, Microsoft Office</div>

        <div class="skill">high-throughput screening (HTS), Cell-based assays, Standard Operating Procedures (SOPs)</div>


    </div>
</div>


    <div class="section" id="certificates">
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
    
    <div class="section" id="contact">
    <h2>Let's connect :)</h2>
    <p>Email: sruthikoppada@gmail.com</p>
    <p>Phone: +1 (317) 912-8735</p>
    <p><a href="https://www.linkedin.com/in/jaya-sruthi-koppada-a07a6b187/" class="white-link">LinkedIn</a></p>
    <p><a href="https://github.com/jayasruthikoppada" class="white-link">GitHub</a></p>
</div>
</div>
<footer>
    <p>&copy; 2025 Jaya Sruthi Koppada. All Rights Reserved.</p>
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
<script>
    document.querySelectorAll('.navbar a').forEach(anchor => {
        anchor.addEventListener('click', function(e) {
            e.preventDefault();
            const targetId = this.getAttribute('href').substring(1);
            const targetElement = document.getElementById(targetId);
            targetElement.scrollIntoView({ behavior: 'smooth' });
        });
    });
</script>

</body>
</html>
