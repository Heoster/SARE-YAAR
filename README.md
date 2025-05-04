
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>SARE YAAR</title>
    <link rel="icon" src="Logo.PNG" type="image/png">
    <meta name="description" content="Celebrating the friendship of our class 10 batch from 2024. Memories that will last forever.">
    <meta property="og:title" content="SARE YAAR - Class of 2024">
    <meta property="og:description" content="A tribute to our unforgettable school friendship and memories.">
    <meta property="og:image" content="https://2024wallepals.simdif.com/images/public/sd_673b6c02b931a.jpg">
    <meta property="og:type" content="website">
    
    <!-- Font Awesome for icons -->
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
    
    <!-- Google Fonts -->
    <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;600;700&family=Dancing+Script:wght@700&display=swap" rel="stylesheet">
    
    <!-- Animate.css -->
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/animate.css/4.1.1/animate.min.css">
    
    <!-- AOS Library -->
    <link href="https://cdn.jsdelivr.net/npm/aos@2.3.4/dist/aos.css" rel="stylesheet">
    
    <style>
        :root {
            --primary-color: #ff6b6b;
            --secondary-color: #4ecdc4;
            --dark-color: #292f36;
            --light-color: #f7fff7;
            --accent-color: #ff9f1c;
            --shadow-color: rgba(0,0,0,0.1);
        }
        
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }
        
        body {
            font-family: 'Poppins', sans-serif;
            background-color: #f5f5f5;
            color: var(--dark-color);
            line-height: 1.6;
            overflow-x: hidden;
            transition: background-color 0.5s ease, color 0.5s ease;
        }
        
        /* Header Styles */
        header {
            background: linear-gradient(135deg, var(--primary-color), var(--secondary-color));
            color: white;
            padding: 3rem 0;
            text-align: center;
            position: relative;
            overflow: hidden;
            box-shadow: 0 4px 20px rgba(.2,.5,.3,0.3);
            transition: background 0.5s ease;
        }
        
        .header-content {
            position: relative;
            z-index: 2;
            max-width: 0 auto;
            margin: 0 auto;
            padding: 0 20px;
        }
        
        .logo {
            width: 140px;
            height: 140px;
            border-radius: 50%;
            object-fit: cover;
            border: 5px solid white;
            margin-bottom: 1.5rem;
            box-shadow: 0 8px 20px rgba(0,0,0,0.2);
            transition: all 0.5s cubic-bezier(0.25, 0.8, 0.25, 1);
        }
        
        .logo:hover {
            transform: scale(1.1) rotate(8deg);
            box-shadow: 0 12px 25px rgba(0,0,0,0.3);
        }
        
        h1.site-title {
            font-family: 'Dancing Script', cursive;
            font-size: 4rem;
            margin-bottom: 0.5rem;
            text-shadow: 2px 2px 6px rgba(0,0,0,0.2);
            animation: fadeInDown 1s both, pulse 2s infinite 2s;
        }
        
        .tagline {
            font-size: 1.3rem;
            opacity: 0.9;
            margin-bottom: 2rem;
            animation: fadeIn 1.5s both, float 4s ease-in-out infinite 1.5s;
        }
        
        /* Navigation */
        nav {
            background-color: white;
            box-shadow: 0 3px 15px rgba(0,.5,0,0.1);
            position: sticky;
            top: 0;
            z-index: 100;
            transition: background-color 0.5s ease, box-shadow 0.5s ease;
        }
        
        .nav-container {
            max-width: 1200px;
            margin: 0 auto;
            display: flex;
            justify-content: space-between;
            align-items: center;
            padding: 1rem 2rem;
        }
        
        .nav-logo {
            font-weight: 700;
            font-size: 1.8rem;
            color: var(--primary-color);
            text-decoration: none;
            transition: all 0.3s ease;
            font-family: 'Dancing Script', cursive;
        }
        
        .nav-logo:hover {
            transform: scale(1.05);
            color: var(--secondary-color);
        }
        
        .nav-links {
            display: flex;
            list-style: none;
        }
        
        .nav-links li {
            margin-left: 2.5rem;
        }
        
        .nav-links a {
            text-decoration: none;
            color: var(--dark-color);
            font-weight: 600;
            position: relative;
            padding: 0.5rem 0;
            transition: all 0.3s ease;
            font-size: 1.1rem;
        }
        
        .nav-links a:after {
            content: '';
            position: absolute;
            width: 0;
            height: 3px;
            bottom: 0;
            left: 0;
            background-color: var(--primary-color);
            transition: width 0.4s cubic-bezier(0.65, 0, 0.35, 1);
        }
        
        .nav-links a:hover {
            color: var(--primary-color);
            transform: translateY(-3px);
        }
        
        .nav-links a:hover:after {
            width: 100%;
        }
        
        .mobile-menu-btn {
            display: none;
            background: none;
            border: none;
            font-size: 1.8rem;
            color: var(--dark-color);
            cursor: pointer;
            transition: transform 0.3s ease;
        }
        
        .mobile-menu-btn:hover {
            transform: scale(1.1);
            color: var(--primary-color);
        }
        
        /* Main Content */
        .container {
            max-width: 1200px;
            margin: 3rem auto;
            padding: 0 20px;
        }

        .scrolling-container {
            width: 100%;
            overflow: hidden;
            white-space: nowrap;
            position: relative;
        }

        .scrolling-content {
            display: inline-block;
            animation: scrollLeft 20s linear infinite;
        }

        .scrolling-content img {
            height: 200px;
            width: auto;
            margin-right: 20px;
        }

        @keyframes scrollLeft {
            0% {
                transform: translateX(0);
            }
            100% {
                transform: translateX(-50%);
            }
        }
         
        section {
            margin-bottom: 4rem;
            background-color: white;
            border-radius: 15px;
            padding: 3rem;
            box-shadow: 0 5px 20px rgba(0,0,0,0.08);
            transition: all 0.5s cubic-bezier(0.25, 0.8, 0.25, 1);
            opacity: 0;
            transform: translateY(30px);
        }
        
        section.animated {
            opacity: 1;
            transform: translateY(0);
        }
        
        section:hover {
            transform: translateY(-10px) scale(1.02);
            box-shadow: 0 10px 30px rgba(0,0,0,0.15);
        }
        
        h2.section-title {
            font-size: 2.5rem;
            margin-bottom: 2rem;
            color: var(--primary-color);
            position: relative;
            padding-bottom: 1rem;
            font-family: 'Dancing Script', cursive;
        }
        
        h2.section-title:after {
            content: '';
            position: absolute;
            width: 80px;
            height: 4px;
            bottom: 0;
            left: 0;
            background: linear-gradient(to right, var(--primary-color), var(--secondary-color));
            border-radius: 2px;
            transform-origin: left;
            transform: scaleX(0);
            transition: transform 0.8s cubic-bezier(0.65, 0, 0.35, 1);
        }
        
        section:hover h2.section-title:after {
            transform: scaleX(1);
        }
        
        p.section-text {
            margin-bottom: 2rem;
            color: #555;
            line-height: 1.8;
            font-size: 1.1rem;
            transition: color 0.5s ease;
        }
        
        /* Gallery Grid */
        .gallery-grid {
            display: grid;
            grid-template-columns: repeat(auto-fill, minmax(280px, 1fr));
            gap: 2rem;
            margin-top: 2.5rem;
        }
        
        .gallery-item {
            position: relative;
            border-radius: 12px;
            overflow: hidden;
            box-shadow: 0 8px 20px rgba(0,0,0,0.1);
            transition: all 0.6s cubic-bezier(0.25, 0.8, 0.25, 1);
            aspect-ratio: 1/1;
            transform-style: preserve-3d;
        }
        
        .gallery-item:hover {
            transform: scale(1.05) translateY(-8px) rotateY(5deg);
            box-shadow: 0 15px 35px rgba(0,0,0,0.2);
            z-index: 2;
        }
        
        .gallery-img {
            width: 100%;
            height: 100%;
            object-fit: cover;
            transition: transform 0.8s ease, filter 0.5s ease;
        }
        
        .gallery-item:hover .gallery-img {
            transform: scale(1.1);
            filter: brightness(1.1);
        }
        
        .gallery-caption {
            position: absolute;
            bottom: 0;
            left: 0;
            right: 0;
            background: linear-gradient(to top, rgba(0,0,0,0.8), transparent);
            color: white;
            padding: 1.5rem;
            transform: translateY(100%);
            transition: transform 0.5s cubic-bezier(0.25, 0.8, 0.25, 1);
            font-weight: 600;
            text-align: center;
            backdrop-filter: blur(1px);
            font-size: 1.1rem;
        }
        
        .gallery-item:hover .gallery-caption {
            transform: translateY(0);
        }
        
        /* Testimonials */
        .testimonials {
            display: grid;
            grid-template-columns: repeat(auto-fill, minmax(320px, 1fr));
            gap: 2.5rem;
        }
        
        .testimonial {
            background-color: #f9f9f9;
            padding: 2rem;
            border-radius: 15px;
            box-shadow: 0 5px 15px rgba(0,0,0,0.08);
            position: relative;
            transition: all 0.5s ease;
            transform: perspective(1000px) rotateX(5deg);
        }
        
        .testimonial:hover {
            transform: perspective(1000px) rotateX(0) translateY(-8px);
            box-shadow: 0 12px 30px rgba(0,0,0,0.15);
        }
        
        .testimonial:before {
            content: '"';
            font-family: Georgia, serif;
            font-size: 6rem;
            color: rgba(0,0,0,0.05);
            position: absolute;
            top: -20px;
            left: 10px;
            line-height: 1;
        }
        
        .testimonial-content {
            margin-bottom: 1.5rem;
            font-style: italic;
            font-size: 1.2rem;
            position: relative;
            z-index: 1;
        }
        
        .testimonial-author {
            display: flex;
            align-items: center;
        }
        
        .author-img {
            width: 70px;
            height: 70px;
            border-radius: 50%;
            object-fit: cover;
            margin-right: 1.5rem;
            border: 3px solid var(--primary-color);
            transition: transform 0.4s ease;
        }
        
        .testimonial:hover .author-img {
            transform: scale(1.1);
        }
        
        .author-info h4 {
            margin-bottom: 0.3rem;
            color: var(--primary-color);
            font-size: 1.2rem;
        }
        
        .author-info p {
            font-size: 0.9rem;
            color: #777;
        }
        
        /* Footer */
        footer {
            background: linear-gradient(135deg, var(--dark-color), #1a1a1a);
            color: white;
            padding: 5rem 0 3rem;
            text-align: center;
            position: relative;
            overflow: hidden;
            transition: background 0.5s ease;
        }
        
        footer:before {
            content: '';
            position: absolute;
            top: 0;
            left: 0;
            right: 0;
            height: 6px;
            background: linear-gradient(to right, var(--primary-color), var(--secondary-color));
        }
        
        .footer-content {
            max-width: 1200px;
            margin: 0 auto;
            padding: 0 20px;
            position: relative;
            z-index: 1;
        }
        
        .social-links {
            display: flex;
            justify-content: center;
            margin: 2.5rem 0;
        }
        
        .social-link {
            display: flex;
            align-items: center;
            justify-content: center;
            width: 55px;
            height: 55px;
            border-radius: 50%;
            background-color: rgba(255,255,255,0.1);
            margin: 0 1rem;
            color: white;
            text-decoration: none;
            transition: all 0.5s cubic-bezier(0.25, 0.8, 0.25, 1);
            font-size: 1.3rem;
        }
        
        .social-link:hover {
            background-color: var(--primary-color);
            transform: translateY(-5px) scale(1.1);
            box-shadow: 0 8px 20px rgba(255,107,107,0.4);
        }
        
        .copyright {
            margin-top: 2.5rem;
            opacity: 0.8;
            font-size: 1rem;
            line-height: 1.6;
        }
        
        /* Animations */
        @keyframes float {
            0%, 100% {
                transform: translateY(0);
            }
            50% {
                transform: translateY(-15px);
            }
        }
        
        @keyframes pulse {
            0%, 100% {
                transform: scale(1);
            }
            50% {
                transform: scale(1.05);
            }
        }
        
        @keyframes wave {
            0%, 100% {
                transform: rotate(0deg);
            }
            25% {
                transform: rotate(5deg);
            }
            75% {
                transform: rotate(-5deg);
            }
        }
        
        @keyframes bounce {
            0%, 20%, 50%, 80%, 100% {
                transform: translateY(0);
            }
            40% {
                transform: translateY(-20px);
            }
            60% {
                transform: translateY(-10px);
            }
        }
        
        .floating {
            animation: float 4s ease-in-out infinite;
        }
        
        .pulse {
            animation: pulse 2s ease infinite;
        }
        
        .wave {
            animation: wave 3s ease infinite;
            transform-origin: center bottom;
        }
        
        .bounce {
            animation: bounce 1.5s ease infinite;
        }
        
        .delay-1 {
            animation-delay: 0.2s;
        }
        
        .delay-2 {
            animation-delay: 0.4s;
        }
        
        .delay-3 {
            animation-delay: 0.6s;
        }
        
        /* Memory Highlight */
        .memory-highlight {
            background-color: rgba(255, 214, 107, 0.2);
            padding: 2.5rem;
            border-radius: 15px;
            border-left: 5px solid var(--accent-color);
            margin: 3rem 0;
            position: relative;
            overflow: hidden;
            transition: transform 0.5s ease, box-shadow 0.5s ease;
        }
        
        .memory-highlight:before {
            content: '';
            position: absolute;
            top: -15px;
            right: -15px;
            width: 50px;
            height: 50px;
            background-color: var(--accent-color);
            opacity: 0.2;
            border-radius: 50%;
        }
        
        .memory-highlight:after {
            content: '';
            position: absolute;
            bottom: -20px;
            left: -20px;
            width: 70px;
            height: 70px;
            background-color: var(--secondary-color);
            opacity: 0.1;
            border-radius: 50%;
        }
        
        .memory-highlight:hover {
            transform: translateY(-5px);
            box-shadow: 0 10px 25px rgba(255,159,28,0.2);
        }
        
        .memory-highlight p {
            position: relative;
            z-index: 1;
            font-style: italic;
            font-size: 1.3rem;
            color: var(--dark-color);
            text-align: center;
            line-height: 1.6;
        }
        
        /* Quote */
        .quote {
            font-style: italic;
            font-size: 1.5rem;
            color: var(--dark-color);
            text-align: center;
            margin: 4rem 0;
            position: relative;
            padding: 2rem;
        }
        
        .quote:before, .quote:after {
            content: '"';
            font-size: 5rem;
            color: var(--primary-color);
            opacity: 0.3;
            position: absolute;
            line-height: 1;
        }
        
        .quote:before {
            top: -15px;
            left: 0;
        }
        
        .quote:after {
            bottom: -60px;
            right: 0;
        }
        
        /* Button */
        .btn {
            display: inline-block;
            background: linear-gradient(45deg, var(--primary-color), var(--secondary-color));
            color: white;
            padding: 1.2rem 2.5rem;
            border-radius: 50px;
            text-decoration: none;
            font-weight: 600;
            margin-top: 2rem;
            transition: all 0.5s cubic-bezier(0.25, 0.8, 0.25, 1);
            box-shadow: 0 8px 20px rgba(0,0,0,0.15);
            position: relative;
            overflow: hidden;
            border: none;
            cursor: pointer;
            font-size: 1.1rem;
        }
        
        .btn:before {
            content: '';
            position: absolute;
            top: 0;
            left: -100%;
            width: 100%;
            height: 100%;
            background: linear-gradient(90deg, transparent, rgba(255,255,255,0.2), transparent);
            transition: 0.6s;
        }
        
        .btn:hover {
            transform: translateY(-5px) scale(1.05);
            box-shadow: 0 12px 30px rgba(0,0,0,0.25);
        }
        
        .btn:hover:before {
            left: 100%;
        }
        
        /* Timeline */
        .timeline {
            position: relative;
            max-width: 1200px;
            margin: 4rem auto;
        }
        
        .timeline:after {
            content: '';
            position: absolute;
            width: 8px;
            background: linear-gradient(to bottom, var(--primary-color), var(--secondary-color));
            top: 0;
            bottom: 0;
            left: 50%;
            margin-left: -4px;
            border-radius: 4px;
        }
        
        .timeline-item {
            padding: 20px 60px;
            position: relative;
            width: 50%;
            box-sizing: border-box;
            opacity: 0;
            transform: translateY(40px);
            transition: all 0.8s ease;
        }
        
        .timeline-item.visible {
            opacity: 1;
            transform: translateY(0);
        }
        
        .timeline-item:after {
            content: '';
            position: absolute;
            width: 30px;
            height: 30px;
            background-color: white;
            border: 6px solid var(--primary-color);
            border-radius: 50%;
            top: 25px;
            z-index: 1;
            transition: all 0.5s ease;
        }
        
        .timeline-item:hover:after {
            transform: scale(1.2);
            background-color: var(--primary-color);
            border-color: white;
        }
        
        .left {
            left: 0;
        }
        
        .right {
            left: 50%;
        }
        
        .left:after {
            right: -20px;
        }
        
        .right:after {
            left: -20px;
        }
        
        .timeline-content {
            padding: 30px;
            background-color: white;
            border-radius: 15px;
            box-shadow: 0 8px 20px rgba(0,0,0,0.1);
            transition: all 0.5s ease;
            position: relative;
        }
        
        .timeline-content:before {
            content: '';
            position: absolute;
            width: 25px;
            height: 25px;
            background-color: white;
            top: 25px;
            transform: rotate(45deg);
        }
        
        .left .timeline-content:before {
            right: -12px;
        }
        
        .right .timeline-content:before {
            left: -12px;
        }
        
        .timeline-item:hover .timeline-content {
            transform: translateY(-8px);
            box-shadow: 0 12px 30px rgba(0,0,0,0.15);
        }
        
        .timeline-date {
            color: var(--primary-color);
            font-weight: 700;
            margin-bottom: 1rem;
            font-size: 1.2rem;
        }
        
        /* Huge Gallery Grid */
        .huge-gallery-grid {
            display: grid;
            grid-template-columns: repeat(auto-fill, minmax(280px, 1fr));
            gap: 2.5rem;
            margin-top: 3rem;
        }
        
        .huge-gallery-grid .gallery-item {
            position: relative;
            overflow: hidden;
            border-radius: 18px;
            box-shadow: 0 12px 30px rgba(0,0,0,0.2);
            transition: all 0.6s cubic-bezier(0.25, 0.8, 0.25, 1);
        }
        
        .huge-gallery-grid .gallery-item:hover {
            transform: scale(1.08);
            box-shadow: 0 18px 40px rgba(0,0,0,0.25);
            z-index: 3;
        }
        
        .huge-gallery-grid .gallery-img {
            width: 100%;
            height: 100%;
            object-fit: cover;
            transition: transform 1s ease, filter 0.6s ease;
        }
        
        .huge-gallery-grid .gallery-caption {
            position: absolute;
            bottom: 0;
            left: 0;
            right: 0;
            background: linear-gradient(to top, rgba(0,0,0,0.8), transparent);
            color: white;
            padding: 2rem;
            text-align: center;
            font-weight: bold;
            font-size: 1.2rem;
            transform: translateY(100%);
            transition: transform 0.6s cubic-bezier(0.25, 0.8, 0.25, 1);
            backdrop-filter: blur(8px);
        }
        
        .huge-gallery-grid .gallery-item:hover .gallery-img {
            transform: scale(1.15);
        }
        
        .huge-gallery-grid .gallery-item:hover .gallery-caption {
            transform: translateY(0);
        }

        /* Masonry Grid Styles */
        .masonry-grid {
            display: flex;
            margin-left: -15px;
            width: auto;
            margin-top: 2.5rem;
        }
        
        .masonry-column {
            padding-left: 15px;
            background-clip: padding-box;
            flex: 1;
        }
        
        .masonry-item {
            margin-bottom: 30px;
            border-radius: 12px;
            overflow: hidden;
            position: relative;
            box-shadow: 0 8px 20px rgba(0,0,0,0.1);
            transition: all 0.5s cubic-bezier(0.25, 0.8, 0.25, 1);
        }
        
        .masonry-img {
            width: 100%;
            height: auto;
            display: block;
            transition: transform 0.8s ease;
        }
        
        .masonry-caption {
            position: absolute;
            bottom: 0;
            left: 0;
            right: 0;
            background: linear-gradient(to top, rgba(0,0,0,0.8), transparent);
            color: white;
            padding: 1.5rem;
            transform: translateY(100%);
            transition: transform 0.5s cubic-bezier(0.25, 0.8, 0.25, 1);
            font-weight: 600;
            text-align: center;
            backdrop-filter: blur(1px);
        }
        
        .masonry-item:hover {
            transform: translateY(-8px);
            box-shadow: 0 15px 35px rgba(0,0,0,0.2);
        }
        
        .masonry-item:hover .masonry-img {
            transform: scale(1.05);
        }
        
        .masonry-item:hover .masonry-caption {
            transform: translateY(0);
        }

        /* Theme Switcher Styles */
        .theme-switcher {
            position: fixed;
            bottom: 30px;
            right: 30px;
            z-index: 9999;
        }
        
        .theme-btn {
            background: linear-gradient(45deg, #3a3a3a, #6a6a6a);
            border-radius: 50px;
            padding: 12px 20px;
            box-shadow: 0 4px 15px rgba(0,0,0,0.2);
            transition: all 0.5s ease;
            display: flex;
            align-items: center;
            gap: 8px;
            color: white;
            border: none;
            cursor: pointer;
            font-weight: 600;
            font-size: 1rem;
            font-family: 'Poppins', sans-serif;
        }
        
        .theme-btn i {
            font-size: 1.2rem;
            transition: transform 0.5s ease;
        }
        
        /* Dark Theme Styles */
        body.dark-theme {
            background-color: #121212;
            color: #e0e0e0;
        }
        
        body.dark-theme header {
            background: linear-gradient(135deg, #1a1a2e, #16213e);
        }
        
        body.dark-theme nav {
            background-color: #1e1e1e;
            box-shadow: 0 3px 15px rgba(0,0,0,0.3);
        }
        
        body.dark-theme .nav-links a {
            color: #e0e0e0;
        }
        
        body.dark-theme section {
            background-color: #1e1e1e;
            box-shadow: 0 5px 20px rgba(0,0,0,0.3);
        }
        
        body.dark-theme p.section-text {
            color: #b0b0b0;
        }
        
        body.dark-theme .gallery-item {
            box-shadow: 0 8px 20px rgba(0,0,0,0.4);
        }
        
        body.dark-theme .testimonial {
            background-color: #252525;
            box-shadow: 0 5px 15px rgba(0,0,0,0.3);
        }
        
        body.dark-theme .testimonial:before {
            color: rgba(255,255,255,0.05);
        }
        
        body.dark-theme footer {
            background: linear-gradient(135deg, #0f0f0f, #1a1a1a);
        }
        
        body.dark-theme .btn {
            background: linear-gradient(45deg, #4a4a4a, #2c3e50);
        }
        
        body.dark-theme .theme-btn {
            background: linear-gradient(45deg, #ff6b6b, #4ecdc4);
        }
        
        body.dark-theme .theme-btn i {
            transform: rotate(180deg);
        }
        
        body.dark-theme .quote {
            color: #e0e0e0;
        }
        
        body.dark-theme .quote:before,
        body.dark-theme .quote:after {
            color: rgba(255,107,107,0.5);
        }
        
        body.dark-theme .timeline-content {
            background-color: #252525;
            box-shadow: 0 8px 20px rgba(0,0,0,0.3);
        }
        
        body.dark-theme .timeline-content:before {
            background-color: #252525;
        }
        
        body.dark-theme .timeline-item:after {
            background-color: #252525;
            border-color: var(--primary-color);
        }
        
        body.dark-theme .memory-highlight p {
            color: #e0e0e0;
        }
        
        body.dark-theme .masonry-item {
            box-shadow: 0 8px 20px rgba(0,0,0,0.3);
        }
        
        body.dark-theme .masonry-item:hover {
            box-shadow: 0 15px 35px rgba(0,0,0,0.4);
        }
        
        /* Responsive Design */
        @media (max-width: 1200px) {
            .container {
                padding: 0 30px;
            }
        }
        
        @media (max-width: 992px) {
            h1.site-title {
                font-size: 3.5rem;
            }
            
            .gallery-grid, .huge-gallery-grid {
                grid-template-columns: repeat(auto-fill, minmax(240px, 1fr));
            }
            
            section {
                padding: 2.5rem;
            }
            
            .masonry-grid {
                flex-wrap: wrap;
            }
            
            .masonry-column {
                flex: 0 0 50%;
                max-width: 50%;
            }
        }
        
        @media (max-width: 768px) {
            h1.site-title {
                font-size: 3rem;
            }
            
            .nav-container {
                padding: 1rem;
            }
            
            .nav-links {
                position: fixed;
                top: 80px;
                left: -100%;
                width: 100%;
                height: calc(100vh - 80px);
                background-color: white;
                flex-direction: column;
                align-items: center;
                justify-content: center;
                transition: left 0.5s cubic-bezier(0.65, 0, 0.35, 1);
                z-index: 99;
            }
            
            .nav-links.active {
                left: 0;
            }
            
            .nav-links li {
                margin: 2rem 0;
            }
            
            .nav-links a {
                font-size: 1.3rem;
            }
            
            .mobile-menu-btn {
                display: block;
            }
            
            section {
                padding: 2rem;
                border-radius: 12px;
            }
            
            .timeline:after {
                left: 31px;
            }
            
            .timeline-item {
                width: 100%;
                padding-left: 80px;
                padding-right: 30px;
            }
            
            .timeline-item:after {
                left: 21px;
            }
            
            .right {
                left: 0;
            }
            
            .left .timeline-content:before, 
            .right .timeline-content:before {
                left: 25px;
                right: auto;
                top: -12px;
                transform: rotate(45deg);
            }
        }
        
        @media (max-width: 576px) {
            h1.site-title {
                font-size: 2.5rem;
            }
            
            .logo {
                width: 120px;
                height: 120px;
            }
            
            .gallery-grid, .huge-gallery-grid {
                grid-template-columns: 1fr;
            }
            
            .testimonials {
                grid-template-columns: 1fr;
            }
            
            .btn {
                width: 100%;
                text-align: center;
                padding: 1rem;
            }
            
            section {
                padding: 1.8rem;
            }
            
            h2.section-title {
                font-size: 2rem;
            }
            
            .masonry-column {
                flex: 0 0 100%;
                max-width: 100%;
            }
            
            .theme-btn {
                padding: 10px 16px;
                font-size: 0.9rem;
            }
        }
    </style>
</head>
<body>
    <!-- Theme Switcher Button -->
    <div class="theme-switcher">
        <button id="themeToggle" class="btn theme-btn">
            <i class="fas fa-moon"></i> Dark Mode
        </button>
    </div>

    <!-- Header with Hero Section -->
    <header class="animate__animated animate__fadeIn">
        <div class="header-content">
            <img src="Logo.PNG" alt="SARE YAAR Logo" class="logo floating">
            <h1 class="site-title pulse">SARE YAAR</h1>
            <p class="tagline">Class of 2024 - Memories That Last a Lifetime</p>
            
            <div class="social-links">
                <a href="https://www.instagram.com/codex._.heoster?igsh=MTF1Mzl3MmFnbGxpMg==" class="social-link" aria-label="Instagram"><i class="fab fa-instagram"></i></a>
                <a href="https://www.instagram.com/__pankajthakur7?igsh=bm40Ynppd3h5bjEx" class="social-link" aria-label="Instagram"><i class="fab fa-instagram"></i></a>
               <a href="https://github.com/Heoster" class="social-link" aria-label="Github"><i class="fab fa-github"></i></a>
                <a href="https://chat.whatsapp.com/CNkUA5HS05D9htJ1KLwkrk" class="social-link" aria-label="WhatsApp"><i class="fab fa-whatsapp"></i></a>
            </div>
        </div>
    </header>
    
    <!-- Navigation -->
    <nav>
        <div class="nav-container">
            <a href="https://2024wallepals.simdif.com/images/public/sd_673b6c02b931a.jpg?no_cache=1733914653" class="nav-logo wave">SARE YAAR</a>
            
            <button class="mobile-menu-btn" id="mobileMenuBtn">
                <i class="fas fa-bars"></i>
            </button>
            
            <ul class="nav-links" id="navLinks">
                <li><a href="#home" class="active">Home</a></li>
                <li><a href="#memories">Our Memories</a></li>
                <li><a href="#gallery">Gallery</a></li>
                <li><a href="#poetry">Poetry</a></li>
                <li><a href="#about">About Us</a></li>
                <li><a href="#contact">Contact</a></li>
            </ul>
        </div>
    </nav>
    <div class="scrolling-container">
        <div class="scrolling-content">
            <img src="11g.jpg" alt="Image 1">
            <img src="12g.jpg" alt="Image 2">
            <img src="10g.jpg" alt="Image 3">
            <img src="9g.jpg" alt="Image 4">
            <img src="8g.jpg" alt="Image 5">
            <img src="7g.jpg" alt="Image 6">
            <img src="6g.jpg" alt="Image 7">
            <img src="5g.jpg" alt="Image 8">
            <!-- Duplicate images for seamless looping -->
            <img src="11g.jpg" alt="Image 1">
            <img src="12g.jpg" alt="Image 2">
            <img src="10g.jpg" alt="Image 3">
            <img src="9g.jpg" alt="Image 4">
            <img src="8g.jpg" alt="Image 5">
            <img src="7g.jpg" alt="Image 6">
            <img src="6g.jpg" alt="Image 7">
            <img src="5g.jpg" alt="Image 8">
        </div>
    </div>
    
    <!-- Main Content -->
    <main class="container">
        <!-- Welcome Section -->
        <section id="home" data-aos="fade-up" data-aos-duration="1000">
            <h2 class="section-title">Welcome to Our Friendship Journey</h2>
            <p class="section-text">We were students of class 10 in 2024. Our friendship has no curve till now, but this year we are going to separate. This separation is not easy for us.</p>
            
            <div class="memory-highlight animate__animated animate__pulse animate__infinite animate__slower">
                <p>"Friendship is the only cement that will ever hold the world together." - Woodrow Wilson</p>
            </div>
            
            <p class="section-text">This website is a tribute to our unforgettable moments, inside jokes, and the bond that will last forever.</p>
            
            <a href="#memories" class="btn bounce">Explore Our Memories</a>
        </section>
        
        <!-- Featured Memories -->
        <section id="memories" data-aos="fade-up" data-aos-duration="1000" data-aos-delay="100">
            <h2 class="section-title">Our Special Memories</h2>
            
            <div class="timeline">
                <div class="timeline-item left">
                    <div class="timeline-content">
                        <div class="timeline-date">First Day - April 2022</div>
                        <p>The day we all met and our journey began. Little did we know we'd become inseparable.</p>
                    </div>
                </div>
                
                <div class="timeline-item right">
                    <div class="timeline-content">
                        <div class="timeline-date">School Trip - October 2023</div>
                        <p>That unforgettable trip where we laughed, explored, and created memories to last a lifetime.</p>
                    </div>
                </div>
                
                <div class="timeline-item left">
                    <div class="timeline-content">
                        <div class="timeline-date">Annual Day - December 2023</div>
                        <p>Our amazing performance that won first prize, thanks to everyone's hard work and teamwork.</p>
                    </div>
                </div>
                
                <div class="timeline-item right">
                    <div class="timeline-content">
                        <div class="timeline-date">Farewell - March 2024</div>
                        <p>The bittersweet day when we realized our school journey was ending but our friendship wasn't.</p>
                    </div>
                </div>
            </div>
            
            <p class="quote">"We didn't realize we were making memories, we just knew we were having fun."</p>
        </section>
        
        <!-- Photo Gallery -->
        <section id="gallery" data-aos="fade-up" data-aos-duration="1000" data-aos-delay="200">
            <h2 class="section-title">Our Gallery</h2>
            <p class="section-text">A collection of our favorite moments together.</p>
            
            <div class="gallery-grid">
                <div class="gallery-item" data-aos="zoom-in" data-aos-duration="800">
                    <img src="https://2024wallepals.simdif.com/images/th/sd_673db7464d01e.jpg?no_cache=1733831618" alt="School View" class="gallery-img">
                    <div class="gallery-caption">School Memory 2023</div>
                </div>
                
                <div class="gallery-item" data-aos="zoom-in" data-aos-duration="800" data-aos-delay="100">
                    <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcTsV0mKDqVb76mClI80jZWF4jmPx3zFfaPPJg&s" alt="Classroom" class="gallery-img">
                    <div class="gallery-caption">Annual Day</div>
                </div>
                
                <div class="gallery-item" data-aos="zoom-in" data-aos-duration="800" data-aos-delay="200">
                    <img src="https://2024wallepals.simdif.com/images/public/sd_673b562a40fd8.jpg?no_cache=1731942029" alt="Classroom fun" class="gallery-img">
                    <div class="gallery-caption">Classroom Memories</div>
                </div>
                
                <div class="gallery-item" data-aos="zoom-in" data-aos-duration="800" data-aos-delay="300">
                    <img src="https://2024wallepals.simdif.com/images/th/sd_675828882bd11.jpg?no_cache=1733834411" alt="Celebration" class="gallery-img">
                    <div class="gallery-caption">Celebration</div>
                </div>
                
                <div class="gallery-item" data-aos="zoom-in" data-aos-duration="800" data-aos-delay="400">
                    <img src="https://2024wallepals.simdif.com/images/th/sd_673b63d9112cb.jpg?no_cache=1731949060" alt="Sports day" class="gallery-img">
                    <div class="gallery-caption">Sports Day 2023</div>
                </div>
                
                <div class="gallery-item" data-aos="zoom-in" data-aos-duration="800" data-aos-delay="500">
                    <img src="https://2024wallepals.simdif.com/images/th/sd_673db927c50c7.jpg?no_cache=1732101961" alt="Memory" class="gallery-img">
                    <div class="gallery-caption">What a Day</div>
                </div>
                
                <div class="gallery-item" data-aos="zoom-in" data-aos-duration="800" data-aos-delay="600">
                    <img src="1.jpg" alt="Special Memory" class="gallery-img">
                    <div class="gallery-caption">Special Moment</div>
                </div>
                
                <div class="gallery-item" data-aos="zoom-in" data-aos-duration="800" data-aos-delay="700">
                    <img src="2g.jpg" alt="Group Photo" class="gallery-img">
                    <div class="gallery-caption">Group Photo</div>
                </div>
                <div class="gallery-item" data-aos="zoom-in" data-aos-duration="800" data-aos-delay="700">
                    <img src="B1.jpg" alt="Group Photo" class="gallery-img">
                    <div class="gallery-caption">Group Photo</div>
                </div>
            </div>
            
            <a href="https://2024wallepals.simdif.com" class="btn">View Full Gallery</a>
        </section>
        
        <!-- Poetry Section -->
        <section id="poetry" data-aos="fade-up" data-aos-duration="1000" data-aos-delay="300">
            <h2 class="section-title">Our Poetry Corner</h2>
            
            <div class="testimonials">
                <div class="testimonial" data-aos="fade-up" data-aos-duration="800">
                    <div class="testimonial-content">
                        <p>Lost in your mind<br>
                        I wanna know<br>
                        Am I losing my mind?<br>
                        Never let me go</p>
                    </div>
                    <div class="testimonial-author">
                        <img src="H3.jpg" alt="Nawajish" class="author-img">
                        <div class="author-info">
                            <h4>Nawajish</h4>
                            <p>Poet & Dreamer</p>
                        </div>
                    </div>
                </div>
                <div class="testimonial" data-aos="fade-up" data-aos-duration="800" data-aos-delay="100">
                    <div class="testimonial-content">
                        <p>If this night is not forever<br>
                        At least we are together<br>
                        I know I'm not alone<br>
                        I know I'm not alone</p>
                    </div>
                    <div class="testimonial-author">
                        <img src="H1.jpg" alt="Heoster" class="author-img">
                        <div class="author-info">
                            <h4>HEOSTER</h4>
                            <p>Who developelop this website.</p>
                        </div>
                    </div>
                </div>
                <div class="testimonial" data-aos="fade-up" data-aos-duration="800" data-aos-delay="100">
                    <div class="testimonial-content">
                        <p>If this night is not forever<br>
                        At least we are together<br>
                        I know I'm not alone<br>
                        I know I'm not alone</p>
                    </div>
                    <div class="testimonial-author">
                        <img src="H4.jpg" alt="Pardhuman" class="author-img">
                        <div class="author-info">
                            <h4>Badmash</h4>
                            <p>He is the ❤.</p>
                        </div>
                    </div>
                </div>
                
                <div class="testimonial" data-aos="fade-up" data-aos-duration="800" data-aos-delay="100">
                    <div class="testimonial-content">
                        <p>If this night is not forever<br>
                        At least we are together<br>
                        I know I'm not alone<br>
                        I know I'm not alone</p>
                    </div>
                    <div class="testimonial-author">
                        <img src="https://2024wallepals.simdif.com/images/th/sd_673d8c617f8cf.jpg?no_cache=1733832584" alt="Pankaj" class="author-img">
                        <div class="author-info">
                            <h4>Pankaj</h4>
                            <p>Founder of Carpenter Samaj</p>
                        </div>
                    </div>
                </div>
                
                <div class="testimonial" data-aos="fade-up" data-aos-duration="800" data-aos-delay="200">
                    <div class="testimonial-content">
                        <p>Nothing can be gained without losing anything,<br>
                        Even heaven demands death.</p>
                    </div>
                    <div class="testimonial-author">
                        <img src="https://2024wallepals.simdif.com/images/th/sd_673c0e0e3eac1.jpg?no_cache=1733914598" alt="Vishesh" class="author-img">
                        <div class="author-info">
                            <h4>Uchiha Vishesh</h4>
                            <p>Philosopher</p>
                        </div>
                    </div>
                </div>
            </div>
        </section>
        
        <!-- Extended Gallery Section -->
        <section id="extended-gallery" data-aos="fade-up" data-aos-duration="1000" data-aos-delay="400">
            <h2 class="section-title">More Beautiful Memories</h2>
            <p class="section-text">Swipe through more moments that made our journey unforgettable.</p>

            <div class="gallery-grid">
                <div class="gallery-item" data-aos="zoom-in">
                    <img src="https://2024wallepals.simdif.com/images/th/sd_673c0ede951de.jpg?no_cache=1733832532" alt="Memory 1" class="gallery-img">
                    <div class="gallery-caption">Fun Times</div>
                </div>
                <div class="gallery-item" data-aos="zoom-in" data-aos-delay="100">
                    <img src="https://2024wallepals.simdif.com/images/th/sd_6745ec9f80eb8.jpg?no_cache=1733831861" alt="Memory 2" class="gallery-img">
                    <div class="gallery-caption">Friendship Bond</div>
                </div>
                <div class="gallery-item" data-aos="zoom-in" data-aos-delay="200">
                    <img src="https://2024wallepals.simdif.com/images/th/sd_673b63d9112cb.jpg?no_cache=1731949060" alt="Memory 3" class="gallery-img">
                    <div class="gallery-caption">Our Group</div>
                </div>
                <div class="gallery-item" data-aos="zoom-in" data-aos-delay="300">
                    <img src="https://2024wallepals.simdif.com/images/th/sd_675828882bd11.jpg?no_cache=1733834411" alt="Memory 4" class="gallery-img">
                    <div class="gallery-caption">Fun Activities</div>
                </div>
                <div class="gallery-item" data-aos="zoom-in" data-aos-delay="400">
                    <img src="3g.jpg" alt="Memory 5" class="gallery-img">
                    <div class="gallery-caption">Special Moment</div>
                </div>
                <div class="gallery-item" data-aos="zoom-in" data-aos-delay="500">
                    <img src="4g.jpg" alt="Memory 6" class="gallery-img">
                    <div class="gallery-caption">Together Forever</div>
                </div>
                <div class="gallery-item" data-aos="zoom-in" data-aos-delay="600">
                    <img src="5g.jpg" alt="Memory 7" class="gallery-img">
                    <div class="gallery-caption">Fun Day</div>
                </div>
                <div class="gallery-item" data-aos="zoom-in" data-aos-delay="700">
                    <img src="6g.jpg" alt="Memory 8" class="gallery-img">
                    <div class="gallery-caption">Group Photo</div>
                </div>
            </div>
        </section>

        <!-- Masonry Gallery Section -->
        <section id="masonry-gallery" data-aos="fade-up" data-aos-duration="1000">
            <h2 class="section-title">Masonry Memories</h2>
            <p class="section-text">A dynamic collage of our special moments in a unique layout.</p>
            
            <div class="masonry-grid">
                <!-- Column 1 -->
                <div class="masonry-column">
                    <div class="masonry-item">
                        <img src="H.jpg" alt="Memory H" class="masonry-img">
                        <div class="masonry-caption">Special Moment H</div>
                    </div>
                    <div class="masonry-item">
                        <img src="H4.jpg" alt="Memory H4" class="masonry-img">
                        <div class="masonry-caption">Special Moment H4</div>
                    </div>
                    <div class="masonry-item">
                        <img src="H8.jpg" alt="Memory H8" class="masonry-img">
                        <div class="masonry-caption">Special Moment H8</div>
                    </div>
                    <div class="masonry-item">
                        <img src="H12.jpg" alt="Memory H12" class="masonry-img">
                        <div class="masonry-caption">Special Moment H12</div>
                    </div>
                </div>
                
                <!-- Column 2 -->
                <div class="masonry-column">
                    <div class="masonry-item">
                        <img src="H2.jpg" alt="Memory H2" class="masonry-img">
                        <div class="masonry-caption">Special Moment H2</div>
                    </div>
                    <div class="masonry-item">
                        <img src="H5.jpg" alt="Memory H5" class="masonry-img">
                        <div class="masonry-caption">Special Moment H5</div>
                    </div>
                    <div class="masonry-item">
                        <img src="H9.jpg" alt="Memory H9" class="masonry-img">
                        <div class="masonry-caption">Special Moment H9</div>
                    </div>
                    <div class="masonry-item">
                        <img src="H13.jpg" alt="Memory H13" class="masonry-img">
                        <div class="masonry-caption">Special Moment H13</div>
                    </div>
                </div>
                
                <!-- Column 3 -->
                <div class="masonry-column">
                    <div class="masonry-item">
                        <img src="H3.jpg" alt="Memory H3" class="masonry-img">
                        <div class="masonry-caption">Special Moment H3</div>
                    </div>
                    <div class="masonry-item">
                        <img src="H6.jpg" alt="Memory H6" class="masonry-img">
                        <div class="masonry-caption">Special Moment H6</div>
                    </div>
                    <div class="masonry-item">
                        <img src="H10.jpg" alt="Memory H10" class="masonry-img">
                        <div class="masonry-caption">Special Moment H10</div>
                    </div>
                    <div class="masonry-item">
                        <img src="H14.jpg" alt="Memory H14" class="masonry-img">
                        <div class="masonry-caption">Special Moment H14</div>
                    </div>
                </div>
                
                <!-- Column 4 -->
                <div class="masonry-column">
                    <div class="masonry-item">
                        <img src="H1.jpg" alt="Memory H1" class="masonry-img">
                        <div class="masonry-caption">Special Moment H1</div>
                    </div>
                    <div class="masonry-item">
                        <img src="H7.jpg" alt="Memory H7" class="masonry-img">
                        <div class="masonry-caption">Special Moment H7</div>
                    </div>
                    <div class="masonry-item">
                        <img src="H11.jpg" alt="Memory H11" class="masonry-img">
                        <div class="masonry-caption">Special Moment H11</div>
                    </div>
                    <div class="masonry-item">
                        <img src="H15.jpg" alt="Memory H15" class="masonry-img">
                        <div class="masonry-caption">Special Moment H15</div>
                    </div>
                </div>
            </div>
        </section>

        <!-- About Section -->
        <section id="about" data-aos="fade-up" data-aos-duration="1000" data-aos-delay="500">
            <h2 class="section-title">About Our Group</h2>
            
            <div class="memory-highlight">
                <p>"Our friendship is a history that never repeats again. We are so lucky to have such friends."</p>
            </div>
            
            <p class="section-text">We are a group of friends from the class 10th of 2024 who share an unbreakable bond. Despite our different personalities and backgrounds, we've created something truly special together.</p>
            
            <div class="gallery-grid" style="grid-template-columns: repeat(auto-fill, minmax(180px, 1fr));">
                <div class="gallery-item" data-aos="zoom-in">
                    <img src="https://2024wallepals.simdif.com/images/th/sd_6745ec9f80eb8.jpg?no_cache=1733831861" alt="Pandat" class="gallery-img">
                    <div class="gallery-caption">Pandat</div>
                </div>
                <div class="gallery-item" data-aos="zoom-in" data-aos-delay="100">
                    <img src="https://2024wallepals.simdif.com/images/public/sd_673dbb5b80450.png?no_cache=1732102520" alt="HEOSTER" class="gallery-img">
                    <div class="gallery-caption">HEOSTER</div>
                </div>
                <div class="gallery-item" data-aos="zoom-in" data-aos-delay="200">
                    <img src="https://2024wallepals.simdif.com/images/public/sd_673d8f920fb97.jpg?no_cache=1732091342" alt="Pankaj" class="gallery-img">
                    <div class="gallery-caption">Pankaj</div>
                </div>
                <div class="gallery-item" data-aos="zoom-in" data-aos-delay="300">
                    <img src="https://2024wallepals.simdif.com/images/th/sd_673b56ae3f883.jpg?no_cache=1733831884" alt="Sahil" class="gallery-img">
                    <div class="gallery-caption">Sahil</div>
                </div>
                <div class="gallery-item" data-aos="zoom-in" data-aos-delay="400">
                    <img src="https://2024wallepals.simdif.com/images/public/sd_673cb450c58c1.jpg?no_cache=1732035187" alt="Lakshay" class="gallery-img">
                    <div class="gallery-caption">Lakshay</div>
                </div>
                <div class="gallery-item" data-aos="zoom-in" data-aos-delay="500">
                    <img src="https://2024wallepals.simdif.com/images/public/sd_673c0ede951de.jpg?no_cache=1733832532" alt="Jani" class="gallery-img">
                    <div class="gallery-caption">Pasandu</div>
                </div>
                <div class="gallery-item" data-aos="zoom-in" data-aos-delay="600">
                    <img src="H5.jpg" alt="Jani" class="gallery-img">
                    <div class="gallery-caption">SARE YAAR💖</div>
                </div>
            </div>   
        </section>
    
        <!-- Extended Huge Gallery Section -->
        <section id="huge-gallery" data-aos="fade-up" data-aos-duration="1000" data-aos-delay="600">
            <h2 class="section-title">Our Ultimate Memory Gallery</h2>
            <p class="section-text">Dive into an extended view of our treasured moments together.</p>

            <div class="huge-gallery-grid">
                <div class="gallery-item" data-aos="zoom-in">
                    <img src="1.jpg" alt="Memory 1" class="gallery-img">
                    <div class="gallery-caption">Special Memory 1</div>
                </div>
                <div class="gallery-item" data-aos="zoom-in" data-aos-delay="100">
                    <img src="2g.jpg" alt="group photo" class="gallery-img">
                    <div class="gallery-caption">Special Memory 2</div>
                </div>
                <div class="gallery-item" data-aos="zoom-in" data-aos-delay="200">
                    <img src="3g.jpg" alt="Memory 3" class="gallery-img">
                    <div class="gallery-caption">Special Memory 3</div>
                </div>
                <div class="gallery-item" data-aos="zoom-in" data-aos-delay="300">
                    <img src="4g.jpg" alt="Memory 4" class="gallery-img">
                    <div class="gallery-caption">Special Memory 4</div>
                </div>
                <div class="gallery-item" data-aos="zoom-in" data-aos-delay="400">
                    <img src="5g.jpg" alt="Memory 5" class="gallery-img">
                    <div class="gallery-caption">Special Memory 5</div>
                </div>
                <div class="gallery-item" data-aos="zoom-in" data-aos-delay="500">
                    <img src="6g.jpg" alt="Memory 6" class="gallery-img">
                    <div class="gallery-caption">Special Memory 6</div>
                </div>
                <div class="gallery-item" data-aos="zoom-in" data-aos-delay="600">
                    <img src="7g.jpg" alt="Memory 7" class="gallery-img">
                    <div class="gallery-caption">Special Memory 7</div>
                </div>
                <div class="gallery-item" data-aos="zoom-in" data-aos-delay="700">
                    <img src="8g.jpg" alt="Memory 8" class="gallery-img">
                    <div class="gallery-caption">Special Memory 8</div>
                </div>
                <div class="gallery-item" data-aos="zoom-in" data-aos-delay="800">
                    <img src="9g.jpg" alt="Memory 9" class="gallery-img">
                    <div class="gallery-caption">Special Memory 9</div>
                </div>
                <div class="gallery-item" data-aos="zoom-in" data-aos-delay="900">
                    <img src="10g.jpg" alt="Memory 10" class="gallery-img">
                    <div class="gallery-caption">Special Memory 10</div>
                </div>
                <div class="gallery-item" data-aos="zoom-in" data-aos-delay="1000">
                    <img src="11g.jpg" alt="Memory 11" class="gallery-img">
                    <div class="gallery-caption">Special Memory 11</div>
                </div>
                <div class="gallery-item" data-aos="zoom-in" data-aos-delay="1100">
                    <img src="12g.jpg" alt="Memory 12" class="gallery-img">
                    <div class="gallery-caption">Special Memory 12</div>
                </div>
                <div class="gallery-item" data-aos="zoom-in" data-aos-delay="1000">
                    <img src="B1.jpg" alt="Memory B1" class="gallery-img">
                    <div class="gallery-caption">Special Memory B1</div>
                </div>
                <div class="gallery-item" data-aos="zoom-in" data-aos-delay="1000">
                    <img src="B2.jpg" alt="Memory B2" class="gallery-img">
                    <div class="gallery-caption">Special Memory B2</div>
                </div>
                <div class="gallery-item" data-aos="zoom-in" data-aos-delay="1000">
                    <img src="B3.jpg" alt="Memory B3" class="gallery-img">
                    <div class="gallery-caption">Special Memory B3</div>
                </div>
                <div class="gallery-item" data-aos="zoom-in" data-aos-delay="1000">
                    <img src="B4.jpg" alt="Memory B4" class="gallery-img">
                    <div class="gallery-caption">Special Memory B4</div>
                </div>
                <div class="gallery-item" data-aos="zoom-in" data-aos-delay="1000">
                    <img src="B5.jpg" alt="Memory B5" class="gallery-img">
                    <div class="gallery-caption">Special Memory B5</div>
                </div>
                <div class="gallery-item" data-aos="zoom-in" data-aos-delay="1000">
                    <img src="B6.jpg" alt="Memory B6" class="gallery-img">
                    <div class="gallery-caption">Special Memory B6</div>
                </div>
                <div class="gallery-item" data-aos="zoom-in" data-aos-delay="1000">
                    <img src="B7.jpg" alt="Memory B7" class="gallery-img">
                    <div class="gallery-caption">Special Memory B7</div>
                </div>
                <div class="gallery-item" data-aos="zoom-in" data-aos-delay="1000">
                    <img src="B8.jpg" alt="Memory B8" class="gallery-img">
                    <div class="gallery-caption">Special Memory B8</div>
                </div>
                <div class="gallery-item" data-aos="zoom-in" data-aos-delay="1000">
                    <img src="B9.jpg" alt="Memory B9" class="gallery-img">
                    <div class="gallery-caption">Special Memory B9</div>
                </div>
                <div class="gallery-item" data-aos="zoom-in" data-aos-delay="1000">
                    <img src="B10.jpg" alt="Memory B10" class="gallery-img">
                    <div class="gallery-caption">Special Memory B10</div>
                </div>
            </div>
        </section>
    </main>
    
    <!-- Footer -->
    <footer>
        <div class="footer-content">
            <h3 data-aos="fade-up">SARE YAAR - Class of 2024</h3>
            
            <div class="social-links">
                <a href="https://www.instagram.com/codex._.heoster?igsh=MTF1Mzl3MmFnbGxpMg==" class="social-link" aria-label="Instagram" data-aos="fade-up" data-aos-delay="100"> <i class="fab fa-instagram"></i></a>
                <a href=" #" class="social-link" aria-label="Instagram"" data-aos="fade-up" data-aos-delay="200"><i class="fab fa-instagram"></i></a>
                <a href="https://github.com/Heoster" class="social-link" aria-label="Github" data-aos="fade-up" data-aos-delay="300"><i class="fab fa-github"></i></a>
                <a href="https://chat.whatsapp.com/CNkUA5HS05D9htJ1KLwkrk" class="social-link" aria-label="WhatsApp" data-aos="fade-up" data-aos-delay="400"><i class="fab fa-whatsapp"></i></a>
            </div>
            
            <p class="copyright" data-aos="fade-up" data-aos-delay="500">Copyright Disclaimer: Under section 107 of the Copyright Act 1976, allowance is made for FAIR USE for purposes such as criticism, comment, news reporting, teaching, scholarship and research.</p>
            
            <p class="copyright" data-aos="fade-up" data-aos-delay="600">© 2024 SARE YAAR. All memories preserved.</p>
            <p class="copyright" data-aos="fade-up" data-aos-delay="700">This website is developed by codeex._.heoster.</p>
        </div>
    </footer>
    
    <!-- JavaScript -->
    <script src="https://cdn.jsdelivr.net/npm/aos@2.3.4/dist/aos.js"></script>
    <script>
        // Initialize AOS animations
        AOS.init({
            duration: 1000,
            once: true,
            easing: 'ease-out-cubic'
        });

        // Mobile menu toggle
        const mobileMenuBtn = document.getElementById('mobileMenuBtn');
        const navLinks = document.getElementById('navLinks');
        
        mobileMenuBtn.addEventListener('click', () => {
            navLinks.classList.toggle('active');
            mobileMenuBtn.innerHTML = navLinks.classList.contains('active') ? 
                '<i class="fas fa-times"></i>' : '<i class="fas fa-bars"></i>';
        });
        
        // Smooth scrolling for navigation links
        document.querySelectorAll('a[href^="#"]').forEach(anchor => {
            anchor.addEventListener('click', function(e) {
                e.preventDefault();
                
                const targetId = this.getAttribute('href');
                const targetElement = document.querySelector(targetId);
                
                window.scrollTo({
                    top: targetElement.offsetTop - 80,
                    behavior: 'smooth'
                });
                
                // Close mobile menu if open
                if (navLinks.classList.contains('active')) {
                    navLinks.classList.remove('active');
                    mobileMenuBtn.innerHTML = '<i class="fas fa-bars"></i>';
                }
            });
        });

        // Animate timeline items on scroll
        const timelineItems = document.querySelectorAll('.timeline-item');
        
        function checkTimelineItems() {
            const triggerBottom = window.innerHeight / 5 * 4;
            
            timelineItems.forEach(item => {
                const itemTop = item.getBoundingClientRect().top;
                
                if (itemTop < triggerBottom) {
                    item.classList.add('visible');
                }
            });
        }
        
        window.addEventListener('scroll', checkTimelineItems);
        checkTimelineItems(); // Check on load
        
        // Animate sections on scroll
        const sections = document.querySelectorAll('section');
        
        function animateSections() {
            const triggerBottom = window.innerHeight / 5 * 4;
            
            sections.forEach(section => {
                const sectionTop = section.getBoundingClientRect().top;
                
                if (sectionTop < triggerBottom) {
                    section.classList.add('animated');
                }
            });
        }
        
        window.addEventListener('scroll', animateSections);
        animateSections(); // Check on load

        // Theme Switcher Functionality
        const themeToggle = document.getElementById('themeToggle');
        
        // Check for saved theme preference
        const currentTheme = localStorage.getItem('theme');
        if (currentTheme === 'dark') {
            document.body.classList.add('dark-theme');
            themeToggle.innerHTML = '<i class="fas fa-sun"></i> Light Mode';
        }
        
        themeToggle.addEventListener('click', () => {
            document.body.classList.toggle('dark-theme');
            
            if (document.body.classList.contains('dark-theme')) {
                localStorage.setItem('theme', 'dark');
                themeToggle.innerHTML = '<i class="fas fa-sun"></i> Light Mode';
            } else {
                localStorage.setItem('theme', 'light');
                themeToggle.innerHTML = '<i class="fas fa-moon"></i> Dark Mode';
            }
            
            updateThemeForElements();
        });
        
        // Update theme-specific elements
        function updateThemeForElements() {
            const isDark = document.body.classList.contains('dark-theme');
            
            // Update timeline items
            document.querySelectorAll('.timeline-content').forEach(item => {
                item.style.backgroundColor = isDark ? '#252525' : 'white';
            });
            
            // Update gallery captions
            document.querySelectorAll('.gallery-caption').forEach(caption => {
                caption.style.background = isDark ? 
                    'linear-gradient(to top, rgba(0,0,0,0.9), transparent)' :
                    'linear-gradient(to top, rgba(0,0,0,0.8), transparent)';
            });
            
            // Update masonry captions
            document.querySelectorAll('.masonry-caption').forEach(caption => {
                caption.style.background = isDark ? 
                    'linear-gradient(to top, rgba(0,0,0,0.9), transparent)' :
                    'linear-gradient(to top, rgba(0,0,0,0.8), transparent)';
            });
        }
        
        // Initialize on load
        window.addEventListener('load', updateThemeForElements);
    </script>
</body>
</html>
