# Class_Portfolio-Clayton-
this is my UI/UX portfolio for my bootcamp course

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Clayton Dunagan - UI/UX Designer Portfolio</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <nav class="navigation">
        <div class="nav-left">
            <a href="#" class="home-icon">
          <svg class="icon" viewBox="0 0 24 24" width="24" height="24">
        <path d="M3 12l2-2m0 0l7-7 7 7M5 10v10a1 1 0 001 1h3m10-11l2 2m-2-2v10a1 1 0 01-1 1h-3m-6 0a1 1 0 001-1v-4a1 1 0 011-1h2a1 1 0 011 1v4a1 1 0 001 1m-6 0h6" stroke="currentColor" fill="none" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"/>
    </svg>
</a>    
            <a href="#" class="nav-link">Top Tracks</a>
            <a href="#" class="nav-link">Featured Designer</a>
        </div>
        <div class="nav-right">
            <a href="#" class="social-icon">
        <svg class="icon" viewBox="0 0 24 24" width="24" height="24">
            <path d="M16 8a6 6 0 0 1 6 6v7h-4v-7a2 2 0 0 0-2-2 2 2 0 0 0-2 2v7h-4v-7a6 6 0 0 1 6-6z" stroke="currentColor" fill="none" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"/>
            <rect x="2" y="9" width="4" height="12" stroke="currentColor" fill="none" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"/>
            <circle cx="4" cy="4" r="2" stroke="currentColor" fill="none" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"/>
        </svg>
    </a>
    <a href="#" class="social-icon">
        <svg class="icon" viewBox="0 0 24 24" width="24" height="24">
            <path d="M22.54 6.42a2.78 2.78 0 0 0-1.94-2C18.88 4 12 4 12 4s-6.88 0-8.6.46a2.78 2.78 0 0 0-1.94 2A29 29 0 0 0 1 11.75a29 29 0 0 0 .46 5.33A2.78 2.78 0 0 0 3.4 19c1.72.46 8.6.46 8.6.46s6.88 0 8.6-.46a2.78 2.78 0 0 0 1.94-2 29 29 0 0 0 .46-5.25 29 29 0 0 0-.46-5.33z" stroke="currentColor" fill="none" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"/>
            <polygon points="9.75 15.02 15.5 11.75 9.75 8.48 9.75 15.02" stroke="currentColor" fill="currentColor"/>
        </svg>
    </a>
</div>
    </nav>

    <main>
        <!-- Hero Section -->
        <section class="hero">
            <div class="hero-image-container">
                <div class="hero-image">
                    <span>HERO IMAGE (ACTION SHOT)</span>
                </div>
            </div>
            <div class="hero-text">
                <h2>Aspiring to build intuitive music experiences that click.</h2>
                <h2>Bringing fresh design perspectives & music industry knowledge.</h2>
                <h2>Encouraging discovery & social engagement</h2>
            </div>
        </section>

        <!-- Case Studies Section -->
        <section class="case-studies">
            <!-- Case Study Player -->
            <div class="case-study-carousel">
                <div class="featured-case-study">
                    <div class="case-study-image">
                        <span>Case Study Cover</span>
                    </div>
                    <p class="case-study-title">CASE STUDY TITLE</p>
                </div>
                <div class="carousel-controls">
               <!-- Left section - Now Favorite -->
    <div class="controls-left">
        <button class="control-btn favorite-btn" title="Save to Favorites">
            <svg width="18" height="18" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2">
                <path d="M12 21.35l-1.45-1.32C5.4 15.36 2 12.28 2 8.5 2 5.42 4.42 3 7.5 3c1.74 0 3.41.81 4.5 2.09C13.09 3.81 14.76 3 16.5 3 19.58 3 22 5.42 22 8.5c0 3.78-3.4 6.86-8.55 11.54L12 21.35z"/>
            </svg>
        </button>
    </div>

    <!-- Center section - Main playback controls -->
    <div class="controls-center">
        <button class="control-btn prev-btn" title="Previous Project">←</button>
        <button class="control-btn play-btn large" title="Auto-Play Projects">▶</button>
        <button class="control-btn next-btn" title="Next Project">→</button>
    </div>

    <!-- Right section - Now Shuffle and Repeat -->
    <div class="controls-right">
        <button class="control-btn shuffle-btn" title="Shuffle Projects">
            <svg width="18" height="18" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2">
                <path d="M16 3h5v5M4 20L21 3M21 16v5h-5M15 15l6 6M4 4l5 5"/>
            </svg>
        </button>
        <button class="control-btn repeat-btn" title="Loop Projects">
            <svg width="18" height="18" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2">
                <path d="M17 1l4 4-4 4"/>
                <path d="M3 11V9a4 4 0 014-4h14"/>
                <path d="M7 23l-4-4 4-4"/>
                <path d="M21 13v2a4 4 0 01-4 4H3"/>
            </svg>
        </button>
    </div>
</div>

            <!-- Case Study Grid -->
            <div class="case-study-grid">
                <div class="case-study-card">
                    <div class="case-study-image"></div>
                </div>
                <div class="case-study-card">
                    <div class="case-study-image"></div>
                </div>
                <div class="case-study-card">
                    <div class="case-study-image"></div>
                </div>
            </div>
        </section>

        <!-- Profile Section -->
        <section class="profile">
            <h2 class="featured-designer">Featured Designer "Clayton Dunagan"</h2>
            <div class="profile-content">
                <div class="headshot-container">
                    <div class="headshot">Head Shot</div>
                </div>
                <div class="profile-text">
                    <p>I am a Junior UI/UX designer bringing music industry instincts to digital design.</p>
                    <p>From artist management to live events, I know what turns on audience into fans on stage or on screen</p>
                    <p>My music business degree & industry experience let me speak both creative vision and business strategy</p>
                    
                    <div class="focus-areas">
                        <h3>Area of Focus:</h3>
                        <ul>
                            <li>Crafting intuitive digital experiences</li>
                            <li>Bringing event planning precision to design</li>
                            <li>Building stronger artist-fan connections</li>
                        </ul>
                    </div>
                </div>
            </div>
        </section>

        <!-- Skills and Discover Section -->
        <section class="skills-discover">
            <div class="skills">
                <h2>Skills & Interests</h2>
                <p>I connect music industry experience with digital design, drawing from my background in artist management and event coordination.</p>
                <p>As a new UI/UX designer with a focus on UX, I create experiences for the music space while planning to learn front and back-end coding and project management.</p>
                <p>I work best in creative spaces where I can use my understanding of what musicians and music lovers need, making digital tools that keep music's human touch.</p>
                <p>In my free time, you'll likely find me at local shows, collaborating with emerging artists, or exploring new design concepts for music-focused platforms.</p>
            </div>

            <div class="discover">
                <h2>Discover More</h2>
                <div class="education-card">
                    <h3>Education</h3>
                    <ul>
                        <li>Associates of Applied Science in Music Business (Austin Community College)</li>
                        <li>UI/UX Certification (University of Texas bootcamp)</li>
                    </ul>
                </div>
                <div class="contact-card">
                    <h3>Contact</h3>
                    <p>Email<br>clayfresh@yahoo.com</p>
                    <p>Phone<br>817-733-3466</p>
                </div>
            </div>
        </section>

        <button class="back-to-top">Back to Top</button>
    </main>

    <script src="script.js"></script>
</body>
</html>

/* Base Styles */
:root {
    --primary-green: #22c55e;
    --background-dark: #171717;
    --text-light: #d1d5db;
    --card-background: #ffffff;
}

* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

body {
    font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Oxygen, Ubuntu, Cantarell, sans-serif;
    background-color: var(--background-dark);
    color: var(--text-light);
    line-height: 1.6;
}

/* Navigation */
.navigation {
    display: flex;
    justify-content: space-between;
    align-items: center;
    padding: 1rem 2rem;
    background-color: var(--background-dark);
}

.nav-left, .nav-right {
    display: flex;
    gap: 1rem;
}

.home-icon {
    display: flex;
    align-items: center;
    color: var(--text-light);
    text-decoration: none;
    transition: color 0.3s ease;
}

.home-icon:hover {
    color: var(--primary-green);
}

.home-icon .icon {
    stroke: currentColor;
}

.nav-link, .social-icon {
    color: var(--text-light);
    text-decoration: none;
    transition: color 0.3s ease;
}

.nav-link {
    color: var(--text-light);
    text-decoration: none;
    transition: all 0.3s ease;
    padding: 8px 16px;
    border: 3px solid #B3B3B3;
    border-radius: 35px;
}

.nav-link:hover, .social-icon:hover {
    color: var(--primary-green);
    border-color: var(--primary-green);
}

.social-icon {
    display: flex;
    align-items: center;
    color: var(--text-light);
    text-decoration: none;
    transition: color 0.3s ease;
}

.social-icon:hover {
    color: var(--primary-green);
}

.social-icon .icon {
    stroke: currentColor;
}

/* Hero Section */
.hero {
    padding: 2rem 1rem;
    text-align: center;
}

.hero-image-container {
    max-width: 1000px;
    margin: 0 auto 2rem;
    padding: 0.5rem;
    background-color: var(--primary-green);
    border-radius: 1.5rem;
}

.hero-image {
    aspect-ratio: 16/9;
    background-color: var(--card-background);
    border-radius: 1rem;
    display: flex;
    align-items: center;
    justify-content: center;
    color: #666;
}

.hero-text {
    max-width: 800px;
    margin: 0 auto;
    text-align: center;
    padding: 2rem 1rem;
}

.hero-text h2 {
    margin-bottom: 1rem;
    font-size: 1.5rem;
    line-height: 1.4;
}

/* Case Studies Section */
.case-studies {
    padding: 1rem 1rem;
    display: flex;
    flex-direction: column;
    align-items: center;
}

/* Case Study Player */
.case-study-carousel {
    width: 100%;
    max-width: 800px;
    margin: 0 auto;
    text-align: center;
    padding: 2rem 1rem;
}

.featured-case-study {
    background-color: var(--primary-green);
    padding: 0.75rem;
    border-radius: 1.5rem;
    margin-bottom: 2rem;
    box-shadow: 0 4px 6px -1px rgba(0, 0, 0, 0.1), 0 2px 4px -1px rgba(0, 0, 0, 0.06);
}

.case-study-image {
    aspect-ratio: 16/9;
    background-color: var(--card-background);
    border-radius: 1rem;
    display: flex;
    align-items: center;
    justify-content: center;
    min-height: 400px;
}

.case-study-title {
    margin: 1.5rem 0;
    font-size: 1.5rem;
    color: var(--text-light);
    font-weight: 500;
}

/* Updated Carousel Controls */
.carousel-controls {
    display: flex;
    justify-content: space-between;
    align-items: center;
    width: 100%;
    max-width: 800px;
    margin: 0 auto;
    padding: 0 2rem;
    background-color: var(--background-dark);
}

.controls-left {
    flex: 1;
    display: flex;
    justify-content: flex-start;
}

.controls-center {
    flex: 2;
    display: flex;
    align-items: center;
    justify-content: center;
    gap: 1.5rem;
}

.controls-right {
    flex: 1;
    display: flex;
    justify-content: flex-end;
    gap: 1rem;
}

.control-btn {
    color: var(--text-light);
    background-color: transparent;
    border: 3px solid #B3B3B3;
    border-radius: 50%;
    width: 3.5rem;
    height: 3.5rem;
    cursor: pointer;
    transition: all 0.3s ease;
    display: flex;
    align-items: center;
    justify-content: center;
}

.control-btn.large {
    width: 4.5rem;
    height: 4.5rem;
}

.control-btn:hover {
    color: var(--primary-green);
    border-color: var(--primary-green);
}

.control-btn.active {
    color: var(--primary-green);
    border-color: var(--primary-green);
}

.control-btn svg {
    width: 24px;
    height: 24px;
    stroke: currentColor;
    stroke-width: 2;
}

/* Case Study Grid */
.case-study-grid {
    width: 100%;
    max-width: 800px;
    margin: 2rem auto;
    display: flex;
    gap: 2rem;
    padding: 1rem 2rem;
    overflow-x: auto;
    scrollbar-width: none; /* Firefox */
    -ms-overflow-style: none; /* IE and Edge */
}

.case-study-grid::-webkit-scrollbar {
    display: none; /* Chrome, Safari, Opera */
}

.case-study-grid .case-study-card {
    background-color: var(--primary-green);
    padding: 0.5rem;
    border-radius: 1.5rem;
    transition: transform 0.3s ease;
    min-width: 300px;
    flex-shrink: 0;
}

.case-study-grid .case-study-card:hover {
    transform: translateY(-5px);
}

.case-study-grid .case-study-image {
    aspect-ratio: 1;
}

/* Profile Section */
.profile {
    padding: 2rem 1rem;
    max-width: 1000px;
    margin: 0 auto;
}

.featured-designer {
    text-align: center;
    margin-bottom: 1rem;
}

.profile-content {
    display: grid;
    grid-template-columns: 1fr 1fr;
    gap: 1rem;
}

.headshot-container {
    background-color: var(--primary-green);
    padding: 0.5rem;
    border-radius: 1.5rem;
}

.headshot {
    aspect-ratio: 1;
    background-color: var(--card-background);
    border-radius: 1rem;
    display: flex;
    align-items: center;
    justify-content: center;
    color: #666;
}

.profile-text {
    display: flex;
    flex-direction: column;
    gap: 1rem;
}

/* Skills and Discover Section */
.skills-discover {
    padding: 2rem 1rem;
    max-width: 1000px;
    margin: 0 auto;
    display: grid;
    grid-template-columns: 1fr 1fr;
    gap: 1rem;
}

.education-card, .contact-card {
    background-color: var(--primary-green);
    padding: 0.5rem;
    border-radius: 1.5rem;
    margin-bottom: 0.5rem;
}

.education-card > div, .contact-card > div {
    background-color: var(--card-background);
    border-radius: 1rem;
    padding: 1.5rem;
    color: black;
}

.back-to-top {
    display: block;
    margin: 2rem auto;
    padding: 8px 16px;
    background-color: transparent;
    color: var(--text-light);
    border: 3px solid #B3B3B3;
    border-radius: 35px;
    cursor: pointer;
    transition: all 0.3s ease;
}

.back-to-top:hover {
    color: var(--primary-green);
    border-color: var(--primary-green);
}

/* Responsive Design */
@media (max-width: 768px) {
    .profile-content,
    .skills-discover {
        grid-template-columns: 1fr;
    }
    
    .case-study-carousel {
        max-width: 100%;
    }
    
    .carousel-controls {
        padding: 0 1rem;
    }
    
    .controls-center {
        gap: 1rem;
    }
}
