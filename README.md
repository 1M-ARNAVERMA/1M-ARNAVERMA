<!DOCTYPE html>
<html lang="en">

<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <meta name="description"
    content="Portfolio of Arnav Verma — ML Engineer & Data Scientist, B.Tech CSE student at Manipal University Jaipur, passionate about LLMs, Deep Learning, and AI automation." />
  <title>Arnav Verma | ML Engineer & Data Scientist</title>
  <link rel="preconnect" href="https://fonts.googleapis.com" />
  <link
    href="https://fonts.googleapis.com/css2?family=Inter:wght@300;400;500;600;700;800;900&family=JetBrains+Mono:wght@400;600&display=swap"
    rel="stylesheet" />
  <link rel="stylesheet" href="style.css" />
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.0/css/all.min.css" />
  <link rel="stylesheet" href="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/devicon.min.css" />
</head>

<body>

  <!-- NAV -->
  <nav id="navbar">
    <div class="nav-container">
      <a href="#hero" class="nav-logo">AV<span class="dot">.</span></a>
      <ul class="nav-links">
        <li><a href="#about">About</a></li>
        <li><a href="#skills">Skills</a></li>
        <li><a href="#projects">Projects</a></li>
        <li><a href="#education">Background</a></li>
        <li><a href="#certificates">Certificates</a></li>
        <li><a href="#contact">Contact</a></li>
      </ul>
      <a href="#contact" class="btn-nav">Hire Me</a>
      <button class="hamburger" id="hamburger" aria-label="Menu">
        <span></span><span></span><span></span>
      </button>
    </div>
  </nav>

  <!-- HERO -->
  <section id="hero">
    <canvas id="neural-canvas"></canvas>
    <div class="hero-content">
      <div class="hero-badge">
        <span class="badge-dot"></span>
        Open to Opportunities
      </div>
      <h1 class="hero-title">
        Hi, I'm <span class="gradient-text">Arnav Verma</span>
      </h1>
      <h2 class="hero-subtitle typewriter" id="typewriter"></h2>
      <p class="hero-desc">
        Final-year B.Tech CS student at Manipal University Jaipur. I build AI-powered systems — from locally trained
        LLMs and document chatbots to automated ML pipelines. Published researcher &amp; Google Cloud Gold League Rank
        1.
      </p>
      <div class="hero-cta">
        <a href="#projects" class="btn-primary">View My Work <i class="fa fa-arrow-right"></i></a>
        <a href="#contact" class="btn-outline">Get In Touch</a>
      </div>
      <div class="hero-stats">
        <div class="stat"><span class="stat-num">4+</span><span class="stat-label">Projects</span></div>
        <div class="stat-div"></div>
        <div class="stat"><span class="stat-num">2</span><span class="stat-label">Publications</span></div>
        <div class="stat-div"></div>
        <div class="stat"><span class="stat-num">🥇 #1</span><span class="stat-label">GCP Gold League</span></div>
      </div>
    </div>
    <div class="scroll-indicator">
      <div class="scroll-line"></div>
    </div>
  </section>

  <!-- ABOUT -->
  <section id="about">
    <div class="container">
      <div class="section-label">Who I Am</div>
      <h2 class="section-title">About <span class="gradient-text">Me</span></h2>
      <div class="about-grid">
        <div class="about-image-wrap">
          <div class="about-img-glow"></div>
          <div class="about-img-placeholder"
            style="background:none;border:3px solid rgba(99,102,241,0.4);overflow:hidden;padding:0;">
            <img src="arnav.jpg" alt="Arnav Verma" style="width:100%;height:100%;object-fit:cover;border-radius:50%;" />
          </div>
          <div class="about-socials">
            <a href="https://github.com/1M-ARNAVERMA" target="_blank" id="github-link" class="social-icon"
              title="GitHub"><i class="fab fa-github"></i></a>
            <a href="https://www.linkedin.com/in/arnav-verma-084331192/" target="_blank" id="linkedin-link"
              class="social-icon" title="LinkedIn"><i class="fab fa-linkedin"></i></a>
            <a href="mailto:arnavverma1110@gmail.com" id="email-social" class="social-icon" title="Email"><i
                class="fa fa-envelope"></i></a>
          </div>
        </div>
        <div class="about-content">
          <p class="about-text">
            I'm <strong>Arnav Verma</strong>, a B.Tech Computer Science student at <strong>Manipal University
              Jaipur</strong> (2023–2027), based in Vadodara, India. I specialize in building end-to-end AI systems —
            from locally trained LLMs to automated ML pipelines using tools like N8N, PyTorch, and Flask.
          </p>
          <p class="about-text">
            I recently led a team of 6 as an <strong>ML Intern at WeSkill</strong>, improving ATS scoring by 15% and
            cutting processing time by 40%. I also secured <strong>Rank 1</strong> in Google Cloud Skill Boost Gold
            League (9,915 pts) and have a <strong>published research paper</strong> in the IMMRC Journal on Generative
            AI.
          </p>
          <div class="about-tags">
            <span class="tag">🤖 LLMs & GenAI</span>
            <span class="tag">🧠 Deep Learning</span>
            <span class="tag">👁️ Computer Vision</span>
            <span class="tag">⚙️ AI Automation</span>
            <span class="tag">🔬 Research</span>
            <span class="tag">☁️ Google Cloud</span>
          </div>
          <a href="https://drive.google.com/file/d/14umuSJfifamgWyI_07s35H_VjpjjL_nG/view?usp=drive_link"
            target="_blank" id="resume-link" class="btn-primary mt-2">Download Resume <i class="fa fa-download"></i></a>
        </div>
      </div>
    </div>
  </section>

  <!-- SKILLS -->
  <section id="skills">
    <div class="container">
      <div class="section-label">What I Know</div>
      <h2 class="section-title">My <span class="gradient-text">Skills</span></h2>
      <div class="skills-icons-section">

        <!-- Programming & Data -->
        <div class="skill-category">
          <div class="skill-cat-title"><i class="fa fa-code"></i> Programming &amp; Data</div>
          <div class="skill-icons-row">
            <a href="https://www.python.org/" target="_blank" class="skill-icon-item" title="Python">
              <i class="devicon-python-plain colored"></i>
              <span>Python</span>
            </a>
            <a href="https://www.mysql.com/" target="_blank" class="skill-icon-item" title="SQL">
              <i class="devicon-mysql-plain colored"></i>
              <span>SQL</span>
            </a>
            <a href="https://www.geeksforgeeks.org/data-structures/" target="_blank" class="skill-icon-item"
              title="DSA">
              <i class="fa fa-sitemap" style="color:#6366f1;"></i>
              <span>DSA</span>
            </a>
            <a href="https://en.wikipedia.org/wiki/Statistics" target="_blank" class="skill-icon-item"
              title="Statistics">
              <i class="fa fa-chart-bar" style="color:#a78bfa;"></i>
              <span>Statistics</span>
            </a>
            <a href="https://numpy.org/" target="_blank" class="skill-icon-item" title="NumPy">
              <i class="devicon-numpy-plain colored"></i>
              <span>NumPy</span>
            </a>
            <a href="https://pandas.pydata.org/" target="_blank" class="skill-icon-item" title="Pandas">
              <i class="devicon-pandas-plain colored"></i>
              <span>Pandas</span>
            </a>
            <a href="https://en.cppreference.com/w/c" target="_blank" class="skill-icon-item" title="C">
              <i class="devicon-c-plain colored"></i>
              <span>C</span>
            </a>
          </div>
        </div>

        <!-- AI / ML Frameworks -->
        <div class="skill-category">
          <div class="skill-cat-title"><i class="fa fa-brain"></i> AI / ML Frameworks</div>
          <div class="skill-icons-row">
            <a href="https://www.tensorflow.org/" target="_blank" class="skill-icon-item" title="TensorFlow">
              <i class="devicon-tensorflow-original colored"></i>
              <span>TensorFlow</span>
            </a>
            <a href="https://keras.io/" target="_blank" class="skill-icon-item" title="Keras">
              <img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/keras/keras-original.svg" alt="Keras"
                style="width:2.4rem;height:2.4rem;" />
              <span>Keras</span>
            </a>
            <a href="https://pytorch.org/" target="_blank" class="skill-icon-item" title="PyTorch">
              <i class="devicon-pytorch-original colored"></i>
              <span>PyTorch</span>
            </a>
            <a href="https://scikit-learn.org/" target="_blank" class="skill-icon-item" title="Scikit-learn">
              <i class="devicon-scikitlearn-plain colored"></i>
              <span>Scikit-learn</span>
            </a>
            <a href="https://huggingface.co/" target="_blank" class="skill-icon-item" title="HuggingFace">
              <span class="icon-emoji">🤗</span>
              <span>HuggingFace</span>
            </a>
            <a href="https://opencv.org/" target="_blank" class="skill-icon-item" title="OpenCV">
              <i class="devicon-opencv-plain colored"></i>
              <span>OpenCV</span>
            </a>
          </div>
        </div>

        <!-- Data Visualization -->
        <div class="skill-category">
          <div class="skill-cat-title"><i class="fa fa-chart-pie"></i> Data Visualization</div>
          <div class="skill-icons-row">
            <a href="https://matplotlib.org/" target="_blank" class="skill-icon-item" title="Matplotlib">
              <i class="devicon-matplotlib-plain colored"></i>
              <span>Matplotlib</span>
            </a>
            <a href="https://seaborn.pydata.org/" target="_blank" class="skill-icon-item" title="Seaborn">
              <span class="icon-text-badge" style="background:linear-gradient(135deg,#4c72b0,#dd8452);">Sb</span>
              <span>Seaborn</span>
            </a>
            <a href="https://plotly.com/" target="_blank" class="skill-icon-item" title="Plotly">
              <span class="icon-text-badge" style="background:linear-gradient(135deg,#3f4f75,#7b9fd4);">Pl</span>
              <span>Plotly</span>
            </a>
            <a href="https://streamlit.io/" target="_blank" class="skill-icon-item" title="Streamlit">
              <i class="devicon-streamlit-plain colored"></i>
              <span>Streamlit</span>
            </a>
          </div>
        </div>

        <!-- Tools & Platforms -->
        <div class="skill-category">
          <div class="skill-cat-title"><i class="fa fa-tools"></i> Tools &amp; Platforms</div>
          <div class="skill-icons-row">
            <a href="https://www.docker.com/" target="_blank" class="skill-icon-item" title="Docker">
              <i class="devicon-docker-plain colored"></i>
              <span>Docker</span>
            </a>
            <a href="https://flask.palletsprojects.com/" target="_blank" class="skill-icon-item" title="Flask">
              <i class="devicon-flask-original" style="color:#e2e8f0;"></i>
              <span>Flask</span>
            </a>
            <a href="https://git-scm.com/" target="_blank" class="skill-icon-item" title="Git">
              <i class="devicon-git-plain colored"></i>
              <span>Git</span>
            </a>
            <a href="https://github.com/" target="_blank" class="skill-icon-item" title="GitHub">
              <i class="devicon-github-original" style="color:#e2e8f0;"></i>
              <span>GitHub</span>
            </a>
            <a href="https://n8n.io/" target="_blank" class="skill-icon-item" title="N8N">
              <span class="icon-text-badge" style="background:linear-gradient(135deg,#ea4b71,#ff6b6b);">N8N</span>
              <span>N8N</span>
            </a>
            <a href="https://cloud.google.com/" target="_blank" class="skill-icon-item" title="Google Cloud">
              <i class="devicon-googlecloud-plain colored"></i>
              <span>Google Cloud</span>
            </a>
          </div>
        </div>

      </div>

      <div class="tech-strip">
        <div class="tech-track">
          <span>Python</span><span>TensorFlow</span><span>PyTorch</span><span>Scikit-learn</span>
          <span>Pandas</span><span>NumPy</span><span>SQL</span><span>Docker</span>
          <span>HuggingFace</span><span>Transformers</span><span>Flask</span><span>N8N</span>
          <span>Plotly</span><span>Seaborn</span><span>Keras</span><span>Google Cloud</span>
          <span>Python</span><span>TensorFlow</span><span>PyTorch</span><span>Scikit-learn</span>
          <span>Pandas</span><span>NumPy</span><span>SQL</span><span>Docker</span>
        </div>
      </div>
    </div>
  </section>

  <!-- PROJECTS -->
  <section id="projects">
    <div class="container">
      <div class="section-label">What I've Built</div>
      <h2 class="section-title">Featured <span class="gradient-text">Projects</span></h2>
      <div class="project-filters">
        <button class="filter-btn active" data-filter="all">All</button>
        <button class="filter-btn" data-filter="nlp">NLP / LLM</button>
        <button class="filter-btn" data-filter="ml">ML / Automation</button>
        <button class="filter-btn" data-filter="da">Full-Stack</button>
      </div>
      <div class="projects-grid" id="projects-grid">

        <div class="project-card featured" data-category="nlp">
          <div class="project-glow"></div>
          <div class="project-badge">Featured</div>
          <div class="project-top">
            <div class="project-icon"><i class="fa fa-comments"></i></div>
            <div class="project-links">
              <a href="https://github.com/1M-ARNAVERMA/LLM_Docker_ETT_Project" target="_blank" title="GitHub"><i
                  class="fab fa-github"></i></a>
            </div>
          </div>
          <h3 class="project-title">LLM Based Document Chatbot</h3>
          <p class="project-desc">Built a document-based chatbot using a locally trained LLM, achieving 90%+ accuracy on
            user files. Added a hybrid rule-based + LLM system reducing hallucinations by 60%. Containerized and
            deployed end-to-end.</p>
          <div class="project-tags">
            <span>LLMs</span><span>PyTorch</span><span>Flask</span><span>Docker</span>
          </div>
          <div class="project-meta"><span>🤖 90%+ Accuracy</span><span>🐳 Dockerized</span></div>
        </div>

        <div class="project-card" data-category="ml">
          <div class="project-glow"></div>
          <div class="project-top">
            <div class="project-icon"><i class="fa fa-paper-plane"></i></div>
            <div class="project-links">
              <a href="https://github.com/1M-ARNAVERMA/Skill_Vistaar" target="_blank" title="GitHub"><i
                  class="fab fa-github"></i></a>
            </div>
          </div>
          <h3 class="project-title">AI-Powered Outreach Automation</h3>
          <p class="project-desc">Engineered an AI-powered outreach pipeline integrating 5+ APIs, automating
            personalized emails to 10+ contacts/company using N8N. Cut outreach time to 5 minutes — 8–10× faster than
            manual effort.</p>
          <div class="project-tags">
            <span>N8N</span><span>Python</span><span>APIs</span><span>Automation</span>
          </div>
          <div class="project-meta"><span>⚡ 90% Less Manual Work</span><span>🔁 8–10× Faster</span></div>
        </div>

        <div class="project-card" data-category="nlp">
          <div class="project-glow"></div>
          <div class="project-top">
            <div class="project-icon"><i class="fa fa-shield-alt"></i></div>
            <div class="project-links">
              <a href="https://github.com/1M-ARNAVERMA/DL_Hate_Speech_Recognition_Project" target="_blank"
                title="GitHub"><i class="fab fa-github"></i></a>
            </div>
          </div>
          <h3 class="project-title">DL Hate Speech Recognition</h3>
          <p class="project-desc">Deep Learning model for hate speech detection using NLP preprocessing, data
            augmentation, and transformer-based classification. Full EDA, preprocessing pipeline & model training
            notebooks. Research tied to a conference submission.</p>
          <div class="project-tags">
            <span>Deep Learning</span><span>Python</span><span>NLP</span><span>Transformers</span>
          </div>
          <div class="project-meta"><span>🛡️ Content Safety</span><span>📊 100% Python</span></div>
        </div>

        <div class="project-card" data-category="da">
          <div class="project-glow"></div>
          <div class="project-top">
            <div class="project-icon"><i class="fa fa-briefcase"></i></div>
            <div class="project-links">
              <a href="https://github.com/1M-ARNAVERMA/FINDEARN" target="_blank" title="GitHub"><i
                  class="fab fa-github"></i></a>
            </div>
          </div>
          <h3 class="project-title">FINDEARN &mdash; Job &amp; Earning Platform</h3>
          <p class="project-desc">Full-stack Next.js web application connecting freelancers and employers. Features job
            listings, user profiles, and a real-time dashboard built with TypeScript, TailwindCSS and modern React
            components.</p>
          <div class="project-tags">
            <span>Next.js</span><span>TypeScript</span><span>TailwindCSS</span><span>React</span>
          </div>
          <div class="project-meta"><span>💼 Full-Stack App</span><span>⚡ Next.js 14</span></div>
        </div>

      </div>
    </div>
  </section>

  <!-- EDUCATION -->
  <section id="education">
    <div class="container">
      <div class="section-label"></div>
      <h2 class="section-title">My <span class="gradient-text">Background</span></h2>
      <div class="edu-timeline">

        <div class="timeline-item">
          <div class="timeline-dot"></div>
          <div class="timeline-card">
            <div class="timeline-year">Aug 2023 — Jun 2027</div>
            <h3>B.Tech — Computer Science &amp; Engineering</h3>
            <p class="timeline-org">Manipal University Jaipur</p>
            <p class="timeline-desc">Relevant coursework: Artificial Intelligence, Machine Learning, Data Structures
              &amp; Algorithms, Predictive Analysis, OOP in Python, Operating Systems, Game Theory, RDBMS, Software
              Engineering.</p>
            <span class="timeline-tag">4th Year · Jaipur, India</span>
          </div>
        </div>

        <div class="timeline-item">
          <div class="timeline-dot"></div>
          <div class="timeline-card">
            <div class="timeline-year">May 2025 — Aug 2025</div>
            <h3>ML Intern — Team Lead</h3>
            <p class="timeline-org">WeSkill · Bangalore (Remote)</p>
            <p class="timeline-desc">Led a team of 6 interns. Built AI models for resume parsing &amp; job-matching (ATS
              +15%). Engineered OCR-based data extraction with PyTesseract (errors −35%). Automated hiring workflows
              using N8N (time −40%).</p>
            <span class="timeline-tag">Internship · Team Lead</span>
          </div>
        </div>



        <div class="timeline-item">
          <div class="timeline-dot"></div>
          <div class="timeline-card">
            <div class="timeline-year">Submitted Apr 2024 &mdash; Published Sept 2024</div>
            <h3>A Comprehensive Review of Generative AI Techniques &amp; Algorithms</h3>
            <p class="timeline-org">IMMRC 2024, IMM College</p>
            <p class="timeline-desc">Investigated and analyzed how AI language models generate responses — examining
              whether their outputs lean toward human-like reasoning and expression or follow rigid, machine-driven
              patterns. The study evaluates generative techniques and their alignment with natural human cognition.</p>
            <span class="timeline-tag">✅ Published</span>
          </div>
        </div>

        <div class="timeline-item">
          <div class="timeline-dot"></div>
          <div class="timeline-card">
            <div class="timeline-year">July 2025</div>
            <h3>Rank 1 — Google Cloud Skill Boost Gold League</h3>
            <p class="timeline-org">Google</p>
            <p class="timeline-desc">Secured Rank 1 in the Google Cloud Skill Boost Gold League with 9,915 points
              through advanced hands-on Cloud and AI/ML labs, demonstrating top-tier practical proficiency in real-world
              cloud infrastructure and machine learning workflows.</p>
            <span class="timeline-tag">🥇 Gold League Topper</span>
          </div>
        </div>

        <div class="timeline-item">
          <div class="timeline-dot"></div>
          <div class="timeline-card">
            <div class="timeline-year">Submitted Apr 2026</div>
            <h3>Effect of Data Augmentation on Transformer Models</h3>
            <p class="timeline-org">IMMRC 2026, IMM College</p>
            <p class="timeline-desc">The study provides insights into the limitations of simple augmentation techniques
              and contributes to understanding their impact on modern NLP models — offering a clearer picture of when
              and how augmentation strategies benefit transformer-based architectures.</p>
            <span class="timeline-tag">🔄 Under Review</span>
          </div>
        </div>

      </div>
    </div>
  </section>

  <!-- CERTIFICATES -->
  <section id="certificates">
    <div class="container">
      <div class="section-label">What I've Earned</div>
      <h2 class="section-title">My <span class="gradient-text">Certificates</span></h2>
      <div class="certs-grid">

        <div class="cert-card">
          <div class="cert-glow"></div>
          <div class="cert-header">
            <div class="cert-platform-badge" style="background:linear-gradient(135deg,#f97316,#fb923c);">Edureka</div>
            <span class="cert-date">March 2026</span>
          </div>
          <div class="cert-icon"><i class="fa fa-robot"></i></div>
          <h3 class="cert-name">Intro to LLMs &amp; HuggingFace</h3>
          <p class="cert-issuer">Edureka</p>
          <div class="cert-tags"><span>AI/ML</span><span>LLMs</span></div>
          <a href="https://www.coursera.org/account/accomplishments/verify/L3D2N5X1ABCI" target="_blank"
            class="cert-verify-btn"><i class="fa fa-external-link-alt"></i> Verify Certificate</a>
        </div>

        <div class="cert-card">
          <div class="cert-glow"></div>
          <div class="cert-header">
            <div class="cert-platform-badge" style="background:linear-gradient(135deg,#0f62fe,#4589ff);">IBM</div>
            <span class="cert-date">Apr 2025</span>
          </div>
          <div class="cert-icon"><i class="fa fa-brain"></i></div>
          <h3 class="cert-name">Generative AI Fundamentals</h3>
          <p class="cert-issuer">IBM &middot; Coursera</p>
          <div class="cert-tags"><span>GenAI</span><span>AI/ML</span></div>
          <a href="https://www.coursera.org/account/accomplishments/specialization/U7OPZ0G4EWGN" target="_blank"
            class="cert-verify-btn"><i class="fa fa-external-link-alt"></i> Verify Certificate</a>
        </div>

        <div class="cert-card">
          <div class="cert-glow"></div>
          <div class="cert-header">
            <div class="cert-platform-badge" style="background:linear-gradient(135deg,#0180ff,#00a8ff);">Meta</div>
            <span class="cert-date">July 2026</span>
          </div>
          <div class="cert-icon"><i class="fa fa-server"></i></div>
          <h3 class="cert-name">Meta Backend Developer Professional Certificate</h3>
          <p class="cert-issuer">Meta &middot; Coursera</p>
          <div class="cert-tags"><span>Backend</span><span>Professional</span></div>
          <a href="https://www.coursera.org/account/accomplishments/professional-cert/Y6DBVHJXC97U" target="_blank"
            class="cert-verify-btn"><i class="fa fa-external-link-alt"></i> Verify Certificate</a>
        </div>

        <div class="cert-card">
          <div class="cert-glow"></div>
          <div class="cert-header">
            <div class="cert-platform-badge" style="background:linear-gradient(135deg,#7c3aed,#a78bfa);">PrepInsta</div>
            <span class="cert-date">Jan 2026</span>
          </div>
          <div class="cert-icon"><i class="fa fa-chart-line"></i></div>
          <h3 class="cert-name">Machine Learning and AI</h3>
          <p class="cert-issuer">PrepInsta</p>
          <div class="cert-tags"><span>AI/ML</span><span>Data Science</span></div>
          <div class="cert-credential"><i class="fa fa-fingerprint"></i> ID: 69634700bc605076759ee9dd</div>
        </div>

      </div>
    </div>
  </section>

  <!-- CONTACT -->
  <section id="contact">
    <div class="container">
      <div class="section-label">Let's Connect</div>
      <h2 class="section-title">Get In <span class="gradient-text">Touch</span></h2>
      <div class="contact-grid">
        <div class="contact-info">
          <p class="contact-desc">I'm currently open to internships, full-time roles, and research collaborations.
            Whether you have a project in mind or just want to connect — my inbox is always open!</p>
          <div class="contact-items">
            <div class="contact-item">
              <div class="contact-icon"><i class="fa fa-envelope"></i></div>
              <div><span class="contact-label">Email</span><a href="mailto:arnavverma1110@gmail.com"
                  id="email-link">arnavverma1110@gmail.com</a></div>
            </div>
            <div class="contact-item">
              <div class="contact-icon"><i class="fab fa-linkedin"></i></div>
              <div><span class="contact-label">LinkedIn</span><a
                  href="https://www.linkedin.com/in/arnav-verma-084331192/" target="_blank"
                  id="linkedin-link2">linkedin.com/in/arnav-verma</a></div>
            </div>
            <div class="contact-item">
              <div class="contact-icon"><i class="fab fa-github"></i></div>
              <div><span class="contact-label">GitHub</span><a href="https://github.com/1M-ARNAVERMA" target="_blank"
                  id="github-link2">github.com/1M-ARNAVERMA</a></div>
            </div>
            <div class="contact-item">
              <div class="contact-icon"><i class="fa fa-phone"></i></div>
              <div><span class="contact-label">Phone</span><a href="tel:+917046106602">+91 7046106602</a></div>
            </div>
          </div>
        </div>
      </div>
    </div>
  </section>

  <!-- FOOTER -->
  <footer>
    <div class="container footer-inner">
      <p>Designed & Built by <span class="gradient-text">Arnav Verma</span> · 2026</p>
      <p class="footer-sub"></p>
    </div>
  </footer>

  <script src="script.js"></script>
</body>

</html>
