
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Anjani Devireddy | Front End Engineer</title>
    <style>
    
    
    .github-button {
    display: inline-block;
    padding: 10px 20px;
    margin-top: 10px;
    font-size: 16px;
    color: white;
    background-color:  #444c56;
    text-decoration: none;
    border-radius: 6px;
    transition: background-color 0.3s ease;
}

.github-button:hover {
    background-color: #6DB0EB;
}
    
    
    
        /* Reset and base styles */
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: system-ui, -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Oxygen, Ubuntu, Cantarell, 'Open Sans', 'Helvetica Neue', sans-serif;
        }

        :root {
            --bg-dark: #0d1620;
            --bg-card: #141f2d;
            --text-primary: #eaf0f8;
            --text-secondary: #a3b3c7;
            --text-highlight: #ffffff;
            --accent: #64b5f6;
            --border: #2a3544;
            --tag-bg: rgba(100, 181, 246, 0.1);
            --tag-text: #77c1ff;
            --hover-effect: rgba(100, 181, 246, 0.05);
        }

        body {
            background-color: var(--bg-dark);
            color: var(--text-secondary);
            line-height: 1.6;
            padding: 0;
            margin: 0;
        }

        .container {
            display: flex;
            min-height: 100vh;
            max-width: 1400px;
            margin: 0 auto;
            padding: 2rem;
            gap: 3rem;
        }

        /* Left sidebar */
        .sidebar {
            width: 400px;
            position: sticky;
            top: 2rem;
            height: fit-content;
            padding-right: 1rem;
        }

        /* Profile image */
        .profile-container {
            position: relative;
            width: 180px;
            height: 180px;
            margin-bottom: 2rem;
            border-radius: 50%;
            overflow: hidden;
            border: 3px solid var(--accent);
            box-shadow: 0 10px 30px rgba(0, 0, 0, 0.3);
        }

        .profile-img {
            width: 100%;
            height: 100%;
            object-fit: cover;
            transition: transform 0.3s ease;
        }

        .profile-container:hover .profile-img {
            transform: scale(1.05);
        }

        /* Main content */
        .main-content {
            flex: 1;
            padding-left: 2rem;
            border-left: 1px solid var(--border);
            max-width: 900px;
        }

        /* Title styles */
        h1 {
            font-size: 2rem;
            font-weight: 700;
            color: var(--text-highlight);
            margin-bottom: 0.5rem;
            letter-spacing: -1px;
        }

        h2 {
            font-size: 1.25rem;
            font-weight: 500;
            color: var(--accent);
            margin-bottom: 1.5rem;
            letter-spacing: 0.5px;
        }

        .subtitle {
            font-size: 1rem;
            line-height: 1.6;
            margin-bottom: 2rem;
            color: var(--text-secondary);
        }

        .contact-info {
            display: flex;
            flex-wrap: wrap;
            gap: 0.5rem;
            margin-bottom: 1.5rem;
            font-size: 0.9rem;
        }

        .contact-info a {
            color: var(--accent);
            text-decoration: none;
            transition: color 0.2s ease;
        }

        .contact-info a:hover {
            color: var(--text-highlight);
            text-decoration: underline;
        }

        /* Navigation */
        nav {
            margin-top: 3rem;
        }

        .nav-item {
            display: flex;
            align-items: center;
            margin-bottom: 1rem;
            padding: 0.5rem 0;
            cursor: pointer;
            transition: all 0.2s ease;
            color: var(--text-secondary);
            text-decoration: none;
            position: relative;
        }

        .nav-item.active {
            color: var(--text-highlight);
            font-weight: 600;
        }

        .nav-item:hover {
            color: var(--text-highlight);
        }

        .nav-line {
            height: 1px;
            width: 2rem;
            background-color: var(--text-secondary);
            margin-right: 1rem;
            transition: width 0.2s ease, background-color 0.2s ease;
        }

        .nav-item.active .nav-line {
            width: 3rem;
            background-color: var(--accent);
        }

        .nav-item:hover .nav-line {
            width: 3rem;
            background-color: var(--text-highlight);
        }

        /* Content sections */
        section {
            margin-bottom: 4rem;
            animation: fadeIn 0.5s ease-in-out;
        }

        h3 {
            font-size: 1.75rem;
            color: var(--text-highlight);
            margin-bottom: 1.5rem;
            position: relative;
            padding-bottom: 0.5rem;
        }

        h3::after {
            content: '';
            position: absolute;
            bottom: 0;
            left: 0;
            width: 3rem;
            height: 3px;
            background-color: var(--accent);
            border-radius: 3px;
        }

        p {
            margin-bottom: 1.5rem;
            font-size: 1.05rem;
        }

        .highlight {
            color: var(--accent);
            font-weight: 500;
        }

        .date {
            color: var(--text-secondary);
            margin-bottom: 0.75rem;
            text-transform: uppercase;
            font-size: 0.85rem;
            letter-spacing: 1px;
        }

        .job-title, .education-title, .project-title {
            font-size: 17px;
            color: var(--text-highlight);
            font-weight: 600;
            margin-bottom: 1rem;
            display: flex;
            align-items: center;
        }

        .job-title a, .education-title a {
            color: var(--text-highlight);
            text-decoration: none;
            transition: color 0.2s ease;
        }

        .job-title a:hover, .education-title a:hover {
            color: var(--accent);
        }

        .job-title svg, .education-title svg {
            margin-left: 0.5rem;
        }

        .job-description, .education-description, .project-description {
            color: var(--text-secondary);
            margin-bottom: 2rem;
            background-color: var(--bg-card);
            padding: 1.5rem;
            border-radius: 8px;
            box-shadow: 0 4px 12px rgba(0, 0, 0, 0.1);
            border: 1px solid var(--border);
        }

        /* Experience, Education, Project item with hover effect */
        .experience-item, .education-item, .project-item, .certification-item {
            padding: 1.5rem;
            border-radius: 8px;
            transition: all 0.2s ease;
            margin-bottom: 2rem;
            border: 1px solid transparent;
        }

        .experience-item:hover, .education-item:hover, .project-item:hover, .certification-item:hover {
            background-color: var(--hover-effect);
            border: 1px solid var(--border);
            transform: translateY(-5px);
        }

        /* Skills section */
        .skills-container {
            display: flex;
            flex-wrap: wrap;
            gap: 1.5rem;
            margin-bottom: 2rem;
        }

        .skill-category {
            flex: 1;
            min-width: 200px;
        }

        .skill-category h4 {
            color: var(--text-highlight);
            margin-bottom: 1rem;
            font-size: 1.1rem;
        }

        /* Tags */
        .tags {
            display: flex;
            flex-wrap: wrap;
            gap: 0.5rem;
            margin-top: 1rem;
        }

        .tag {
            background-color: var(--tag-bg);
            color: var(--tag-text);
            padding: 0.35rem 0.75rem;
            border-radius: 1.5rem;
            font-size: 0.85rem;
            font-weight: 500;
            letter-spacing: 0.5px;
            transition: all 0.2s ease;
        }

        .tag:hover {
            background-color: rgba(100, 181, 246, 0.2);
            transform: translateY(-2px);
        }

        /* Social links */
        .social-links {
            display: flex;
            gap: 1rem;
            margin-top: 3rem;
        }

        .social-link {
            color: var(--text-secondary);
            transition: all 0.2s ease;
            background-color: var(--bg-card);
            width: 40px;
            height: 40px;
            border-radius: 50%;
            display: flex;
            align-items: center;
            justify-content: center;
            border: 1px solid var(--border);
        }

        .social-link:hover {
            color: var(--accent);
            transform: translateY(-3px);
            box-shadow: 0 5px 15px rgba(0, 0, 0, 0.2);
        }

        /* Projects section */
        .projects-grid {
            display: grid;
            grid-template-columns: repeat(auto-fill, minmax(300px, 1fr));
            gap: 1.5rem;
        }

        .project-card {
            background-color: var(--bg-card);
            border-radius: 8px;
            padding: 1.5rem;
            transition: all 0.3s ease;
            border: 1px solid var(--border);
            height: 100%;
            display: flex;
            flex-direction: column;
        }

        .project-card:hover {
            transform: translateY(-5px);
            box-shadow: 0 10px 30px rgba(0, 0, 0, 0.15);
            border-color: var(--accent);
        }

        .project-title {
            font-size: 1.25rem;
            color: var(--text-highlight);
            margin-bottom: 1rem;
            font-weight: 600;
        }

        .project-description {
            color: var(--text-secondary);
            margin-bottom: 1.5rem;
            flex-grow: 1;
        }

        /* Certifications */
        .certifications-list {
            display: grid;
            grid-template-columns: repeat(auto-fill, minmax(300px, 1fr));
            gap: 1.5rem;
        }

        .cert-card {
            background-color: var(--bg-card);
            border-radius: 8px;
            padding: 1.5rem;
            transition: all 0.3s ease;
            border: 1px solid var(--border);
            height: 100%;
        }

        .cert-card:hover {
            transform: translateY(-5px);
            box-shadow: 0 10px 30px rgba(0, 0, 0, 0.15);
            border-color: var(--accent);
        }

        .cert-title {
            font-size: 1.1rem;
            color: var(--text-highlight);
            margin-bottom: 0.75rem;
            font-weight: 600;
        }

        .cert-issuer {
            color: var(--accent);
            font-size: 0.9rem;
            margin-bottom: 0.5rem;
        }

        /* Animations */
        @keyframes fadeIn {
            from { opacity: 0; transform: translateY(10px); }
            to { opacity: 1; transform: translateY(0); }
        }

        /* Scrollbar styling */
        ::-webkit-scrollbar {
            width: 8px;
        }

        ::-webkit-scrollbar-track {
            background: var(--bg-dark);
        }

        ::-webkit-scrollbar-thumb {
            background: var(--border);
            border-radius: 4px;
        }

        ::-webkit-scrollbar-thumb:hover {
            background: var(--accent);
        }

        @media (max-width: 900px) {
            .container {
                flex-direction: column;
            }

            .sidebar {
                width: 100%;
                position: relative;
                top: 0;
                padding-right: 0;
                margin-bottom: 3rem;
                display: flex;
                flex-direction: column;
                align-items: center;
                text-align: center;
            }

            .main-content {
                padding-left: 0;
                border-left: none;
                padding-top: 2rem;
                border-top: 1px solid var(--border);
                max-width: 100%;
            }

            nav {
                margin-top: 2rem;
                width: 100%;
                display: flex;
                justify-content: center;
                gap: 1rem;
            }

            .nav-item {
                flex-direction: column;
                padding: 0.5rem;
            }

            .nav-line {
                width: 2rem;
                height: 3px;
                margin-right: 0;
                margin-bottom: 0.5rem;
            }

            .nav-item.active .nav-line,
            .nav-item:hover .nav-line {
                width: 2rem;
            }

            .social-links {
                justify-content: center;
            }

            .projects-grid, .certifications-list {
                grid-template-columns: 1fr;
            }

            .skills-container {
                flex-direction: column;
            }
        }
    </style>
</head>
<body>
    <div class="container">
        <div class="sidebar">
            <div class="profile-container">
                <img src="profile.jpeg" alt="Anjani Devireddy" class="profile-img">
            </div>
            
            <h1>ANJANI DEVIREDDY</h1>
            <div class="contact-info">
                <span>+91 8121130388</span> | 
                <span>Hyderabad</span> | 
                <a href="mailto:email@anjani.ai">mail</a> | 
                <a href="https://www.linkedin.com/in/anjani-devireddy/" target="_blank">linkedin</a> | 
                <a href="https://github.com/anjani-ai" target="_blank">github</a>
            </div>
            <p class="subtitle">AI/ML Engineer specializing in computer vision and accessible digital experiences.</p>

            <nav>
                <a href="#about" class="nav-item active">
                    <div class="nav-line"></div>
                    <span>ABOUT</span>
                </a>
                <a href="#education" class="nav-item">
                    <div class="nav-line"></div>
                    <span>EDUCATION</span>
                </a>
                <a href="#skills" class="nav-item">
                    <div class="nav-line"></div>
                    <span>SKILLS</span>
                </a>
                <a href="#projects" class="nav-item">
                    <div class="nav-line"></div>
                    <span>PROJECTS</span>
                </a>
                <a href="#certifications" class="nav-item">
                    <div class="nav-line"></div>
                    <span>CERTIFICATIONS</span>
                </a>


                 
                
            </nav>
            
            
            
            <a href="resume.pdf" target="_blank" style="
  display: inline-flex;
  align-items: center;
  padding: 10px 16px;
  background-color: #e63946;
  color: white;
  text-decoration: none;
  border-radius: 6px;
  font-weight: 500;
  font-family: sans-serif;
  gap: 8px;
">
  <img src="pdf.png" width="16px" alt="PDF Icon" />
  Download Resume
</a>

         
                 
            

            <div class="social-links">
                <a href="https://github.com/anjani-ai" class="social-link" target="_blank">
                    <svg xmlns="http://www.w3.org/2000/svg" width="20" height="20" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round">
                        <path d="M9 19c-5 1.5-5-2.5-7-3m14 6v-3.87a3.37 3.37 0 0 0-.94-2.61c3.14-.35 6.44-1.54 6.44-7A5.44 5.44 0 0 0 20 4.77 5.07 5.07 0 0 0 19.91 1S18.73.65 16 2.48a13.38 13.38 0 0 0-7 0C6.27.65 5.09 1 5.09 1A5.07 5.07 0 0 0 5 4.77a5.44 5.44 0 0 0-1.5 3.78c0 5.42 3.3 6.61 6.44 7A3.37 3.37 0 0 0 9 18.13V22"></path>
                    </svg>
                </a>
                <a href="https://www.linkedin.com/in/anjani-devireddy/" class="social-link" target="_blank">
                    <svg xmlns="http://www.w3.org/2000/svg" width="20" height="20" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round">
                        <path d="M16 8a6 6 0 0 1 6 6v7h-4v-7a2 2 0 0 0-2-2 2 2 0 0 0-2 2v7h-4v-7a6 6 0 0 1 6-6z"></path>
                        <rect x="2" y="9" width="4" height="12"></rect>
                        <circle cx="4" cy="4" r="2"></circle>
                    </svg>
                </a>
       
      
            </div>
        </div>

        <div class="main-content">
            <section id="about">
                <h3>About Me</h3>
                <p>I'm an AI/ML Engineer passionate about developing innovative solutions that blend cutting-edge artificial intelligence with robust engineering principles. My work focuses on computer vision applications and creating accessible technologies that solve real-world problems.</p>
                
                <p>Currently pursuing my B-Tech in Computer Science with a specialization in AI & ML, I'm actively involved in research and development projects that push the boundaries of what's possible with machine learning. I have particular interest in computer vision, predictive analytics, and building intelligent systems that enhance human capabilities.</p>
                
                <p>Beyond academics, I've developed practical experience through various projects including traffic optimization systems, electronic scent detection, and property valuation models. I'm also a licensed drone operator with expertise in UAV development and remote sensing applications.</p>
            </section>

            <section id="education">
                <h3>Education</h3>
                <div class="education-item">
                    <div class="date">July 2021 — July 2025</div>
                    <div class="education-title">
                        B-Tech in CSE (AI&ML) — TKR College of Engineering & Technology
                    </div>
                    <div class="education-description">
                        <p>GPA: 7.05/10</p>
                        <p>Key Courses: Deep Learning, Computer Vision, Data Structures & Algorithms</p>
                    </div>
                </div>
                
                <div class="education-item">
                    <div class="date">June 2019 — June 2021</div>
                    <div class="education-title">
                        MPC Course - N120 Batch — Narayana Jr. College
                    </div>
                    <div class="education-description">
                        <p>Senior Secondary Education</p>
                    </div>
                </div>
                
                <div class="education-item">
                    <div class="date">June 2009 — June 2019</div>
                    <div class="education-title">
                        Computer Applications — Hyderabad Public School, Begumpet
                    </div>
                    <div class="education-description">
                        <p>Secondary Education</p>
                        <p>Score: 91%</p>
                    </div>
                </div>
            </section>

            <section id="skills">
                <h3>Skills</h3>
                <div class="skills-container">
                    <div class="skill-category">
                        <h4>Programming Languages</h4>
                        <div class="tags">
                            <span class="tag">Python</span>
                            <span class="tag">Java</span>
                            <span class="tag">C</span>
                            <span class="tag">C++</span>
                        </div>
                    </div>
                    
                    <div class="skill-category">
                        <h4>AI/ML Frameworks</h4>
                        <div class="tags">
                            <span class="tag">TensorFlow</span>
                            <span class="tag">PyTorch</span>
                            <span class="tag">OpenCV</span>
                            <span class="tag">YOLO</span>
                        </div>
                    </div>
                    
                    <div class="skill-category">
                        <h4>Additional Skills</h4>
                        <div class="tags">
                            <span class="tag">UAV Operations</span>
                            <span class="tag">Remote Sensing</span>
                            <span class="tag">Predictive Analytics</span>
                            <span class="tag">Data Visualization</span>
                        </div>
                    </div>
                </div>
            </section>

            <section id="projects">
                <h3>Projects</h3>
                <div class="project-item">
                    <div class="date">September 2024 — Present</div>
                    <div class="project-title">Adaptive Traffic Optimization</div>
                <div class="project-description">
    <p>
        Developing an AI-powered traffic management system that uses real-time data from sensors to optimize signal timings based on live traffic density. The system applies predictive analytics to anticipate congestion and make proactive adjustments, reducing wait times and improving flow. Designed for integration with smart city infrastructure to support scalable, sustainable urban mobility.
         <br> <a href="https://github.com/anjani-ai/Adaptive-Traffic-Signal-Control-System" target="_blank" class="github-button" >View Project on GitHub</a>
    </p>
</div>
                    <div class="tags">
                        <span class="tag">Computer Vision</span>
                        <span class="tag">IoT</span>
                        <span class="tag">Predictive Analytics</span>
                        <span class="tag">Smart Cities</span>
                    </div>
                </div>
                
                <div class="project-item">
                    <div class="date">September 2024 — February 2025</div>
                    <div class="project-title">AI Nose</div>
                    <div class="project-description">
    <p>
        Built a DIY electronic nose inspired by the human sense of smell, using gas sensors to detect and learn different odors. Collected scent data and trained lightweight machine learning models to recognize and classify smells. The system can be customized for various real-world applications like food freshness, air quality, and safety monitoring.
       <br> <a href="https://github.com/anjani-ai/ai-nose" target="_blank" class="github-button" >View Project on GitHub</a>
    </p>
</div>

                    <div class="tags">
                        <span class="tag">IoT</span>
                        <span class="tag">Classification ML</span>
                        <span class="tag">Sensor Networks</span>
                        <span class="tag">Embedded Systems</span>
                    </div>
                </div>
                
                <div class="project-item">
                    <div class="date">January 2023 — December 2023</div>
                    <div class="project-title">Property Price Prediction</div>
                    <div class="project-description">
    <p>
        The property price prediction project leverages machine learning models to analyze historical data, economic trends, and local factors such as infrastructure, amenities, and crime rates to accurately forecast property values. By using a combination of regression models and real-time data inputs, the system predicts future price fluctuations, helping investors, buyers, and sellers make informed decisions. The model also accounts for macroeconomic trends like interest rates and inflation, providing comprehensive and reliable property valuation insights tailored to specific regions or neighborhoods.
          <br><a href="https://github.com/anjani-ai/property-price-prediction" target="_blank" class="github-button">View Project on GitHub</a>
    </p>
</div>

                    <div class="tags">
                        <span class="tag">Regression Models</span>
                        <span class="tag">Feature Engineering</span>
                        <span class="tag">Economic Analysis</span>
                        <span class="tag">Data Mining</span>
                    </div>
                </div>
            </section>

            <section id="certifications">
                <h3>Certifications & Achievements</h3>
                <div class="certifications-list">
                    <div class="cert-card">
                        <div class="cert-title">Smart India Hackathon 2024</div>
                        <div class="cert-issuer">Ministry of Education, Government of India</div>
                    </div>
                    
                    <div class="cert-card">
                        <div class="cert-title">Sawit AI Hackathon</div>
                        <div class="cert-issuer">Guvi Geek Networks</div>
                    </div>
                    
                    <div class="cert-card">
                        <div class="cert-title">Drawing with LLMs and Lux AI Challenge</div>
                        <div class="cert-issuer">Featured Simulation Competition - Kaggle</div>
                    </div>
                    
                    <div class="cert-card">
                        <div class="cert-title">Programming Using Python</div>
                        <div class="cert-issuer">Infosys Springboard</div>
                    </div>
                    
                    <div class="cert-card">
                        <div class="cert-title">Advanced Software Engineering Job Simulation</div>
                        <div class="cert-issuer">Walmart USA</div>
                    </div>
                    
                    <div class="cert-card">
                        <div class="cert-title">DGCA Remote Pilot Certification</div>
                        <div class="cert-issuer">Licensed Drone Operator</div>
                    </div>
                    
                    <div class="cert-card">
                        <div class="cert-title">CUAV Tech Inc. Sponsorship Recipient</div>
                        <div class="cert-issuer">UAV Development</div>
                    </div>
                    
                    <div class="cert-card">
                        <div class="cert-title">NRSC ISRO Drone Data Processing Certificate</div>
                        <div class="cert-issuer">Remote Sensing Applications</div>
                    </div>
                </div>
            </section>
        </div>
    </div>

    <script>
        // Sticky navigation functionality
        document.addEventListener('DOMContentLoaded', function() {
            const navItems = document.querySelectorAll('.nav-item');
            const sections = document.querySelectorAll('section');
            
            // Handle click on nav items
            navItems.forEach(item => {
                item.addEventListener('click', function(e) {
                    e.preventDefault();
                    const targetId = this.getAttribute('href').substring(1);
                    const targetSection = document.getElementById(targetId);
                    
                    window.scrollTo({
                        top: targetSection.offsetTop - 20,
                        behavior: 'smooth'
                    });
                    
                    // Update active state
                    navItems.forEach(navItem => navItem.classList.remove('active'));
                    this.classList.add('active');
                });
            });
            
            // Update active nav item on scroll
            window.addEventListener('scroll', function() {
                let current = '';
                
                sections.forEach(section => {
                    const sectionTop = section.offsetTop - 100;
                    const sectionHeight = section.clientHeight;
                    
                    if (pageYOffset >= sectionTop) {
                        current = section.getAttribute('id');
                    }
                });
                
                navItems.forEach(item => {
                    item.classList.remove('active');
                    if (item.getAttribute('href').substring(1) === current) {
                        item.classList.add('active');
                    }
                });
            });
        });
    </script>
</body>
</html>
