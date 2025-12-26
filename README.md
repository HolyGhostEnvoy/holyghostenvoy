
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta name="description" content="Adigun Micheal Damilare - Award-winning Digital Marketing Expert in Lagos, Nigeria. Specializing in social media marketing, SEO/AEO, brand identity, and WordPress design. Proven 220% ROAS with 5+ years delivering measurable results.">
    <meta name="keywords" content="digital marketing Lagos, social media manager Nigeria, SEO expert Lagos, AEO optimization Nigeria, brand designer Nigeria, WordPress developer Lagos">
    <meta name="author" content="Adigun Micheal Damilare">
    <meta name="robots" content="index, follow">
    
    <!-- Open Graph -->
    <meta property="og:type" content="website">
    <meta property="og:url" content="https://adigunmicheal.com/">
    <meta property="og:title" content="Adigun Micheal | Digital Marketing Expert Lagos Nigeria">
    <meta property="og:description" content="Expert Digital Marketer & Visual Designer delivering 220% ROAS. Social media, SEO/AEO, brand identity & WordPress design services in Lagos, Nigeria.">
    <meta property="og:image" content="https://adigunmicheal.com/img/mike.jpg">
    
    <link rel="canonical" href="https://adigunmicheal.com/">
    <title>Adigun Micheal | Digital Marketing Expert Lagos Nigeria - SEO, Social Media & Brand Design</title>
    
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Playfair+Display:wght@600;700&family=Inter:wght@400;500;600;700&display=swap" rel="stylesheet">
    <script src="https://cdn.jsdelivr.net/npm/chart.js@4.4.0/dist/chart.umd.min.js"></script>
    
    <style>
        /* ==================== CSS VARIABLES ==================== */
        :root {
            /* Classic Color Palette */
            --primary: #1e3a8a;
            --primary-dark: #1e293b;
            --primary-light: #3b5998;
            --accent: #92400e;
            --accent-light: #b45309;
            --success: #166534;
            --dark: #0f172a;
            --dark-light: #334155;
            --gray: #64748b;
            --gray-light: #94a3b8;
            --gray-lighter: #cbd5e1;
            --bg-cream: #faf8f3;
            --bg-light: #f8fafc;
            --white: #ffffff;
            --border-color: #e2e8f0;
            
            /* Spacing System */
            --space-unit: 1rem;
            --space-xs: 0.5rem;
            --space-sm: 1rem;
            --space-md: 1.5rem;
            --space-lg: 2rem;
            --space-xl: 3rem;
            --space-2xl: 4rem;
            --space-3xl: 6rem;
            
            /* Shadows - More Classic/Subtle */
            --shadow-sm: 0 1px 3px rgba(0, 0, 0, 0.08);
            --shadow: 0 2px 8px rgba(0, 0, 0, 0.1);
            --shadow-lg: 0 4px 12px rgba(0, 0, 0, 0.12);
            --shadow-xl: 0 8px 24px rgba(0, 0, 0, 0.15);
            
            /* Border Radius - More Conservative */
            --radius-sm: 4px;
            --radius: 8px;
            --radius-lg: 12px;
            --radius-xl: 16px;
            --radius-full: 50px;
            
            /* Transitions */
            --transition: all 0.3s ease;
            --transition-fast: all 0.15s ease;
            
            /* Typography */
            --font-serif: 'Playfair Display', serif;
            --font-sans: 'Inter', -apple-system, sans-serif;
            --line-height-tight: 1.2;
            --line-height-normal: 1.5;
            --line-height-relaxed: 1.7;
        }
        
        /* ==================== RESET & BASE ==================== */
        *, *::before, *::after {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }
        
        html {
            scroll-behavior: smooth;
            font-size: 16px;
            -webkit-text-size-adjust: 100%;
        }
        
        body {
            font-family: var(--font-sans);
            color: var(--dark);
            line-height: var(--line-height-relaxed);
            background: var(--white);
            -webkit-font-smoothing: antialiased;
            -moz-osx-font-smoothing: grayscale;
            overflow-x: hidden;
        }
        
        /* Typography */
        h1, h2, h3, h4, h5, h6 {
            font-family: var(--font-serif);
            font-weight: 700;
            line-height: var(--line-height-tight);
            letter-spacing: -0.02em;
            color: var(--dark);
            margin-bottom: var(--space-md);
        }
        
        h1 { font-size: clamp(2rem, 4vw + 1rem, 3.5rem); }
        h2 { font-size: clamp(1.75rem, 3vw + 1rem, 2.75rem); }
        h3 { font-size: clamp(1.25rem, 2vw + 0.5rem, 1.75rem); }
        h4 { font-size: clamp(1.1rem, 1.5vw + 0.5rem, 1.35rem); }
        
        p {
            margin-bottom: var(--space-md);
            line-height: var(--line-height-relaxed);
        }
        
        a {
            color: var(--primary);
            text-decoration: none;
            transition: var(--transition);
        }
        
        img {
            max-width: 100%;
            height: auto;
            display: block;
        }
        
        /* Skip to content link for accessibility */
        .skip-link {
            position: absolute;
            top: -40px;
            left: 0;
            background: var(--primary);
            color: var(--white);
            padding: var(--space-sm) var(--space-md);
            z-index: 100;
            border-radius: var(--radius);
        }
        
        .skip-link:focus {
            top: var(--space-sm);
            outline: 3px solid var(--accent);
        }
        
        /* Container */
        .container {
            width: 100%;
            max-width: 1200px;
            margin: 0 auto;
            padding: 0 var(--space-md);
        }
        
        @media (min-width: 768px) {
            .container { padding: 0 var(--space-lg); }
        }
        
        @media (min-width: 1024px) {
            .container { padding: 0 var(--space-xl); }
        }
        
        /* ==================== HEADER ==================== */
        header {
            background: var(--white);
            border-bottom: 1px solid var(--border-color);
            position: sticky;
            top: 0;
            z-index: 1000;
            transition: var(--transition);
        }
        
        header.scrolled {
            box-shadow: var(--shadow);
        }
        
        .header-content {
            display: flex;
            justify-content: space-between;
            align-items: center;
            padding: var(--space-md) 0;
            min-height: 70px;
        }
        
        .logo {
            font-family: var(--font-serif);
            font-size: clamp(1.25rem, 3vw, 1.5rem);
            font-weight: 700;
            color: var(--primary);
            letter-spacing: -0.02em;
        }
        
        /* Navigation */
        nav ul {
            display: flex;
            list-style: none;
            gap: var(--space-lg);
            align-items: center;
        }
        
        nav a {
            color: var(--dark);
            font-weight: 500;
            font-size: 0.9375rem;
            padding: var(--space-xs) 0;
            position: relative;
        }
        
        nav a::after {
            content: '';
            position: absolute;
            bottom: -2px;
            left: 0;
            width: 0;
            height: 2px;
            background: var(--primary);
            transition: var(--transition);
        }
        
        nav a:hover::after,
        nav a:focus::after {
            width: 100%;
        }
        
        nav a:focus {
            outline: 2px solid var(--primary);
            outline-offset: 4px;
            border-radius: var(--radius-sm);
        }
        
        /* Mobile Menu Toggle */
        .menu-toggle {
            display: none;
            flex-direction: column;
            gap: 5px;
            cursor: pointer;
            padding: var(--space-xs);
            background: none;
            border: none;
            z-index: 1001;
        }
        
        .menu-toggle span {
            width: 26px;
            height: 2px;
            background: var(--dark);
            border-radius: 2px;
            transition: var(--transition);
        }
        
        .menu-toggle[aria-expanded="true"] span:nth-child(1) {
            transform: rotate(45deg) translate(6px, 6px);
        }
        
        .menu-toggle[aria-expanded="true"] span:nth-child(2) {
            opacity: 0;
        }
        
        .menu-toggle[aria-expanded="true"] span:nth-child(3) {
            transform: rotate(-45deg) translate(5px, -5px);
        }
        
        /* ==================== HERO SECTION ==================== */
        .hero {
            background: linear-gradient(to bottom, var(--bg-cream), var(--white));
            padding: clamp(3rem, 8vh, 5rem) 0;
            border-bottom: 1px solid var(--border-color);
        }
        
        .hero-grid {
            display: grid;
            grid-template-columns: 1fr;
            gap: var(--space-xl);
            align-items: center;
        }
        
        @media (min-width: 768px) {
            .hero-grid {
                grid-template-columns: 1.2fr 0.8fr;
                gap: var(--space-2xl);
            }
        }
        
        .hero-content h1 {
            margin-bottom: var(--space-md);
        }
        
        .hero .highlight {
            color: var(--accent);
        }
        
        .hero-subtitle {
            font-size: clamp(1rem, 2vw, 1.125rem);
            color: var(--gray);
            margin-bottom: var(--space-lg);
            line-height: var(--line-height-relaxed);
        }
        
        /* Hero Features */
        .hero-features {
            display: flex;
            flex-wrap: wrap;
            gap: var(--space-md);
            margin-bottom: var(--space-lg);
        }
        
        .hero-feature {
            display: flex;
            align-items: center;
            gap: 0.625rem;
            color: var(--dark-light);
            font-size: 0.9375rem;
            font-weight: 500;
        }
        
        .hero-feature svg {
            width: 20px;
            height: 20px;
            color: var(--success);
            flex-shrink: 0;
        }
        
        /* Buttons */
        .btn {
            display: inline-block;
            padding: 0.875rem 2rem;
            border-radius: var(--radius-full);
            font-weight: 600;
            font-size: 0.9375rem;
            text-align: center;
            transition: var(--transition);
            border: 2px solid transparent;
            cursor: pointer;
            min-height: 44px;
            min-width: 44px;
        }
        
        .btn:focus {
            outline: 3px solid var(--accent);
            outline-offset: 2px;
        }
        
        .btn-primary {
            background: var(--primary);
            color: var(--white);
            box-shadow: var(--shadow);
        }
        
        .btn-primary:hover,
        .btn-primary:focus {
            background: var(--primary-dark);
            transform: translateY(-2px);
            box-shadow: var(--shadow-lg);
        }
        
        .btn-secondary {
            background: transparent;
            color: var(--primary);
            border: 2px solid var(--primary);
        }
        
        .btn-secondary:hover,
        .btn-secondary:focus {
            background: var(--primary);
            color: var(--white);
        }
        
        .hero-buttons {
            display: flex;
            gap: var(--space-md);
            flex-wrap: wrap;
        }
        
        /* Hero Image */
        .hero-image-wrapper {
            position: relative;
        }
        
        .hero-img {
            width: 100%;
            max-width: 450px;
            margin: 0 auto;
            border-radius: var(--radius-lg);
            box-shadow: var(--shadow-xl);
            border: 1px solid var(--border-color);
        }
        
        /* ==================== STATS SECTION ==================== */
        .stats {
            background: var(--white);
            padding: var(--space-xl) 0;
            border-bottom: 1px solid var(--border-color);
        }
        
        .stats-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(140px, 1fr));
            gap: var(--space-lg);
            text-align: center;
        }
        
        @media (max-width: 480px) {
            .stats-grid {
                grid-template-columns: repeat(2, 1fr);
                gap: var(--space-md);
            }
        }
        
        .stat-number {
            font-family: var(--font-serif);
            font-size: clamp(2rem, 5vw, 2.75rem);
            font-weight: 700;
            color: var(--primary);
            display: block;
            line-height: 1;
            margin-bottom: var(--space-xs);
        }
        
        .stat-label {
            color: var(--gray);
            font-weight: 600;
            font-size: 0.875rem;
            text-transform: uppercase;
            letter-spacing: 0.05em;
        }
        
        /* ==================== SECTION STYLING ==================== */
        .section {
            padding: clamp(3rem, 8vw, 5rem) 0;
        }
        
        .section-header {
            text-align: center;
            max-width: 800px;
            margin: 0 auto var(--space-2xl);
        }
        
        .section-title {
            margin-bottom: var(--space-md);
        }
        
        .section-subtitle {
            color: var(--gray);
            font-size: clamp(1rem, 2vw, 1.125rem);
            line-height: var(--line-height-relaxed);
        }
        
        /* ==================== ABOUT SECTION ==================== */
        #about {
            background: var(--bg-cream);
        }
        
        .about-grid {
            display: grid;
            grid-template-columns: 1fr;
            gap: var(--space-xl);
            align-items: start;
        }
        
        @media (min-width: 768px) {
            .about-grid {
                grid-template-columns: 1fr 1fr;
                gap: var(--space-2xl);
            }
        }
        
        .about-content p {
            font-size: 1.0625rem;
            line-height: var(--line-height-relaxed);
            color: var(--gray);
        }
        
        .about-content strong {
            color: var(--dark);
            font-weight: 600;
        }
        
        .about-highlight {
            background: var(--white);
            padding: var(--space-lg);
            border-radius: var(--radius);
            border-left: 4px solid var(--primary);
            margin: var(--space-lg) 0;
            box-shadow: var(--shadow);
        }
        
        .about-highlight p {
            margin: 0;
            font-size: 1.125rem;
            font-style: italic;
            color: var(--dark-light);
        }
        
        /* Skills Grid */
        .skills-grid {
            display: grid;
            grid-template-columns: repeat(auto-fill, minmax(140px, 1fr));
            gap: var(--space-sm);
        }
        
        @media (max-width: 480px) {
            .skills-grid {
                grid-template-columns: repeat(2, 1fr);
            }
        }
        
        .skill-badge {
            background: var(--white);
            padding: var(--space-md) var(--space-sm);
            border-radius: var(--radius);
            text-align: center;
            font-weight: 600;
            font-size: 0.875rem;
            color: var(--primary);
            border: 1px solid var(--border-color);
            transition: var(--transition);
            min-height: 44px;
            display: flex;
            align-items: center;
            justify-content: center;
        }
        
        .skill-badge:hover {
            transform: translateY(-3px);
            box-shadow: var(--shadow-lg);
            border-color: var(--primary);
        }
        
        /* ==================== SERVICES SECTION ==================== */
        #services {
            background: var(--white);
        }
        
        .services-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(min(100%, 280px), 1fr));
            gap: var(--space-lg);
        }
        
        .service-card {
            background: var(--bg-cream);
            padding: var(--space-xl);
            border-radius: var(--radius);
            border: 1px solid var(--border-color);
            transition: var(--transition);
        }
        
        .service-card:hover {
            transform: translateY(-4px);
            box-shadow: var(--shadow-lg);
            border-color: var(--primary);
        }
        
        .service-icon {
            width: 60px;
            height: 60px;
            background: var(--primary);
            border-radius: var(--radius);
            display: flex;
            align-items: center;
            justify-content: center;
            margin-bottom: var(--space-md);
            font-size: 1.75rem;
        }
        
        .service-card h3 {
            font-size: 1.35rem;
            margin-bottom: var(--space-sm);
        }
        
        .service-card p {
            color: var(--gray);
            line-height: var(--line-height-relaxed);
            margin-bottom: var(--space-md);
        }
        
        .service-features {
            list-style: none;
        }
        
        .service-features li {
            padding: 0.5rem 0;
            color: var(--dark-light);
            font-size: 0.9375rem;
            display: flex;
            align-items: flex-start;
            gap: 0.625rem;
            line-height: var(--line-height-normal);
        }
        
        .service-features li::before {
            content: '✓';
            color: var(--success);
            font-weight: 700;
            font-size: 1rem;
            flex-shrink: 0;
        }
        
        /* ==================== PROCESS SECTION ==================== */
        #process {
            background: var(--bg-cream);
        }
        
        .process-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(min(100%, 220px), 1fr));
            gap: var(--space-lg);
            margin-top: var(--space-xl);
        }
        
        .process-step {
            text-align: center;
            padding: var(--space-lg);
        }
        
        .process-number {
            width: 56px;
            height: 56px;
            background: var(--primary);
            color: var(--white);
            border-radius: 50%;
            display: flex;
            align-items: center;
            justify-content: center;
            font-size: 1.5rem;
            font-weight: 700;
            margin: 0 auto var(--space-md);
            font-family: var(--font-serif);
        }
        
        .process-step h3 {
            font-size: 1.25rem;
            margin-bottom: var(--space-sm);
        }
        
        .process-step p {
            color: var(--gray);
            line-height: var(--line-height-relaxed);
            margin: 0;
        }
        
        /* ==================== PORTFOLIO SECTION ==================== */
        #portfolio {
            background: var(--white);
        }
        
        .portfolio-item {
            background: var(--bg-cream);
            padding: var(--space-xl);
            border-radius: var(--radius-lg);
            border: 1px solid var(--border-color);
            margin-bottom: var(--space-xl);
            box-shadow: var(--shadow);
        }
        
        @media (max-width: 768px) {
            .portfolio-item {
                padding: var(--space-lg);
            }
        }
        
        .portfolio-header {
            display: flex;
            justify-content: space-between;
            align-items: center;
            margin-bottom: var(--space-md);
            flex-wrap: wrap;
            gap: var(--space-md);
        }
        
        .portfolio-title {
            font-size: 1.625rem;
            color: var(--primary);
            margin: 0;
        }
        
        .portfolio-date {
            background: var(--white);
            padding: 0.5rem 1rem;
            border-radius: var(--radius-full);
            color: var(--gray);
            font-weight: 600;
            font-size: 0.875rem;
            border: 1px solid var(--border-color);
        }
        
        .portfolio-desc {
            color: var(--gray);
            margin-bottom: var(--space-lg);
            line-height: var(--line-height-relaxed);
            font-size: 1.0625rem;
        }
        
        /* Metrics Grid */
        .metrics-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(140px, 1fr));
            gap: var(--space-md);
            margin: var(--space-lg) 0;
        }
        
        .metric-box {
            background: var(--white);
            padding: var(--space-lg) var(--space-md);
            border-radius: var(--radius);
            text-align: center;
            border: 1px solid var(--border-color);
            transition: var(--transition);
        }
        
        .metric-box:hover {
            transform: translateY(-3px);
            box-shadow: var(--shadow-lg);
            border-color: var(--primary);
        }
        
        .metric-value {
            font-family: var(--font-serif);
            font-size: 2rem;
            font-weight: 700;
            color: var(--primary);
            display: block;
            line-height: 1;
            margin-bottom: var(--space-xs);
        }
        
        .metric-label {
            color: var(--gray);
            font-size: 0.875rem;
            font-weight: 600;
            text-transform: uppercase;
            letter-spacing: 0.05em;
        }
        
        /* Chart Container */
        .chart-container {
            height: 300px;
            margin: var(--space-lg) 0;
            background: var(--white);
            padding: var(--space-md);
            border-radius: var(--radius);
            border: 1px solid var(--border-color);
        }
        
        @media (max-width: 768px) {
            .chart-container {
                height: 250px;
                padding: var(--space-sm);
            }
        }
        
        /* ==================== TESTIMONIALS SECTION ==================== */
        #testimonials {
            background: var(--bg-cream);
        }
        
        .testimonials-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(min(100%, 280px), 1fr));
            gap: var(--space-lg);
        }
        
        .testimonial-card {
            background: var(--white);
            padding: var(--space-xl);
            border-radius: var(--radius-lg);
            border: 1px solid var(--border-color);
            box-shadow: var(--shadow);
            position: relative;
        }
        
        .testimonial-card::before {
            content: '"';
            position: absolute;
            top: var(--space-md);
            left: var(--space-md);
            font-size: 3.5rem;
            color: var(--primary);
            opacity: 0.1;
            font-family: var(--font-serif);
            line-height: 1;
        }
        
        .testimonial-text {
            color: var(--gray);
            line-height: var(--line-height-relaxed);
            margin-bottom: var(--space-md);
            font-style: italic;
            position: relative;
            z-index: 1;
        }
        
        .testimonial-author {
            display: flex;
            align-items: center;
            gap: var(--space-md);
        }
        
        .author-avatar {
            width: 48px;
            height: 48px;
            background: var(--primary);
            border-radius: 50%;
            display: flex;
            align-items: center;
            justify-content: center;
            color: var(--white);
            font-weight: 700;
            font-size: 1.125rem;
            flex-shrink: 0;
        }
        
        .author-info h4 {
            font-size: 1.0625rem;
            margin-bottom: 0.25rem;
        }
        
        .author-info p {
            color: var(--gray);
            font-size: 0.875rem;
            margin: 0;
        }
        
        /* ==================== FAQ SECTION ==================== */
        #faq {
            background: var(--white);
        }
        
        .faq-container {
            max-width: 900px;
            margin: 0 auto;
        }
        
        .faq-item {
            background: var(--bg-cream);
            border-radius: var(--radius);
            margin-bottom: var(--space-md);
            border: 1px solid var(--border-color);
            overflow: hidden;
        }
        
        .faq-question {
            width: 100%;
            padding: var(--space-lg);
            background: none;
            border: none;
            text-align: left;
            cursor: pointer;
            display: flex;
            justify-content: space-between;
            align-items: center;
            gap: var(--space-md);
            font-size: 1.0625rem;
            font-weight: 600;
            color: var(--dark);
            transition: var(--transition);
            min-height: 44px;
        }
        
        @media (max-width: 768px) {
            .faq-question {
                padding: var(--space-md);
                font-size: 1rem;
            }
        }
        
        .faq-question:hover,
        .faq-question:focus {
            color: var(--primary);
        }
        
        .faq-question:focus {
            outline: 2px solid var(--primary);
            outline-offset: -2px;
        }
        
        .faq-icon {
            width: 24px;
            height: 24px;
            flex-shrink: 0;
            transition: var(--transition);
            color: var(--primary);
        }
        
        .faq-item.active .faq-icon {
            transform: rotate(180deg);
        }
        
        .faq-answer {
            max-height: 0;
            overflow: hidden;
            transition: max-height 0.4s ease;
        }
        
        .faq-item.active .faq-answer {
            max-height: 800px;
        }
        
        .faq-answer-content {
            padding: 0 var(--space-lg) var(--space-lg);
            color: var(--gray);
            line-height: var(--line-height-relaxed);
        }
        
        @media (max-width: 768px) {
            .faq-answer-content {
                padding: 0 var(--space-md) var(--space-md);
            }
        }
        
        /* ==================== CTA SECTION ==================== */
        #cta {
            background: var(--primary);
            color: var(--white);
            text-align: center;
            padding: clamp(3rem, 8vw, 5rem) 0;
        }
        
        #cta .section-title {
            color: var(--white);
        }
        
        #cta .section-subtitle {
            color: rgba(255, 255, 255, 0.9);
        }
        
        .cta-buttons {
            display: flex;
            gap: var(--space-md);
            justify-content: center;
            flex-wrap: wrap;
            margin-top: var(--space-lg);
        }
        
        .btn-white {
            background: var(--white);
            color: var(--primary);
        }
        
        .btn-white:hover {
            background: var(--bg-light);
            transform: translateY(-2px);
        }
        
        .btn-outline-white {
            background: transparent;
            color: var(--white);
            border: 2px solid var(--white);
        }
        
        .btn-outline-white:hover {
            background: var(--white);
            color: var(--primary);
        }
        
        /* ==================== CONTACT SECTION ==================== */
        #contact {
            background: var(--bg-cream);
        }
        
        .contact-grid {
            display: grid;
            grid-template-columns: 1fr;
            gap: var(--space-lg);
            margin-top: var(--space-xl);
        }
        
        @media (min-width: 768px) {
            .contact-grid {
                grid-template-columns: repeat(2, 1fr);
                gap: var(--space-xl);
            }
        }
        
        .contact-info-card {
            background: var(--white);
            padding: var(--space-xl);
            border-radius: var(--radius-lg);
            border: 1px solid var(--border-color);
            box-shadow: var(--shadow);
        }
        
        .contact-info-card h3 {
            font-size: 1.5rem;
            margin-bottom: var(--space-md);
        }
        
        .contact-item {
            display: flex;
            align-items: flex-start;
            gap: var(--space-md);
            padding: var(--space-md) 0;
            border-bottom: 1px solid var(--border-color);
        }
        
        .contact-item:last-child {
            border-bottom: none;
        }
        
        .contact-icon {
            width: 44px;
            height: 44px;
            background: var(--primary);
            border-radius: var(--radius);
            display: flex;
            align-items: center;
            justify-content: center;
            font-size: 1.125rem;
            flex-shrink: 0;
        }
        
        .contact-details p {
            margin: 0 0 0.25rem 0;
            color: var(--gray);
            font-size: 0.875rem;
        }
        
        .contact-details a {
            color: var(--primary);
            font-weight: 600;
            font-size: 1.0625rem;
            word-break: break-word;
        }
        
        .contact-details a:hover {
            text-decoration: underline;
        }
        
        /* ==================== FOOTER ==================== */
        footer {
            background: var(--dark);
            color: var(--white);
            padding: var(--space-2xl) 0 var(--space-md);
        }
        
        .footer-content {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(220px, 1fr));
            gap: var(--space-xl);
            margin-bottom: var(--space-lg);
        }
        
        .footer-section h4 {
            font-size: 1.125rem;
            margin-bottom: var(--space-md);
            color: var(--white);
        }
        
        .footer-section p,
        .footer-section a {
            color: var(--gray-light);
            line-height: var(--line-height-relaxed);
        }
        
        .footer-section a:hover {
            color: var(--white);
        }
        
        .footer-links {
            list-style: none;
        }
        
        .footer-links li {
            margin-bottom: 0.625rem;
        }
        
        .footer-bottom {
            border-top: 1px solid rgba(255, 255, 255, 0.1);
            padding-top: var(--space-md);
            text-align: center;
            color: var(--gray-light);
            font-size: 0.875rem;
        }
        
        /* ==================== FLOATING ELEMENTS ==================== */
        .whatsapp-float {
            position: fixed;
            bottom: 30px;
            right: 30px;
            z-index: 999;
        }
        
        .whatsapp-float a {
            display: flex;
            align-items: center;
            gap: 10px;
            background: #25D366;
            color: var(--white);
            padding: 14px 22px;
            border-radius: var(--radius-full);
            font-weight: 600;
            box-shadow: var(--shadow-lg);
            transition: var(--transition);
            min-height: 44px;
        }
        
        .whatsapp-float a:hover,
        .whatsapp-float a:focus {
            transform: translateY(-3px);
            box-shadow: var(--shadow-xl);
        }
        
        .whatsapp-icon {
            width: 24px;
            height: 24px;
        }
        
        .back-to-top {
            position: fixed;
            bottom: 100px;
            right: 30px;
            width: 50px;
            height: 50px;
            background: var(--primary);
            color: var(--white);
            border-radius: 50%;
            display: flex;
            align-items: center;
            justify-content: center;
            cursor: pointer;
            opacity: 0;
            visibility: hidden;
            transition: var(--transition);
            z-index: 998;
            box-shadow: var(--shadow-lg);
            border: none;
        }
        
        .back-to-top.visible {
            opacity: 1;
            visibility: visible;
        }
        
        .back-to-top:hover,
        .back-to-top:focus {
            background: var(--primary-dark);
            transform: translateY(-3px);
            outline: 2px solid var(--accent);
            outline-offset: 2px;
        }
        
        /* ==================== RESPONSIVE DESIGN ==================== */
        @media (max-width: 768px) {
            .menu-toggle {
                display: flex;
            }
            
            nav ul {
                position: fixed;
                top: 70px;
                right: -100%;
                flex-direction: column;
                background: var(--white);
                width: 85%;
                max-width: 320px;
                height: calc(100vh - 70px);
                padding: var(--space-lg);
                box-shadow: -5px 0 25px rgba(0, 0, 0, 0.15);
                transition: right 0.3s ease;
                align-items: flex-start;
                overflow-y: auto;
            }
            
            nav ul.active {
                right: 0;
            }
            
            nav a {
                width: 100%;
                padding: var(--space-sm) 0;
                font-size: 1.0625rem;
            }
            
            .whatsapp-float a span {
                display: none;
            }
            
            .whatsapp-float a {
                width: 56px;
                height: 56px;
                padding: 0;
                justify-content: center;
                border-radius: 50%;
            }
            
            .back-to-top {
                bottom: 120px;
                width: 48px;
                height: 48px;
            }
            
            .hero-buttons {
                flex-direction: column;
                width: 100%;
            }
            
            .btn {
                width: 100%;
                text-align: center;
            }
        }
        
        @media (max-width: 480px) {
            :root {
                --space-unit: 0.875rem;
            }
            
            .hero {
                padding: var(--space-lg) 0;
            }
            
            .stats-grid {
                gap: var(--space-sm);
            }
            
            .portfolio-item,
            .service-card,
            .testimonial-card,
            .contact-info-card {
                padding: var(--space-md);
            }
            
            .metrics-grid {
                grid-template-columns: 1fr;
            }
        }
        
        /* ==================== PRINT STYLES ==================== */
        @media print {
            header,
            .whatsapp-float,
            .back-to-top,
            .menu-toggle,
            #cta {
                display: none;
            }
            
            body {
                font-size: 12pt;
                line-height: 1.5;
            }
            
            .section {
                page-break-inside: avoid;
            }
            
            a {
                text-decoration: underline;
            }
        }
    </style>
</head>
<body>
    <a href="#main" class="skip-link">Skip to main content</a>
    
    <header id="header">
        <div class="container header-content">
            <div class="logo">Adigun Micheal</div>
            <button class="menu-toggle" id="menuToggle" aria-expanded="false" aria-controls="navMenu" aria-label="Toggle navigation menu">
                <span></span>
                <span></span>
                <span></span>
            </button>
            <nav>
                <ul id="navMenu">
                    <li><a href="#home">Home</a></li>
                    <li><a href="#about">About</a></li>
                    <li><a href="#services">Services</a></li>
                    <li><a href="#portfolio">Portfolio</a></li>
                    <li><a href="#testimonials">Testimonials</a></li>
                    <li><a href="#faq">FAQ</a></li>
                    <li><a href="#contact">Contact</a></li>
                </ul>
            </nav>
        </div>
    </header>

    <main id="main">
        <section id="home" class="hero">
            <div class="container">
                <div class="hero-grid">
                    <div class="hero-content">
                        <h1>Digital Marketer & <span class="highlight">Visual Designer</span></h1>
                        <p class="hero-subtitle">I help Nigerian and global brands grow through strategic social media, AI-enhanced content, and stunning visual design that converts. Transform your brand with data-driven marketing strategies that deliver measurable results.</p>
                        
                        <div class="hero-features">
                            <div class="hero-feature">
                                <svg fill="none" stroke="currentColor" viewBox="0 0 24 24" aria-hidden="true"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M5 13l4 4L19 7"/></svg>
                                <span>220% Average ROAS</span>
                            </div>
                            <div class="hero-feature">
                                <svg fill="none" stroke="currentColor" viewBox="0 0 24 24" aria-hidden="true"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M5 13l4 4L19 7"/></svg>
                                <span>5+ Years Experience</span>
                            </div>
                            <div class="hero-feature">
                                <svg fill="none" stroke="currentColor" viewBox="0 0 24 24" aria-hidden="true"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M5 13l4 4L19 7"/></svg>
                                <span>50+ Projects Delivered</span>
                            </div>
                        </div>
                        
                        <div class="hero-buttons">
                            <a href="https://wa.me/2347080821125?text=Hello%20Adigun!%20I%20need%20help%20with%20my%20digital%20marketing" class="btn btn-primary">Let's Build Your Brand</a>
                            <a href="#portfolio" class="btn btn-secondary">View Portfolio</a>
                        </div>
                    </div>
                    <div class="hero-image-wrapper">
                        <img src="img/mike.jpg" alt="Adigun Micheal Damilare - Digital Marketing Expert" class="hero-img" loading="eager">
                    </div>
                </div>
            </div>
        </section>

        <section class="stats">
            <div class="container">
                <div class="stats-grid">
                    <div class="stat-item">
                        <span class="stat-number">220%</span>
                        <span class="stat-label">Average ROAS</span>
                    </div>
                    <div class="stat-item">
                        <span class="stat-number">50+</span>
                        <span class="stat-label">Projects Completed</span>
                    </div>
                    <div class="stat-item">
                        <span class="stat-number">120%</span>
                        <span class="stat-label">Traffic Growth</span>
                    </div>
                    <div class="stat-item">
                        <span class="stat-number">30+</span>
                        <span class="stat-label">Happy Clients</span>
                    </div>
                </div>
            </div>
        </section>

        <section id="about" class="section">
            <div class="container">
                <div class="section-header">
                    <h2 class="section-title">About Me</h2>
                    <p class="section-subtitle">Digital Marketing Specialist with a Passion for Results</p>
                </div>
                <div class="about-grid">
                    <div class="about-content">
                        <p>I am <strong>Adigun Micheal Damilare</strong>, a creative and analytical Digital Marketer, Social Media Manager, and Visual Designer based in Agege, Lagos, Nigeria.</p>
                        <p>With over <strong>5 years of hands-on experience</strong>, I've partnered with startups, SMEs, NGOs, and multinational clients to build powerful digital identities through storytelling, data, and design.</p>
                        <div class="about-highlight">
                            <p>My work is guided by one principle: marketing that looks beautiful should also perform brilliantly.</p>
                        </div>
                        <p>I specialize in creating integrated marketing strategies that combine creative excellence with analytical rigor. From social media campaigns that go viral to SEO-optimized websites that convert visitors into customers, I deliver solutions that drive real business growth.</p>
                    </div>
                    <div class="skills-grid">
                        <div class="skill-badge">Social Media Marketing</div>
                        <div class="skill-badge">SEO & AEO</div>
                        <div class="skill-badge">Brand Strategy</div>
                        <div class="skill-badge">WordPress Design</div>
                        <div class="skill-badge">Content Creation</div>
                        <div class="skill-badge">Data Analytics</div>
                        <div class="skill-badge">Video Editing</div>
                        <div class="skill-badge">AI Marketing</div>
                        <div class="skill-badge">Meta Ads</div>
                        <div class="skill-badge">Google Ads</div>
                        <div class="skill-badge">Email Marketing</div>
                        <div class="skill-badge">Graphic Design</div>
                    </div>
                </div>
            </div>
        </section>

        <section id="services" class="section">
            <div class="container">
                <div class="section-header">
                    <h2 class="section-title">What I Offer</h2>
                    <p class="section-subtitle">Comprehensive Digital Marketing Solutions for Modern Businesses</p>
                </div>
                <div class="services-grid">
                    <article class="service-card">
                        <div class="service-icon" aria-hidden="true">📱</div>
                        <h3>Social Media Management</h3>
                        <p>Full-service strategy, content calendars, community engagement, and performance reporting for Instagram, Facebook, TikTok, LinkedIn, and Twitter.</p>
                        <ul class="service-features">
                            <li>Content Strategy & Planning</li>
                            <li>Daily Posting & Scheduling</li>
                            <li>Community Management</li>
                            <li>Analytics & Reporting</li>
                        </ul>
                    </article>
                    <article class="service-card">
                        <div class="service-icon" aria-hidden="true">🎨</div>
                        <h3>Brand Identity Design</h3>
                        <p>Comprehensive logos, style guides, and visual systems that make your brand professional, consistent, and memorable across all touchpoints.</p>
                        <ul class="service-features">
                            <li>Logo Design & Branding</li>
                            <li>Brand Guidelines</li>
                            <li>Marketing Collateral</li>
                            <li>Visual Identity Systems</li>
                        </ul>
                    </article>
                    <article class="service-card">
                        <div class="service-icon" aria-hidden="true">💻</div>
                        <h3>WordPress Website Design</h3>
                        <p>Mobile-responsive, SEO-optimized websites built with WordPress—fast, secure, easy to update, and designed to convert visitors into customers.</p>
                        <ul class="service-features">
                            <li>Custom WordPress Themes</li>
                            <li>SEO Optimization</li>
                            <li>Mobile Responsive Design</li>
                            <li>E-commerce Integration</li>
                        </ul>
                    </article>
                    <article class="service-card">
                        <div class="service-icon" aria-hidden="true">🎯</div>
                        <h3>Paid Advertising</h3>
                        <p>Strategic ad campaigns on Facebook, Instagram, and Google that maximize ROI with data-driven targeting, creative testing, and conversion optimization.</p>
                        <ul class="service-features">
                            <li>Campaign Strategy</li>
                            <li>Ad Creative Development</li>
                            <li>A/B Testing</li>
                            <li>Performance Optimization</li>
                        </ul>
                    </article>
                    <article class="service-card">
                        <div class="service-icon" aria-hidden="true">🔍</div>
                        <h3>SEO & AEO Optimization</h3>
                        <p>Comprehensive search engine and answer engine optimization to improve your visibility on Google, ChatGPT, and other AI platforms.</p>
                        <ul class="service-features">
                            <li>Keyword Research</li>
                            <li>On-Page Optimization</li>
                            <li>Technical SEO</li>
                            <li>Content Optimization</li>
                        </ul>
                    </article>
                    <article class="service-card">
                        <div class="service-icon" aria-hidden="true">📹</div>
                        <h3>Video Content Creation</h3>
                        <p>Engaging short-form and long-form video content for social media, YouTube, and advertising campaigns that capture attention and drive action.</p>
                        <ul class="service-features">
                            <li>Video Production</li>
                            <li>Video Editing</li>
                            <li>Motion Graphics</li>
                            <li>Social Media Reels</li>
                        </ul>
                    </article>
                </div>
            </div>
        </section>

        <section id="process" class="section">
            <div class="container">
                <div class="section-header">
                    <h2 class="section-title">How I Work</h2>
                    <p class="section-subtitle">A proven process that delivers results every time</p>
                </div>
                <div class="process-grid">
                    <div class="process-step">
                        <div class="process-number" aria-hidden="true">1</div>
                        <h3>Discovery & Research</h3>
                        <p>I start by understanding your business goals, target audience, and competitive landscape through in-depth consultation and market research.</p>
                    </div>
                    <div class="process-step">
                        <div class="process-number" aria-hidden="true">2</div>
                        <h3>Strategy Development</h3>
                        <p>Based on insights, I develop a comprehensive digital marketing strategy tailored to your objectives, budget, and timeline.</p>
                    </div>
                    <div class="process-step">
                        <div class="process-number" aria-hidden="true">3</div>
                        <h3>Creative Execution</h3>
                        <p>I bring the strategy to life through high-quality content creation, design work, and campaign implementation across chosen channels.</p>
                    </div>
                    <div class="process-step">
                        <div class="process-number" aria-hidden="true">4</div>
                        <h3>Launch & Optimize</h3>
                        <p>After launch, I continuously monitor performance, run A/B tests, and optimize campaigns to maximize your return on investment.</p>
                    </div>
                </div>
            </div>
        </section>

        <section id="portfolio" class="section">
            <div class="container">
                <div class="section-header">
                    <h2 class="section-title">Portfolio Highlights</h2>
                    <p class="section-subtitle">Measurable Results Across Diverse Industries</p>
                </div>
                
                <article class="portfolio-item">
                    <div class="portfolio-header">
                        <h3 class="portfolio-title">Royal Insight Rebrand</h3>
                        <span class="portfolio-date">2024 – Present</span>
                    </div>
                    <p class="portfolio-desc">Directed complete visual rebranding across digital and print channels. Result: 60% growth in engagement metrics and significantly stronger media presence.</p>
                    <div class="metrics-grid">
                        <div class="metric-box">
                            <span class="metric-value">60%</span>
                            <span class="metric-label">Engagement Growth</span>
                        </div>
                        <div class="metric-box">
                            <span class="metric-value">45%</span>
                            <span class="metric-label">Follower Increase</span>
                        </div>
                        <div class="metric-box">
                            <span class="metric-value">85%</span>
                            <span class="metric-label">Brand Recognition</span>
                        </div>
                    </div>
                    <div class="chart-container">
                        <canvas id="chartRoyal" aria-label="Royal Insight engagement growth chart"></canvas>
                    </div>
                </article>

                <article class="portfolio-item">
                    <div class="portfolio-header">
                        <h3 class="portfolio-title">Bella Cosmetics Campaign</h3>
                        <span class="portfolio-date">Oct – Dec 2025</span>
                    </div>
                    <p class="portfolio-desc">Executed integrated short-form video content and Meta ads strategy. Delivered exceptional 220% ROAS and acquired 94 qualified customers.</p>
                    <div class="metrics-grid">
                        <div class="metric-box">
                            <span class="metric-value">220%</span>
                            <span class="metric-label">ROAS Achieved</span>
                        </div>
                        <div class="metric-box">
                            <span class="metric-value">94</span>
                            <span class="metric-label">Customers Acquired</span>
                        </div>
                        <div class="metric-box">
                            <span class="metric-value">3.2x</span>
                            <span class="metric-label">Revenue Growth</span>
                        </div>
                    </div>
                    <div class="chart-container">
                        <canvas id="chartBella" aria-label="Bella Cosmetics campaign performance chart"></canvas>
                    </div>
                </article>

                <article class="portfolio-item">
                    <div class="portfolio-header">
                        <h3 class="portfolio-title">imperiainsight.ng Redesign</h3>
                        <span class="portfolio-date">2024</span>
                    </div>
                    <p class="portfolio-desc">Complete WordPress website redesign with SEO optimization. Achieved 120% increase in organic search traffic within 4 months.</p>
                    <div class="metrics-grid">
                        <div class="metric-box">
                            <span class="metric-value">120%</span>
                            <span class="metric-label">Traffic Growth</span>
                        </div>
                        <div class="metric-box">
                            <span class="metric-value">75%</span>
                            <span class="metric-label">Bounce Rate Drop</span>
                        </div>
                        <div class="metric-box">
                            <span class="metric-value">4.5min</span>
                            <span class="metric-label">Avg Session Time</span>
                        </div>
                    </div>
                    <div class="chart-container">
                        <canvas id="chartImperia" aria-label="Imperia Insight traffic sources chart"></canvas>
                    </div>
                </article>
            </div>
        </section>

        <section id="testimonials" class="section">
            <div class="container">
                <div class="section-header">
                    <h2 class="section-title">Client Testimonials</h2>
                    <p class="section-subtitle">What my clients say about working with me</p>
                </div>
                <div class="testimonials-grid">
                    <article class="testimonial-card">
                        <p class="testimonial-text">Adigun transformed our social media presence completely. Our engagement increased by 80% and we saw a direct impact on sales. His creativity and strategic thinking are exceptional.</p>
                        <div class="testimonial-author">
                            <div class="author-avatar" aria-hidden="true">AS</div>
                            <div class="author-info">
                                <h4>Adebayo Solomon</h4>
                                <p>CEO, Bella Cosmetics</p>
                            </div>
                        </div>
                    </article>
                    <article class="testimonial-card">
                        <p class="testimonial-text">Working with Micheal was a game-changer for our brand. He didn't just design a website; he created a digital experience that resonates with our audience. Traffic is up 120% and conversions have doubled.</p>
                        <div class="testimonial-author">
                            <div class="author-avatar" aria-hidden="true">OE</div>
                            <div class="author-info">
                                <h4>Okafor Emmanuel</h4>
                                <p>Founder, Imperia Insight</p>
                            </div>
                        </div>
                    </article>
                    <article class="testimonial-card">
                        <p class="testimonial-text">His attention to detail and commitment to results is unmatched. The rebranding project exceeded all expectations, and our brand now stands out in a crowded market. Highly recommended!</p>
                        <div class="testimonial-author">
                            <div class="author-avatar" aria-hidden="true">FO</div>
                            <div class="author-info">
                                <h4>Folake Ogunleye</h4>
                                <p>Managing Director, Royal Insight</p>
                            </div>
                        </div>
                    </article>
                </div>
            </div>
        </section>

        <section id="faq" class="section">
            <div class="container">
                <div class="section-header">
                    <h2 class="section-title">Frequently Asked Questions</h2>
                    <p class="section-subtitle">Everything you need to know about my services</p>
                </div>
                <div class="faq-container">
                    <div class="faq-item">
                        <button class="faq-question" aria-expanded="false">
                            <span>What digital marketing services do you offer in Lagos?</span>
                            <svg class="faq-icon" fill="none" stroke="currentColor" viewBox="0 0 24 24" aria-hidden="true"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M19 9l-7 7-7-7"/></svg>
                        </button>
                        <div class="faq-answer">
                            <div class="faq-answer-content">
                                <p>I offer comprehensive digital marketing services including social media management (Instagram, Facebook, TikTok, LinkedIn, Twitter), SEO and AEO optimization, brand identity design, WordPress website development, content creation, Meta and Google ads management, video production and editing, and data analytics. All services are tailored to help Nigerian businesses grow their online presence and revenue.</p>
                            </div>
                        </div>
                    </div>

                    <div class="faq-item">
                        <button class="faq-question" aria-expanded="false">
                            <span>How much do your digital marketing services cost?</span>
                            <svg class="faq-icon" fill="none" stroke="currentColor" viewBox="0 0 24 24" aria-hidden="true"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M19 9l-7 7-7-7"/></svg>
                        </button>
                        <div class="faq-answer">
                            <div class="faq-answer-content">
                                <p>My pricing depends on your specific needs and project scope. Social media management starts from ₦100,000/month, website design from ₦200,000, and brand identity packages from ₦150,000. I offer flexible payment plans and custom packages for startups and SMEs. Contact me for a personalized quote based on your requirements and budget.</p>
                            </div>
                        </div>
                    </div>

                    <div class="faq-item">
                        <button class="faq-question" aria-expanded="false">
                            <span>What results can I expect from your digital marketing services?</span>
                            <svg class="faq-icon" fill="none" stroke="currentColor" viewBox="0 0 24 24" aria-hidden="true"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M19 9l-7 7-7-7"/></svg>
                        </button>
                        <div class="faq-answer">
                            <div class="faq-answer-content">
                                <p>My clients typically see 60-120% growth in engagement, 220% average ROAS on ad campaigns, and significant increases in organic traffic. Results vary by industry and budget, but I focus on data-driven strategies that deliver measurable ROI within 3-6 months. I provide monthly reports showing all key metrics and performance indicators.</p>
                            </div>
                        </div>
                    </div>

                    <div class="faq-item">
                        <button class="faq-question" aria-expanded="false">
                            <span>Do you work with businesses outside Lagos?</span>
                            <svg class="faq-icon" fill="none" stroke="currentColor" viewBox="0 0 24 24" aria-hidden="true"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M19 9l-7 7-7-7"/></svg>
                        </button>
                        <div class="faq-answer">
                            <div class="faq-answer-content">
                                <p>Yes! While I'm based in Lagos, I work with clients across Nigeria and internationally. All services can be delivered remotely through video calls, collaborative tools, and cloud-based platforms. I've successfully managed projects for clients in Abuja, Port Harcourt, and beyond, as well as international clients.</p>
                            </div>
                        </div>
                    </div>

                    <div class="faq-item">
                        <button class="faq-question" aria-expanded="false">
                            <span>How long does it take to see results from digital marketing?</span>
                            <svg class="faq-icon" fill="none" stroke="currentColor" viewBox="0 0 24 24" aria-hidden="true"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M19 9l-7 7-7-7"/></svg>
                        </button>
                        <div class="faq-answer">
                            <div class="faq-answer-content">
                                <p>Timeline varies by service: Social media growth typically shows results in 2-3 months, paid ads can generate leads immediately, SEO takes 3-6 months for significant traffic increases, and brand identity delivers immediate visual impact with long-term brand recognition benefits. I set realistic expectations and provide regular updates throughout the process.</p>
                            </div>
                        </div>
                    </div>

                    <div class="faq-item">
                        <button class="faq-question" aria-expanded="false">
                            <span>What makes you different from other digital marketers in Lagos?</span>
                            <svg class="faq-icon" fill="none" stroke="currentColor" viewBox="0 0 24 24" aria-hidden="true"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M19 9l-7 7-7-7"/></svg>
                        </button>
                        <div class="faq-answer">
                            <div class="faq-answer-content">
                                <p>I combine creative excellence with analytical rigor. Every campaign is data-driven, every design decision is strategic, and every result is measurable. With 5+ years of proven results (220% average ROAS, 120% traffic growth), I don't just create content—I create growth. I also stay ahead of trends including AI marketing and AEO optimization.</p>
                            </div>
                        </div>
                    </div>

                    <div class="faq-item">
                        <button class="faq-question" aria-expanded="false">
                            <span>Do you provide ongoing support after project completion?</span>
                            <svg class="faq-icon" fill="none" stroke="currentColor" viewBox="0 0 24 24" aria-hidden="true"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M19 9l-7 7-7-7"/></svg>
                        </button>
                        <div class="faq-answer">
                            <div class="faq-answer-content">
                                <p>Absolutely! I offer various maintenance and retainer packages for ongoing support. This includes website maintenance, social media management, campaign optimization, content updates, and strategic consultation. Most clients prefer monthly retainers for continuous growth and optimization of their digital presence.</p>
                            </div>
                        </div>
                    </div>

                    <div class="faq-item">
                        <button class="faq-question" aria-expanded="false">
                            <span>What industries do you specialize in?</span>
                            <svg class="faq-icon" fill="none" stroke="currentColor" viewBox="0 0 24 24" aria-hidden="true"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M19 9l-7 7-7-7"/></svg>
                        </button>
                        <div class="faq-answer">
                            <div class="faq-answer-content">
                                <p>I've worked successfully across various industries including e-commerce, beauty and cosmetics, media and publishing, professional services, NGOs, real estate, and technology startups. My approach is adaptable—I take time to understand each industry's unique challenges and opportunities to create effective marketing strategies.</p>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </section>

        <section id="cta" class="section">
            <div class="container">
                <div class="section-header">
                    <h2 class="section-title">Ready to Transform Your Brand?</h2>
                    <p class="section-subtitle">Let's create a digital marketing strategy that drives real results for your business</p>
                </div>
                <div class="cta-buttons">
                    <a href="https://wa.me/2347080821125?text=Hello%20Adigun!%20I%27m%20ready%20to%20transform%20my%20brand" class="btn btn-white">Start Your Project Today</a>
                    <a href="#contact" class="btn btn-outline-white">Get in Touch</a>
                </div>
            </div>
        </section>

        <section id="contact" class="section">
            <div class="container">
                <div class="section-header">
                    <h2 class="section-title">Get in Touch</h2>
                    <p class="section-subtitle">Let's discuss how I can help grow your brand</p>
                </div>
                <div class="contact-grid">
                    <div class="contact-info-card">
                        <h3>Contact Information</h3>
                        <div class="contact-item">
                            <div class="contact-icon" aria-hidden="true">📍</div>
                            <div class="contact-details">
                                <p>Location</p>
                                <a href="https://maps.google.com/?q=Agege,Lagos,Nigeria">Agege, Lagos, Nigeria</a>
                            </div>
                        </div>
                        <div class="contact-item">
                            <div class="contact-icon" aria-hidden="true">📞</div>
                            <div class="contact-details">
                                <p>Phone / WhatsApp</p>
                                <a href="tel:+2347080821125">+234 708 082 1125</a>
                            </div>
                        </div>
                        <div class="contact-item">
                            <div class="contact-icon" aria-hidden="true">📧</div>
                            <div class="contact-details">
                                <p>Email</p>
                                <a href="mailto:adigunmichealoluwadamilare@gmail.com">adigunmichealoluwadamilare@gmail.com</a>
                            </div>
                        </div>
                    </div>
                    <div class="contact-info-card">
                        <h3>Business Hours</h3>
                        <div class="contact-item">
                            <div class="contact-icon" aria-hidden="true">🕐</div>
                            <div class="contact-details">
                                <p>Monday - Friday</p>
                                <span style="color: var(--dark-light); font-weight: 600;">9:00 AM - 6:00 PM (WAT)</span>
                            </div>
                        </div>
                        <div class="contact-item">
                            <div class="contact-icon" aria-hidden="true">📱</div>
                            <div class="contact-details">
                                <p>Weekend Availability</p>
                                <span style="color: var(--dark-light); font-weight: 600;">By Appointment Only</span>
                            </div>
                        </div>
                        <div class="contact-item">
                            <div class="contact-icon" aria-hidden="true">⚡</div>
                            <div class="contact-details">
                                <p>Response Time</p>
                                <span style="color: var(--dark-light); font-weight: 600;">Within 24 Hours</span>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </section>
    </main>

    <footer>
        <div class="container">
            <div class="footer-content">
                <div class="footer-section">
                    <h4>Adigun Micheal</h4>
                    <p>Digital Marketing Expert & Visual Designer based in Lagos, Nigeria. Helping brands grow through strategic marketing and stunning design.</p>
                </div>
                <div class="footer-section">
                    <h4>Quick Links</h4>
                    <ul class="footer-links">
                        <li><a href="#about">About Me</a></li>
                        <li><a href="#services">Services</a></li>
                        <li><a href="#portfolio">Portfolio</a></li>
                        <li><a href="#contact">Contact</a></li>
                    </ul>
                </div>
                <div class="footer-section">
                    <h4>Services</h4>
                    <ul class="footer-links">
                        <li><a href="#services">Social Media Marketing</a></li>
                        <li><a href="#services">SEO & AEO</a></li>
                        <li><a href="#services">Brand Design</a></li>
                        <li><a href="#services">WordPress Development</a></li>
                    </ul>
                </div>
                <div class="footer-section">
                    <h4>Contact</h4>
                    <p>📧 adigunmichealoluwadamilare@gmail.com</p>
                    <p>📞 +234 708 082 1125</p>
                    <p>📍 Agege, Lagos, Nigeria</p>
                </div>
            </div>
            <div class="footer-bottom">
                <p>&copy; 2025 Adigun Micheal Damilare. All rights reserved. Digital Marketing Expert Lagos Nigeria</p>
            </div>
        </div>
    </footer>

    <div class="whatsapp-float">
        <a href="https://wa.me/2347080821125?text=Hello%20Adigun!%20I%20need%20help%20with..." target="_blank" rel="noopener noreferrer" aria-label="Chat on WhatsApp">
            <svg class="whatsapp-icon" viewBox="0 0 24 24" fill="white" aria-hidden="true"><path d="M17.472 14.382c-.297-.149-1.758-.867-2.03-.967-.273-.099-.471-.148-.67.15-.197.297-.767.966-.94 1.164-.173.199-.347.223-.644.075-.297-.15-1.255-.463-2.39-1.475-.883-.788-1.48-1.761-1.653-2.059-.173-.297-.018-.458.13-.606.134-.133.298-.347.446-.52.149-.174.198-.298.298-.497.099-.198.05-.371-.025-.52-.075-.149-.669-1.612-.916-2.207-.242-.579-.487-.5-.669-.51-.173-.008-.371-.01-.57-.01-.198 0-.52.074-.792.372-.272.297-1.04 1.016-1.04 2.479 0 1.462 1.065 2.875 1.213 3.074.149.198 2.096 3.2 5.077 4.487.709.306 1.262.489 1.694.625.712.227 1.36.195 1.871.118.571-.085 1.758-.719 2.006-1.413.248-.694.248-1.289.173-1.413-.074-.124-.272-.198-.57-.347m-5.421 7.403h-.004a9.87 9.87 0 01-5.031-1.378l-.361-.214-3.741.982.998-3.648-.235-.374a9.86 9.86 0 01-1.51-5.26c.001-5.45 4.436-9.884 9.888-9.884 2.64 0 5.122 1.03 6.988 2.898a9.825 9.825 0 012.893 6.994c-.003 5.45-4.437 9.884-9.885 9.884m8.413-18.297A11.815 11.815 0 0012.05 0C5.495 0 .16 5.335.157 11.892c0 2.096.547 4.142 1.588 5.945L.057 24l6.305-1.654a11.882 11.882 0 005.683 1.448h.005c6.554 0 11.89-5.335 11.893-11.893a11.821 11.821 0 00-3.48-8.413z"/></svg>
            <span>Chat with us</span>
        </a>
    </div>

    <button class="back-to-top" id="backToTop" aria-label="Back to top">
        <svg width="24" height="24" fill="none" stroke="currentColor" viewBox="0 0 24 24" aria-hidden="true"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M5 10l7-7m0 0l7 7m-7-7v18"/></svg>
    </button>

    <script>
        // Mobile Menu Toggle
        const menuToggle = document.getElementById('menuToggle');
        const navMenu = document.getElementById('navMenu');

        if (menuToggle && navMenu) {
            menuToggle.addEventListener('click', () => {
                const isExpanded = menuToggle.getAttribute('aria-expanded') === 'true';
                menuToggle.setAttribute('aria-expanded', !isExpanded);
                navMenu.classList.toggle('active');
                
                // Prevent body scroll when menu is open
                document.body.style.overflow = navMenu.classList.contains('active') ? 'hidden' : '';
            });

            // Close menu when clicking on a link
            navMenu.querySelectorAll('a').forEach(link => {
                link.addEventListener('click', () => {
                    navMenu.classList.remove('active');
                    menuToggle.setAttribute('aria-expanded', 'false');
                    document.body.style.overflow = '';
                });
            });

            // Close menu when clicking outside
            document.addEventListener('click', (e) => {
                if (!menuToggle.contains(e.target) && !navMenu.contains(e.target)) {
                    navMenu.classList.remove('active');
                    menuToggle.setAttribute('aria-expanded', 'false');
                    document.body.style.overflow = '';
                }
            });
        }

        // Header scroll effect
        const header = document.getElementById('header');
        let lastScroll = 0;

        window.addEventListener('scroll', () => {
            const currentScroll = window.pageYOffset;
            
            if (currentScroll > 100) {
                header.classList.add('scrolled');
            } else {
                header.classList.remove('scrolled');
            }
            
            lastScroll = currentScroll;
        });

        // FAQ Accordion
        const faqItems = document.querySelectorAll('.faq-item');
        faqItems.forEach(item => {
            const question = item.querySelector('.faq-question');
            if (question) {
                question.addEventListener('click', () => {
                    const isActive = item.classList.contains('active');
                    
                    // Close all items
                    faqItems.forEach(faq => {
                        faq.classList.remove('active');
                        const btn = faq.querySelector('.faq-question');
                        if (btn) btn.setAttribute('aria-expanded', 'false');
                    });
                    
                    // Open clicked item if it wasn't active
                    if (!isActive) {
                        item.classList.add('active');
                        question.setAttribute('aria-expanded', 'true');
                    }
                });
            }
        });

        // Back to top button
        const backToTop = document.getElementById('backToTop');
        
        window.addEventListener('scroll', () => {
            if (window.pageYOffset > 500) {
                backToTop.classList.add('visible');
            } else {
                backToTop.classList.remove('visible');
            }
        });

        if (backToTop) {
            backToTop.addEventListener('click', () => {
                window.scrollTo({ top: 0, behavior: 'smooth' });
            });
        }

        // Smooth scroll for anchor links
        document.querySelectorAll('a[href^="#"]').forEach(anchor => {
            anchor.addEventListener('click', function (e) {
                const href = this.getAttribute('href');
                if (href !== '#' && href.length > 1) {
                    e.preventDefault();
                    const target = document.querySelector(href);
                    if (target) {
                        const headerHeight = header.offsetHeight;
                        const targetPosition = target.offsetTop - headerHeight - 20;
                        window.scrollTo({
                            top: targetPosition,
                            behavior: 'smooth'
                        });
                    }
                }
            });
        });

        // Chart.js configurations
        const chartConfig = {
            responsive: true,
            maintainAspectRatio: false,
            plugins: {
                legend: {
                    display: true,
                    position: 'top',
                    labels: {
                        padding: 12,
                        font: { size: 11, weight: '600' },
                        usePointStyle: true,
                        boxWidth: 8
                    }
                },
                tooltip: {
                    backgroundColor: 'rgba(15, 23, 42, 0.9)',
                    padding: 12,
                    titleFont: { size: 13, weight: '600' },
                    bodyFont: { size: 12 },
                    borderColor: 'rgba(148, 163, 184, 0.3)',
                    borderWidth: 1
                }
            }
        };

        // Royal Insight Chart - Line Chart
        const ctxRoyal = document.getElementById('chartRoyal');
        if (ctxRoyal) {
            try {
                new Chart(ctxRoyal.getContext('2d'), {
                    type: 'line',
                    data: {
                        labels: ['Jan', 'Feb', 'Mar', 'Apr', 'May', 'Jun'],
                        datasets: [{
                            label: 'Engagement Rate (%)',
                            data: [25, 32, 38, 45, 52, 60],
                            borderColor: '#1e3a8a',
                            backgroundColor: 'rgba(30, 58, 138, 0.1)',
                            tension: 0.4,
                            fill: true,
                            borderWidth: 2,
                            pointRadius: 4,
                            pointHoverRadius: 6
                        }, {
                            label: 'Follower Growth (%)',
                            data: [15, 22, 28, 35, 40, 45],
                            borderColor: '#92400e',
                            backgroundColor: 'rgba(146, 64, 14, 0.1)',
                            tension: 0.4,
                            fill: true,
                            borderWidth: 2,
                            pointRadius: 4,
                            pointHoverRadius: 6
                        }]
                    },
                    options: chartConfig
                });
            } catch (error) {
                console.error('Error creating Royal chart:', error);
            }
        }

        // Bella Cosmetics Chart - Bar Chart
        const ctxBella = document.getElementById('chartBella');
        if (ctxBella) {
            try {
                new Chart(ctxBella.getContext('2d'), {
                    type: 'bar',
                    data: {
                        labels: ['Week 1', 'Week 2', 'Week 3', 'Week 4', 'Week 5', 'Week 6'],
                        datasets: [{
                            label: 'Ad Spend (₦)',
                            data: [50000, 55000, 60000, 65000, 70000, 75000],
                            backgroundColor: 'rgba(100, 116, 139, 0.8)',
                            borderColor: '#64748b',
                            borderWidth: 1
                        }, {
                            label: 'Revenue (₦)',
                            data: [110000, 125000, 140000, 155000, 165000, 180000],
                            backgroundColor: 'rgba(30, 58, 138, 0.8)',
                            borderColor: '#1e3a8a',
                            borderWidth: 1
                        }]
                    },
                    options: {
                        ...chartConfig,
                        scales: {
                            y: {
                                beginAtZero: true,
                                ticks: {
                                    callback: function(value) {
                                        return '₦' + value.toLocaleString();
                                    }
                                }
                            }
                        }
                    }
                });
            } catch (error) {
                console.error('Error creating Bella chart:', error);
            }
        }

        // Imperia Insight Chart - Doughnut Chart
        const ctxImperia = document.getElementById('chartImperia');
        if (ctxImperia) {
            try {
                new Chart(ctxImperia.getContext('2d'), {
                    type: 'doughnut',
                    data: {
                        labels: ['Organic Traffic', 'Direct Traffic', 'Social Traffic', 'Referral Traffic'],
                        datasets: [{
                            data: [55, 20, 15, 10],
                            backgroundColor: [
                                'rgba(30, 58, 138, 0.8)',
                                'rgba(146, 64, 14, 0.8)',
                                'rgba(22, 101, 52, 0.8)',
                                'rgba(100, 116, 139, 0.8)'
                            ],
                            borderColor: [
                                '#1e3a8a',
                                '#92400e',
                                '#166534',
                                '#64748b'
                            ],
                            borderWidth: 2
                        }]
                    },
                    options: {
                        ...chartConfig,
                        cutout: '65%'
                    }
                });
            } catch (error) {
                console.error('Error creating Imperia chart:', error);
            }
        }

        // Lazy loading for images
        if ('IntersectionObserver' in window) {
            const imageObserver = new IntersectionObserver((entries, observer) => {
                entries.forEach(entry => {
                    if (entry.isIntersecting) {
                        const img = entry.target;
                        if (img.dataset.src) {
                            img.src = img.dataset.src;
                            img.removeAttribute('data-src');
                        }
                        observer.unobserve(img);
                    }
                });
            });

            document.querySelectorAll('img[data-src]').forEach(img => {
                imageObserver.observe(img);
            });
        }
    </script>
</body>
</html>
