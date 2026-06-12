<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>JoshArt - Where silence becomes color</title>
    <link href="https://fonts.googleapis.com/css2?family=Cormorant+Garamond:ital,wght@0,300;0,400;0,500;0,600;0,700;1,300;1,400;1,500;1,600;1,700&family=Inter:wght@100..900&display=swap" rel="stylesheet">
    <style>
        /* === VARIABLES === */
        :root {
            --color-deep-navy: #050d1a;
            --color-rich-midnight: #080f20;
            --color-cyan-accent: #00d4ff;
            --color-electric-teal: #00ffee;
            --color-muted-steel-blue: #1a3a5c;
            --color-soft-ice: #b8e8f0;
            --color-white-text: #f0f8ff;
            --color-subtle-glow: rgba(0, 212, 255, 0.08);

            --font-heading: 'Cormorant Garamond', serif;
            --font-body: 'Inter', sans-serif;
        }

        /* === BASE STYLES === */
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        html {
            scroll-behavior: smooth;
        }

        body {
            font-family: var(--font-body);
            color: var(--color-white-text);
            background-color: var(--color-deep-navy);
            line-height: 1.6;
            overflow-x: hidden;
            position: relative;
        }

        h1, h2, h3, h4, h5, h6 {
            font-family: var(--font-heading);
            font-style: italic;
            color: var(--color-white-text);
            line-height: 1.2;
        }

        a {
            color: var(--color-cyan-accent);
            text-decoration: none;
            transition: color 0.3s ease;
        }

        a:hover {
            color: var(--color-electric-teal);
        }

        /* === UTILITIES === */
        .container {
            max-width: 1440px;
            margin: 0 auto;
            padding: 0 20px;
        }

        .text-center {
            text-align: center;
        }

        .reveal-element {
            opacity: 0;
            transform: translateY(40px);
            transition: opacity 1s ease-out, transform 1s ease-out;
        }

        .reveal-element.is-visible {
            opacity: 1;
            transform: translateY(0);
        }

        .reveal-left {
            transform: translateX(-60px);
        }
        .reveal-right {
            transform: translateX(60px);
        }

        /* Glass Morphism */
        .glass-morphism {
            background: rgba(8, 15, 32, 0.4); /* rich midnight with transparency */
            backdrop-filter: blur(12px);
            border: 1px solid rgba(0, 212, 255, 0.2); /* subtle cyan border */
            box-shadow: 0 8px 32px 0 rgba(0, 0, 0, 0.3);
            border-radius: 10px;
            padding: 20px;
        }

        /* Button Glow */
        .btn-primary {
            display: inline-block;
            padding: 15px 30px;
            background: linear-gradient(90deg, var(--color-cyan-accent), var(--color-electric-teal));
            color: var(--color-deep-navy);
            font-weight: bold;
            text-transform: uppercase;
            border-radius: 50px;
            border: none;
            cursor: pointer;
            position: relative;
            overflow: hidden;
            z-index: 1;
            transition: all 0.3s ease;
            box-shadow: 0 0 15px var(--color-cyan-accent);
        }

        .btn-primary:hover {
            transform: translateY(-3px);
            box-shadow: 0 0 25px var(--color-electric-teal);
        }

        .btn-primary::before {
            content: '';
            position: absolute;
            top: 50%;
            left: 50%;
            width: 300%;
            height: 300%;
            background: rgba(0, 212, 255, 0.2);
            border-radius: 50%;
            transition: all 0.7s ease;
            z-index: -1;
            transform: translate(-50%, -50%) scale(0);
        }

        .btn-primary:hover::before {
            transform: translate(-50%, -50%) scale(1);
        }

        @keyframes pulse-glow {
            0% { box-shadow: 0 0 10px var(--color-cyan-accent); }
            50% { box-shadow: 0 0 25px var(--color-electric-teal), 0 0 50px var(--color-cyan-accent); }
            100% { box-shadow: 0 0 10px var(--color-cyan-accent); }
        }

        .btn-primary.pulsing {
            animation: pulse-glow 2s infinite ease-in-out;
        }

        /* === HEADER / NAVIGATION === */
        .main-header {
            position: fixed;
            top: 0;
            left: 0;
            width: 100%;
            z-index: 1000;
            padding: 20px;
            display: flex;
            justify-content: space-between;
            align-items: center;
            transition: background-color 0.4s ease, backdrop-filter 0.4s ease, padding 0.4s ease;
        }

        .main-header.scrolled {
            background: rgba(8, 15, 32, 0.8);
            backdrop-filter: blur(10px);
            padding: 10px 20px;
        }

        .main-header .logo {
            font-family: var(--font-heading);
            font-style: italic;
            font-size: 2em;
            color: var(--color-white-text);
            letter-spacing: 1px;
        }

        .main-nav ul {
            list-style: none;
            display: flex;
            gap: 30px;
        }

        .main-nav a {
            font-family: var(--font-body);
            font-weight: 500;
            font-size: 1.1em;
            color: var(--color-soft-ice);
            position: relative;
            padding-bottom: 5px;
        }

        .main-nav a::after {
            content: '';
            position: absolute;
            left: 0;
            bottom: 0;
            width: 0;
            height: 2px;
            background-color: var(--color-cyan-accent);
            transition: width 0.3s ease;
        }

        .main-nav a:hover::after {
            width: 100%;
        }

        /* Mobile Menu */
        .menu-toggle {
            display: none;
            flex-direction: column;
            cursor: pointer;
            gap: 5px;
        }

        .menu-toggle span {
            width: 30px;
            height: 3px;
            background-color: var(--color-cyan-accent);
            transition: all 0.3s ease;
        }

        .main-nav.active {
            display: flex;
        }

        /* === HERO SECTION === */
        .hero {
            position: relative;
            width: 100%;
            height: 100vh;
            display: flex;
            flex-direction: column;
            justify-content: center;
            align-items: center;
            text-align: center;
            overflow: hidden;
            background-color: var(--color-deep-navy); /* Fallback */
        }

        .hero-canvas {
            position: absolute;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            z-index: 0;
        }

        .hero-content {
            position: relative;
            z-index: 1;
            transform: translateY(20px);
            opacity: 0;
            animation: hero-text-fade-in 1.5s forwards ease-out 0.5s;
        }

        @keyframes hero-text-fade-in {
            to {
                opacity: 1;
                transform: translateY(0);
            }
        }

        .hero h1 {
            font-size: 8vw; /* Responsive font size */
            margin-bottom: 0.1em;
            letter-spacing: 2px;
            text-shadow: 0 0 20px var(--color-cyan-accent), 0 0 40px var(--color-electric-teal);
        }

        .hero p {
            font-family: var(--font-body);
            font-size: 2vw;
            color: var(--color-soft-ice);
            letter-spacing: 1px;
        }

        .scroll-down {
            position: absolute;
            bottom: 30px;
            left: 50%;
            transform: translateX(-50%);
            z-index: 2;
            display: flex;
            flex-direction: column;
            align-items: center;
            color: var(--color-cyan-accent);
            animation: pulse-arrow 2s infinite ease-in-out;
        }

        .scroll-down span {
            font-size: 0.8em;
            margin-bottom: 5px;
        }

        .scroll-down .arrow {
            width: 0;
            height: 0;
            border-left: 10px solid transparent;
            border-right: 10px solid transparent;
            border-top: 15px solid var(--color-cyan-accent);
        }

        @keyframes pulse-arrow {
            0% { opacity: 0.7; transform: translateY(0); }
            50% { opacity: 1; transform: translateY(-10px); }
            100% { opacity: 0.7; transform: translateY(0); }
        }

        /* === ABOUT SECTION === */
        .about-section {
            padding: 80px 0;
            background-color: var(--color-rich-midnight);
            position: relative;
            overflow: hidden;
        }

        .about-content {
            display: flex;
            flex-direction: row;
            gap: 60px;
            align-items: center;
        }

        .about-image {
            flex: 1;
            min-width: 300px;
            position: relative;
        }

        .about-image svg {
            width: 100%;
            height: auto;
            display: block;
            border-radius: 10px;
            background: linear-gradient(135deg, var(--color-muted-steel-blue) 0%, var(--color-rich-midnight) 100%);
            box-shadow: 0 10px 30px rgba(0, 0, 0, 0.5);
            padding: 20px;
        }

        .about-image .svg-fill {
            fill: var(--color-cyan-accent);
            opacity: 0.8;
        }

        .about-text {
            flex: 2;
            padding: 20px;
            border-left: 2px solid var(--color-muted-steel-blue);
            padding-left: 40px;
        }

        .about-text h2 {
            font-size: 3.5em;
            margin-bottom: 25px;
            color: var(--color-electric-teal);
            text-shadow: 0 0 10px var(--color-cyan-accent);
        }

        .about-text p {
            font-size: 1.1em;
            color: var(--color-soft-ice);
            margin-bottom: 15px;
        }

        /* === FEATURED WORKS SECTION === */
        .featured-works {
            padding: 80px 0;
            background-color: var(--color-deep-navy);
            text-align: center;
            overflow-x: hidden;
        }

        .featured-works h2 {
            font-size: 3.5em;
            margin-bottom: 60px;
        }

        .gallery-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
            gap: 40px;
            padding: 0 20px;
        }

        .art-card {
            background-color: var(--color-rich-midnight);
            border-radius: 15px;
            overflow: hidden;
            box-shadow: 0 15px 30px rgba(0, 0, 0, 0.4), 0 0 20px var(--color-subtle-glow);
            transition: transform 0.1s ease-out; /* For 3D tilt */
            transform-style: preserve-3d;
            perspective: 1000px;
            border: 1px solid rgba(0, 212, 255, 0.2);
            position: relative;
            display: flex;
            flex-direction: column;
            height: 100%;
        }

        .art-card-image-placeholder {
            width: 100%;
            padding-top: 75%; /* 4:3 Aspect Ratio */
            position: relative;
            overflow: hidden;
            background-color: var(--color-muted-steel-blue); /* Fallback */
        }

        .art-card-image-placeholder::before {
            content: '';
            position: absolute;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            border-radius: 15px 15px 0 0;
            background: 
                radial-gradient(circle at 10% 20%, rgba(0,255,255,0.3) 0%, rgba(0,255,255,0) 50%),
                radial-gradient(circle at 90% 80%, rgba(0,212,255,0.4) 0%, rgba(0,212,255,0) 50%),
                conic-gradient(from 0deg at 50% 50%, var(--color-deep-navy), var(--color-muted-steel-blue), var(--color-electric-teal), var(--color-cyan-accent), var(--color-deep-navy));
            filter: blur(2px) brightness(0.9);
            animation: subtle-shift 20s infinite alternate linear;
        }

        /* Unique gradients for each card */
        .art-card:nth-child(1) .art-card-image-placeholder::before {
            background: conic-gradient(from 45deg at 70% 30%, var(--color-electric-teal), var(--color-muted-steel-blue), var(--color-deep-navy));
            animation-delay: 0s;
        }
        .art-card:nth-child(2) .art-card-image-placeholder::before {
            background: radial-gradient(circle at 20% 80%, var(--color-cyan-accent) 0%, transparent 60%), linear-gradient(160deg, var(--color-rich-midnight), var(--color-deep-navy));
            animation-delay: 5s;
        }
        .art-card:nth-child(3) .art-card-image-placeholder::before {
            background: linear-gradient(45deg, var(--color-muted-steel-blue), var(--color-electric-teal));
            animation-delay: 10s;
        }
        .art-card:nth-child(4) .art-card-image-placeholder::before {
            background: conic-gradient(at 30% 60%, var(--color-deep-navy), var(--color-cyan-accent), var(--color-rich-midnight));
            animation-delay: 15s;
        }
        .art-card:nth-child(5) .art-card-image-placeholder::before {
            background: radial-gradient(circle at 50% 10%, var(--color-electric-teal), transparent 70%), linear-gradient(-45deg, var(--color-muted-steel-blue), var(--color-deep-navy));
            animation-delay: 20s;
        }
        .art-card:nth-child(6) .art-card-image-placeholder::before {
            background: linear-gradient(to right top, var(--color-rich-midnight), var(--color-cyan-accent), var(--color-electric-teal));
            animation-delay: 25s;
        }

        @keyframes subtle-shift {
            0% { background-position: 0% 0%; }
            100% { background-position: 100% 100%; }
        }

        .art-card-info {
            padding: 25px;
            text-align: left;
            flex-grow: 1;
            display: flex;
            flex-direction: column;
            justify-content: space-between;
        }

        .art-card h3 {
            font-size: 1.8em;
            margin-bottom: 10px;
            color: var(--color-cyan-accent);
        }

        .art-card p {
            font-size: 0.95em;
            color: var(--color-soft-ice);
            margin-bottom: 8px;
        }

        .art-card .price {
            font-size: 1.2em;
            font-weight: bold;
            color: var(--color-electric-teal);
            margin-top: 15px;
            margin-bottom: 20px;
        }

        .art-card .btn-inquire {
            display: block;
            width: 100%;
            padding: 12px 20px;
            background: rgba(0, 212, 255, 0.15); /* Cyan with transparency */
            backdrop-filter: blur(8px);
            border: 1px solid rgba(0, 212, 255, 0.4);
            color: var(--color-white-text);
            font-weight: 600;
            border-radius: 8px;
            text-transform: uppercase;
            letter-spacing: 0.5px;
            transition: all 0.3s ease;
            box-shadow: 0 0 10px rgba(0, 212, 255, 0.3);
        }

        .art-card .btn-inquire:hover {
            background: rgba(0, 212, 255, 0.3);
            box-shadow: 0 0 15px rgba(0, 212, 255, 0.6);
            transform: translateY(-2px);
        }

        /* === EXHIBITION TIMELINE SECTION === */
        .exhibition-timeline {
            padding: 80px 0;
            background-color: var(--color-rich-midnight);
        }

        .exhibition-timeline h2 {
            font-size: 3.5em;
            text-align: center;
            margin-bottom: 60px;
        }

        .timeline {
            position: relative;
            max-width: 900px;
            margin: 0 auto;
            padding: 40px 0;
        }

        .timeline::before {
            content: '';
            position: absolute;
            left: 50%;
            top: 0;
            width: 2px;
            height: 100%;
            background-color: var(--color-muted-steel-blue);
            transform: translateX(-50%);
            z-index: 0;
        }

        .timeline-entry {
            display: flex;
            justify-content: space-between;
            margin-bottom: 60px;
            position: relative;
            opacity: 0;
            transform: translateY(40px);
            transition: opacity 1s ease-out, transform 1s ease-out;
            z-index: 1;
        }

        .timeline-entry.is-visible {
            opacity: 1;
            transform: translateY(0);
        }

        .timeline-entry:nth-child(even) {
            flex-direction: row-reverse;
        }

        .timeline-entry-content {
            width: 45%;
            padding: 25px;
            background-color: var(--color-rich-midnight);
            border-radius: 10px;
            box-shadow: 0 5px 20px rgba(0, 0, 0, 0.3);
            border: 1px solid rgba(0, 212, 255, 0.2);
            position: relative;
            opacity: 0; /* Handled by JS for stagger */
            transform: translateX(0); /* Handled by JS for stagger */
            transition: opacity 0.8s ease-out, transform 0.8s ease-out;
        }

        .timeline-entry-content.is-visible-left {
            opacity: 1;
            transform: translateX(0);
        }
        .timeline-entry-content.is-visible-right {
            opacity: 1;
            transform: translateX(0);
        }


        .timeline-entry:nth-child(odd) .timeline-entry-content {
            transform: translateX(-60px);
        }
        .timeline-entry:nth-child(even) .timeline-entry-content {
            transform: translateX(60px);
        }

        .timeline-entry .dot {
            position: absolute;
            top: 50%;
            left: 50%;
            transform: translate(-50%, -50%);
            width: 20px;
            height: 20px;
            background-color: var(--color-cyan-accent);
            border-radius: 50%;
            box-shadow: 0 0 15px var(--color-electric-teal);
            z-index: 2;
            animation: timeline-dot-pulse 2s infinite ease-in-out;
            opacity: 0;
            transition: opacity 0.5s ease-out;
        }

        .timeline-entry .dot.is-visible {
            opacity: 1;
        }

        @keyframes timeline-dot-pulse {
            0% { transform: translate(-50%, -50%) scale(1); box-shadow: 0 0 8px var(--color-electric-teal); }
            50% { transform: translate(-50%, -50%) scale(1.1); box-shadow: 0 0 20px var(--color-cyan-accent), 0 0 30px var(--color-electric-teal); }
            100% { transform: translate(-50%, -50%) scale(1); box-shadow: 0 0 8px var(--color-electric-teal); }
        }

        .timeline-entry h3 {
            font-size: 1.8em;
            color: var(--color-electric-teal);
            margin-bottom: 10px;
        }

        .timeline-entry p {
            font-size: 1em;
            color: var(--color-soft-ice);
        }

        /* === PROCESS SECTION === */
        .process-section {
            padding: 80px 0;
            background-color: var(--color-deep-navy);
            text-align: center;
        }

        .process-section h2 {
            font-size: 3.5em;
            margin-bottom: 60px;
        }

        .process-grid {
            display: flex;
            justify-content: center;
            gap: 50px;
            flex-wrap: wrap;
        }

        .process-step {
            flex: 1;
            min-width: 280px;
            max-width: 350px;
            position: relative;
            padding: 40px 20px;
            border-radius: 15px;
            background-color: var(--color-rich-midnight);
            border: 1px solid rgba(0, 212, 255, 0.2);
            box-shadow: 0 10px 30px rgba(0, 0, 0, 0.3);
            overflow: hidden;
            opacity: 0;
            transform: translateY(40px);
            transition: opacity 1s ease-out, transform 1s ease-out;
        }

        .process-step .step-number {
            position: absolute;
            top: -20px;
            left: -20px;
            font-size: 8em;
            font-family: var(--font-heading);
            font-style: italic;
            color: rgba(0, 212, 255, 0.05);
            z-index: 0;
            line-height: 1;
        }

        .process-step .icon {
            font-size: 3em;
            color: var(--color-electric-teal);
            margin-bottom: 20px;
            position: relative;
            z-index: 1;
            text-shadow: 0 0 10px var(--color-cyan-accent);
        }

        .process-step h3 {
            font-size: 2em;
            color: var(--color-cyan-accent);
            margin-bottom: 15px;
            position: relative;
            z-index: 1;
        }

        .process-step p {
            font-size: 1em;
            color: var(--color-soft-ice);
            position: relative;
            z-index: 1;
        }

        /* === COLLECTORS / TESTIMONIALS SECTION === */
        .collectors-section {
            padding: 80px 0;
            background-color: var(--color-rich-midnight);
        }

        .collectors-section h2 {
            font-size: 3.5em;
            text-align: center;
            margin-bottom: 60px;
        }

        .testimonials-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
            gap: 40px;
            padding: 0 20px;
        }

        .testimonial-card {
            padding: 30px;
            text-align: center;
            position: relative;
            opacity: 0;
            transform: translateY(40px);
            transition: opacity 1s ease-out, transform 1s ease-out;
        }

        /* Glass morphism with glow for testimonial cards */
        .testimonial-card.glass-morphism {
            background: rgba(8, 15, 32, 0.5); /* slightly more transparent */
            backdrop-filter: blur(15px);
            border: 1px solid rgba(0, 212, 255, 0.3);
            box-shadow: 0 0 25px var(--color-subtle-glow), 0 8px 40px 0 rgba(0, 0, 0, 0.4);
        }

        .testimonial-card p.quote {
            font-size: 1.2em;
            font-style: italic;
            color: var(--color-soft-ice);
            margin-bottom: 25px;
            position: relative;
        }

        .testimonial-card p.quote::before,
        .testimonial-card p.quote::after {
            content: '"';
            font-size: 2em;
            color: var(--color-cyan-accent);
            position: absolute;
            opacity: 0.6;
            line-height: 1;
        }

        .testimonial-card p.quote::before {
            top: -10px;
            left: -10px;
        }
        .testimonial-card p.quote::after {
            bottom: -10px;
            right: -10px;
        }


        .testimonial-card .collector-name {
            font-weight: bold;
            color: var(--color-electric-teal);
            font-size: 1.1em;
        }

        /* === ACQUIRE / CONTACT SECTION === */
        .contact-section {
            padding: 80px 0;
            background-color: var(--color-deep-navy);
            text-align: center;
        }

        .contact-section h2 {
            font-size: 3.5em;
            margin-bottom: 60px;
        }

        .contact-form-container {
            max-width: 700px;
            margin: 0 auto;
            padding: 40px;
            text-align: left;
            opacity: 0;
            transform: translateY(40px);
            transition: opacity 1s ease-out, transform 1s ease-out;
        }

        .contact-form-container .glass-morphism {
             background: rgba(8, 15, 32, 0.6); /* Slightly darker glass for forms */
             border: 1px solid rgba(0, 212, 255, 0.3);
        }

        .contact-form label {
            display: block;
            margin-bottom: 10px;
            color: var(--color-soft-ice);
            font-size: 1.1em;
            font-weight: 500;
        }

        .contact-form input[type="text"],
        .contact-form input[type="email"],
        .contact-form textarea,
        .contact-form select {
            width: 100%;
            padding: 15px;
            margin-bottom: 25px;
            border-radius: 8px;
            border: 1px solid var(--color-muted-steel-blue);
            background-color: rgba(26, 58, 92, 0.5); /* Muted steel blue with transparency */
            color: var(--color-white-text);
            font-family: var(--font-body);
            font-size: 1em;
            transition: border-color 0.3s ease, box-shadow 0.3s ease;
        }

        .contact-form input[type="text"]:focus,
        .contact-form input[type="email"]:focus,
        .contact-form textarea:focus,
        .contact-form select:focus {
            outline: none;
            border-color: var(--color-cyan-accent);
            box-shadow: 0 0 10px var(--color-subtle-glow);
        }

        .contact-form textarea {
            min-height: 150px;
            resize: vertical;
        }

        .contact-form select {
            appearance: none; /* Remove default arrow */
            -webkit-appearance: none;
            -moz-appearance: none;
            background-image: url('data:image/svg+xml;utf8,<svg fill="%2300d4ff" height="24" viewBox="0 0 24 24" width="24" xmlns="http://www.w3.org/2000/svg"><path d="M7 10l5 5 5-5z"/><path d="M0 0h24v24H0z" fill="none"/></svg>');
            background-repeat: no-repeat;
            background-position: right 15px center;
            background-size: 20px;
        }

        .form-message {
            margin-top: -15px;
            margin-bottom: 20px;
            padding: 10px 15px;
            border-radius: 5px;
            font-size: 0.95em;
            display: none; /* Hidden by default */
            opacity: 0;
            transition: opacity 0.5s ease-out;
        }

        .form-message.success {
            background-color: rgba(0, 255, 0, 0.2);
            color: #aff;
            border: 1px solid rgba(0, 255, 0, 0.4);
        }
        .form-message.error {
            background-color: rgba(255, 0, 0, 0.2);
            color: #faa;
            border: 1px solid rgba(255, 0, 0, 0.4);
        }
        .form-message.show {
            display: block;
            opacity: 1;
        }


        .social-links {
            margin-top: 50px;
            display: flex;
            justify-content: center;
            gap: 30px;
        }

        .social-link {
            font-size: 2.5em;
            color: var(--color-cyan-accent);
            transition: color 0.3s ease, transform 0.3s ease;
            text-shadow: 0 0 10px rgba(0, 212, 255, 0.4);
        }

        .social-link:hover {
            color: var(--color-electric-teal);
            transform: translateY(-5px) scale(1.1);
            text-shadow: 0 0 20px var(--color-electric-teal);
        }

        /* Using Unicode for social icons */
        .icon-instagram::before { content: ""; font-family: 'Font Awesome 5 Brands', 'Inter'; }
        .icon-twitter::before { content: ""; font-family: 'Font Awesome 5 Brands', 'Inter'; } /* Assuming Font Awesome for illustrative unicode */
        .icon-email::before { content: "✉"; } /* Simple envelope unicode */


        /* === FOOTER === */
        .main-footer {
            background-color: var(--color-rich-midnight);
            padding: 40px 20px;
            text-align: center;
            border-top: 1px solid var(--color-muted-steel-blue);
        }

        .main-footer p {
            font-size: 0.9em;
            color: var(--color-soft-ice);
            margin-bottom: 10px;
        }

        .main-footer .logo {
            font-family: var(--font-heading);
            font-style: italic;
            font-size: 1.8em;
            color: var(--color-electric-teal);
            margin-bottom: 5px;
        }

        /* === RESPONSIVE DESIGN === */
        @media (max-width: 1440px) {
            .container {
                padding: 0 40px;
            }
        }

        @media (max-width: 1024px) {
            .hero h1 {
                font-size: 10vw;
            }
            .hero p {
                font-size: 3vw;
            }
            .about-text h2, .featured-works h2, .exhibition-timeline h2, .process-section h2, .collectors-section h2, .contact-section h2 {
                font-size: 3em;
            }
            .about-content {
                flex-direction: column;
                text-align: center;
            }
            .about-text {
                border-left: none;
                padding-left: 20px;
                padding-top: 40px;
                border-top: 2px solid var(--color-muted-steel-blue);
            }
            .about-image {
                min-width: unset;
                max-width: 500px;
            }
            .timeline::before {
                left: 20px;
            }
            .timeline-entry {
                flex-direction: column;
                align-items: flex-start;
                margin-bottom: 40px;
            }
            .timeline-entry:nth-child(even) {
                flex-direction: column;
                align-items: flex-start;
            }
            .timeline-entry-content {
                width: calc(100% - 60px);
                margin-left: 60px;
                transform: translateX(0) !important; /* Override for mobile */
            }
            .timeline-entry .dot {
                left: 20px;
                transform: translateX(0) translateY(-50%);
            }
            .timeline-entry:nth-child(odd) .timeline-entry-content,
            .timeline-entry:nth-child(even) .timeline-entry-content {
                transform: translateX(0); /* Ensure no horizontal translation on mobile */
            }
            .process-grid, .testimonials-grid {
                grid-template-columns: 1fr;
            }
            .process-step {
                max-width: 100%;
            }
        }

        @media (max-width: 768px) {
            .hero h1 {
                font-size: 12vw;
            }
            .hero p {
                font-size: 4vw;
            }
            .main-nav {
                display: none;
                flex-direction: column;
                position: absolute;
                top: 80px; /* Adjust based on header height */
                left: 0;
                width: 100%;
                background: rgba(8, 15, 32, 0.95);
                backdrop-filter: blur(15px);
                padding: 20px 0;
                border-bottom-left-radius: 10px;
                border-bottom-right-radius: 10px;
                box-shadow: 0 10px 20px rgba(0, 0, 0, 0.4);
            }
            .main-nav ul {
                flex-direction: column;
                align-items: center;
                gap: 20px;
            }
            .menu-toggle {
                display: flex;
            }
            .menu-toggle.active span:nth-child(1) { transform: translateY(8px) rotate(45deg); }
            .menu-toggle.active span:nth-child(2) { opacity: 0; }
            .menu-toggle.active span:nth-child(3) { transform: translateY(-8px) rotate(-45deg); }

            .about-text h2, .featured-works h2, .exhibition-timeline h2, .process-section h2, .collectors-section h2, .contact-section h2 {
                font-size: 2.5em;
            }
            .contact-form-container {
                padding: 20px;
            }
        }

        @media (max-width: 480px) {
            .container {
                padding: 0 15px;
            }
            .hero h1 {
                font-size: 14vw;
            }
            .hero p {
                font-size: 5vw;
            }
            .about-text h2, .featured-works h2, .exhibition-timeline h2, .process-section h2, .collectors-section h2, .contact-section h2 {
                font-size: 2em;
            }
        }

        /* === Custom Cursor === */
        #custom-cursor {
            position: fixed;
            width: 30px;
            height: 30px;
            background: radial-gradient(circle, var(--color-cyan-accent) 0%, transparent 70%);
            border-radius: 50%;
            pointer-events: none;
            transform: translate(-50%, -50%);
            z-index: 9999;
            opacity: 0.6;
            mix-blend-mode: screen;
            transition: width 0.2s ease, height 0.2s ease, opacity 0.2s ease;
        }

        body:hover #custom-cursor {
            opacity: 0.6;
        }
        body:active #custom-cursor {
            width: 40px;
            height: 40px;
            opacity: 0.8;
        }

    </style>
</head>
<body>
    <div id="custom-cursor"></div>
    <header class="main-header">
        <div class="logo">JoshArt</div>
        <nav class="main-nav">
            <ul>
                <li><a href="#hero">Home</a></li>
                <li><a href="#about">About</a></li>
                <li><a href="#works">Works</a></li>
                <li><a href="#exhibitions">Exhibitions</a></li>
                <li><a href="#process">Process</a></li>
                <li><a href="#collectors">Collectors</a></li>
                <li><a href="#contact">Contact</a></li>
            </ul>
        </nav>
        <div class="menu-toggle" aria-label="Toggle navigation">
            <span></span>
            <span></span>
            <span></span>
        </div>
    </header>

    <main>
        <!-- HERO SECTION -->
        <section id="hero" class="hero">
            <canvas id="hero-canvas" class="hero-canvas"></canvas>
            <div class="hero-content">
                <h1>JoshArt</h1>
                <p>Where silence becomes color</p>
            </div>
            <a href="#about" class="scroll-down" aria-label="Scroll down to About section">
                <span>Scroll</span>
                <div class="arrow"></div>
            </a>
        </section>

        <!-- ABOUT THE ARTIST SECTION -->
        <section id="about" class="about-section container reveal-element">
            <div class="about-content">
                <div class="about-image reveal-element reveal-left">
                    <svg viewBox="0 0 400 500" xmlns="http://www.w3.org/2000/svg">
                        <defs>
                            <linearGradient id="gradient-svg" x1="0%" y1="0%" x2="100%" y2="100%">
                                <stop offset="0%" stop-color="var(--color-cyan-accent)" />
                                <stop offset="100%" stop-color="var(--color-electric-teal)" />
                            </linearGradient>
                        </defs>
                        <path class="svg-fill" d="M200,50 C100,0 0,150 0,250 C0,350 100,500 200,450 C300,500 400,350 400,250 C400,150 300,0 200,50 Z" fill="url(#gradient-svg)"/>
                        <circle cx="200" cy="150" r="50" fill="var(--color-white-text)" opacity="0.1"/>
                        <path d="M150 280 C180 320 220 320 250 280 L200 250 Z" fill="var(--color-white-text)" opacity="0.15"/>
                    </svg>
                </div>
                <div class="about-text reveal-element reveal-right">
                    <h2>About the Artist</h2>
                    <p>JoshArt paints the unseen architecture of emotion — light as memory, shadow as longing. Each canvas is a universe folded into silence.</p>
                    <p>His work explores the ethereal connection between the human spirit and the cosmos, inviting viewers into a contemplative space where vibrant colors and fluid forms converge to tell stories beyond words.</p>
                </div>
            </div>
        </section>

        <!-- FEATURED WORKS SECTION -->
        <section id="works" class="featured-works container">
            <h2 class="reveal-element">Featured Works</h2>
            <div class="gallery-grid">
                <div class="art-card reveal-element">
                    <div class="art-card-image-placeholder"></div>
                    <div class="art-card-info">
                        <h3>Nocturne in Blue</h3>
                        <p>2024 — Oil on canvas, 120×90cm</p>
                        <p class="price">$2,400</p>
                        <button class="btn-inquire" aria-label="Inquire about Nocturne in Blue">Inquire</button>
                    </div>
                </div>
                <div class="art-card reveal-element">
                    <div class="art-card-image-placeholder"></div>
                    <div class="art-card-info">
                        <h3>The Weight of Dawn</h3>
                        <p>2024 — Acrylic on wood, 100×100cm</p>
                        <p class="price">$2,100</p>
                        <button class="btn-inquire" aria-label="Inquire about The Weight of Dawn">Inquire</button>
                    </div>
                </div>
                <div class="art-card reveal-element">
                    <div class="art-card-image-placeholder"></div>
                    <div class="art-card-info">
                        <h3>Coastal Elegy</h3>
                        <p>2023 — Mixed media, 150×80cm</p>
                        <p class="price">$2,800</p>
                        <button class="btn-inquire" aria-label="Inquire about Coastal Elegy">Inquire</button>
                    </div>
                </div>
                <div class="art-card reveal-element">
                    <div class="art-card-image-placeholder"></div>
                    <div class="art-card-info">
                        <h3>Threshold</h3>
                        <p>2023 — Digital print on metal, 90×90cm</p>
                        <p class="price">$1,950</p>
                        <button class="btn-inquire" aria-label="Inquire about Threshold">Inquire</button>
                    </div>
                </div>
                <div class="art-card reveal-element">
                    <div class="art-card-image-placeholder"></div>
                    <div class="art-card-info">
                        <h3>Chroma Storm</h3>
                        <p>2024 — Oil on canvas, 110×140cm</p>
                        <p class="price">$2,650</p>
                        <button class="btn-inquire" aria-label="Inquire about Chroma Storm">Inquire</button>
                    </div>
                </div>
                <div class="art-card reveal-element">
                    <div class="art-card-image-placeholder"></div>
                    <div class="art-card-info">
                        <h3>Still</h3>
                        <p>2023 — Ink on paper, framed, 70×50cm</p>
                        <p class="price">$1,500</p>
                        <button class="btn-inquire" aria-label="Inquire about Still">Inquire</button>
                    </div>
                </div>
            </div>
        </section>

        <!-- EXHIBITION TIMELINE SECTION -->
        <section id="exhibitions" class="exhibition-timeline">
            <h2 class="reveal-element">Exhibitions</h2>
            <div class="timeline container">
                <div class="timeline-entry">
                    <div class="timeline-entry-content glass-morphism">
                        <h3>Upcoming — London Emerging Artists, 2025</h3>
                        <p>A prestigious group exhibition showcasing innovative contemporary artists. Dates to be announced soon.</p>
                    </div>
                    <div class="dot" aria-hidden="true"></div>
                </div>
                <div class="timeline-entry">
                    <div class="timeline-entry-content glass-morphism">
                        <h3>Featured Artist — Digital Canvas Festival, 2024</h3>
                        <p>Online exhibition focusing on the intersection of traditional art and digital expression.</p>
                    </div>
                    <div class="dot" aria-hidden="true"></div>
                </div>
                <div class="timeline-entry">
                    <div class="timeline-entry-content glass-morphism">
                        <h3>Group Show — East Africa Biennale, 2023</h3>
                        <p>Participated in the regional biennale, exploring themes of identity and landscape.</p>
                    </div>
                    <div class="dot" aria-hidden="true"></div>
                </div>
                <div class="timeline-entry">
                    <div class="timeline-entry-content glass-morphism">
                        <h3>Solo Exhibition — Kampala Art House, 2023</h3>
                        <p>Debut solo exhibition, "Echoes of Silence," featuring 15 new works.</p>
                    </div>
                    <div class="dot" aria-hidden="true"></div>
                </div>
            </div>
        </section>

        <!-- PROCESS SECTION -->
        <section id="process" class="process-section">
            <h2 class="reveal-element">Behind the Canvas</h2>
            <div class="process-grid container">
                <div class="process-step reveal-element">
                    <span class="step-number">1</span>
                    <div class="icon">👁️</div>
                    <h3>Observe</h3>
                    <p>Every piece begins with deep observation – of nature, human emotion, and the subtle dance of light and shadow.</p>
                </div>
                <div class="process-step reveal-element">
                    <span class="step-number">2</span>
                    <div class="icon">✨</div>
                    <h3>Abstract</h3>
                    <p>The observed world is then abstracted, distilled into core forms and a vibrant, yet silent, color language.</p>
                </div>
                <div class="process-step reveal-element">
                    <span class="step-number">3</span>
                    <div class="icon">🎨</div>
                    <h3>Manifest</h3>
                    <p>Finally, the abstract vision is manifested onto canvas, a tangible universe born from the unseen.</p>
                </div>
            </div>
        </section>

        <!-- COLLECTORS / TESTIMONIALS SECTION -->
        <section id="collectors" class="collectors-section">
            <h2 class="reveal-element">What Collectors Say</h2>
            <div class="testimonials-grid container">
                <div class="testimonial-card glass-morphism reveal-element">
                    <p class="quote">"JoshArt's work transcends mere painting; it's an experience. Each piece holds a universe within."</p>
                    <p class="collector-name">— Amara K., Nairobi</p>
                </div>
                <div class="testimonial-card glass-morphism reveal-element">
                    <p class="quote">"The depth of emotion in 'Nocturne in Blue' is breathtaking. It's a conversation with silence itself."</p>
                    <p class="collector-name">— Stefan V., Berlin</p>
                </div>
                <div class="testimonial-card glass-morphism reveal-element">
                    <p class="quote">"Owning a JoshArt piece is like having a portal to another dimension. Truly inspiring."</p>
                    <p class="collector-name">— Priya M., Singapore</p>
                </div>
            </div>
        </section>

        <!-- ACQUIRE / CONTACT SECTION -->
        <section id="contact" class="contact-section">
            <h2 class="reveal-element">Own a Piece of the Infinite</h2>
            <div class="contact-form-container glass-morphism reveal-element">
                <form class="contact-form">
                    <label for="name">Name</label>
                    <input type="text" id="name" name="name" required aria-label="Your name">

                    <label for="email">Email</label>
                    <input type="email" id="email" name="email" required aria-label="Your email address">

                    <label for="painting-interest">Which painting interests you?</label>
                    <select id="painting-interest" name="painting-interest" aria-label="Select a painting of interest">
                        <option value="">— Select an artwork —</option>
                        <option value="Nocturne in Blue">Nocturne in Blue</option>
                        <option value="The Weight of Dawn">The Weight of Dawn</option>
                        <option value="Coastal Elegy">Coastal Elegy</option>
                        <option value="Threshold">Threshold</option>
                        <option value="Chroma Storm">Chroma Storm</option>
                        <option value="Still">Still</option>
                    </select>

                    <label for="message">Message</label>
                    <textarea id="message" name="message" rows="6" required aria-label="Your message"></textarea>

                    <div id="form-message" class="form-message" role="alert" aria-live="polite"></div>

                    <button type="submit" class="btn-primary pulsing" aria-label="Begin the Conversation">Begin the Conversation</button>
                </form>

                <div class="social-links">
                    <a href="https://instagram.com/joshart" target="_blank" class="social-link icon-instagram" aria-label="JoshArt Instagram"></a>
                    <a href="https://twitter.com/joshart" target="_blank" class="social-link icon-twitter" aria-label="JoshArt Twitter/X"></a>
                    <a href="mailto:contact@joshart.com" class="social-link icon-email" aria-label="Contact JoshArt by Email"></a>
                </div>
            </div>
        </section>
    </main>

    <!-- FOOTER -->
    <footer class="main-footer">
        <p class="logo">JoshArt</p>
        <p>Where silence becomes color</p>
        <p>&copy; 2025 JoshArt. All rights reserved.</p>
    </footer>

    <script>
        // === GLOBAL JS UTILITIES ===
        document.addEventListener('DOMContentLoaded', () => {
            // Smooth scrolling for navigation links
            document.querySelectorAll('a[href^="#"]').forEach(anchor => {
                anchor.addEventListener('click', function (e) {
                    e.preventDefault();
                    document.querySelector(this.getAttribute('href')).scrollIntoView({
                        behavior: 'smooth'
                    });
                });
            });

            // Sticky Navbar
            const header = document.querySelector('.main-header');
            window.addEventListener('scroll', () => {
                if (window.scrollY > 100) {
                    header.classList.add('scrolled');
                } else {
                    header.classList.remove('scrolled');
                }
            });

            // Mobile Menu Toggle
            const menuToggle = document.querySelector('.menu-toggle');
            const mainNav = document.querySelector('.main-nav');

            menuToggle.addEventListener('click', () => {
                mainNav.classList.toggle('active');
                menuToggle.classList.toggle('active');
            });

            // Hide mobile menu when a link is clicked
            mainNav.querySelectorAll('a').forEach(link => {
                link.addEventListener('click', () => {
                    mainNav.classList.remove('active');
                    menuToggle.classList.remove('active');
                });
            });

            // Intersection Observer for scroll-triggered animations
            const revealElements = document.querySelectorAll('.reveal-element');
            const observerOptions = {
                root: null,
                rootMargin: '0px',
                threshold: 0.1
            };

            const observer = new IntersectionObserver((entries, observer) => {
                entries.forEach(entry => {
                    if (entry.isIntersecting) {
                        entry.target.classList.add('is-visible');
                        observer.unobserve(entry.target);

                        // Specific staggered animation for gallery cards
                        if (entry.target.classList.contains('art-card')) {
                            const cards = document.querySelectorAll('.gallery-grid .art-card');
                            cards.forEach((card, index) => {
                                setTimeout(() => {
                                    card.style.opacity = '1';
                                    card.style.transform = 'translateY(0)';
                                }, index * 150); // Stagger by 150ms
                            });
                        }
                         // Specific staggered animation for timeline entries
                        if (entry.target.classList.contains('timeline-entry')) {
                            const content = entry.target.querySelector('.timeline-entry-content');
                            const dot = entry.target.querySelector('.dot');
                            const isOdd = Array.from(entry.target.parentNode.children).indexOf(entry.target) % 2 === 0;

                            setTimeout(() => {
                                dot.classList.add('is-visible');
                                if (isOdd) {
                                    content.classList.add('is-visible-left');
                                } else {
                                    content.classList.add('is-visible-right');
                                }
                            }, 300); // Slight delay for dot and content
                        }
                    }
                });
            }, observerOptions);

            revealElements.forEach(el => observer.observe(el));

            // Initial animation for hero content
            const heroContent = document.querySelector('.hero-content');
            heroContent.style.opacity = '1';
            heroContent.style.transform = 'translateY(0)';

            // === HERO PARTICLE CANVAS ===
            const canvas = document.getElementById('hero-canvas');
            const ctx = canvas.getContext('2d');
            let particles = [];
            const particleCount = 80;
            const maxLineDistance = 150; // Max distance for particles to connect
            let animationFrameId;

            function resizeCanvas() {
                canvas.width = window.innerWidth;
                canvas.height = window.innerHeight;
            }

            class Particle {
                constructor(x, y) {
                    this.x = x;
                    this.y = y;
                    this.size = Math.random() * 2 + 1; // 1 to 3
                    this.speedX = Math.random() * 1 - 0.5; // -0.5 to 0.5
                    this.speedY = Math.random() * 1 - 0.5; // -0.5 to 0.5
                    this.color = 'rgba(0, 212, 255, ' + (Math.random() * 0.5 + 0.2) + ')'; // Cyan with varying opacity
                }

                update() {
                    this.x += this.speedX;
                    this.y += this.speedY;

                    // Bounce off edges
                    if (this.x > canvas.width || this.x < 0) this.speedX *= -1;
                    if (this.y > canvas.height || this.y < 0) this.speedY *= -1;
                }

                draw() {
                    ctx.fillStyle = this.color;
                    ctx.beginPath();
                    ctx.arc(this.x, this.y, this.size, 0, Math.PI * 2);
                    ctx.fill();
                }
            }

            function initParticles() {
                particles = [];
                for (let i = 0; i < particleCount; i++) {
                    const x = Math.random() * canvas.width;
                    const y = Math.random() * canvas.height;
                    particles.push(new Particle(x, y));
                }
            }

            function connectParticles() {
                for (let a = 0; a < particles.length; a++) {
                    for (let b = a; b < particles.length; b++) {
                        const distance = ((particles[a].x - particles[b].x) ** 2 + (particles[a].y - particles[b].y) ** 2) ** 0.5;
                        if (distance < maxLineDistance) {
                            ctx.strokeStyle = `rgba(0, 212, 255, ${1 - (distance / maxLineDistance) * 0.7})`;
                            ctx.lineWidth = 0.5;
                            ctx.beginPath();
                            ctx.moveTo(particles[a].x, particles[a].y);
                            ctx.lineTo(particles[b].x, particles[b].y);
                            ctx.stroke();
                        }
                    }
                }
            }

            function animateParticles() {
                ctx.clearRect(0, 0, canvas.width, canvas.height);
                for (let i = 0; i < particles.length; i++) {
                    particles[i].update();
                    particles[i].draw();
                }
                connectParticles();
                animationFrameId = requestAnimationFrame(animateParticles);
            }

            window.addEventListener('resize', resizeCanvas);
            resizeCanvas();
            initParticles();
            animateParticles();

            // Pause/resume animation based on tab visibility
            document.addEventListener('visibilitychange', () => {
                if (document.hidden) {
                    cancelAnimationFrame(animationFrameId);
                } else {
                    animateParticles();
                }
            });

            // === 3D TILT EFFECT FOR ART CARDS ===
            const artCards = document.querySelectorAll('.art-card');

            artCards.forEach(card => {
                card.addEventListener('mousemove', (e) => {
                    const { left, top, width, height } = card.getBoundingClientRect();
                    const centerX = left + width / 2;
                    const centerY = top + height / 2;

                    const mouseX = e.clientX;
                    const mouseY = e.clientY;

                    const rotateX = (mouseY - centerY) / height * 30; // Max 15deg up/down
                    const rotateY = (mouseX - centerX) / width * -30; // Max 15deg left/right (inverted for natural feel)

                    card.style.transform = `perspective(1000px) rotateX(${rotateX}deg) rotateY(${rotateY}deg)`;
                });

                card.addEventListener('mouseleave', () => {
                    card.style.transform = `perspective(1000px) rotateX(0deg) rotateY(0deg)`;
                });
            });

            // === CONTACT FORM SUBMISSION ===
            const contactForm = document.querySelector('.contact-form');
            const formMessage = document.getElementById('form-message');

            contactForm.addEventListener('submit', function(e) {
                e.preventDefault();

                // Simple validation
                const name = document.getElementById('name').value.trim();
                const email = document.getElementById('email').value.trim();
                const message = document.getElementById('message').value.trim();

                if (!name || !email || !message) {
                    showFormMessage('Please fill in all fields.', 'error');
                    return;
                }

                if (!/^[^\s@]+@[^\s@]+\.[^\s@]+$/.test(email)) {
                    showFormMessage('Please enter a valid email address.', 'error');
                    return;
                }

                // Simulate form submission
                setTimeout(() => {
                    showFormMessage('Thank you for your inquiry! We will get back to you soon.', 'success');
                    contactForm.reset(); // Clear form fields
                }, 1000);
            });

            function showFormMessage(msg, type) {
                formMessage.textContent = msg;
                formMessage.className = `form-message show ${type}`;
            }

            // === CUSTOM CURSOR ===
            const customCursor = document.getElementById('custom-cursor');
            let mouseX = 0;
            let mouseY = 0;
            let cursorX = 0;
            let cursorY = 0;
            const speed = 0.2; // Lerping speed

            function animateCursor() {
                const distX = mouseX - cursorX;
                const distY = mouseY - cursorY;

                cursorX += (distX * speed);
                cursorY += (distY * speed);

                customCursor.style.left = cursorX + 'px';
                customCursor.style.top = cursorY + 'px';

                requestAnimationFrame(animateCursor);
            }

            document.addEventListener('mousemove', (e) => {
                mouseX = e.clientX;
                mouseY = e.clientY;
            });

            animateCursor();

        });
    </script>
</body>
</html>
