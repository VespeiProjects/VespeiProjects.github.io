<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Vespei | Infrastructure & Systems</title>
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=IBM+Plex+Mono:wght@400;500;600&family=Instrument+Sans:wght@400;500;600&display=swap" rel="stylesheet">
    <style>
        :root {
            --bg: #0a0a0b;
            --surface: #111113;
            --border: #1e1e21;
            --text-primary: #e8e8ea;
            --text-secondary: #6e6e76;
            --accent: #3b82f6;
            --accent-dim: rgba(59, 130, 246, 0.1);
        }

        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        body {
            font-family: 'Instrument Sans', -apple-system, sans-serif;
            background: var(--bg);
            color: var(--text-primary);
            min-height: 100vh;
            line-height: 1.6;
            overflow-x: hidden;
        }

        /* Subtle grid background */
        .grid-bg {
            position: fixed;
            inset: 0;
            background-image:
                linear-gradient(rgba(255,255,255,0.02) 1px, transparent 1px),
                linear-gradient(90deg, rgba(255,255,255,0.02) 1px, transparent 1px);
            background-size: 60px 60px;
            pointer-events: none;
            z-index: 0;
        }

        .container {
            position: relative;
            z-index: 1;
            max-width: 720px;
            margin: 0 auto;
            padding: 0 24px;
            min-height: 100vh;
            display: flex;
            flex-direction: column;
            justify-content: center;
        }

        .content {
            padding: 80px 0;
        }

        /* Header */
        .header {
            margin-bottom: 48px;
        }

        .name {
            font-family: 'IBM Plex Mono', monospace;
            font-size: clamp(2rem, 6vw, 3rem);
            font-weight: 600;
            letter-spacing: -0.02em;
            margin-bottom: 8px;
            opacity: 0;
            animation: fadeUp 0.6s ease forwards;
        }

        .name span {
            color: var(--accent);
        }

        .tagline {
            font-family: 'IBM Plex Mono', monospace;
            font-size: 0.875rem;
            color: var(--text-secondary);
            letter-spacing: 0.05em;
            text-transform: uppercase;
            opacity: 0;
            animation: fadeUp 0.6s ease 0.1s forwards;
        }

        /* Divider */
        .divider {
            height: 1px;
            background: linear-gradient(90deg, var(--border), transparent);
            margin-bottom: 48px;
            opacity: 0;
            animation: fadeUp 0.6s ease 0.2s forwards;
        }

        /* About */
        .about {
            margin-bottom: 48px;
            opacity: 0;
            animation: fadeUp 0.6s ease 0.3s forwards;
        }

        .about p {
            color: var(--text-secondary);
            font-size: 1.125rem;
            max-width: 540px;
        }

        .about p strong {
            color: var(--text-primary);
            font-weight: 500;
        }

        /* Services */
        .services {
            display: grid;
            gap: 12px;
            margin-bottom: 48px;
            opacity: 0;
            animation: fadeUp 0.6s ease 0.4s forwards;
        }

        .service {
            display: flex;
            align-items: center;
            gap: 16px;
            padding: 16px 20px;
            background: var(--surface);
            border: 1px solid var(--border);
            border-radius: 8px;
            transition: all 0.2s ease;
        }

        .service:hover {
            border-color: var(--accent);
            background: var(--accent-dim);
        }

        .service-icon {
            width: 40px;
            height: 40px;
            display: flex;
            align-items: center;
            justify-content: center;
            background: var(--bg);
            border-radius: 6px;
            flex-shrink: 0;
        }

        .service-icon svg {
            width: 20px;
            height: 20px;
            stroke: var(--accent);
        }

        .service-text {
            font-family: 'IBM Plex Mono', monospace;
            font-size: 0.875rem;
            color: var(--text-primary);
        }

        /* Contact */
        .contact {
            opacity: 0;
            animation: fadeUp 0.6s ease 0.5s forwards;
        }

        .contact-label {
            font-family: 'IBM Plex Mono', monospace;
            font-size: 0.75rem;
            color: var(--text-secondary);
            letter-spacing: 0.1em;
            text-transform: uppercase;
            margin-bottom: 16px;
        }

        .links {
            display: flex;
            flex-wrap: wrap;
            gap: 12px;
        }

        .link {
            display: inline-flex;
            align-items: center;
            gap: 8px;
            padding: 12px 20px;
            background: transparent;
            border: 1px solid var(--border);
            border-radius: 6px;
            color: var(--text-primary);
            text-decoration: none;
            font-family: 'IBM Plex Mono', monospace;
            font-size: 0.875rem;
            transition: all 0.2s ease;
        }

        .link:hover {
            border-color: var(--text-primary);
            background: var(--text-primary);
            color: var(--bg);
        }

        .link svg {
            width: 16px;
            height: 16px;
        }

        /* Status indicator */
        .status {
            display: inline-flex;
            align-items: center;
            gap: 8px;
            margin-top: 32px;
            font-family: 'IBM Plex Mono', monospace;
            font-size: 0.75rem;
            color: var(--text-secondary);
            opacity: 0;
            animation: fadeUp 0.6s ease 0.6s forwards;
        }

        .status-dot {
            width: 6px;
            height: 6px;
            background: #22c55e;
            border-radius: 50%;
            animation: pulse 2s ease infinite;
        }

        /* Animations */
        @keyframes fadeUp {
            from {
                opacity: 0;
                transform: translateY(20px);
            }
            to {
                opacity: 1;
                transform: translateY(0);
            }
        }

        @keyframes pulse {
            0%, 100% { opacity: 1; }
            50% { opacity: 0.4; }
        }

        /* Responsive */
        @media (max-width: 480px) {
            .content {
                padding: 60px 0;
            }

            .links {
                flex-direction: column;
            }

            .link {
                justify-content: center;
            }
        }
    </style>
</head>
<body>
    <div class="grid-bg"></div>

    <div class="container">
        <div class="content">
            <header class="header">
                <h1 class="name">vespei<span>_</span></h1>
                <p class="tagline">Infrastructure &amp; Systems</p>
            </header>

            <div class="divider"></div>

            <section class="about">
                <p>Building and maintaining the <strong>servers</strong>, <strong>networks</strong>, and <strong>systems</strong> that keep things running.</p>
            </section>

            <section class="services">
                <div class="service">
                    <div class="service-icon">
                        <svg fill="none" stroke="currentColor" stroke-width="1.5" viewBox="0 0 24 24">
                            <path stroke-linecap="round" stroke-linejoin="round" d="M5.25 14.25h13.5m-13.5 0a3 3 0 01-3-3m3 3a3 3 0 100 6h13.5a3 3 0 100-6m-16.5-3a3 3 0 013-3h13.5a3 3 0 013 3m-19.5 0a4.5 4.5 0 01.9-2.7L5.737 5.1a3.375 3.375 0 012.7-1.35h7.126c1.062 0 2.062.5 2.7 1.35l2.587 3.45a4.5 4.5 0 01.9 2.7m0 0a3 3 0 01-3 3m0 3h.008v.008h-.008v-.008zm0-6h.008v.008h-.008v-.008zm-3 6h.008v.008h-.008v-.008zm0-6h.008v.008h-.008v-.008z" />
                        </svg>
                    </div>
                    <span class="service-text">Linux Server Management</span>
                </div>
                <div class="service">
                    <div class="service-icon">
                        <svg fill="none" stroke="currentColor" stroke-width="1.5" viewBox="0 0 24 24">
                            <path stroke-linecap="round" stroke-linejoin="round" d="M5.25 14.25h13.5m-13.5 0a3 3 0 01-3-3m3 3a3 3 0 100 6h13.5a3 3 0 100-6m-16.5-3a3 3 0 013-3h13.5a3 3 0 013 3m-19.5 0a4.5 4.5 0 01.9-2.7L5.737 5.1a3.375 3.375 0 012.7-1.35h7.126c1.062 0 2.062.5 2.7 1.35l2.587 3.45a4.5 4.5 0 01.9 2.7m0 0a3 3 0 01-3 3m0 3h.008v.008h-.008v-.008zm0-6h.008v.008h-.008v-.008zm-3 6h.008v.008h-.008v-.008zm0-6h.008v.008h-.008v-.008z" />
                        </svg>
                    </div>
                    <span class="service-text">Private Game Server Hosting</span>
                </div>
                <div class="service">
                    <div class="service-icon">
                        <svg fill="none" stroke="currentColor" stroke-width="1.5" viewBox="0 0 24 24">
                            <path stroke-linecap="round" stroke-linejoin="round" d="M9 17.25v1.007a3 3 0 01-.879 2.122L7.5 21h9l-.621-.621A3 3 0 0115 18.257V17.25m6-12V15a2.25 2.25 0 01-2.25 2.25H5.25A2.25 2.25 0 013 15V5.25m18 0A2.25 2.25 0 0018.75 3H5.25A2.25 2.25 0 003 5.25m18 0V12a2.25 2.25 0 01-2.25 2.25H5.25A2.25 2.25 0 013 12V5.25" />
                        </svg>
                    </div>
                    <span class="service-text">Server Hardware Enthusiast</span>
                </div>
            </section>
        </div>
    </div>
</body>
</html>
