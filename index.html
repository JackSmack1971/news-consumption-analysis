<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>News Consumption Across the Political Spectrum: A Comprehensive Analysis</title>
    <link href="https://cdn.jsdelivr.net/npm/tailwindcss@2.2.19/dist/tailwind.min.css" rel="stylesheet">
    <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/@fortawesome/fontawesome-free@6.4.0/css/all.min.css">
    <script src="https://cdn.jsdelivr.net/npm/chart.js"></script>
    <script src="https://cdn.jsdelivr.net/npm/aos@2.3.4/dist/aos.js"></script>
    <link href="https://cdn.jsdelivr.net/npm/aos@2.3.4/dist/aos.css" rel="stylesheet">
    <style>
        @import url('https://fonts.googleapis.com/css2?family=Inter:wght@300;400;500;600;700;800&family=Poppins:wght@300;400;500;600;700;800&display=swap');
        
        :root {
            --primary-gradient: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
            --secondary-gradient: linear-gradient(135deg, #f093fb 0%, #f5576c 100%);
            --accent-gradient: linear-gradient(135deg, #4facfe 0%, #00f2fe 100%);
            --success-gradient: linear-gradient(135deg, #11998e 0%, #38ef7d 100%);
            --warning-gradient: linear-gradient(135deg, #fad961 0%, #f76b1c 100%);
            --card-shadow: 0 20px 25px -5px rgba(0, 0, 0, 0.1), 0 10px 10px -5px rgba(0, 0, 0, 0.04);
            --card-shadow-hover: 0 25px 50px -12px rgba(0, 0, 0, 0.25);
        }
        
        * {
            scroll-behavior: smooth;
        }
        
        body {
            font-family: 'Inter', sans-serif;
            line-height: 1.7;
            overflow-x: hidden;
        }
        
        .gradient-bg {
            background: var(--primary-gradient);
            position: relative;
            overflow: hidden;
        }
        
        .gradient-bg::before {
            content: '';
            position: absolute;
            top: 0;
            left: 0;
            right: 0;
            bottom: 0;
            background: url('data:image/svg+xml,<svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 1000 1000"><defs><radialGradient id="a" cx="50%" cy="50%" r="50%"><stop offset="0%" style="stop-color:rgba(255,255,255,0.1)"/><stop offset="100%" style="stop-color:rgba(255,255,255,0)"/></radialGradient></defs><circle cx="200" cy="200" r="100" fill="url(%23a)"/><circle cx="800" cy="300" r="150" fill="url(%23a)"/><circle cx="400" cy="700" r="120" fill="url(%23a)"/></svg>');
            opacity: 0.3;
            animation: float 20s ease-in-out infinite;
        }
        
        @keyframes float {
            0%, 100% { transform: translateY(0px) rotate(0deg); }
            50% { transform: translateY(-20px) rotate(180deg); }
        }
        
        .chart-container {
            height: 400px;
            margin: 20px 0;
            position: relative;
            background: rgba(255, 255, 255, 0.05);
            border-radius: 15px;
            padding: 20px;
            backdrop-filter: blur(10px);
        }
        
        .podcast-player {
            background: var(--secondary-gradient);
            border-radius: 20px;
            padding: 30px;
            color: white;
            box-shadow: var(--card-shadow);
            position: relative;
            overflow: hidden;
        }
        
        .podcast-player::before {
            content: '';
            position: absolute;
            top: -50%;
            left: -50%;
            width: 200%;
            height: 200%;
            background: radial-gradient(circle, rgba(255,255,255,0.1) 0%, transparent 70%);
            animation: pulse 4s ease-in-out infinite;
        }
        
        @keyframes pulse {
            0%, 100% { transform: scale(1); opacity: 0.7; }
            50% { transform: scale(1.05); opacity: 1; }
        }
        
        .finding-card {
            transition: all 0.4s cubic-bezier(0.175, 0.885, 0.32, 1.275);
            background: white;
            border-radius: 20px;
            padding: 30px;
            box-shadow: var(--card-shadow);
            position: relative;
            overflow: hidden;
        }
        
        .finding-card::before {
            content: '';
            position: absolute;
            top: 0;
            left: 0;
            right: 0;
            height: 4px;
            background: var(--primary-gradient);
            transform: scaleX(0);
            transform-origin: left;
            transition: transform 0.3s ease;
        }
        
        .finding-card:hover::before {
            transform: scaleX(1);
        }
        
        .finding-card:hover {
            transform: translateY(-10px) scale(1.02);
            box-shadow: var(--card-shadow-hover);
        }
        
        .stat-number {
            font-size: 3.5rem;
            font-weight: 800;
            font-family: 'Poppins', sans-serif;
            background: var(--primary-gradient);
            -webkit-background-clip: text;
            -webkit-text-fill-color: transparent;
            background-clip: text;
            display: inline-block;
            animation: countUp 2s ease-out;
        }
        
        @keyframes countUp {
            from { opacity: 0; transform: translateY(20px); }
            to { opacity: 1; transform: translateY(0); }
        }
        
        .section-divider {
            height: 3px;
            background: var(--primary-gradient);
            margin: 60px 0;
            border-radius: 3px;
            position: relative;
            overflow: hidden;
        }
        
        .section-divider::after {
            content: '';
            position: absolute;
            top: 0;
            left: -100%;
            width: 100%;
            height: 100%;
            background: linear-gradient(90deg, transparent, rgba(255,255,255,0.8), transparent);
            animation: shimmer 3s ease-in-out infinite;
        }
        
        @keyframes shimmer {
            0% { left: -100%; }
            100% { left: 100%; }
        }
        
        .icon-container {
            width: 80px;
            height: 80px;
            border-radius: 50%;
            display: flex;
            align-items: center;
            justify-content: center;
            margin: 0 auto 24px;
            position: relative;
            overflow: hidden;
        }
        
        .icon-container::before {
            content: '';
            position: absolute;
            top: 0;
            left: 0;
            right: 0;
            bottom: 0;
            background: inherit;
            border-radius: 50%;
            filter: blur(8px);
            opacity: 0.3;
            z-index: -1;
        }
        
        .progress-bar {
            position: fixed;
            top: 0;
            left: 0;
            width: 100%;
            height: 4px;
            background: rgba(255, 255, 255, 0.1);
            z-index: 1000;
        }
        
        .progress-fill {
            height: 100%;
            background: var(--accent-gradient);
            width: 0%;
            transition: width 0.3s ease;
        }
        
        .floating-nav {
            position: fixed;
            right: 30px;
            top: 50%;
            transform: translateY(-50%);
            z-index: 100;
            display: flex;
            flex-direction: column;
            gap: 10px;
        }
        
        .nav-dot {
            width: 12px;
            height: 12px;
            border-radius: 50%;
            background: rgba(255, 255, 255, 0.3);
            cursor: pointer;
            transition: all 0.3s ease;
        }
        
        .nav-dot.active {
            background: white;
            transform: scale(1.3);
        }
        
        .glass-card {
            background: rgba(255, 255, 255, 0.15);
            backdrop-filter: blur(10px);
            border: 1px solid rgba(255, 255, 255, 0.2);
            border-radius: 20px;
            padding: 30px;
            color: white;
        }
        
        .metric-card {
            background: white;
            border-radius: 20px;
            padding: 30px;
            box-shadow: var(--card-shadow);
            transition: all 0.3s ease;
            position: relative;
            overflow: hidden;
        }
        
        .metric-card::after {
            content: '';
            position: absolute;
            top: 0;
            left: 0;
            right: 0;
            bottom: 0;
            background: var(--primary-gradient);
            opacity: 0;
            transition: opacity 0.3s ease;
            pointer-events: none;
        }
        
        .metric-card:hover::after {
            opacity: 0.05;
        }
        
        .animated-counter {
            font-size: 3.5rem;
            font-weight: 800;
            font-family: 'Poppins', sans-serif;
            background: var(--primary-gradient);
            -webkit-background-clip: text;
            -webkit-text-fill-color: transparent;
            background-clip: text;
            display: inline-block;
        }
        
        .chart-wrapper {
            background: white;
            border-radius: 20px;
            padding: 40px;
            box-shadow: var(--card-shadow);
            margin: 30px 0;
        }
        
        .hero-subtitle {
            font-size: 1.5rem;
            font-weight: 300;
            opacity: 0.9;
            max-width: 800px;
            margin: 0 auto;
            line-height: 1.6;
        }
        
        .section-header {
            text-align: center;
            margin-bottom: 50px;
        }
        
        .section-title {
            font-size: 2.5rem;
            font-weight: 700;
            font-family: 'Poppins', sans-serif;
            margin-bottom: 20px;
            background: var(--primary-gradient);
            -webkit-background-clip: text;
            -webkit-text-fill-color: transparent;
            background-clip: text;
        }
        
        .perfect-storm-item {
            text-align: center;
            padding: 30px;
            background: white;
            border-radius: 15px;
            box-shadow: var(--card-shadow);
            transition: all 0.3s ease;
        }
        
        .perfect-storm-item:hover {
            transform: translateY(-5px);
            box-shadow: var(--card-shadow-hover);
        }
        
        .conclusion-card {
            background: white;
            border-radius: 25px;
            padding: 50px;
            box-shadow: var(--card-shadow);
            position: relative;
            overflow: hidden;
        }
        
        .conclusion-card::before {
            content: '';
            position: absolute;
            top: 0;
            left: 0;
            right: 0;
            height: 5px;
            background: var(--primary-gradient);
        }
        
        .cta-section {
            background: var(--primary-gradient);
            border-radius: 25px;
            padding: 50px;
            text-align: center;
            color: white;
            position: relative;
            overflow: hidden;
        }
        
        .cta-section::before {
            content: '';
            position: absolute;
            top: 0;
            left: 0;
            right: 0;
            bottom: 0;
            background: url('data:image/svg+xml,<svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 100 100"><defs><pattern id="grain" width="100" height="100" patternUnits="userSpaceOnUse"><circle cx="25" cy="25" r="1" fill="rgba(255,255,255,0.1)"/><circle cx="75" cy="75" r="1" fill="rgba(255,255,255,0.1)"/><circle cx="50" cy="10" r="1" fill="rgba(255,255,255,0.1)"/><circle cx="20" cy="60" r="1" fill="rgba(255,255,255,0.1)"/><circle cx="80" cy="40" r="1" fill="rgba(255,255,255,0.1)"/></pattern></defs><rect width="100" height="100" fill="url(%23grain)"/></svg>');
            opacity: 0.3;
        }
        
        .quote-highlight {
            background: rgba(255, 255, 255, 0.15);
            border-left: 4px solid white;
            padding: 20px;
            border-radius: 10px;
            font-style: italic;
            margin: 20px 0;
        }
        
        audio {
            width: 100%;
            border-radius: 10px;
            background: rgba(255, 255, 255, 0.1);
        }
        
        .mechanism-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
            gap: 30px;
            margin: 30px 0;
        }
        
        .mechanism-item {
            background: white;
            border-radius: 15px;
            padding: 30px;
            box-shadow: var(--card-shadow);
            transition: all 0.3s ease;
        }
        
        .mechanism-item:hover {
            transform: translateY(-5px);
        }
        
        .fade-in {
            opacity: 0;
            transform: translateY(30px);
            animation: fadeInUp 0.8s ease forwards;
        }
        
        @keyframes fadeInUp {
            to {
                opacity: 1;
                transform: translateY(0);
            }
        }
        
        @media (max-width: 768px) {
            .floating-nav {
                display: none;
            }
            
            .stat-number {
                font-size: 2.5rem;
            }
            
            .hero-subtitle {
                font-size: 1.2rem;
            }
            
            .section-title {
                font-size: 2rem;
            }
        }
        
        @media print {
            .floating-nav, .progress-bar {
                display: none !important;
            }
            
            .gradient-bg::before {
                display: none;
            }
            
            * {
                color-adjust: exact !important;
                -webkit-print-color-adjust: exact !important;
            }
        }
    </style>
</head>
<body class="bg-gray-50">
    <!-- Progress Bar -->
    <div class="progress-bar">
        <div class="progress-fill"></div>
    </div>
    
    <!-- Floating Navigation -->
    <div class="floating-nav">
        <div class="nav-dot active" data-target="#header"></div>
        <div class="nav-dot" data-target="#podcast"></div>
        <div class="nav-dot" data-target="#statistics"></div>
        <div class="nav-dot" data-target="#charts"></div>
        <div class="nav-dot" data-target="#findings"></div>
        <div class="nav-dot" data-target="#psychology"></div>
        <div class="nav-dot" data-target="#conclusion"></div>
    </div>

    <!-- Header -->
    <header id="header" class="gradient-bg text-white py-16 relative">
        <div class="max-w-7xl mx-auto px-6 relative z-10">
            <div class="text-center" data-aos="fade-up" data-aos-duration="1000">
                <h1 class="text-5xl md:text-6xl font-bold mb-6 leading-tight">
                    News Consumption Across the Political Spectrum
                </h1>
                <p class="hero-subtitle">
                    A Comprehensive Analysis of Media Consumption Patterns in the Digital Age
                </p>
                <div class="mt-8 flex justify-center">
                    <div class="bg-white bg-opacity-20 backdrop-filter backdrop-blur-lg rounded-full px-8 py-4">
                        <p class="text-lg font-medium">
                            <i class="fas fa-chart-line mr-2"></i>
                            Data-Driven Insights from Leading Research Institutions
                        </p>
                    </div>
                </div>
            </div>
        </div>
    </header>

    <!-- Main Content -->
    <main class="max-w-7xl mx-auto px-6 py-12">
        
        <!-- Podcast Player Section -->
        <section id="podcast" class="mb-16" data-aos="fade-up" data-aos-duration="800">
            <div class="podcast-player relative z-10">
                <div class="flex flex-col lg:flex-row items-center gap-8">
                    <div class="w-40 h-40 rounded-2xl overflow-hidden shadow-2xl flex-shrink-0">
                        <img src="https://cdn1.genspark.ai/user-upload-image/gpt_image_generated/5141ce01-797b-494a-b379-5fcbf8096efc" 
                             alt="Podcast Cover" 
                             class="w-full h-full object-cover transform hover:scale-105 transition-transform duration-300">
                    </div>
                    <div class="flex-1">
                        <h2 class="text-3xl font-bold mb-3">
                            <i class="fas fa-podcast mr-3"></i>
                            Listen to the Full Analysis
                        </h2>
                        <div class="flex items-center gap-6 mb-6 text-white opacity-90">
                            <div class="flex items-center gap-2">
                                <i class="fas fa-clock"></i>
                                <span>5 minutes 47 seconds</span>
                            </div>
                            <div class="flex items-center gap-2">
                                <i class="fas fa-users"></i>
                                <span>Two-host dialogue</span>
                            </div>
                            <div class="flex items-center gap-2">
                                <i class="fas fa-microphone"></i>
                                <span>Expert Commentary</span>
                            </div>
                        </div>
                        <audio controls class="w-full rounded-lg">
                            <source src="https://cdn1.genspark.ai/user-upload-image/8/a2b5bf28-3803-4012-bd9a-05e08bd26a13.mp3" type="audio/mpeg">
                            Your browser does not support the audio element.
                        </audio>
                    </div>
                </div>
            </div>
        </section>

        <div class="section-divider"></div>

        <!-- Key Statistics -->
        <section id="statistics" class="mb-16">
            <div class="section-header" data-aos="fade-up">
                <h2 class="section-title">Key Statistics</h2>
                <p class="text-xl text-gray-600">Critical data points that reveal the depth of media consumption patterns</p>
            </div>
            <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-4 gap-8">
                <div class="metric-card text-center" data-aos="fade-up" data-aos-delay="100">
                    <div class="animated-counter" data-target="57">0</div>
                    <div class="text-lg font-semibold text-gray-800 mt-2">%</div>
                    <p class="text-gray-600 mt-3 font-medium">Republicans get news from Fox News</p>
                </div>
                <div class="metric-card text-center" data-aos="fade-up" data-aos-delay="200">
                    <div class="animated-counter" data-target="58">0</div>
                    <div class="text-lg font-semibold text-gray-800 mt-2">%</div>
                    <p class="text-gray-600 mt-3 font-medium">Democrats trust CNN</p>
                </div>
                <div class="metric-card text-center" data-aos="fade-up" data-aos-delay="300">
                    <div class="animated-counter" data-target="58">0</div>
                    <div class="text-lg font-semibold text-gray-800 mt-2">%</div>
                    <p class="text-gray-600 mt-3 font-medium">Republicans distrust CNN</p>
                </div>
                <div class="metric-card text-center" data-aos="fade-up" data-aos-delay="400">
                    <div class="animated-counter" data-target="79">0</div>
                    <div class="text-lg font-semibold text-gray-800 mt-2">%</div>
                    <p class="text-gray-600 mt-3 font-medium">Gen Z & Millennials get news daily</p>
                </div>
            </div>
        </section>

        <!-- Charts Section -->
        <section id="charts" class="mb-16">
            <!-- Source Diversity Chart -->
            <div class="chart-wrapper" data-aos="fade-up" data-aos-duration="800">
                <h3 class="text-2xl font-bold mb-6 text-center">News Source Diversity by Political Affiliation</h3>
                <div class="chart-container">
                    <canvas id="sourceDiversityChart"></canvas>
                </div>
            </div>

            <!-- Trust Levels Chart -->
            <div class="chart-wrapper" data-aos="fade-up" data-aos-duration="800">
                <h3 class="text-2xl font-bold mb-6 text-center">Trust Levels in Major News Sources</h3>
                <div class="chart-container">
                    <canvas id="trustChart"></canvas>
                </div>
            </div>

            <!-- Generational Preferences Chart -->
            <div class="chart-wrapper" data-aos="fade-up" data-aos-duration="800">
                <h3 class="text-2xl font-bold mb-6 text-center">News Platform Preferences by Generation</h3>
                <div class="chart-container">
                    <canvas id="generationalChart"></canvas>
                </div>
            </div>
        </section>

        <!-- Key Findings -->
        <section id="findings" class="mb-16">
            <div class="section-header" data-aos="fade-up">
                <h2 class="section-title">Key Findings</h2>
                <p class="text-xl text-gray-600">Discover the critical insights that shape our understanding of modern media consumption</p>
            </div>
            <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 gap-8">
                <div class="finding-card" data-aos="fade-up" data-aos-delay="100">
                    <div class="icon-container bg-blue-100 mb-6">
                        <i class="fas fa-balance-scale text-3xl text-blue-600"></i>
                    </div>
                    <h3 class="text-xl font-bold mb-4">The Asymmetrical Divide</h3>
                    <p class="text-gray-600 leading-relaxed">Democrats consume from a wide range of sources, while Republicans concentrate heavily on Fox News and select conservative outlets.</p>
                </div>
                
                <div class="finding-card" data-aos="fade-up" data-aos-delay="200">
                    <div class="icon-container bg-red-100 mb-6">
                        <i class="fas fa-brain text-3xl text-red-600"></i>
                    </div>
                    <h3 class="text-xl font-bold mb-4">Partisanship Trumps Truth</h3>
                    <p class="text-gray-600 leading-relaxed">People are more likely to reject TRUE information that challenges their worldview than accept FALSE information that confirms it.</p>
                </div>
                
                <div class="finding-card" data-aos="fade-up" data-aos-delay="300">
                    <div class="icon-container bg-green-100 mb-6">
                        <i class="fas fa-shield-alt text-3xl text-green-600"></i>
                    </div>
                    <h3 class="text-xl font-bold mb-4">Identity Protection</h3>
                    <p class="text-gray-600 leading-relaxed">Our brains act like "security guards," filtering information to protect our political identity and group membership.</p>
                </div>
                
                <div class="finding-card" data-aos="fade-up" data-aos-delay="400">
                    <div class="icon-container bg-purple-100 mb-6">
                        <i class="fas fa-robot text-3xl text-purple-600"></i>
                    </div>
                    <h3 class="text-xl font-bold mb-4">Algorithmic Amplification</h3>
                    <p class="text-gray-600 leading-relaxed">Social media algorithms create echo chambers by limiting exposure to opposing viewpoints, even when users subscribe to diverse sources.</p>
                </div>
                
                <div class="finding-card" data-aos="fade-up" data-aos-delay="500">
                    <div class="icon-container bg-orange-100 mb-6">
                        <i class="fas fa-users text-3xl text-orange-600"></i>
                    </div>
                    <h3 class="text-xl font-bold mb-4">Generational Shift</h3>
                    <p class="text-gray-600 leading-relaxed">Gen Z and Millennials increasingly trust individual creators on social platforms over traditional institutional sources.</p>
                </div>
                
                <div class="finding-card" data-aos="fade-up" data-aos-delay="600">
                    <div class="icon-container bg-indigo-100 mb-6">
                        <i class="fas fa-graduation-cap text-3xl text-indigo-600"></i>
                    </div>
                    <h3 class="text-xl font-bold mb-4">Education Doesn't Protect</h3>
                    <p class="text-gray-600 leading-relaxed">Higher education and reasoning ability don't protect against partisan bias in news consumption and interpretation.</p>
                </div>
            </div>
        </section>

        <!-- Psychological Mechanisms -->
        <section id="psychology" class="mb-16">
            <div class="section-header" data-aos="fade-up">
                <h2 class="section-title">Psychological Mechanisms</h2>
                <p class="text-xl text-gray-600">Understanding the mental processes that drive news consumption patterns</p>
            </div>
            <div class="mechanism-grid">
                <div class="mechanism-item" data-aos="fade-up" data-aos-delay="100">
                    <div class="flex items-center mb-4">
                        <div class="w-12 h-12 bg-blue-100 rounded-full flex items-center justify-center mr-4">
                            <i class="fas fa-search text-blue-600"></i>
                        </div>
                        <h3 class="text-xl font-bold text-blue-600">Confirmation Bias</h3>
                    </div>
                    <p class="text-gray-600 leading-relaxed">The tendency to seek information that confirms existing beliefs while avoiding contradictory evidence.</p>
                </div>
                
                <div class="mechanism-item" data-aos="fade-up" data-aos-delay="200">
                    <div class="flex items-center mb-4">
                        <div class="w-12 h-12 bg-red-100 rounded-full flex items-center justify-center mr-4">
                            <i class="fas fa-lightbulb text-red-600"></i>
                        </div>
                        <h3 class="text-xl font-bold text-red-600">Motivated Reasoning</h3>
                    </div>
                    <p class="text-gray-600 leading-relaxed">Actively looking for reasons to justify predetermined conclusions rather than objectively evaluating evidence.</p>
                </div>
                
                <div class="mechanism-item" data-aos="fade-up" data-aos-delay="300">
                    <div class="flex items-center mb-4">
                        <div class="w-12 h-12 bg-green-100 rounded-full flex items-center justify-center mr-4">
                            <i class="fas fa-users text-green-600"></i>
                        </div>
                        <h3 class="text-xl font-bold text-green-600">Social Identity Theory</h3>
                    </div>
                    <p class="text-gray-600 leading-relaxed">Deriving self-worth from group membership, making political tribe a primary source of identity.</p>
                </div>
                
                <div class="mechanism-item" data-aos="fade-up" data-aos-delay="400">
                    <div class="flex items-center mb-4">
                        <div class="w-12 h-12 bg-purple-100 rounded-full flex items-center justify-center mr-4">
                            <i class="fas fa-exclamation-triangle text-purple-600"></i>
                        </div>
                        <h3 class="text-xl font-bold text-purple-600">Cognitive Dissonance</h3>
                    </div>
                    <p class="text-gray-600 leading-relaxed">Discomfort when confronted with information that contradicts existing beliefs or values.</p>
                </div>
            </div>
        </section>

        <!-- The Perfect Storm -->
        <section class="mb-16" data-aos="fade-up">
            <div class="section-header">
                <h2 class="section-title">The Perfect Storm</h2>
                <p class="text-xl text-gray-600">How multiple factors combine to create unprecedented polarization</p>
            </div>
            <div class="bg-gradient-to-br from-red-50 via-purple-50 to-blue-50 rounded-3xl p-8">
                <div class="text-center mb-8">
                    <p class="text-xl text-gray-700 font-medium">Current media landscape creates ideal conditions for polarization through:</p>
                </div>
                <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-4 gap-6">
                    <div class="perfect-storm-item" data-aos="fade-up" data-aos-delay="100">
                        <div class="icon-container bg-blue-100 mb-4">
                            <i class="fas fa-building text-2xl text-blue-600"></i>
                        </div>
                        <h4 class="font-bold mb-3 text-lg">Structural Asymmetry</h4>
                        <p class="text-sm text-gray-600">Different consumption patterns between political groups</p>
                    </div>
                    <div class="perfect-storm-item" data-aos="fade-up" data-aos-delay="200">
                        <div class="icon-container bg-red-100 mb-4">
                            <i class="fas fa-cogs text-2xl text-red-600"></i>
                        </div>
                        <h4 class="font-bold mb-3 text-lg">Algorithmic Amplification</h4>
                        <p class="text-sm text-gray-600">Technology that reinforces existing preferences</p>
                    </div>
                    <div class="perfect-storm-item" data-aos="fade-up" data-aos-delay="300">
                        <div class="icon-container bg-green-100 mb-4">
                            <i class="fas fa-brain text-2xl text-green-600"></i>
                        </div>
                        <h4 class="font-bold mb-3 text-lg">Psychological Predisposition</h4>
                        <p class="text-sm text-gray-600">Natural tendency to defend tribal identity</p>
                    </div>
                    <div class="perfect-storm-item" data-aos="fade-up" data-aos-delay="400">
                        <div class="icon-container bg-purple-100 mb-4">
                            <i class="fas fa-chart-line-down text-2xl text-purple-600"></i>
                        </div>
                        <h4 class="font-bold mb-3 text-lg">Declining Trust</h4>
                        <p class="text-sm text-gray-600">Erosion of shared authoritative sources</p>
                    </div>
                </div>
            </div>
        </section>

        <!-- Conclusion -->
        <section id="conclusion" class="mb-16">
            <div class="conclusion-card" data-aos="fade-up" data-aos-duration="1000">
                <div class="section-header">
                    <h2 class="section-title">The Bottom Line</h2>
                </div>
                <div class="prose prose-lg max-w-4xl mx-auto">
                    <p class="text-gray-700 mb-6 text-lg leading-relaxed">
                        This analysis reveals that news consumption patterns aren't simply about preference—they're deeply intertwined with identity, psychology, and technology. The divide isn't just about different sources; it's about fundamentally different information ecosystems that shape how we understand reality itself.
                    </p>
                    <p class="text-gray-700 mb-6 text-lg leading-relaxed">
                        The most concerning finding? Education and reasoning ability don't protect against these biases. This suggests that bridging the divide requires more than just better media literacy—it demands conscious effort to overcome our natural psychological defenses.
                    </p>
                    <div class="bg-gradient-to-r from-blue-50 to-purple-50 p-8 rounded-2xl border-l-4 border-blue-500">
                        <h3 class="text-xl font-bold mb-4 text-blue-800">
                            <i class="fas fa-key mr-2"></i>Key Takeaway
                        </h3>
                        <p class="text-blue-700 text-lg leading-relaxed">
                            Understanding these patterns is the first step toward more informed consumption and, potentially, a more shared understanding of facts in our democratic society.
                        </p>
                    </div>
                </div>
            </div>
        </section>

        <!-- Call to Action -->
        <section class="mb-16" data-aos="fade-up" data-aos-duration="1000">
            <div class="cta-section relative z-10">
                <h2 class="text-3xl font-bold mb-6">What's Your Next Step?</h2>
                <p class="text-xl mb-8 leading-relaxed max-w-3xl mx-auto">
                    The podcast challenges listeners to identify one concrete action they can take this week to engage with perspectives beyond their usual media comfort zone.
                </p>
                <div class="quote-highlight max-w-4xl mx-auto">
                    <p class="text-lg italic leading-relaxed">
                        <i class="fas fa-quote-left mr-2"></i>
                        "Knowing that your brain is built to filter the world this way, what is one small, concrete step you could take this week to consciously look past your own mental security guard?"
                        <i class="fas fa-quote-right ml-2"></i>
                    </p>
                </div>
                <div class="mt-8 grid grid-cols-1 md:grid-cols-3 gap-6 max-w-4xl mx-auto">
                    <div class="glass-card text-center">
                        <i class="fas fa-newspaper text-2xl mb-3"></i>
                        <h4 class="font-bold mb-2">Read Across the Aisle</h4>
                        <p class="text-sm opacity-90">Subscribe to one news source from a different political perspective</p>
                    </div>
                    <div class="glass-card text-center">
                        <i class="fas fa-comments text-2xl mb-3"></i>
                        <h4 class="font-bold mb-2">Engage Respectfully</h4>
                        <p class="text-sm opacity-90">Have one thoughtful conversation with someone who disagrees with you</p>
                    </div>
                    <div class="glass-card text-center">
                        <i class="fas fa-question-circle text-2xl mb-3"></i>
                        <h4 class="font-bold mb-2">Question Your Sources</h4>
                        <p class="text-sm opacity-90">Ask yourself: "What might I be missing?" before sharing news</p>
                    </div>
                </div>
            </div>
        </section>
    </main>

    <!-- Footer -->
    <footer class="bg-gray-900 text-white py-12">
        <div class="max-w-7xl mx-auto px-6 text-center">
            <div class="mb-6">
                <h3 class="text-xl font-bold mb-2">Sources & Methodology</h3>
                <p class="text-gray-300">Based on comprehensive research from Pew Research Center, Stanford University, and other leading institutions</p>
            </div>
            <div class="border-t border-gray-700 pt-6">
                <p class="text-gray-400">&copy; 2025 News Consumption Analysis. All rights reserved.</p>
            </div>
        </div>
    </footer>

    <script>
        // Initialize AOS
        AOS.init({
            duration: 800,
            once: true,
            offset: 100
        });

        // Animated counters
        function animateCounter(element, target, duration = 2000) {
            const startTime = Date.now();
            const startValue = 0;
            
            function updateCounter() {
                const currentTime = Date.now();
                const elapsed = currentTime - startTime;
                const progress = Math.min(elapsed / duration, 1);
                
                const currentValue = Math.round(startValue + (target - startValue) * progress);
                element.textContent = currentValue;
                
                if (progress < 1) {
                    requestAnimationFrame(updateCounter);
                }
            }
            
            requestAnimationFrame(updateCounter);
        }

        // Trigger counters when in view
        const counterElements = document.querySelectorAll('.animated-counter');
        const observer = new IntersectionObserver((entries) => {
            entries.forEach(entry => {
                if (entry.isIntersecting) {
                    const target = parseInt(entry.target.dataset.target);
                    animateCounter(entry.target, target);
                    observer.unobserve(entry.target);
                }
            });
        });

        counterElements.forEach(el => observer.observe(el));

        // Progress bar
        function updateProgressBar() {
            const scrollTop = window.pageYOffset;
            const docHeight = document.body.offsetHeight;
            const winHeight = window.innerHeight;
            const scrollPercent = scrollTop / (docHeight - winHeight);
            const scrollPercentRounded = Math.round(scrollPercent * 100);
            
            document.querySelector('.progress-fill').style.width = scrollPercentRounded + '%';
        }

        window.addEventListener('scroll', updateProgressBar);

        // Floating navigation
        const navDots = document.querySelectorAll('.nav-dot');
        const sections = document.querySelectorAll('section[id], header[id]');

        function updateActiveNavDot() {
            let currentSection = '';
            sections.forEach(section => {
                const sectionTop = section.offsetTop;
                const sectionHeight = section.clientHeight;
                if (window.pageYOffset >= sectionTop - 200) {
                    currentSection = section.getAttribute('id');
                }
            });

            navDots.forEach(dot => {
                dot.classList.remove('active');
                const target = dot.getAttribute('data-target').substring(1);
                if (target === currentSection) {
                    dot.classList.add('active');
                }
            });
        }

        window.addEventListener('scroll', updateActiveNavDot);

        navDots.forEach(dot => {
            dot.addEventListener('click', () => {
                const targetId = dot.getAttribute('data-target');
                const targetElement = document.querySelector(targetId);
                if (targetElement) {
                    targetElement.scrollIntoView({ behavior: 'smooth' });
                }
            });
        });

        // Charts
        Chart.defaults.font.family = 'Inter';
        Chart.defaults.font.size = 14;

        // Source Diversity Chart
        const sourceDiversityCtx = document.getElementById('sourceDiversityChart').getContext('2d');
        new Chart(sourceDiversityCtx, {
            type: 'bar',
            data: {
                labels: ['Democrats', 'Republicans'],
                datasets: [{
                    label: 'Number of Trusted Sources',
                    data: [12, 3],
                    backgroundColor: ['rgba(59, 130, 246, 0.8)', 'rgba(239, 68, 68, 0.8)'],
                    borderColor: ['rgba(59, 130, 246, 1)', 'rgba(239, 68, 68, 1)'],
                    borderWidth: 2,
                    borderRadius: 8,
                    borderSkipped: false
                }]
            },
            options: {
                responsive: true,
                maintainAspectRatio: false,
                plugins: {
                    legend: {
                        display: false
                    }
                },
                scales: {
                    y: {
                        beginAtZero: true,
                        max: 15,
                        grid: {
                            color: 'rgba(0, 0, 0, 0.05)'
                        }
                    },
                    x: {
                        grid: {
                            display: false
                        }
                    }
                },
                animation: {
                    duration: 2000,
                    easing: 'easeInOutQuart'
                }
            }
        });

        // Trust Chart
        const trustCtx = document.getElementById('trustChart').getContext('2d');
        new Chart(trustCtx, {
            type: 'bar',
            data: {
                labels: ['Fox News', 'CNN', 'NPR', 'The New York Times', 'ABC News'],
                datasets: [{
                    label: 'Republican Trust (%)',
                    data: [56, 21, 15, 12, 25],
                    backgroundColor: 'rgba(239, 68, 68, 0.8)',
                    borderColor: 'rgba(239, 68, 68, 1)',
                    borderWidth: 2,
                    borderRadius: 8
                }, {
                    label: 'Democrat Trust (%)',
                    data: [18, 58, 52, 49, 46],
                    backgroundColor: 'rgba(59, 130, 246, 0.8)',
                    borderColor: 'rgba(59, 130, 246, 1)',
                    borderWidth: 2,
                    borderRadius: 8
                }]
            },
            options: {
                responsive: true,
                maintainAspectRatio: false,
                plugins: {
                    legend: {
                        position: 'top',
                        labels: {
                            boxWidth: 12,
                            padding: 15
                        }
                    }
                },
                scales: {
                    y: {
                        beginAtZero: true,
                        max: 70,
                        grid: {
                            color: 'rgba(0, 0, 0, 0.05)'
                        }
                    },
                    x: {
                        grid: {
                            display: false
                        }
                    }
                },
                animation: {
                    duration: 2000,
                    easing: 'easeInOutQuart'
                }
            }
        });

        // Generational Chart
        const generationalCtx = document.getElementById('generationalChart').getContext('2d');
        new Chart(generationalCtx, {
            type: 'doughnut',
            data: {
                labels: ['Social Media', 'Traditional TV', 'Online News Sites', 'Podcasts', 'Print Media'],
                datasets: [{
                    label: 'Gen Z/Millennials (%)',
                    data: [45, 15, 25, 12, 3],
                    backgroundColor: [
                        'rgba(139, 92, 246, 0.8)',
                        'rgba(6, 182, 212, 0.8)',
                        'rgba(16, 185, 129, 0.8)',
                        'rgba(245, 158, 11, 0.8)',
                        'rgba(239, 68, 68, 0.8)'
                    ],
                    borderColor: [
                        'rgba(139, 92, 246, 1)',
                        'rgba(6, 182, 212, 1)',
                        'rgba(16, 185, 129, 1)',
                        'rgba(245, 158, 11, 1)',
                        'rgba(239, 68, 68, 1)'
                    ],
                    borderWidth: 2
                }]
            },
            options: {
                responsive: true,
                maintainAspectRatio: false,
                plugins: {
                    legend: {
                        position: 'right',
                        labels: {
                            boxWidth: 12,
                            padding: 15
                        }
                    }
                },
                animation: {
                    duration: 2000,
                    easing: 'easeInOutQuart'
                }
            }
        });

        // Smooth scroll for all internal links
        document.querySelectorAll('a[href^="#"]').forEach(anchor => {
            anchor.addEventListener('click', function (e) {
                e.preventDefault();
                const target = document.querySelector(this.getAttribute('href'));
                if (target) {
                    target.scrollIntoView({
                        behavior: 'smooth',
                        block: 'start'
                    });
                }
            });
        });
    </script>
</body>
</html>
