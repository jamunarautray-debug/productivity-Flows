<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>ProductivityFlow - Notion-Style Productivity App</title>
    <script async src="https://pagead2.googlesyndication.com/pagead/js/adsbygoogle.js?client=ca-pub-5305623168423224" crossorigin="anonymous"></script>
    <script src="https://unpkg.com/browser-image-compression@2.0.2/dist/browser-image-compression.js"></script>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
    <style>
        :root {
            --bg: #0f1115;
            --panel: rgba(21, 24, 35, 0.85);
            --panel-solid: #151823;
            --muted: #aab2c5;
            --text: #e8ecf3;
            --accent: #7aa2f7;
            --accent-2: #34d399;
            --accent-3: #bb9af7;
            --border: rgba(36, 42, 58, 0.6);
            --ad-bg: rgba(11, 14, 20, 0.8);
            --success: #9ece6a;
            --warning: #e0af68;
            --error: #f7768e;
            --student: #7aa2f7;
            --adult: #bb9af7;
        }

        * {
            box-sizing: border-box;
            margin: 0;
            padding: 0;
        }

        body {
            font-family: 'Inter', 'Segoe UI', system-ui, -apple-system, sans-serif;
            background: var(--bg);
            color: var(--text);
            line-height: 1.6;
            overflow-x: hidden;
        }

        .container {
            max-width: 1200px;
            margin: 0 auto;
            padding: 0 20px;
        }

        /* Welcome Screen */
        #welcome-screen {
            position: fixed;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            background: linear-gradient(135deg, rgba(15, 17, 21, 0.9), rgba(21, 24, 35, 0.9)), 
                        url('https://images.unsplash.com/photo-1517245386807-bb43f82c33c4?ixlib=rb-4.0.3&auto=format&fit=crop&w=1500&q=80');
            background-size: cover;
            display: flex;
            justify-content: center;
            align-items: center;
            z-index: 1000;
        }

        .welcome-card {
            background: var(--panel);
            backdrop-filter: blur(12px);
            border-radius: 20px;
            padding: 40px;
            text-align: center;
            max-width: 500px;
            width: 90%;
            box-shadow: 0 20px 40px rgba(0, 0, 0, 0.3);
            border: 1px solid var(--border);
        }

        .welcome-logo {
            font-size: 3rem;
            margin-bottom: 20px;
            color: var(--accent);
        }

        .welcome-title {
            font-size: 2.2rem;
            margin-bottom: 10px;
            background: linear-gradient(135deg, var(--accent), var(--accent-3));
            -webkit-background-clip: text;
            -webkit-text-fill-color: transparent;
        }

        .welcome-subtitle {
            color: var(--muted);
            margin-bottom: 30px;
            font-size: 1.1rem;
        }

        .user-type-selector {
            display: flex;
            justify-content: center;
            gap: 20px;
            margin-bottom: 30px;
        }

        .user-type-btn {
            padding: 15px 25px;
            border-radius: 12px;
            background: rgba(12, 15, 23, 0.6);
            border: 2px solid var(--border);
            color: var(--text);
            cursor: pointer;
            transition: all 0.3s ease;
            flex: 1;
            text-align: center;
        }

        .user-type-btn:hover {
            transform: translateY(-3px);
            box-shadow: 0 10px 20px rgba(0, 0, 0, 0.2);
        }

        .user-type-btn.student {
            border-color: var(--student);
        }

        .user-type-btn.adult {
            border-color: var(--adult);
        }

        .user-type-btn.selected {
            background: linear-gradient(135deg, var(--accent), var(--accent-3));
            color: white;
            border-color: transparent;
        }

        .user-type-btn i {
            font-size: 2rem;
            margin-bottom: 10px;
            display: block;
        }

        /* Main App */
        #app {
            display: none;
        }

        header {
            position: sticky;
            top: 0;
            z-index: 100;
            background: rgba(15, 17, 21, 0.85);
            backdrop-filter: blur(10px);
            border-bottom: 1px solid var(--border);
            padding: 15px 0;
        }

        .header-content {
            display: flex;
            align-items: center;
            justify-content: space-between;
        }

        .brand {
            display: flex;
            align-items: center;
            gap: 12px;
            font-weight: 700;
            font-size: 22px;
            color: var(--text);
        }

        .brand-logo {
            width: 36px;
            height: 36px;
            background: linear-gradient(135deg, var(--accent), var(--accent-3));
            border-radius: 10px;
            display: flex;
            align-items: center;
            justify-content: center;
        }

        .nav-actions {
            display: flex;
            gap: 15px;
            align-items: center;
        }

        .btn {
            padding: 10px 18px;
            border-radius: 12px;
            font-weight: 500;
            font-size: 14px;
            cursor: pointer;
            transition: all 0.3s ease;
            border: 1px solid var(--border);
            background: rgba(21, 24, 35, 0.6);
            color: var(--text);
            display: flex;
            align-items: center;
            gap: 8px;
        }

        .btn:hover {
            transform: translateY(-2px);
            box-shadow: 0 6px 16px rgba(0, 0, 0, 0.2);
        }

        .btn-primary {
            background: linear-gradient(135deg, var(--accent), var(--accent-3));
            border: none;
            color: white;
        }

        .btn-outline {
            background: transparent;
            border: 1px solid var(--accent);
            color: var(--accent);
        }

        /* Main Grid Layout */
        .main-grid {
            display: grid;
            grid-template-columns: 1fr 300px;
            gap: 24px;
            margin: 24px 0;
        }

        @media (max-width: 900px) {
            .main-grid {
                grid-template-columns: 1fr;
            }
            .ad-column {
                display: none;
            }
        }

        /* Card Styles */
        .card {
            padding: 20px;
            margin-bottom: 24px;
            background: var(--panel);
            backdrop-filter: blur(12px);
            border-radius: 16px;
            border: 1px solid var(--border);
        }

        .card-header {
            margin-bottom: 16px;
            display: flex;
            align-items: center;
            justify-content: space-between;
        }

        .card-title {
            font-size: 18px;
            font-weight: 600;
            color: var(--text);
            display: flex;
            align-items: center;
            gap: 10px;
        }

        /* Template Button */
        .template-button-container {
            text-align: center;
            margin: 20px 0;
        }

        .template-btn {
            padding: 15px 30px;
            font-size: 16px;
            background: linear-gradient(135deg, var(--accent), var(--accent-3));
            color: white;
            border: none;
            border-radius: 12px;
            cursor: pointer;
            transition: all 0.3s ease;
            display: inline-flex;
            align-items: center;
            gap: 10px;
        }

        .template-btn:hover {
            transform: translateY(-3px);
            box-shadow: 0 10px 20px rgba(122, 162, 247, 0.3);
        }

        /* Template Modal */
        .template-modal {
            display: none;
            position: fixed;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            background: rgba(15, 17, 21, 0.9);
            z-index: 1000;
            overflow-y: auto;
            padding: 20px;
        }

        .modal-content {
            background: var(--panel);
            backdrop-filter: blur(12px);
            border-radius: 16px;
            padding: 30px;
            max-width: 1000px;
            margin: 0 auto;
            border: 1px solid var(--border);
            box-shadow: 0 20px 40px rgba(0, 0, 0, 0.3);
        }

        .modal-header {
            display: flex;
            justify-content: space-between;
            align-items: center;
            margin-bottom: 25px;
        }

        .modal-title {
            font-size: 24px;
            font-weight: 600;
            color: var(--text);
            display: flex;
            align-items: center;
            gap: 10px;
        }

        .close-modal {
            background: none;
            border: none;
            color: var(--muted);
            font-size: 24px;
            cursor: pointer;
            transition: color 0.3s ease;
        }

        .close-modal:hover {
            color: var(--text);
        }

        .template-filter {
            display: flex;
            gap: 15px;
            margin-bottom: 25px;
            flex-wrap: wrap;
        }

        .search-box {
            flex: 1;
            position: relative;
            min-width: 250px;
        }

        .search-input {
            width: 100%;
            padding: 12px 16px 12px 42px;
            border-radius: 12px;
            font-size: 14px;
            background: rgba(12, 15, 23, 0.7);
            border: 1px solid var(--border);
            color: var(--text);
        }

        .search-icon {
            position: absolute;
            left: 14px;
            top: 50%;
            transform: translateY(-50%);
            color: var(--muted);
        }

        .category-filter {
            padding: 12px 16px;
            border-radius: 12px;
            font-size: 14px;
            background: rgba(12, 15, 23, 0.7);
            border: 1px solid var(--border);
            color: var(--text);
            min-width: 180px;
        }

        .template-grid {
            display: grid;
            grid-template-columns: repeat(auto-fill, minmax(200px, 1fr));
            gap: 16px;
        }

        .template-card {
            padding: 16px;
            border-radius: 12px;
            background: rgba(12, 15, 23, 0.6);
            border: 1px dashed var(--border);
            transition: all 0.3s ease;
            cursor: pointer;
            height: 140px;
            display: flex;
            flex-direction: column;
            justify-content: space-between;
        }

        .template-card:hover {
            border-color: var(--accent);
            transform: translateY(-4px);
            box-shadow: 0 10px 25px rgba(0, 0, 0, 0.2);
        }

        .template-card.selected {
            border: 2px solid var(--accent);
            background: rgba(122, 162, 247, 0.1);
        }

        .template-title {
            font-size: 15px;
            font-weight: 500;
            margin-bottom: 8px;
        }

        .template-category {
            font-size: 12px;
            padding: 4px 10px;
            background: rgba(122, 162, 247, 0.15);
            color: var(--accent);
            border-radius: 20px;
            display: inline-block;
        }

        /* Editor Styles */
        .editor-container {
            min-height: 400px;
            padding: 20px;
            border-radius: 12px;
            background: rgba(12, 15, 23, 0.7);
            border: 1px solid var(--border);
            margin-bottom: 24px;
        }

        .editor-toolbar {
            display: flex;
            gap: 8px;
            padding: 12px;
            background: rgba(12, 15, 23, 0.5);
            border-radius: 10px;
            margin-bottom: 16px;
            flex-wrap: wrap;
        }

        .editor-toolbar button {
            padding: 8px 12px;
            border-radius: 8px;
            background: transparent;
            border: 1px solid var(--border);
            color: var(--muted);
            cursor: pointer;
            transition: all 0.2s ease;
        }

        .editor-toolbar button:hover {
            background: rgba(122, 162, 247, 0.1);
            color: var(--accent);
        }

        /* Task List Styles */
        .task-section {
            margin-bottom: 25px;
        }

        .section-header {
            font-size: 1.2rem;
            margin-bottom: 15px;
            padding-bottom: 8px;
            border-bottom: 1px solid var(--border);
            display: flex;
            align-items: center;
            gap: 10px;
        }

        .task-list {
            list-style: none;
        }

        .task-item {
            display: flex;
            align-items: center;
            padding: 12px;
            margin-bottom: 10px;
            background: rgba(12, 15, 23, 0.5);
            border-radius: 8px;
            border: 1px solid var(--border);
        }

        .task-checkbox {
            width: 22px;
            height: 22px;
            border-radius: 6px;
            border: 2px solid var(--border);
            margin-right: 12px;
            cursor: pointer;
            display: flex;
            align-items: center;
            justify-content: center;
            transition: all 0.2s ease;
        }

        .task-checkbox.checked {
            background: var(--accent-2);
            border-color: var(--accent-2);
        }

        .task-checkbox.checked::after {
            content: "✓";
            color: white;
            font-size: 14px;
        }

        .task-text {
            flex: 1;
        }

        .task-completed {
            text-decoration: line-through;
            color: var(--muted);
        }

        /* Progress Tracking */
        .progress-container {
            margin: 20px 0;
            padding: 15px;
            background: rgba(12, 15, 23, 0.5);
            border-radius: 12px;
            border: 1px solid var(--border);
        }

        .progress-header {
            display: flex;
            justify-content: space-between;
            margin-bottom: 10px;
        }

        .progress-bar {
            height: 10px;
            background: var(--border);
            border-radius: 5px;
            overflow: hidden;
        }

        .progress-fill {
            height: 100%;
            background: linear-gradient(90deg, var(--accent), var(--accent-2));
            border-radius: 5px;
            transition: width 0.5s ease;
        }

        /* Ad Styles */
        .ad-slot {
            padding: 20px;
            border-radius: 12px;
            background: var(--ad-bg);
            border: 1px dashed var(--border);
            margin-bottom: 20px;
            text-align: center;
            min-height: 280px;
            display: flex;
            flex-direction: column;
            align-items: center;
            justify-content: center;
        }

        .ad-slot.horizontal {
            grid-column: 1 / -1;
            min-height: 120px;
        }

        .ad-label {
            font-size: 12px;
            color: var(--muted);
            margin-bottom: 10px;
        }

        /* Student Templates Gallery */
        .templates-gallery {
            padding: 40px 0;
            background: var(--bg);
        }

        .gallery-header {
            text-align: center;
            padding: 40px 20px;
            margin-bottom: 30px;
            background: var(--panel);
            border-radius: 16px;
            border: 1px solid var(--border);
        }

        .gallery-title {
            font-size: 2.8rem;
            margin-bottom: 15px;
            background: linear-gradient(135deg, var(--accent), var(--accent-3));
            -webkit-background-clip: text;
            -webkit-text-fill-color: transparent;
        }

        .gallery-subtitle {
            color: var(--muted);
            font-size: 1.2rem;
            max-width: 800px;
            margin: 0 auto 30px;
        }

        .author {
            display: flex;
            align-items: center;
            justify-content: center;
            gap: 15px;
            margin-bottom: 20px;
        }

        .author-img {
            width: 50px;
            height: 50px;
            border-radius: 50%;
            background: linear-gradient(135deg, var(--accent), var(--accent-3));
            display: flex;
            align-items: center;
            justify-content: center;
            font-size: 1.5rem;
        }

        .author-info {
            text-align: left;
        }

        .author-name {
            font-weight: 600;
            color: var(--text);
        }

        .publish-date {
            color: var(--muted);
            font-size: 0.9rem;
        }

        .social-icons {
            display: flex;
            justify-content: center;
            gap: 15px;
            margin-top: 20px;
        }

        .social-icon {
            width: 40px;
            height: 40px;
            border-radius: 50%;
            background: rgba(122, 162, 247, 0.1);
            display: flex;
            align-items: center;
            justify-content: center;
            color: var(--accent);
            transition: all 0.3s ease;
        }

        .social-icon:hover {
            background: var(--accent);
            color: white;
            transform: translateY(-3px);
        }

        .templates-grid {
            display: grid;
            grid-template-columns: repeat(auto-fill, minmax(300px, 1fr));
            gap: 25px;
            margin-bottom: 50px;
        }

        .gallery-template-card {
            background: var(--panel);
            border-radius: 16px;
            overflow: hidden;
            border: 1px solid var(--border);
            transition: all 0.3s ease;
            height: 100%;
            display: flex;
            flex-direction: column;
        }

        .gallery-template-card:hover {
            transform: translateY(-5px);
            box-shadow: 0 15px 30px rgba(0, 0, 0, 0.3);
            border-color: var(--accent);
        }

        .template-img {
            height: 180px;
            background: linear-gradient(135deg, rgba(122, 162, 247, 0.2), rgba(187, 154, 247, 0.2));
            display: flex;
            align-items: center;
            justify-content: center;
            font-size: 3rem;
            color: var(--accent);
        }

        .template-content {
            padding: 25px;
            flex: 1;
            display: flex;
            flex-direction: column;
        }

        .template-number {
            width: 36px;
            height: 36px;
            background: linear-gradient(135deg, var(--accent), var(--accent-3));
            color: white;
            border-radius: 50%;
            display: flex;
            align-items: center;
            justify-content: center;
            font-weight: bold;
            margin-bottom: 15px;
        }

        .template-title {
            font-size: 1.4rem;
            margin-bottom: 12px;
            color: var(--text);
        }

        .template-desc {
            color: var(--muted);
            margin-bottom: 20px;
            flex: 1;
        }

        .template-features {
            margin-bottom: 20px;
        }

        .feature {
            display: flex;
            align-items: center;
            gap: 10px;
            margin-bottom: 8px;
            font-size: 0.9rem;
            color: var(--muted);
        }

        .feature i {
            color: var(--accent-2);
        }

        .use-template-btn {
            display: block;
            width: 100%;
            padding: 12px;
            background: rgba(122, 162, 247, 0.1);
            color: var(--accent);
            border: 1px solid var(--accent);
            border-radius: 10px;
            text-align: center;
            font-weight: 500;
            transition: all 0.3s ease;
            text-decoration: none;
        }

        .use-template-btn:hover {
            background: var(--accent);
            color: white;
        }

        .gallery-template-card:nth-child(1) .template-img { background: linear-gradient(135deg, rgba(52, 211, 153, 0.2), rgba(122, 162, 247, 0.2)); }
        .gallery-template-card:nth-child(1) .template-number { background: linear-gradient(135deg, #34d399, #7aa2f7); }
        .gallery-template-card:nth-child(2) .template-img { background: linear-gradient(135deg, rgba(122, 162, 247, 0.2), rgba(187, 154, 247, 0.2)); }
        .gallery-template-card:nth-child(2) .template-number { background: linear-gradient(135deg, #7aa2f7, #bb9af7); }
        .gallery-template-card:nth-child(3) .template-img { background: linear-gradient(135deg, rgba(158, 206, 106, 0.2), rgba(52, 211, 153, 0.2)); }
        .gallery-template-card:nth-child(3) .template-number { background: linear-gradient(135deg, #9ece6a, #34d399); }
        .gallery-template-card:nth-child(4) .template-img { background: linear-gradient(135deg, rgba(187, 154, 247, 0.2), rgba(122, 162, 247, 0.2)); }
        .gallery-template-card:nth-child(4) .template-number { background: linear-gradient(135deg, #bb9af7, #7aa2f7); }
        .gallery-template-card:nth-child(5) .template-img { background: linear-gradient(135deg, rgba(224, 175, 104, 0.2), rgba(247, 118, 142, 0.2)); }
        .gallery-template-card:nth-child(5) .template-number { background: linear-gradient(135deg, #e0af68, #f7768e); }
        .gallery-template-card:nth-child(6) .template-img { background: linear-gradient(135deg, rgba(122, 162, 247, 0.2), rgba(52, 211, 153, 0.2)); }
        .gallery-template-card:nth-child(6) .template-number { background: linear-gradient(135deg, #7aa2f7, #34d399); }
        .gallery-template-card:nth-child(7) .template-img { background: linear-gradient(135deg, rgba(52, 211, 153, 0.2), rgba(158, 206, 106, 0.2)); }
        .gallery-template-card:nth-child(7) .template-number { background: linear-gradient(135deg, #34d399, #9ece6a); }

        .gallery-footer {
            text-align: center;
            padding: 40px 20px;
            background: var(--panel);
            border-radius: 16px;
            border: 1px solid var(--border);
            margin-top: 50px;
        }

        .footer-title {
            font-size: 1.8rem;
            margin-bottom: 20px;
            color: var(--text);
        }

        .footer-text {
            color: var(--muted);
            max-width: 800px;
            margin: 0 auto 30px;
        }

        .footer-cta {
            display: inline-block;
            padding: 15px 30px;
            background: linear-gradient(135deg, var(--accent), var(--accent-3));
            color: white;
            border-radius: 12px;
            text-decoration: none;
            font-weight: 500;
            transition: all 0.3s ease;
        }

        .footer-cta:hover {
            transform: translateY(-3px);
            box-shadow: 0 10px 20px rgba(122, 162, 247, 0.3);
        }

        /* Footer Styles */
        footer {
            margin-top: 40px;
            padding: 30px 0;
            border-top: 1px solid var(--border);
        }

        .footer-content {
            display: flex;
            justify-content: space-between;
            align-items: center;
        }

        .footer-nav {
            display: flex;
            gap: 20px;
        }

        .footer-nav a {
            color: var(--muted);
            font-size: 14px;
            transition: color 0.2s ease;
        }

        .footer-nav a:hover {
            color: var(--accent);
        }

        /* Stats and badges */
        .stat {
            font-size: 13px;
            color: var(--muted);
            display: flex;
            align-items: center;
            gap: 6px;
        }

        .badge {
            padding: 4px 10px;
            border-radius: 20px;
            font-size: 12px;
            font-weight: 500;
        }

        .badge-primary {
            background: rgba(122, 162, 247, 0.15);
            color: var(--accent);
        }

        .badge-success {
            background: rgba(52, 211, 153, 0.15);
            color: var(--accent-2);
        }

        /* Utility Classes */
        .mt-20 {
            margin-top: 20px;
        }

        .text-center {
            text-align: center;
        }

        .hidden {
            display: none;
        }

        /* Animation */
        @keyframes fadeIn {
            from { opacity: 0; transform: translateY(10px); }
            to { opacity: 1; transform: translateY(0); }
        }

        .animate-in {
            animation: fadeIn 0.5s ease forwards;
        }

        @media (max-width: 768px) {
            .templates-grid {
                grid-template-columns: 1fr;
            }
            
            .gallery-title {
                font-size: 2.2rem;
            }
        }
    </style>
</head>
<body>
    <!-- Welcome Screen -->
    <div id="welcome-screen">
        <div class="welcome-card">
            <div class="welcome-logo">
                <i class="fas fa-th-large"></i>
            </div>
            <h1 class="welcome-title">ProductivityFlow</h1>
            <p class="welcome-subtitle">Select your profile to get started with your personalized productivity space</p>
            
            <div class="user-type-selector">
                <div class="user-type-btn student" data-type="student">
                    <i class="fas fa-graduation-cap"></i>
                    <span>Student</span>
                </div>
                <div class="user-type-btn adult" data-type="adult">
                    <i class="fas fa-briefcase"></i>
                    <span>Adult (18+)</span>
                </div>
            </div>
            
            <button id="start-btn" class="btn btn-primary" disabled>
                <i class="fas fa-play"></i> Get Started
            </button>
        </div>
    </div>

    <!-- Template Modal -->
    <div id="template-modal" class="template-modal">
        <div class="modal-content">
            <div class="modal-header">
                <h2 class="modal-title"><i class="fas fa-layer-group"></i> Templates</h2>
                <button class="close-modal">&times;</button>
            </div>
            
            <div class="template-filter">
                <div class="search-box">
                    <i class="fas fa-search search-icon"></i>
                    <input type="text" placeholder="Search templates..." class="search-input" id="template-search">
                </div>
                <select class="category-filter" id="category-filter">
                    <option value="">All Categories</option>
                    <option value="Academic">Academic</option>
                    <option value="Work">Work</option>
                    <option value="Personal">Personal</option>
                    <option value="Project">Project</option>
                    <option value="Health">Health</option>
                    <option value="Finance">Finance</option>
                </select>
            </div>
            
            <div class="template-grid" id="template-list">
                <!-- Templates will be dynamically inserted here -->
            </div>
        </div>
    </div>

    <!-- Main App -->
    <div id="app">
        <header>
            <div class="container">
                <div class="header-content">
                    <div class="brand">
                        <div class="brand-logo">
                            <i class="fas fa-th-large"></i>
                        </div>
                        <span>ProductivityFlow <sup id="user-type-badge"></sup></span>
                    </div>
                    <div class="nav-actions">
                        <button class="btn btn-outline" id="export-btn">
                            <i class="fas fa-download"></i> Export
                        </button>
                        <button class="btn btn-primary" id="save-btn">
                            <i class="fas fa-save"></i> Save
                        </button>
                    </div>
                </div>
            </div>
        </header>

        <div class="container">
            <div class="main-grid">
                <!-- Main Content: Editor & Task Management -->
                <main class="content">
                    <div class="card">
                        <div class="card-header">
                            <h2 class="card-title"><i class="fas fa-edit"></i> Editor</h2>
                            <div class="stat">
                                <i class="fas fa-clock"></i> Auto-saved 2 min ago
                            </div>
                        </div>
                        <div class="editor-container">
                            <div class="editor-toolbar">
                                <button><i class="fas fa-bold"></i></button>
                                <button><i class="fas fa-italic"></i></button>
                                <button><i class="fas fa-underline"></i></button>
                                <button><i class="fas fa-list-ul"></i></button>
                                <button><i class="fas fa-list-ol"></i></button>
                                <button><i class="fas fa-link"></i></button>
                                <button><i class="fas fa-image"></i></button>
                                <button><i class="fas fa-code"></i></button>
                                <button><i class="fas fa-quote-right"></i></button>
                            </div>
                            <div id="editor" contenteditable="true">
                                <h2>Welcome to ProductivityFlow</h2>
                                <p>Select a template from the button below to get started or start typing to create your own content.</p>
                            </div>
                        </div>
                    </div>

                    <!-- Template Button -->
                    <div class="template-button-container">
                        <button class="template-btn" id="template-modal-btn">
                            <i class="fas fa-layer-group"></i> Browse Templates
                        </button>
                    </div>

                    <div class="card">
                        <div class="card-header">
                            <h2 class="card-title"><i class="fas fa-tasks"></i> Task Management</h2>
                            <div class="stat">
                                <span id="completed-tasks">0</span>/<span id="total-tasks">0</span> tasks completed
                            </div>
                        </div>
                        
                        <div class="progress-container">
                            <div class="progress-header">
                                <span>Today's Progress</span>
                                <span id="progress-percent">0%</span>
                            </div>
                            <div class="progress-bar">
                                <div class="progress-fill" style="width: 0%"></div>
                            </div>
                        </div>
                        
                        <div class="task-section">
                            <h3 class="section-header"><i class="fas fa-calendar-day"></i> Today's Tasks</h3>
                            <ul class="task-list" id="today-tasks">
                                <!-- Today's tasks will be added here -->
                            </ul>
                        </div>
                        
                        <div class="task-section">
                            <h3 class="section-header"><i class="fas fa-calendar-plus"></i> Future Tasks</h3>
                            <ul class="task-list" id="future-tasks">
                                <!-- Future tasks will be added here -->
                            </ul>
                        </div>
                    </div>

                    <div class="ad-slot horizontal">
                        <div class="ad-label">ADVERTISEMENT</div>
                        <ins class="adsbygoogle"
                             style="display:block"
                             data-ad-client="ca-pub-5305623168423224"
                             data-ad-slot="4327181560"
                             data-ad-format="auto"
                             data-full-width-responsive="true"></ins>
                    </div>

                    <!-- Student Templates Gallery -->
                    <section class="templates-gallery">
                        <div class="gallery-header">
                            <h1 class="gallery-title">7 Notion Templates I Use as a Student</h1>
                            <p class="gallery-subtitle">Organize your academic life, track assignments, build habits, and dominate your studies with these powerful Notion templates</p>
                            
                            <div class="author">
                                <div class="author-img">
                                    <i class="fas fa-user"></i>
                                </div>
                                <div class="author-info">
                                    <div class="author-name">Anshuman Rautray</div>
                                    <div class="publish-date">Published September 10, 2025</div>
                                </div>
                            </div>
                            
                            <div class="social-icons">
                                <a href="#" class="social-icon">
                                    <i class="far fa-heart"></i>
                                </a>
                                <a href="#" class="social-icon">
                                    <i class="far fa-comment"></i>
                                </a>
                                <a href="#" class="social-icon">
                                    <i class="fas fa-share-alt"></i>
                                </a>
                            </div>
                        </div>

                        <div class="templates-grid">
                            <!-- Template 1 -->
                            <div class="gallery-template-card">
                                <div class="template-img">
                                    <i class="fas fa-calendar-alt"></i>
                                </div>
                                <div class="template-content">
                                    <div class="template-number">7</div>
                                    <h3 class="template-title">Quick Class Schedule</h3>
                                    <p class="template-desc">Manage your entire schedule from one dynamic board with color-coded classes and customizable fields.</p>
                                    <div class="template-features">
                                        <div class="feature"><i class="fas fa-check"></i> Visual board layout</div>
                                        <div class="feature"><i class="fas fa-check"></i> Color-coding for subjects</div>
                                        <div class="feature"><i class="fas fa-check"></i> Custom properties & notes</div>
                                    </div>
                                    <a href="#" class="use-template-btn">Use This Template</a>
                                </div>
                            </div>

                            <!-- Template 2 -->
                            <div class="gallery-template-card">
                                <div class="template-img">
                                    <i class="fas fa-tasks"></i>
                                </div>
                                <div class="template-content">
                                    <div class="template-number">6</div>
                                    <h3 class="template-title">Homework Tracker</h3>
                                    <p class="template-desc">Centralize all your homework, assignments, quizzes, and exams with automatic sorting by due date and priority.</p>
                                    <div class="template-features">
                                        <div class="feature"><i class="fas fa-check"></i> Centralized dashboard</div>
                                        <div class="feature"><i class="fas fa-check"></i> Monthly calendar view</div>
                                        <div class="feature"><i class="fas fa-check"></i> Automatic priority sorting</div>
                                    </div>
                                    <a href="#" class="use-template-btn">Use This Template</a>
                                </div>
                            </div>

                            <!-- Template 3 -->
                            <div class="gallery-template-card">
                                <div class="template-img">
                                    <i class="fas fa-book"></i>
                                </div>
                                <div class="template-content">
                                    <div class="template-number">5</div>
                                    <h3 class="template-title">Reading Book Tracker</h3>
                                    <p class="template-desc">Organize your entire book collection, track reading progress, and capture notes and reflections.</p>
                                    <div class="template-features">
                                        <div class="feature"><i class="fas fa-check"></i> Progress tracking</div>
                                        <div class="feature"><i class="fas fa-check"></i> Reading goals</div>
                                        <div class="feature"><i class="fas fa-check"></i> Quote collection</div>
                                    </div>
                                    <a href="#" class="use-template-btn">Use This Template</a>
                                </div>
                            </div>

                            <!-- Template 4 -->
                            <div class="gallery-template-card">
                                <div class="template-img">
                                    <i class="fas fa-chart-line"></i>
                                </div>
                                <div class="template-content">
                                    <div class="template-number">4</div>
                                    <h3 class="template-title">Habit Tracker</h3>
                                    <p class="template-desc">Build consistency and achieve your goals with daily, weekly, and monthly habit tracking.</p>
                                    <div class="template-features">
                                        <div class="feature"><i class="fas fa-check"></i> Streak visualization</div>
                                        <div class="feature"><i class="fas fa-check"></i> Progress reports</div>
                                        <div class="feature"><i class="fas fa-check"></i> Customizable habits</div>
                                    </div>
                                    <a href="#" class="use-template-btn">Use This Template</a>
                                </div>
                            </div>

                            <!-- Template 5 -->
                            <div class="gallery-template-card">
                                <div class="template-img">
                                    <i class="fas fa-code"></i>
                                </div>
                                <div class="template-content">
                                    <div class="template-number">3</div>
                                    <h3 class="template-title">DSA and LeetCode Journal</h3>
                                    <p class="template-desc">Conquer coding challenges with a systematic approach to tracking problems and solutions.</p>
                                    <div class="template-features">
                                        <div class="feature"><i class="fas fa-check"></i> Problem categorization</div>
                                        <div class="feature"><i class="fas fa-check"></i> Solution approaches</div>
                                        <div class="feature"><i class="fas fa-check"></i> Progress tracking</div>
                                    </div>
                                    <a href="#" class="use-template-btn">Use This Template</a>
                                </div>
                            </div>

                            <!-- Template 6 -->
                            <div class="gallery-template-card">
                                <div class="template-img">
                                    <i class="fas fa-dollar-sign"></i>
                                </div>
                                <div class="template-content">
                                    <div class="template-number">2</div>
                                    <h3 class="template-title">Budget Tracker</h3>
                                    <p class="template-desc">Manage your money smarter with clear expense tracking and budgeting for student life.</p>
                                    <div class="template-features">
                                        <div class="feature"><i class="fas fa-check"></i> Income/expense logging</div>
                                        <div class="feature"><i class="fas fa-check"></i> Spending patterns</div>
                                        <div class="feature"><i class="fas fa-check"></i> Budget categories</div>
                                    </div>
                                    <a href="#" class="use-template-btn">Use This Template</a>
                                </div>
                            </div>

                            <!-- Template 7 -->
                            <div class="gallery-template-card">
                                <div class="template-img">
                                    <i class="fas fa-graduation-cap"></i>
                                </div>
                                <div class="template-content">
                                    <div class="template-number">1</div>
                                    <h3 class="template-title">Matcha Student Planner</h3>
                                    <p class="template-desc">The ultimate all-in-one student hub with course tracking, assignments, goals, and more.</p>
                                    <div class="template-features">
                                        <div class="feature"><i class="fas fa-check"></i> All-in-one dashboard</div>
                                        <div class="feature"><i class="fas fa-check"></i> Course management</div>
                                        <div class="feature"><i class="fas fa-check"></i> Integrated widgets</div>
                                    </div>
                                    <a href="#" class="use-template-btn">Use This Template</a>
                                </div>
                            </div>
                        </div>

                        <div class="gallery-footer">
                            <h2 class="footer-title">Say Goodbye to Academic Chaos</h2>
                            <p class="footer-text">By integrating these Notion templates into your routine, you're not just organizing — you're actively mastering your academic journey. You'll no longer feel overwhelmed by deadlines and lectures.</p>
                            <a href="#" class="footer-cta">Get Started with ProductivityFlow</a>
                        </div>
                    </section>
                </main>

                <!-- Right Column: Ads & Tools -->
                <aside class="ad-column">
                    <div class="card">
                        <div class="card-header">
                            <h2 class="card-title"><i class="fas fa-compress-arrows-alt"></i> Image Optimizer</h2>
                            <div class="stat">
                                <i class="fas fa-bolt"></i> Client-side
                            </div>
                        </div>
                        <div class="input-group">
                            <i class="input-icon fas fa-file-image"></i>
                            <input type="file" id="image-input" accept="image/*">
                        </div>
                        <div class="mt-20">
                            <select id="compression-level">
                                <option value="low">Low Compression (Better Quality)</option>
                                <option value="medium" selected>Medium Compression (Recommended)</option>
                                <option value="high">High Compression (Smaller Size)</option>
                            </select>
                        </div>
                        <div class="mt-20">
                            <button class="btn" id="compress-btn" style="width: 100%">
                                <i class="fas fa-compress-arrows-alt"></i> Compress Image
                            </button>
                        </div>
                        <div class="progress-bar mt-20">
                            <div class="progress-fill" id="compression-progress" style="width: 0%"></div>
                        </div>
                        <div class="stat mt-20" id="compression-stats">No image selected</div>
                    </div>

                    <div class="ad-slot">
                        <div class="ad-label">ADVERTISEMENT</div>
                        <ins class="adsbygoogle"
                             style="display:block"
                             data-ad-client="ca-pub-5305623168423224"
                             data-ad-slot="5668145408"
                             data-ad-format="auto"
                             data-full-width-responsive="true"></ins>
                    </div>
                    
                    <div class="ad-slot">
                        <div class="ad-label">ADVERTISEMENT</div>
                        <ins class="adsbygoogle"
                             style="display:block"
                             data-ad-client="ca-pub-5305623168423224"
                             data-ad-slot="8174889248"
                             data-ad-format="auto"
                             data-full-width-responsive="true"></ins>
                    </div>

                    <div class="ad-slot">
                        <div class="ad-label">ADVERTISEMENT</div>
                        <ins class="adsbygoogle"
                             style="display:block"
                             data-ad-client="ca-pub-5305623168423224"
                             data-ad-slot="8070947467"
                             data-ad-format="auto"
                             data-full-width-responsive="true"></ins>
                    </div>
                </aside>
            </div>
        </div>

        <footer>
            <div class="container">
                <div class="footer-content">
                    <div>
                        <div class="brand" style="font-size: 18px; margin-bottom: 10px;">
                            <div class="brand-logo">
                                <i class="fas fa-th-large"></i>
                            </div>
                            <span>ProductivityFlow</span>
                        </div>
                        <p style="color: var(--muted); font-size: 14px;">&copy; 2023 ProductivityFlow. All rights reserved.</p>
                    </div>
                    <div class="footer-nav">
                        <a href="#">Privacy Policy</a>
                        <a href="#">Terms of Service</a>
                        <a href="#">Contact</a>
                    </div>
                </div>
            </div>
        </footer>
    </div>

    <script>
        document.addEventListener('DOMContentLoaded', function() {
            // Initialize AdSense
            initializeAds();
            
            // Set up user type selection
            setupUserTypeSelection();
            
            // Generate templates
            generateTemplates();
            
            // Set up image compression functionality
            setupImageCompression();
            
            // Set up template filtering
            setupTemplateFiltering();
            
            // Set up task management
            setupTaskManagement();
            
            // Set up template modal
            setupTemplateModal();
            
            // Set up gallery animations
            setupGalleryAnimations();
        });

        // Initialize AdSense
        function initializeAds() {
            if (window.adsbygoogle) {
                (adsbygoogle = window.adsbygoogle || []).push({});
            }
        }

        // Set up template modal
        function setupTemplateModal() {
            const modal = document.getElementById('template-modal');
            const modalBtn = document.getElementById('template-modal-btn');
            const closeBtn = document.querySelector('.close-modal');
            
            modalBtn.addEventListener('click', function() {
                modal.style.display = 'block';
            });
            
            closeBtn.addEventListener('click', function() {
                modal.style.display = 'none';
            });
            
            window.addEventListener('click', function(event) {
                if (event.target === modal) {
                    modal.style.display = 'none';
                }
            });
        }

        // Set up user type selection
        function setupUserTypeSelection() {
            const userTypeBtns = document.querySelectorAll('.user-type-btn');
            const startBtn = document.getElementById('start-btn');
            let selectedType = null;

            userTypeBtns.forEach(btn => {
                btn.addEventListener('click', function() {
                    userTypeBtns.forEach(b => b.classList.remove('selected'));
                    this.classList.add('selected');
                    selectedType = this.getAttribute('data-type');
                    startBtn.disabled = false;
                });
            });

            startBtn.addEventListener('click', function() {
                if (selectedType) {
                    document.getElementById('welcome-screen').style.display = 'none';
                    document.getElementById('app').style.display = 'block';
                    
                    // Set user type badge
                    const badge = document.getElementById('user-type-badge');
                    badge.textContent = selectedType === 'student' ? 'Student' : 'Adult';
                    badge.className = selectedType === 'student' ? 'badge badge-primary' : 'badge';
                    
                    // Load appropriate templates based on user type
                    filterTemplatesByUserType(selectedType);
                }
            });
        }

        // Filter templates by user type
        function filterTemplatesByUserType(userType) {
            const categoryFilter = document.getElementById('category-filter');
            
            if (userType === 'student') {
                categoryFilter.value = 'Academic';
            } else {
                categoryFilter.value = 'Work';
            }
            
            filterTemplates();
        }

        // Generate template data
        function generateTemplates() {
            const categories = [
                'Academic', 'Work', 'Personal', 'Project', 'Health', 'Finance'
            ];
            
            const templates = [
                { name: 'Class Notes', category: 'Academic', icon: 'fas fa-book' },
                { name: 'Assignment Tracker', category: 'Academic', icon: 'fas fa-tasks' },
                { name: 'Study Schedule', category: 'Academic', icon: 'fas fa-calendar' },
                { name: 'Research Paper', category: 'Academic', icon: 'fas fa-file-alt' },
                { name: 'Exam Preparation', category: 'Academic', icon: 'fas fa-graduation-cap' },
                { name: 'Meeting Notes', category: 'Work', icon: 'fas fa-sticky-note' },
                { name: 'Project Plan', category: 'Work', icon: 'fas fa-project-diagram' },
                { name: 'Task List', category: 'Work', icon: 'fas fa-check-circle' },
                { name: 'Business Goals', category: 'Work', icon: 'fas fa-bullseye' },
                { name: 'Performance Review', category: 'Work', icon: 'fas fa-chart-line' },
                { name: 'Daily Journal', category: 'Personal', icon: 'fas fa-pen' },
                { name: 'Habit Tracker', category: 'Personal', icon: 'fas fa-chart-pie' },
                { name: 'Reading List', category: 'Personal', icon: 'fas fa-book-open' },
                { name: 'Travel Planner', category: 'Personal', icon: 'fas fa-plane' },
                { name: 'Budget Tracker', category: 'Finance', icon: 'fas fa-money-bill-wave' },
                { name: 'Savings Goals', category: 'Finance', icon: 'fas fa-piggy-bank' },
                { name: 'Workout Plan', category: 'Health', icon: 'fas fa-running' },
                { name: 'Meal Planner', category: 'Health', icon: 'fas fa-utensils' },
                // Add more templates to reach 100+
            ];
            
            // Add more templates to reach 100+
            for (let i = 1; i <= 82; i++) {
                const category = categories[Math.floor(Math.random() * categories.length)];
                templates.push({
                    name: `${category} Template ${i}`,
                    category: category,
                    icon: 'fas fa-file'
                });
            }
            
            const templateList = document.getElementById('template-list');
            
            templates.forEach(template => {
                const templateEl = document.createElement('div');
                templateEl.className = 'template-card animate-in';
                templateEl.setAttribute('data-category', template.category);
                templateEl.innerHTML = `
                    <div>
                        <div class="template-title">${template.name}</div>
                        <span class="template-category">${template.category}</span>
                    </div>
                    <div style="color: var(--muted); font-size: 12px;">
                        <i class="${template.icon}"></i> Click to use
                    </div>
                `;
                
                templateEl.addEventListener('click', () => {
                    // Remove selected class from all templates
                    document.querySelectorAll('.template-card').forEach(card => {
                        card.classList.remove('selected');
                    });
                    
                    // Add selected class to clicked template
                    templateEl.classList.add('selected');
                    
                    loadTemplate(template);
                    
                    // Close the modal after selection
                    document.getElementById('template-modal').style.display = 'none';
                });
                
                templateList.appendChild(templateEl);
            });
        }

        // Load a template into the editor
        function loadTemplate(template) {
            const editor = document.getElementById('editor');
            const todayTasks = document.getElementById('today-tasks');
            const futureTasks = document.getElementById('future-tasks');
            
            // Clear existing tasks
            todayTasks.innerHTML = '';
            futureTasks.innerHTML = '';
            
            // Load template-specific content
            if (template.category === 'Academic') {
                editor.innerHTML = `
                    <h2>${template.name}</h2>
                    <p>This is an academic template for students. Use it to organize your studies and assignments.</p>
                    <h3>Course Information</h3>
                    <ul>
                        <li>Course Name: </li>
                        <li>Professor: </li>
                        <li>Semester: </li>
                    </ul>
                    <h3>Study Materials</h3>
                    <ul>
                        <li>Textbooks</li>
                        <li>Notes</li>
                        <li>Online Resources</li>
                    </ul>
                `;
                
                // Add academic tasks
                addTask(todayTasks, 'Review lecture notes', false);
                addTask(todayTasks, 'Complete reading assignment', false);
                addTask(todayTasks, 'Work on problem set', false);
                addTask(futureTasks, 'Prepare for upcoming exam', false);
                addTask(futureTasks, 'Start research paper', false);
                
            } else if (template.category === 'Work') {
                editor.innerHTML = `
                    <h2>${template.name}</h2>
                    <p>This is a professional work template. Use it to manage your projects and tasks.</p>
                    <h3>Project Overview</h3>
                    <ul>
                        <li>Project Name: </li>
                        <li>Client: </li>
                        <li>Deadline: </li>
                    </ul>
                    <h3>Key Objectives</h3>
                    <ul>
                        <li>Primary Goal</li>
                        <li>Secondary Goals</li>
                        <li>Success Metrics</li>
                    </ul>
                `;
                
                // Add work tasks
                addTask(todayTasks, 'Check and respond to emails', false);
                addTask(todayTasks, 'Attend team meeting', false);
                addTask(todayTasks, 'Complete project milestone', false);
                addTask(futureTasks, 'Prepare quarterly report', false);
                addTask(futureTasks, 'Schedule client presentation', false);
                
            } else {
                editor.innerHTML = `
                    <h2>${template.name}</h2>
                    <p>This is a ${template.category.toLowerCase()} template. Customize it for your needs.</p>
                    <h3>Overview</h3>
                    <p>Describe your goals and objectives here.</p>
                    <h3>Key Points</h3>
                    <ul>
                        <li>Important item 1</li>
                        <li>Important item 2</li>
                        <li>Important item 3</li>
                    </ul>
                `;
                
                // Add generic tasks
                addTask(todayTasks, 'Complete priority task', false);
                addTask(todayTasks, 'Schedule important activities', false);
                addTask(futureTasks, 'Plan for upcoming events', false);
            }
            
            // Update task counters
            updateTaskCounters();
            
            // Show success notification
            showNotification(`"${template.name}" template loaded successfully!`);
        }

        // Set up task management
        function setupTaskManagement() {
            // This will be handled by the template loading function
        }

        // Add a task to a list
        function addTask(listElement, text, completed) {
            const taskItem = document.createElement('li');
            taskItem.className = 'task-item';
            taskItem.innerHTML = `
                <div class="task-checkbox ${completed ? 'checked' : ''}"></div>
                <div class="task-text ${completed ? 'task-completed' : ''}">${text}</div>
            `;
            
            // Add click event to checkbox
            const checkbox = taskItem.querySelector('.task-checkbox');
            const taskText = taskItem.querySelector('.task-text');
            
            checkbox.addEventListener('click', function() {
                this.classList.toggle('checked');
                taskText.classList.toggle('task-completed');
                updateTaskCounters();
            });
            
            listElement.appendChild(taskItem);
        }

        // Update task completion counters
        function updateTaskCounters() {
            const todayTasks = document.getElementById('today-tasks');
            const futureTasks = document.getElementById('future-tasks');
            const completedTasksElem = document.getElementById('completed-tasks');
            const totalTasksElem = document.getElementById('total-tasks');
            const progressPercentElem = document.getElementById('progress-percent');
            const progressFill = document.querySelector('.progress-fill');
            
            // Count tasks
            const allTasks = todayTasks.querySelectorAll('.task-item').length + 
                             futureTasks.querySelectorAll('.task-item').length;
            
            const completedTasks = todayTasks.querySelectorAll('.task-checkbox.checked').length + 
                                  futureTasks.querySelectorAll('.task-checkbox.checked').length;
            
            // Update counters
            completedTasksElem.textContent = completedTasks;
            totalTasksElem.textContent = allTasks;
            
            // Calculate and update progress
            const progressPercent = allTasks > 0 ? Math.round((completedTasks / allTasks) * 100) : 0;
            progressPercentElem.textContent = `${progressPercent}%`;
            progressFill.style.width = `${progressPercent}%`;
        }

        // Set up image compression functionality
        function setupImageCompression() {
            const imageInput = document.getElementById('image-input');
            const compressBtn = document.getElementById('compress-btn');
            const compressionProgress = document.getElementById('compression-progress');
            const compressionStats = document.getElementById('compression-stats');
            
            let originalFile = null;
            
            imageInput.addEventListener('change', function(e) {
                if (e.target.files && e.target.files[0]) {
                    originalFile = e.target.files[0];
                    compressionStats.textContent = `Ready to compress: ${formatFileSize(originalFile.size)}`;
                }
            });
            
            compressBtn.addEventListener('click', async function() {
                if (!originalFile) {
                    showNotification('Please select an image first', 'error');
                    return;
                }
                
                const compressionLevel = document.getElementById('compression-level').value;
                const options = getCompressionOptions(compressionLevel);
                
                // Update UI
                compressBtn.disabled = true;
                compressBtn.innerHTML = '<i class="fas fa-spinner fa-spin"></i> Compressing...';
                compressionProgress.style.width = '0%';
                
                try {
                    const compressedFile = await imageCompression(originalFile, {
                        ...options,
                        onProgress: (progress) => {
                            compressionProgress.style.width = `${progress * 100}%`;
                        }
                    });
                    
                    // Calculate savings
                    const savings = originalFile.size - compressedFile.size;
                    const percent = (savings / originalFile.size * 100).toFixed(1);
                    
                    // Update stats
                    compressionStats.innerHTML = `
                        Compression successful: 
                        <span style="color: var(--accent-2)">${percent}% reduction</span> 
                        (${formatFileSize(originalFile.size)} → ${formatFileSize(compressedFile.size)})
                    `;
                    
                    // Create download link
                    const downloadLink = document.createElement('a');
                    downloadLink.href = URL.createObjectURL(compressedFile);
                    downloadLink.download = `optimized-${originalFile.name}`;
                    downloadLink.click();
                    
                    showNotification('Image compressed and downloaded successfully!', 'success');
                } catch (error) {
                    console.error('Compression error:', error);
                    showNotification('Compression failed. Please try again.', 'error');
                } finally {
                    compressBtn.disabled = false;
                    compressBtn.innerHTML = '<i class="fas fa-compress-arrows-alt"></i> Compress Image';
                }
            });
        }

        // Set up template filtering
        function setupTemplateFiltering() {
            const searchInput = document.getElementById('template-search');
            const categoryFilter = document.getElementById('category-filter');
            
            searchInput.addEventListener('input', filterTemplates);
            categoryFilter.addEventListener('change', filterTemplates);
        }

        // Filter templates based on search and category
        function filterTemplates() {
            const searchTerm = document.getElementById('template-search').value.toLowerCase();
            const category = document.getElementById('category-filter').value;
            
            const templateCards = document.querySelectorAll('.template-card');
            
            templateCards.forEach(card => {
                const title = card.querySelector('.template-title').textContent.toLowerCase();
                const cardCategory = card.getAttribute('data-category');
                
                const matchesSearch = title.includes(searchTerm);
                const matchesCategory = category === '' || cardCategory === category;
                
                if (matchesSearch && matchesCategory) {
                    card.style.display = 'flex';
                } else {
                    card.style.display = 'none';
                }
            });
        }

        // Set up gallery animations
        function setupGalleryAnimations() {
            // Simple animation for template cards
            document.querySelectorAll('.gallery-template-card').forEach((card, index) => {
                card.style.opacity = '0';
                card.style.transform = 'translateY(20px)';
                
                setTimeout(() => {
                    card.style.transition = 'opacity 0.5s ease, transform 0.5s ease';
                    card.style.opacity = '1';
                    card.style.transform = 'translateY(0)';
                }, 100 + (index * 100));
            });

            // Simple like functionality
            const likeBtn = document.querySelector('.fa-heart');
            if (likeBtn) {
                likeBtn.addEventListener('click', function(e) {
                    e.preventDefault();
                    this.classList.toggle('fas');
                    this.classList.toggle('far');
                });
            }
        }

        // Get compression options based on selected level
        function getCompressionOptions(level) {
            switch(level) {
                case 'low':
                    return { maxSizeMB: 2, maxWidthOrHeight: 1920, useWebWorker: true };
                case 'high':
                    return { maxSizeMB: 0.5, maxWidthOrHeight: 1280, useWebWorker: true };
                case 'medium':
                default:
                    return { maxSizeMB: 1, maxWidthOrHeight: 1600, useWebWorker: true };
            }
        }

        // Format file size for display
        function formatFileSize(bytes) {
            if (bytes < 1024) return bytes + ' B';
            else if (bytes < 1048576) return (bytes / 1024).toFixed(1) + ' KB';
            else return (bytes / 1048576).toFixed(1) + ' MB';
        }

        // Show notification
        function showNotification(message, type = 'success') {
            // In a real app, this would show a proper notification
            console.log(`${type}: ${message}`);
            // You can implement a toast notification system here
        }
    </script>
</body>
</html>
