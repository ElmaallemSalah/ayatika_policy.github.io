<!DOCTYPE html>
<html lang="en" dir="ltr" data-theme="dark">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Privacy Policy | Ayatika - Islamic Companion</title>
  <meta name="description" content="Official Privacy Policy for Ayatika iOS App. Learn how we protect your privacy, handle location data, and maintain 100% respect for your personal information.">
  <meta name="author" content="Ayatika / Elmaallem">
  <meta name="robots" content="index, follow">
  
  <!-- Open Graph / Social Sharing -->
  <meta property="og:title" content="Privacy Policy - Ayatika App">
  <meta property="og:description" content="Comprehensive Apple App Store compliant privacy policy for Ayatika Islamic App.">
  <meta property="og:type" content="website">

  <style>
    :root {
      --primary: #00897B;
      --primary-dark: #004D40;
      --primary-deep: #00251A;
      --accent-gold: #D4AF37;
      --accent-gold-light: #F9E79F;
      --accent-gold-glow: rgba(212, 175, 55, 0.25);
      
      /* Dark Theme (Default) */
      --bg-body: #061A14;
      --bg-surface: #0B2920;
      --bg-surface-elevated: #11382D;
      --bg-card: rgba(16, 48, 38, 0.7);
      --bg-glass: rgba(11, 41, 32, 0.75);
      --border-glass: rgba(212, 175, 55, 0.18);
      --border-subtle: rgba(255, 255, 255, 0.08);
      
      --text-primary: #F0FDF4;
      --text-secondary: #A7D7C5;
      --text-muted: #6B9B8A;
      --badge-bg: rgba(0, 137, 123, 0.25);
      --badge-text: #5EEAD4;
      
      --shadow-sm: 0 4px 12px rgba(0, 0, 0, 0.25);
      --shadow-md: 0 12px 32px rgba(0, 0, 0, 0.4);
      --shadow-glow: 0 0 40px rgba(0, 137, 123, 0.2);
      
      --font-main: -apple-system, BlinkMacSystemFont, 'SF Pro Display', 'SF Pro Text', 'Segoe UI', Roboto, 'Helvetica Neue', Arial, sans-serif;
      --font-arabic: -apple-system, BlinkMacSystemFont, 'SF Arabic', 'Geeza Pro', 'Traditional Arabic', 'Segoe UI', Tahoma, sans-serif;
      --radius-sm: 8px;
      --radius-md: 16px;
      --radius-lg: 24px;
      --radius-full: 9999px;
      
      --transition: all 0.25s cubic-bezier(0.4, 0, 0.2, 1);
    }

    [data-theme="light"] {
      --bg-body: #F4F8F6;
      --bg-surface: #FFFFFF;
      --bg-surface-elevated: #E8F3EE;
      --bg-card: rgba(255, 255, 255, 0.9);
      --bg-glass: rgba(255, 255, 255, 0.85);
      --border-glass: rgba(0, 77, 64, 0.15);
      --border-subtle: rgba(0, 77, 64, 0.08);
      
      --text-primary: #0A261E;
      --text-secondary: #2C5E50;
      --text-muted: #5B8577;
      --badge-bg: rgba(0, 137, 123, 0.12);
      --badge-text: #00695C;
      
      --shadow-sm: 0 4px 12px rgba(0, 77, 64, 0.06);
      --shadow-md: 0 12px 32px rgba(0, 77, 64, 0.08);
      --shadow-glow: 0 0 40px rgba(0, 137, 123, 0.1);
    }

    /* RTL Support for Arabic */
    [dir="rtl"] {
      font-family: var(--font-arabic);
    }

    * {
      box-sizing: border-box;
      margin: 0;
      padding: 0;
    }

    html {
      scroll-behavior: smooth;
      font-size: 16px;
    }

    body {
      font-family: var(--font-main);
      background-color: var(--bg-body);
      color: var(--text-primary);
      line-height: 1.7;
      min-height: 100vh;
      overflow-x: hidden;
      transition: background-color 0.3s ease, color 0.3s ease;
      background-image: 
        radial-gradient(circle at 10% 20%, rgba(0, 137, 123, 0.15) 0%, transparent 40%),
        radial-gradient(circle at 90% 80%, rgba(212, 175, 55, 0.08) 0%, transparent 45%),
        radial-gradient(circle at 50% 50%, rgba(0, 77, 64, 0.1) 0%, transparent 60%);
      background-attachment: fixed;
    }

    /* SVG Icons Common Style */
    .icon {
      width: 18px;
      height: 18px;
      display: inline-block;
      vertical-align: middle;
      fill: currentColor;
      flex-shrink: 0;
    }

    .icon-lg {
      width: 24px;
      height: 24px;
    }

    /* Geometric Islamic Pattern Background */
    .bg-pattern {
      position: fixed;
      inset: 0;
      pointer-events: none;
      opacity: 0.04;
      z-index: 0;
      background-image: radial-gradient(#D4AF37 1px, transparent 1px), radial-gradient(#00897B 1px, transparent 1px);
      background-size: 40px 40px;
      background-position: 0 0, 20px 20px;
    }

    /* Container */
    .container {
      max-width: 1240px;
      margin: 0 auto;
      padding: 0 24px;
      position: relative;
      z-index: 1;
    }

    /* Header / Navbar */
    header.site-header {
      position: sticky;
      top: 0;
      z-index: 100;
      backdrop-filter: blur(16px);
      -webkit-backdrop-filter: blur(16px);
      background: var(--bg-glass);
      border-bottom: 1px solid var(--border-glass);
      transition: var(--transition);
    }

    .navbar {
      display: flex;
      align-items: center;
      justify-content: space-between;
      height: 76px;
    }

    .brand {
      display: flex;
      align-items: center;
      gap: 14px;
      text-decoration: none;
      color: var(--text-primary);
    }

    .brand-logo-wrap {
      width: 44px;
      height: 44px;
      border-radius: var(--radius-md);
      background: linear-gradient(135deg, #004D40, #00897B);
      border: 1.5px solid var(--accent-gold);
      display: flex;
      align-items: center;
      justify-content: center;
      box-shadow: 0 4px 12px rgba(0, 0, 0, 0.2);
      color: var(--accent-gold);
    }

    .brand-text {
      display: flex;
      flex-direction: column;
    }

    .brand-name {
      font-size: 1.35rem;
      font-weight: 800;
      letter-spacing: -0.02em;
      background: linear-gradient(135deg, #FFFFFF, var(--accent-gold-light));
      -webkit-background-clip: text;
      -webkit-text-fill-color: transparent;
    }

    [data-theme="light"] .brand-name {
      background: linear-gradient(135deg, #004D40, #00897B);
      -webkit-background-clip: text;
      -webkit-text-fill-color: transparent;
    }

    .brand-tag {
      font-size: 0.72rem;
      color: var(--accent-gold);
      font-weight: 600;
      letter-spacing: 0.05em;
      text-transform: uppercase;
    }

    .header-actions {
      display: flex;
      align-items: center;
      gap: 10px;
    }

    .btn-action {
      background: var(--bg-surface-elevated);
      border: 1px solid var(--border-glass);
      color: var(--text-primary);
      padding: 8px 14px;
      border-radius: var(--radius-full);
      font-size: 0.85rem;
      font-weight: 600;
      cursor: pointer;
      display: inline-flex;
      align-items: center;
      gap: 8px;
      transition: var(--transition);
      text-decoration: none;
      font-family: inherit;
    }

    .btn-action:hover {
      background: var(--primary);
      color: #FFFFFF;
      border-color: var(--primary);
      transform: translateY(-1px);
    }

    .btn-action.active {
      background: var(--primary);
      color: #FFFFFF;
      border-color: var(--primary);
    }

    /* Hero Banner */
    .hero-section {
      padding: 56px 0 40px;
      text-align: center;
      position: relative;
    }

    .hero-badge {
      display: inline-flex;
      align-items: center;
      gap: 8px;
      background: var(--badge-bg);
      border: 1px solid var(--border-glass);
      color: var(--badge-text);
      padding: 6px 16px;
      border-radius: var(--radius-full);
      font-size: 0.82rem;
      font-weight: 700;
      letter-spacing: 0.03em;
      margin-bottom: 20px;
      text-transform: uppercase;
    }

    .hero-title {
      font-size: 2.75rem;
      font-weight: 800;
      line-height: 1.15;
      margin-bottom: 16px;
      letter-spacing: -0.02em;
    }

    .hero-title span {
      background: linear-gradient(135deg, var(--accent-gold), #FFF);
      -webkit-background-clip: text;
      -webkit-text-fill-color: transparent;
    }

    [data-theme="light"] .hero-title span {
      background: linear-gradient(135deg, #00695C, var(--accent-gold));
      -webkit-background-clip: text;
      -webkit-text-fill-color: transparent;
    }

    .hero-subtitle {
      max-width: 680px;
      margin: 0 auto 24px;
      color: var(--text-secondary);
      font-size: 1.05rem;
      font-weight: 400;
    }

    .meta-bar {
      display: inline-flex;
      flex-wrap: wrap;
      align-items: center;
      justify-content: center;
      gap: 20px;
      background: var(--bg-surface);
      border: 1px solid var(--border-glass);
      padding: 10px 24px;
      border-radius: var(--radius-full);
      font-size: 0.85rem;
      color: var(--text-muted);
    }

    .meta-item {
      display: flex;
      align-items: center;
      gap: 8px;
    }

    .meta-item svg {
      color: var(--accent-gold);
    }

    .meta-item strong {
      color: var(--text-primary);
    }

    /* Nutrition Label Cards (Apple Style Privacy Cards) */
    .privacy-nutrition-grid {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(260px, 1fr));
      gap: 20px;
      margin: 40px 0;
    }

    .nutrition-card {
      background: var(--bg-card);
      border: 1px solid var(--border-glass);
      backdrop-filter: blur(12px);
      -webkit-backdrop-filter: blur(12px);
      border-radius: var(--radius-lg);
      padding: 24px;
      transition: var(--transition);
      position: relative;
      overflow: hidden;
    }

    .nutrition-card:hover {
      transform: translateY(-4px);
      border-color: var(--accent-gold);
      box-shadow: var(--shadow-glow);
    }

    .nutrition-icon {
      width: 48px;
      height: 48px;
      border-radius: var(--radius-md);
      background: var(--bg-surface-elevated);
      border: 1px solid var(--border-glass);
      display: flex;
      align-items: center;
      justify-content: center;
      margin-bottom: 16px;
      color: var(--accent-gold);
    }

    .nutrition-card h3 {
      font-size: 1.1rem;
      font-weight: 700;
      margin-bottom: 8px;
      color: var(--text-primary);
    }

    .nutrition-card p {
      font-size: 0.88rem;
      color: var(--text-secondary);
      line-height: 1.5;
    }

    .nutrition-badge {
      display: inline-block;
      margin-top: 12px;
      padding: 4px 10px;
      border-radius: var(--radius-sm);
      font-size: 0.75rem;
      font-weight: 700;
      text-transform: uppercase;
    }

    .badge-success {
      background: rgba(34, 197, 94, 0.15);
      color: #4ADE80;
      border: 1px solid rgba(74, 222, 128, 0.3);
    }

    .badge-info {
      background: rgba(56, 189, 248, 0.15);
      color: #38BDF8;
      border: 1px solid rgba(56, 189, 248, 0.3);
    }

    /* Main Content Layout */
    .layout-wrapper {
      display: grid;
      grid-template-columns: 290px 1fr;
      gap: 40px;
      margin-bottom: 80px;
      align-items: start;
    }

    /* Sticky Sidebar Navigation */
    .sidebar {
      position: sticky;
      top: 96px;
      background: var(--bg-card);
      border: 1px solid var(--border-glass);
      border-radius: var(--radius-lg);
      padding: 24px 18px;
      backdrop-filter: blur(12px);
      -webkit-backdrop-filter: blur(12px);
      box-shadow: var(--shadow-sm);
      max-height: calc(100vh - 120px);
      overflow-y: auto;
    }

    .sidebar-title {
      font-size: 0.85rem;
      font-weight: 800;
      text-transform: uppercase;
      letter-spacing: 0.08em;
      color: var(--accent-gold);
      margin-bottom: 16px;
      padding-left: 12px;
      display: flex;
      align-items: center;
      gap: 8px;
    }

    [dir="rtl"] .sidebar-title {
      padding-left: 0;
      padding-right: 12px;
    }

    .toc-nav {
      display: flex;
      flex-direction: column;
      gap: 4px;
    }

    .toc-link {
      display: flex;
      align-items: center;
      gap: 10px;
      padding: 8px 12px;
      border-radius: var(--radius-sm);
      color: var(--text-secondary);
      text-decoration: none;
      font-size: 0.88rem;
      font-weight: 500;
      transition: var(--transition);
    }

    .toc-link svg {
      width: 16px;
      height: 16px;
      color: var(--text-muted);
      transition: var(--transition);
    }

    .toc-link:hover {
      color: var(--text-primary);
      background: var(--bg-surface-elevated);
    }

    .toc-link.active {
      color: #FFFFFF;
      background: var(--primary);
      font-weight: 600;
    }

    .toc-link.active svg {
      color: var(--accent-gold);
    }

    /* Policy Content Document */
    .policy-content {
      background: var(--bg-card);
      border: 1px solid var(--border-glass);
      backdrop-filter: blur(12px);
      -webkit-backdrop-filter: blur(12px);
      border-radius: var(--radius-lg);
      padding: 48px;
      box-shadow: var(--shadow-md);
    }

    .policy-section {
      margin-bottom: 48px;
      padding-bottom: 36px;
      border-bottom: 1px solid var(--border-subtle);
    }

    .policy-section:last-child {
      margin-bottom: 0;
      padding-bottom: 0;
      border-bottom: none;
    }

    .section-header {
      display: flex;
      align-items: center;
      gap: 14px;
      margin-bottom: 20px;
    }

    .section-num {
      width: 38px;
      height: 38px;
      border-radius: var(--radius-md);
      background: var(--bg-surface-elevated);
      border: 1px solid var(--accent-gold);
      color: var(--accent-gold);
      display: flex;
      align-items: center;
      justify-content: center;
      font-weight: 800;
      font-size: 1rem;
      flex-shrink: 0;
    }

    .section-title {
      font-size: 1.55rem;
      font-weight: 800;
      color: var(--text-primary);
      letter-spacing: -0.01em;
    }

    .policy-section p {
      color: var(--text-secondary);
      font-size: 1rem;
      margin-bottom: 16px;
      line-height: 1.75;
    }

    .policy-section h4 {
      font-size: 1.15rem;
      font-weight: 700;
      color: var(--text-primary);
      margin: 24px 0 12px;
      display: flex;
      align-items: center;
      gap: 8px;
    }

    .policy-section h4 svg {
      color: var(--accent-gold);
      width: 18px;
      height: 18px;
    }

    .feature-list {
      list-style: none;
      margin: 16px 0 24px;
      display: flex;
      flex-direction: column;
      gap: 12px;
    }

    .feature-list li {
      display: flex;
      align-items: flex-start;
      gap: 12px;
      color: var(--text-secondary);
      font-size: 0.95rem;
      line-height: 1.6;
    }

    .feature-list li svg.check-icon {
      color: #10B981;
      width: 18px;
      height: 18px;
      margin-top: 3px;
      flex-shrink: 0;
    }

    /* Custom Callouts / Alerts */
    .callout {
      background: var(--bg-surface-elevated);
      border-radius: var(--radius-md);
      padding: 20px 24px;
      margin: 20px 0;
      border-left: 4px solid var(--primary);
      display: flex;
      gap: 16px;
      align-items: flex-start;
    }

    [dir="rtl"] .callout {
      border-left: none;
      border-right: 4px solid var(--primary);
    }

    .callout.gold {
      border-color: var(--accent-gold);
      background: rgba(212, 175, 55, 0.08);
    }

    .callout.info {
      border-color: #38BDF8;
      background: rgba(56, 189, 248, 0.08);
    }

    .callout.success {
      border-color: #10B981;
      background: rgba(16, 185, 129, 0.08);
    }

    .callout-icon {
      color: var(--accent-gold);
      width: 22px;
      height: 22px;
      flex-shrink: 0;
      margin-top: 2px;
    }

    .callout.info .callout-icon { color: #38BDF8; }
    .callout.success .callout-icon { color: #10B981; }

    .callout-body strong {
      display: block;
      color: var(--text-primary);
      font-size: 0.98rem;
      margin-bottom: 4px;
    }

    .callout-body p {
      color: var(--text-secondary);
      font-size: 0.9rem;
      margin-bottom: 0 !important;
      line-height: 1.6;
    }

    /* Table Styles */
    .data-table-wrap {
      overflow-x: auto;
      margin: 20px 0;
      border-radius: var(--radius-md);
      border: 1px solid var(--border-glass);
    }

    table.data-table {
      width: 100%;
      border-collapse: collapse;
      text-align: left;
      font-size: 0.9rem;
    }

    [dir="rtl"] table.data-table {
      text-align: right;
    }

    table.data-table th {
      background: var(--bg-surface-elevated);
      color: var(--accent-gold);
      font-weight: 700;
      padding: 14px 18px;
      border-bottom: 1px solid var(--border-glass);
      text-transform: uppercase;
      font-size: 0.78rem;
      letter-spacing: 0.05em;
    }

    table.data-table td {
      padding: 14px 18px;
      border-bottom: 1px solid var(--border-subtle);
      color: var(--text-secondary);
    }

    table.data-table code {
      font-family: ui-monospace, SFMono-Regular, Menlo, Monaco, Consolas, monospace;
      background: rgba(0, 137, 123, 0.15);
      padding: 2px 6px;
      border-radius: 4px;
      color: var(--badge-text);
      font-size: 0.85em;
    }

    table.data-table tr:last-child td {
      border-bottom: none;
    }

    table.data-table tr:hover td {
      background: rgba(255, 255, 255, 0.02);
    }

    .table-tag {
      display: inline-block;
      padding: 3px 8px;
      border-radius: var(--radius-sm);
      font-size: 0.75rem;
      font-weight: 600;
      background: var(--badge-bg);
      color: var(--badge-text);
    }

    /* Contact Card */
    .contact-card {
      background: linear-gradient(135deg, rgba(0, 77, 64, 0.5), rgba(11, 41, 32, 0.8));
      border: 1.5px solid var(--accent-gold);
      border-radius: var(--radius-lg);
      padding: 32px;
      text-align: center;
      margin-top: 32px;
    }

    .contact-card h4 {
      font-size: 1.35rem;
      color: #FFFFFF;
      margin-bottom: 10px;
      justify-content: center;
      display: flex;
      align-items: center;
      gap: 10px;
    }

    .contact-card p {
      max-width: 540px;
      margin: 0 auto 20px;
      color: var(--text-secondary);
    }

    .contact-btn {
      display: inline-flex;
      align-items: center;
      gap: 10px;
      background: linear-gradient(135deg, var(--accent-gold), #F7DC6F);
      color: #042017;
      font-weight: 800;
      font-size: 1rem;
      padding: 12px 28px;
      border-radius: var(--radius-full);
      text-decoration: none;
      transition: var(--transition);
      box-shadow: 0 4px 16px var(--accent-gold-glow);
    }

    .contact-btn:hover {
      transform: translateY(-2px);
      box-shadow: 0 8px 24px var(--accent-gold-glow);
    }

    /* Footer */
    footer.site-footer {
      border-top: 1px solid var(--border-glass);
      background: var(--bg-surface);
      padding: 40px 0;
      text-align: center;
      color: var(--text-muted);
      font-size: 0.88rem;
    }

    .footer-links {
      display: flex;
      justify-content: center;
      gap: 24px;
      margin-bottom: 16px;
      flex-wrap: wrap;
    }

    .footer-links a {
      color: var(--text-secondary);
      text-decoration: none;
      transition: var(--transition);
      display: inline-flex;
      align-items: center;
      gap: 6px;
    }

    .footer-links a:hover {
      color: var(--accent-gold);
    }

    /* Language Switcher Section Visibility */
    .lang-content {
      display: none;
    }

    .lang-content.active-lang {
      display: block;
      animation: fadeIn 0.3s ease;
    }

    @keyframes fadeIn {
      from { opacity: 0; transform: translateY(6px); }
      to { opacity: 1; transform: translateY(0); }
    }

    /* Print Styles */
    @media print {
      body {
        background: #FFFFFF !important;
        color: #000000 !important;
      }
      .bg-pattern, header, .sidebar, .header-actions, .privacy-nutrition-grid, .contact-btn, footer {
        display: none !important;
      }
      .layout-wrapper {
        display: block !important;
      }
      .policy-content {
        border: none !important;
        box-shadow: none !important;
        padding: 0 !important;
        background: transparent !important;
      }
      .policy-section {
        page-break-inside: avoid;
      }
    }

    /* Responsive */
    @media (max-width: 992px) {
      .layout-wrapper {
        grid-template-columns: 1fr;
      }
      .sidebar {
        position: relative;
        top: 0;
        max-height: none;
      }
      .policy-content {
        padding: 32px 20px;
      }
      .hero-title {
        font-size: 2.1rem;
      }
    }

    @media (max-width: 600px) {
      .navbar {
        height: auto;
        padding: 14px 0;
        flex-direction: column;
        gap: 12px;
      }
      .header-actions {
        width: 100%;
        justify-content: center;
        flex-wrap: wrap;
      }
      .meta-bar {
        flex-direction: column;
        border-radius: var(--radius-md);
        gap: 10px;
      }
      .hero-title {
        font-size: 1.8rem;
      }
    }
  </style>
</head>
<body>
  <div class="bg-pattern"></div>

  <!-- Main Site Header -->
  <header class="site-header">
    <div class="container">
      <nav class="navbar">
        <a href="#section-overview" class="brand">
          <div class="brand-logo-wrap">
            <!-- Crescent Moon SVG -->
            <svg class="icon icon-lg" viewBox="0 0 24 24">
              <path d="M12 3a9 9 0 1 0 9 9c0-.46-.04-.92-.1-1.36a5.389 5.389 0 0 1-4.4 2.26 5.403 5.403 0 0 1-3.14-9.8A9 9 0 0 0 12 3z"/>
            </svg>
          </div>
          <div class="brand-text">
            <span class="brand-name">Ayatika • آياتك</span>
            <span class="brand-tag">Islamic Companion App</span>
          </div>
        </a>

        <div class="header-actions">
          <!-- Language Toggle Buttons -->
          <button id="btn-en" class="btn-action active" onclick="setLanguage('en')">
            <svg class="icon" viewBox="0 0 24 24"><path d="M12 2C6.48 2 2 6.48 2 12s4.48 10 10 10 10-4.48 10-10S17.52 2 12 2zm-1 17.93c-3.95-.49-7-3.85-7-7.93 0-.62.08-1.21.21-1.79L9 15v1c0 1.1.9 2 2 2v1.93zm6.9-2.54c-.26-.81-1-1.39-1.9-1.39h-1v-3c0-.55-.45-1-1-1H8v-2h2c.55 0 1-.45 1-1V7h2c1.1 0 2-.9 2-2v-.41c2.93 1.19 5 4.06 5 7.41 0 2.08-.8 3.97-2.1 5.39z"/></svg>
            English
          </button>
          <button id="btn-ar" class="btn-action" onclick="setLanguage('ar')">
            <svg class="icon" viewBox="0 0 24 24"><path d="M12.87 15.07l-2.54-2.51.03-.03c1.74-1.94 2.98-4.17 3.71-6.53H17V4h-7V2H8v2H1v1.99h11.17C11.5 7.92 10.44 9.75 9 11.35 8.07 10.32 7.3 9.19 6.69 8h-2c.73 1.63 1.73 3.17 2.98 4.56l-5.09 5.02L4 19l5-5 3.11 3.11.76-2.04zM18.5 10h-2L12 22h2l1.12-3h4.75L21 22h2l-4.5-12zm-2.62 7l1.62-4.33L19.12 17h-3.24z"/></svg>
            العربية
          </button>

          <!-- Theme Toggle -->
          <button id="theme-toggle" class="btn-action" onclick="toggleTheme()" aria-label="Toggle Theme">
            <span id="theme-icon-wrap">
              <svg class="icon" id="theme-icon" viewBox="0 0 24 24"><path d="M12 7c-2.76 0-5 2.24-5 5s2.24 5 5 5 5-2.24 5-5-2.24-5-5-5zM2 13h2c.55 0 1-.45 1-1s-.45-1-1-1H2c-.55 0-1 .45-1 1s.45 1 1 1zm18 0h2c.55 0 1-.45 1-1s-.45-1-1-1h-2c-.55 0-1 .45-1 1s.45 1 1 1zM11 2v2c0 .55.45 1 1 1s1-.45 1-1V2c0-.55-.45-1-1-1s-1 .45-1 1zm0 18v2c0 .55.45 1 1 1s1-.45 1-1v-2c0-.55-.45-1-1-1s-1 .45-1 1zM5.99 4.58a.996.996 0 0 0-1.41 0 .996.996 0 0 0 0 1.41l1.06 1.06c.39.39 1.03.39 1.41 0s.39-1.03 0-1.41L5.99 4.58zm12.37 12.37a.996.996 0 0 0-1.41 0 .996.996 0 0 0 0 1.41l1.06 1.06c.39.39 1.03.39 1.41 0s.39-1.03 0-1.41l-1.06-1.06zm1.06-10.96a.996.996 0 0 0 0-1.41.996.996 0 0 0-1.41 0l-1.06 1.06c-.39.39-.39 1.03 0 1.41s1.03.39 1.41 0l1.06-1.06zM7.05 18.36a.996.996 0 0 0 0-1.41.996.996 0 0 0-1.41 0l-1.06 1.06c-.39.39-.39 1.03 0 1.41s1.03.39 1.41 0l1.06-1.06z"/></svg>
            </span>
          </button>

          <!-- Print / Save -->
          <button class="btn-action" onclick="window.print()" title="Print / PDF">
            <svg class="icon" viewBox="0 0 24 24"><path d="M19 8H5c-1.66 0-3 1.34-3 3v6h4v4h12v-4h4v-6c0-1.66-1.34-3-3-3zm-3 11H8v-5h8v5zm3-7c-.55 0-1-.45-1-1s.45-1 1-1 1 .45 1 1-.45 1-1 1zm-1-9H6v4h12V3z"/></svg>
          </button>
        </div>
      </nav>
    </div>
  </header>

  <main class="container">
    <!-- Hero Header -->
    <section class="hero-section">
      <div class="hero-badge">
        <!-- Apple Icon SVG -->
        <svg class="icon" viewBox="0 0 24 24"><path d="M18.71 19.5c-.83 1.24-1.71 2.45-3.05 2.47-1.34.03-1.77-.79-3.29-.79-1.53 0-2 .77-3.27.82-1.31.05-2.3-1.32-3.14-2.53C4.25 17 2.94 12.45 4.7 9.39c.87-1.52 2.43-2.48 4.12-2.51 1.28-.02 2.5.87 3.29.87.78 0 2.26-1.07 3.81-.91.65.03 2.47.26 3.64 1.98-.09.06-2.17 1.28-2.15 3.81.03 3.02 2.65 4.03 2.68 4.04-.03.07-.42 1.44-1.38 2.83M15.97 6.37c.61-.75 1.04-1.8 0.92-2.87-.93.04-2.03.63-2.67 1.38-.56.65-.99 1.7-0.86 2.73 1.04.08 2.06-.52 2.61-1.24z"/></svg>
        <span id="badge-text">Apple App Store Compliant Privacy Document</span>
      </div>
      
      <h1 class="hero-title" id="hero-title">
        Privacy Policy & <span>Data Protection</span>
      </h1>
      
      <p class="hero-subtitle" id="hero-subtitle">
        Your spiritual journey is personal. Ayatika is architected with a strict privacy-first foundation: we do not sell your data, do not track you across apps, and perform prayer calculations locally.
      </p>

      <div class="meta-bar">
        <div class="meta-item">
          <!-- Calendar Icon -->
          <svg class="icon" viewBox="0 0 24 24"><path d="M19 4h-1V2h-2v2H8V2H6v2H5c-1.11 0-1.99.9-1.99 2L3 20a2 2 0 0 0 2 2h14c1.1 0 2-.9 2-2V6c0-1.1-.9-2-2-2zm0 16H5V10h14v10zm0-12H5V6h14v2z"/></svg>
          <span>Effective Date: <strong>August 17, 2026</strong></span>
        </div>
        <div class="meta-item">
          <!-- Shield Icon -->
          <svg class="icon" viewBox="0 0 24 24"><path d="M12 1L3 5v6c0 5.55 3.84 10.74 9 12 5.16-1.26 9-6.45 9-12V5l-9-4zm-2 16l-4-4 1.41-1.41L10 14.17l6.59-6.59L18 9l-8 8z"/></svg>
          <span>App Store Status: <strong>Fully Compliant (iOS 17 & 18+)</strong></span>
        </div>
        <div class="meta-item">
          <!-- Code/Version Icon -->
          <svg class="icon" viewBox="0 0 24 24"><path d="M9.4 16.6L4.8 12l4.6-4.6L8 6l-6 6 6 6 1.4-1.4zm5.2 0l4.6-4.6-4.6-4.6L16 6l6 6-6 6-1.4-1.4z"/></svg>
          <span>App Version: <strong>1.1.4+</strong></span>
        </div>
      </div>
    </section>

    <!-- Apple App Store Privacy Nutrition Label Grid -->
    <section class="privacy-nutrition-grid">
      <div class="nutrition-card">
        <div class="nutrition-icon">
          <!-- Ban Icon -->
          <svg class="icon icon-lg" viewBox="0 0 24 24"><path d="M12 2C6.48 2 2 6.48 2 12s4.48 10 10 10 10-4.48 10-10S17.52 2 12 2zm0 18c-4.42 0-8-3.58-8-8 0-1.85.63-3.55 1.69-4.9L16.9 18.31C15.55 19.37 13.85 20 12 20zm6.31-3.1L7.1 5.69C8.45 4.63 10.15 4 12 4c4.42 0 8 3.58 8 8 0 1.85-.63 3.55-1.69 4.9z"/></svg>
        </div>
        <h3 id="nutri-1-title">No Tracking</h3>
        <p id="nutri-1-desc">We do not use advertising identifiers (IDFA) and never track you across apps or websites owned by other companies.</p>
        <span class="nutrition-badge badge-success" id="nutri-1-badge">Data Used to Track You: None</span>
      </div>

      <div class="nutrition-card">
        <div class="nutrition-icon">
          <!-- User Shield Icon -->
          <svg class="icon icon-lg" viewBox="0 0 24 24"><path d="M12 2C6.48 2 2 6.48 2 12s4.48 10 10 10 10-4.48 10-10S17.52 2 12 2zm0 3c1.66 0 3 1.34 3 3s-1.34 3-3 3-3-1.34-3-3 1.34-3 3-3zm0 14.2c-2.5 0-4.71-1.28-6-3.22.03-1.99 4-3.08 6-3.08 1.99 0 5.97 1.09 6 3.08-1.29 1.94-3.5 3.22-6 3.22z"/></svg>
        </div>
        <h3 id="nutri-2-title">No Account Required</h3>
        <p id="nutri-2-desc">Ayatika operates without mandatory sign-ups. Your bookmarks, Dhikr counts, and settings remain solely on your device.</p>
        <span class="nutrition-badge badge-success" id="nutri-2-badge">Data Linked to You: None</span>
      </div>

      <div class="nutrition-card">
        <div class="nutrition-icon">
          <!-- Location Icon -->
          <svg class="icon icon-lg" viewBox="0 0 24 24"><path d="M12 2C8.13 2 5 5.13 5 9c0 5.25 7 13 7 13s7-7.75 7-13c0-3.87-3.13-7-7-7zm0 9.5c-1.38 0-2.5-1.12-2.5-2.5s1.12-2.5 2.5-2.5 2.5 1.12 2.5 2.5-1.12 2.5-2.5 2.5z"/></svg>
        </div>
        <h3 id="nutri-3-title">On-Device Location</h3>
        <p id="nutri-3-desc">GPS coordinates are used strictly in real time to calculate astronomical prayer times and Qibla compass direction.</p>
        <span class="nutrition-badge badge-info" id="nutri-3-badge">Data Not Linked: Coarse Location</span>
      </div>

      <div class="nutrition-card">
        <div class="nutrition-icon">
          <!-- Lock Icon -->
          <svg class="icon icon-lg" viewBox="0 0 24 24"><path d="M18 8h-1V6c0-2.76-2.24-5-5-5S7 3.24 7 6v2H6c-1.1 0-2 .9-2 2v10c0 1.1.9 2 2 2h12c1.1 0 2-.9 2-2V10c0-1.1-.9-2-2-2zm-6 9c-1.1 0-2-.9-2-2s.9-2 2-2 2 .9 2 2-.9 2-2 2zm3.1-9H8.9V6c0-1.71 1.39-3.1 3.1-3.1 1.71 0 3.1 1.39 3.1 3.1v2z"/></svg>
        </div>
        <h3 id="nutri-4-title">Encrypted & Secure</h3>
        <p id="nutri-4-desc">All network requests to fetch Quran recitations, hadiths, and Islamic library resources use strict HTTPS/TLS encryption.</p>
        <span class="nutrition-badge badge-success" id="nutri-4-badge">Standard TLS 1.3 Security</span>
      </div>
    </section>

    <!-- Main Layout: Sidebar TOC + Content -->
    <div class="layout-wrapper">
      
      <!-- Sticky Navigation Sidebar -->
      <aside class="sidebar">
        <div class="sidebar-title">
          <svg class="icon" viewBox="0 0 24 24"><path d="M3 13h2v-2H3v2zm0 4h2v-2H3v2zm0-8h2V7H3v2zm4 4h14v-2H7v2zm0 4h14v-2H7v2zM7 7v2h14V7H7z"/></svg>
          <span id="toc-heading">Table of Contents</span>
        </div>
        <nav class="toc-nav" id="toc-nav-container">
          <a href="#section-overview" class="toc-link active"><svg class="icon" viewBox="0 0 24 24"><path d="M12 2C6.48 2 2 6.48 2 12s4.48 10 10 10 10-4.48 10-10S17.52 2 12 2zm1 15h-2v-6h2v6zm0-8h-2V7h2v2z"/></svg> <span class="toc-text">1. Overview & Commitment</span></a>
          <a href="#section-collection" class="toc-link"><svg class="icon" viewBox="0 0 24 24"><path d="M12 2C6.48 2 2 6.48 2 12s4.48 10 10 10 10-4.48 10-10S17.52 2 12 2zm-1 17.93c-3.95-.49-7-3.85-7-7.93 0-.62.08-1.21.21-1.79L9 15v1c0 1.1.9 2 2 2v1.93z"/></svg> <span class="toc-text">2. Information We Handle</span></a>
          <a href="#section-apple-ios" class="toc-link"><svg class="icon" viewBox="0 0 24 24"><path d="M18.71 19.5c-.83 1.24-1.71 2.45-3.05 2.47-1.34.03-1.77-.79-3.29-.79-1.53 0-2 .77-3.27.82-1.31.05-2.3-1.32-3.14-2.53C4.25 17 2.94 12.45 4.7 9.39c.87-1.52 2.43-2.48 4.12-2.51 1.28-.02 2.5.87 3.29.87.78 0 2.26-1.07 3.81-.91.65.03 2.47.26 3.64 1.98-.09.06-2.17 1.28-2.15 3.81.03 3.02 2.65 4.03 2.68 4.04-.03.07-.42 1.44-1.38 2.83M15.97 6.37c.61-.75 1.04-1.8 0.92-2.87-.93.04-2.03.63-2.67 1.38-.56.65-.99 1.7-0.86 2.73 1.04.08 2.06-.52 2.61-1.24z"/></svg> <span class="toc-text">3. iOS Permissions & Usage</span></a>
          <a href="#section-storage" class="toc-link"><svg class="icon" viewBox="0 0 24 24"><path d="M17 1.01L7 1c-1.1 0-2 .9-2 2v18c0 1.1.9 2 2 2h10c1.1 0 2-.9 2-2V3c0-1.1-.9-1.99-2-1.99zM17 19H7V5h10v14z"/></svg> <span class="toc-text">4. Offline & Local Storage</span></a>
          <a href="#section-third-parties" class="toc-link"><svg class="icon" viewBox="0 0 24 24"><path d="M12 2C6.48 2 2 6.48 2 12s4.48 10 10 10 10-4.48 10-10S17.52 2 12 2zm-1 17.93c-3.95-.49-7-3.85-7-7.93 0-.62.08-1.21.21-1.79L9 15v1c0 1.1.9 2 2 2v1.93z"/></svg> <span class="toc-text">5. Third-Party Services & APIs</span></a>
          <a href="#section-children" class="toc-link"><svg class="icon" viewBox="0 0 24 24"><path d="M12 12c2.21 0 4-1.79 4-4s-1.79-4-4-4-4 1.79-4 4 1.79 4 4 4zm0 2c-2.67 0-8 1.34-8 4v2h16v-2c0-2.66-5.33-4-8-4z"/></svg> <span class="toc-text">6. Children's Privacy (COPPA)</span></a>
          <a href="#section-gdpr-ccpa" class="toc-link"><svg class="icon" viewBox="0 0 24 24"><path d="M12 1L3 5v6c0 5.55 3.84 10.74 9 12 5.16-1.26 9-6.45 9-12V5l-9-4zm-2 16l-4-4 1.41-1.41L10 14.17l6.59-6.59L18 9l-8 8z"/></svg> <span class="toc-text">7. GDPR & CCPA Rights</span></a>
          <a href="#section-retention" class="toc-link"><svg class="icon" viewBox="0 0 24 24"><path d="M6 19c0 1.1.9 2 2 2h8c1.1 0 2-.9 2-2V7H6v12zM19 4h-3.5l-1-1h-5l-1 1H5v2h14V4z"/></svg> <span class="toc-text">8. Data Retention & Deletion</span></a>
          <a href="#section-changes" class="toc-link"><svg class="icon" viewBox="0 0 24 24"><path d="M13 3c-4.97 0-9 4.03-9 9H1l3.89 3.89.07.14L9 12H6c0-3.87 3.13-7 7-7s7 3.13 7 7-3.13 7-7 7c-1.93 0-3.68-.79-4.94-2.06l-1.42 1.42C8.27 19.99 10.51 21 13 21c4.97 0 9-4.03 9-9s-4.03-9-9-9zm-1 5v5l4.28 2.54.72-1.21-3.5-2.08V8H12z"/></svg> <span class="toc-text">9. Policy Updates</span></a>
          <a href="#section-contact" class="toc-link"><svg class="icon" viewBox="0 0 24 24"><path d="M20 4H4c-1.1 0-1.99.9-1.99 2L2 18c0 1.1.9 2 2 2h16c1.1 0 2-.9 2-2V6c0-1.1-.9-2-2-2zm0 4l-8 5-8-5V6l8 5 8-5v2z"/></svg> <span class="toc-text">10. Contact Developer</span></a>
        </nav>
      </aside>

      <!-- Policy Content Body -->
      <article class="policy-content">

        <!-- ======================================================== -->
        <!-- ENGLISH LANGUAGE VERSION -->
        <!-- ======================================================== -->
        <div id="content-en" class="lang-content active-lang">
          
          <!-- Section 1 -->
          <section id="section-overview" class="policy-section">
            <div class="section-header">
              <div class="section-num">1</div>
              <h2 class="section-title">Overview & Privacy Commitment</h2>
            </div>
            <p>
              Welcome to <strong>Ayatika</strong> ("we," "our," or "the App"), developed by <strong>Elmaallem</strong>. We recognize and respect the sacred nature of your religious practices and the absolute importance of personal privacy.
            </p>
            <p>
              This Privacy Policy explains how Ayatika collects, uses, processes, and protects your information in accordance with <strong>Apple’s App Store Review Guidelines (specifically Guideline 5.1 - Privacy)</strong>, the EU General Data Protection Regulation (<strong>GDPR</strong>), the California Consumer Privacy Act (<strong>CCPA/CPRA</strong>), and global privacy standards.
            </p>
            
            <div class="callout gold">
              <svg class="callout-icon" viewBox="0 0 24 24"><path d="M12 1L3 5v6c0 5.55 3.84 10.74 9 12 5.16-1.26 9-6.45 9-12V5l-9-4zm-2 16l-4-4 1.41-1.41L10 14.17l6.59-6.59L18 9l-8 8z"/></svg>
              <div class="callout-body">
                <strong>Our Core Privacy Promise</strong>
                <p>Ayatika does not sell, rent, monetize, or trade your personal information. We do not run third-party tracking advertisements, and we do not profile your religious habits.</p>
              </div>
            </div>
          </section>

          <!-- Section 2 -->
          <section id="section-collection" class="policy-section">
            <div class="section-header">
              <div class="section-num">2</div>
              <h2 class="section-title">Information We Handle & How It Is Used</h2>
            </div>
            <p>
              Ayatika is built following the principle of <em>Data Minimization</em>. We collect only what is strictly necessary to deliver Islamic features accurately.
            </p>

            <h4>
              <svg class="icon" viewBox="0 0 24 24"><path d="M12 2C8.13 2 5 5.13 5 9c0 5.25 7 13 7 13s7-7.75 7-13c0-3.87-3.13-7-7-7zm0 9.5c-1.38 0-2.5-1.12-2.5-2.5s1.12-2.5 2.5-2.5 2.5 1.12 2.5 2.5-1.12 2.5-2.5 2.5z"/></svg>
              A. Location Data (Foreground / When In Use)
            </h4>
            <p>
              When you grant location permission, Ayatika accesses your device’s latitude and longitude to:
            </p>
            <ul class="feature-list">
              <li>
                <svg class="check-icon" viewBox="0 0 24 24"><path d="M12 2C6.48 2 2 6.48 2 12s4.48 10 10 10 10-4.48 10-10S17.52 2 12 2zm-2 15l-5-5 1.41-1.41L10 14.17l7.59-7.59L19 8l-9 9z"/></svg>
                <span><strong>Calculate Prayer Times:</strong> Calculate precise Fajr, Dhuhr, Asr, Maghrib, and Isha times based on your exact astronomical coordinates and your chosen calculation method (e.g., Muslim World League, Umm Al-Qura, Egyptian Authority).</span>
              </li>
              <li>
                <svg class="check-icon" viewBox="0 0 24 24"><path d="M12 2C6.48 2 2 6.48 2 12s4.48 10 10 10 10-4.48 10-10S17.52 2 12 2zm-2 15l-5-5 1.41-1.41L10 14.17l7.59-7.59L19 8l-9 9z"/></svg>
                <span><strong>Qibla Direction:</strong> Compute the exact angle and bearing towards the Holy Kaaba in Makkah relative to your device's compass heading.</span>
              </li>
              <li>
                <svg class="check-icon" viewBox="0 0 24 24"><path d="M12 2C6.48 2 2 6.48 2 12s4.48 10 10 10 10-4.48 10-10S17.52 2 12 2zm-2 15l-5-5 1.41-1.41L10 14.17l7.59-7.59L19 8l-9 9z"/></svg>
                <span><strong>Nearby Mosques:</strong> Display mosques within your immediate vicinity using map data.</span>
              </li>
              <li>
                <svg class="check-icon" viewBox="0 0 24 24"><path d="M12 2C6.48 2 2 6.48 2 12s4.48 10 10 10 10-4.48 10-10S17.52 2 12 2zm-2 15l-5-5 1.41-1.41L10 14.17l7.59-7.59L19 8l-9 9z"/></svg>
                <span><strong>Reverse Geocoding:</strong> Convert coordinates into a human-readable city/country name (e.g., "Casablanca, Morocco") displayed on your home dashboard.</span>
              </li>
            </ul>

            <div class="callout info">
              <svg class="callout-icon" viewBox="0 0 24 24"><path d="M12 2C6.48 2 2 6.48 2 12s4.48 10 10 10 10-4.48 10-10S17.52 2 12 2zm1 15h-2v-6h2v6zm0-8h-2V7h2v2z"/></svg>
              <div class="callout-body">
                <strong>No Location Tracking or History</strong>
                <p>Your location is processed ephemerally on your device. We do NOT record your location history, do NOT track your background movements, and do NOT transmit your persistent location to any advertising network.</p>
              </div>
            </div>

            <h4>
              <svg class="icon" viewBox="0 0 24 24"><path d="M12 22c1.1 0 2-.9 2-2h-4c0 1.1.89 2 2 2zm6-6v-5c0-3.07-1.64-5.64-4.5-6.32V4c0-.83-.67-1.5-1.5-1.5s-1.5.67-1.5 1.5v.68C7.63 5.36 6 7.92 6 11v5l-2 2v1h16v-1l-2-2z"/></svg>
              B. Push Notifications & Local Alerts
            </h4>
            <p>
              Ayatika uses local notifications to sound the Adhan and send prayer alerts directly from your device clock. If you opt into remote announcements, an anonymous device push token (APNs / Firebase Cloud Messaging) is assigned to deliver relevant spiritual reminders and app updates.
            </p>

            <h4>
              <svg class="icon" viewBox="0 0 24 24"><path d="M19 3H5c-1.1 0-2 .9-2 2v14c0 1.1.9 2 2 2h14c1.1 0 2-.9 2-2V5c0-1.1-.9-2-2-2zm-6 14H7v-2h6v2zm4-4H7v-2h10v2zm0-4H7V7h10v2z"/></svg>
              C. Zakat & Financial Input
            </h4>
            <p>
              When you utilize the Zakat Calculator to compute Nisab on gold, silver, savings, or investments, all numbers and calculations are processed <strong>100% locally</strong> on your device. No financial figures are ever transmitted to external servers.
            </p>
          </section>

          <!-- Section 3 -->
          <section id="section-apple-ios" class="policy-section">
            <div class="section-header">
              <div class="section-num">3</div>
              <h2 class="section-title">Apple iOS Specific Permissions & Disclosures</h2>
            </div>
            <p>
              In compliance with Apple iOS App Store guidelines, here is the transparent breakdown of the permissions Ayatika may request on your iPhone or iPad:
            </p>

            <div class="data-table-wrap">
              <table class="data-table">
                <thead>
                  <tr>
                    <th>iOS Permission Key</th>
                    <th>Purpose & Usage Description</th>
                    <th>Required / Optional</th>
                  </tr>
                </thead>
                <tbody>
                  <tr>
                    <td><code>NSLocationWhenInUseUsageDescription</code></td>
                    <td>Required to calculate precise prayer times, determine the accurate Qibla direction, and locate nearby mosques based on your current position.</td>
                    <td><span class="table-tag">Optional (Manual City fallback available)</span></td>
                  </tr>
                  <tr>
                    <td><code>UIBackgroundModes (remote-notification, fetch)</code></td>
                    <td>Enables the delivery of timely Adhan notifications and background prayer schedule synchronization.</td>
                    <td><span class="table-tag">Optional</span></td>
                  </tr>
                  <tr>
                    <td><code>Device Motion & Compass Sensors</code></td>
                    <td>Accesses magnetometer and gyroscope sensors locally on the device to point the Qibla compass in real-time.</td>
                    <td><span class="table-tag">Used Locally</span></td>
                  </tr>
                </tbody>
              </table>
            </div>

            <div class="callout success">
              <svg class="callout-icon" viewBox="0 0 24 24"><path d="M12 1L3 5v6c0 5.55 3.84 10.74 9 12 5.16-1.26 9-6.45 9-12V5l-9-4zm-2 16l-4-4 1.41-1.41L10 14.17l6.59-6.59L18 9l-8 8z"/></svg>
              <div class="callout-body">
                <strong>App Tracking Transparency (ATT)</strong>
                <p>Ayatika contains zero cross-app ad tracking trackers. Therefore, we do not prompt you for Apple's App Tracking Transparency permission because tracking is strictly absent from our architecture.</p>
              </div>
            </div>
          </section>

          <!-- Section 4 -->
          <section id="section-storage" class="policy-section">
            <div class="section-header">
              <div class="section-num">4</div>
              <h2 class="section-title">Offline & Local Data Storage</h2>
            </div>
            <p>
              Ayatika is architected with an <strong>offline-first philosophy</strong>. The following user preferences are stored securely in local device sandbox storage (using <code>SharedPreferences</code> and <code>SQLite</code>):
            </p>
            <ul class="feature-list">
              <li>
                <svg class="check-icon" viewBox="0 0 24 24"><path d="M12 2C6.48 2 2 6.48 2 12s4.48 10 10 10 10-4.48 10-10S17.52 2 12 2zm-2 15l-5-5 1.41-1.41L10 14.17l7.59-7.59L19 8l-9 9z"/></svg>
                <span>Holy Quran reading bookmarks, favorite surahs, and last-read ayah positions.</span>
              </li>
              <li>
                <svg class="check-icon" viewBox="0 0 24 24"><path d="M12 2C6.48 2 2 6.48 2 12s4.48 10 10 10 10-4.48 10-10S17.52 2 12 2zm-2 15l-5-5 1.41-1.41L10 14.17l7.59-7.59L19 8l-9 9z"/></svg>
                <span>Personal Tasbih & Dhikr counters and target milestones.</span>
              </li>
              <li>
                <svg class="check-icon" viewBox="0 0 24 24"><path d="M12 2C6.48 2 2 6.48 2 12s4.48 10 10 10 10-4.48 10-10S17.52 2 12 2zm-2 15l-5-5 1.41-1.41L10 14.17l7.59-7.59L19 8l-9 9z"/></svg>
                <span>App theme preferences (Dark Mode / Light Mode) and selected language (English / Arabic).</span>
              </li>
              <li>
                <svg class="check-icon" viewBox="0 0 24 24"><path d="M12 2C6.48 2 2 6.48 2 12s4.48 10 10 10 10-4.48 10-10S17.52 2 12 2zm-2 15l-5-5 1.41-1.41L10 14.17l7.59-7.59L19 8l-9 9z"/></svg>
                <span>Custom prayer calculation methods, Juristic school (Shafi / Hanafi), and adhan audio choices.</span>
              </li>
            </ul>
            <p>
              This local data is never sent to our servers. If you delete the app or clear app data in iOS Settings, this local data is immediately deleted.
            </p>
          </section>

          <!-- Section 5 -->
          <section id="section-third-parties" class="policy-section">
            <div class="section-header">
              <div class="section-num">5</div>
              <h2 class="section-title">Third-Party Services & APIs</h2>
            </div>
            <p>
              To provide Quranic recitations, Hadith collections, and Islamic library resources, Ayatika connects to vetted, public Islamic and utility APIs via encrypted HTTPS connections:
            </p>

            <div class="data-table-wrap">
              <table class="data-table">
                <thead>
                  <tr>
                    <th>Service / API Provider</th>
                    <th>Data Exchanged</th>
                    <th>Privacy & Usage Policy</th>
                  </tr>
                </thead>
                <tbody>
                  <tr>
                    <td><strong>Islamic API & Quran APIs</strong><br><small>quranapi.pages.dev / alquran-api</small></td>
                    <td>Fetches Quranic text, recitations, translations, and tafsir.</td>
                    <td>Non-identifiable content requests.</td>
                  </tr>
                  <tr>
                    <td><strong>Hadith API</strong><br><small>hadithapi.com</small></td>
                    <td>Retrieves verified prophetic hadiths and chapter categorizations.</td>
                    <td>Content delivery only.</td>
                  </tr>
                  <tr>
                    <td><strong>IslamHouse API</strong><br><small>api3.islamhouse.com</small></td>
                    <td>Provides Islamic articles, books, and educational resources.</td>
                    <td>Public knowledge library.</td>
                  </tr>
                  <tr>
                    <td><strong>OpenStreetMap / Reverse Geocoding</strong></td>
                    <td>Coordinates sent securely to resolve city name and display local mosques.</td>
                    <td>No user identity linked.</td>
                  </tr>
                  <tr>
                    <td><strong>Apple APNs & Google Firebase Cloud Messaging</strong></td>
                    <td>Anonymous device push token for delivering notifications.</td>
                    <td>Encrypted transmission compliant with Apple & Google terms.</td>
                  </tr>
                </tbody>
              </table>
            </div>
          </section>

          <!-- Section 6 -->
          <section id="section-children" class="policy-section">
            <div class="section-header">
              <div class="section-num">6</div>
              <h2 class="section-title">Children's Privacy Protection (COPPA)</h2>
            </div>
            <p>
              Ayatika is a family-friendly educational and spiritual app appropriate for users of all ages, including children under the age of 13.
            </p>
            <p>
              We comply with the <strong>Children's Online Privacy Protection Act (COPPA)</strong> and global child safety frameworks:
            </p>
            <ul class="feature-list">
              <li>
                <svg class="check-icon" viewBox="0 0 24 24"><path d="M12 2C6.48 2 2 6.48 2 12s4.48 10 10 10 10-4.48 10-10S17.52 2 12 2zm-2 15l-5-5 1.41-1.41L10 14.17l7.59-7.59L19 8l-9 9z"/></svg>
                <span>We do NOT collect personally identifiable information (PII) from children.</span>
              </li>
              <li>
                <svg class="check-icon" viewBox="0 0 24 24"><path d="M12 2C6.48 2 2 6.48 2 12s4.48 10 10 10 10-4.48 10-10S17.52 2 12 2zm-2 15l-5-5 1.41-1.41L10 14.17l7.59-7.59L19 8l-9 9z"/></svg>
                <span>We do NOT contain behavioural tracking or targeted advertisements.</span>
              </li>
              <li>
                <svg class="check-icon" viewBox="0 0 24 24"><path d="M12 2C6.48 2 2 6.48 2 12s4.48 10 10 10 10-4.48 10-10S17.52 2 12 2zm-2 15l-5-5 1.41-1.41L10 14.17l7.59-7.59L19 8l-9 9z"/></svg>
                <span>All Quran, Hadith, and Islamic content is curated, safe, and family-oriented.</span>
              </li>
            </ul>
          </section>

          <!-- Section 7 -->
          <section id="section-gdpr-ccpa" class="policy-section">
            <div class="section-header">
              <div class="section-num">7</div>
              <h2 class="section-title">Your Rights (GDPR & CCPA/CPRA Compliance)</h2>
            </div>
            <p>
              Regardless of your geographical location, we extend full privacy rights to all users:
            </p>
            <ul class="feature-list">
              <li>
                <svg class="check-icon" viewBox="0 0 24 24"><path d="M12 2C6.48 2 2 6.48 2 12s4.48 10 10 10 10-4.48 10-10S17.52 2 12 2zm-2 15l-5-5 1.41-1.41L10 14.17l7.59-7.59L19 8l-9 9z"/></svg>
                <span><strong>Right to Access & Portability:</strong> Since all your user data (bookmarks, tasbih counts) is stored locally on your device, you have direct, unhindered access at all times.</span>
              </li>
              <li>
                <svg class="check-icon" viewBox="0 0 24 24"><path d="M12 2C6.48 2 2 6.48 2 12s4.48 10 10 10 10-4.48 10-10S17.52 2 12 2zm-2 15l-5-5 1.41-1.41L10 14.17l7.59-7.59L19 8l-9 9z"/></svg>
                <span><strong>Right to Erasure (Deletion):</strong> You can erase all app data instantly by clearing cache or deleting Ayatika from your device.</span>
              </li>
              <li>
                <svg class="check-icon" viewBox="0 0 24 24"><path d="M12 2C6.48 2 2 6.48 2 12s4.48 10 10 10 10-4.48 10-10S17.52 2 12 2zm-2 15l-5-5 1.41-1.41L10 14.17l7.59-7.59L19 8l-9 9z"/></svg>
                <span><strong>Right to Revoke Consent:</strong> You can revoke location and notification permissions at any time via <em>iOS Settings &gt; Ayatika</em>.</span>
              </li>
              <li>
                <svg class="check-icon" viewBox="0 0 24 24"><path d="M12 2C6.48 2 2 6.48 2 12s4.48 10 10 10 10-4.48 10-10S17.52 2 12 2zm-2 15l-5-5 1.41-1.41L10 14.17l7.59-7.59L19 8l-9 9z"/></svg>
                <span><strong>"Do Not Sell My Personal Information":</strong> We do not sell personal data under CCPA/CPRA definitions.</span>
              </li>
            </ul>
          </section>

          <!-- Section 8 -->
          <section id="section-retention" class="policy-section">
            <div class="section-header">
              <div class="section-num">8</div>
              <h2 class="section-title">Data Retention & Security</h2>
            </div>
            <p>
              We do not maintain remote user accounts or persistent databases containing user identities. All network requests are encrypted using industry-standard <strong>Transport Layer Security (TLS 1.2/1.3)</strong>.
            </p>
            <p>
              Any ephemeral server logs maintained for API uptime monitoring are automatically cycled and deleted within standard operational windows (typically 30 days or less).
            </p>
          </section>

          <!-- Section 9 -->
          <section id="section-changes" class="policy-section">
            <div class="section-header">
              <div class="section-num">9</div>
              <h2 class="section-title">Changes to This Privacy Policy</h2>
            </div>
            <p>
              We may update our Privacy Policy periodically to reflect new app features, legal requirements, or Apple guideline updates. When revisions occur, we will update the "Effective Date" at the top of this document. Continued use of Ayatika following updates signifies your acceptance of the updated terms.
            </p>
          </section>

          <!-- Section 10 -->
          <section id="section-contact" class="policy-section">
            <div class="section-header">
              <div class="section-num">10</div>
              <h2 class="section-title">Contact Information & Support</h2>
            </div>
            <p>
              If you have any questions, suggestions, or privacy requests regarding Ayatika or this Privacy Policy, please contact our development team:
            </p>

            <div class="contact-card">
              <h4>
                <svg class="icon icon-lg" viewBox="0 0 24 24"><path d="M2.01 21L23 12 2.01 3 2 10l15 2-15 2z"/></svg>
                Contact Ayatika Team
              </h4>
              <p>We are dedicated to maintaining the highest ethical and privacy standards for the global Muslim community.</p>
              <a href="mailto:support@elmaallem.com?subject=Ayatika%20Privacy%20Inquiry" class="contact-btn">
                <svg class="icon" viewBox="0 0 24 24"><path d="M20 4H4c-1.1 0-1.99.9-1.99 2L2 18c0 1.1.9 2 2 2h16c1.1 0 2-.9 2-2V6c0-1.1-.9-2-2-2zm0 4l-8 5-8-5V6l8 5 8-5v2z"/></svg>
                Email: support@elmaallem.com
              </a>
              <p style="margin-top: 16px; font-size: 0.85rem; color: var(--text-muted);">
                Website: <span style="color: var(--accent-gold);">https://ayatika.elmaallem.com</span>
              </p>
            </div>
          </section>

        </div>

        <!-- ======================================================== -->
        <!-- ARABIC LANGUAGE VERSION (العربية) -->
        <!-- ======================================================== -->
        <div id="content-ar" class="lang-content" dir="rtl">
          
          <!-- Section 1 (AR) -->
          <section id="section-overview-ar" class="policy-section">
            <div class="section-header">
              <div class="section-num">١</div>
              <h2 class="section-title">نظرة عامة والتزامنا بالخصوصية</h2>
            </div>
            <p>
              مرحباً بكم في تطبيق <strong>آياتك (Ayatika)</strong>، المطوّر بواسطة <strong>المعلم (Elmaallem)</strong>. نحن ندرك قدسية عبادتكم وأهمية حماية خصوصيتكم الرقمية إلى أقصى درجة.
            </p>
            <p>
              توضح سياسة الخصوصية هذه كيفية تعامل تطبيق آياتك مع البيانات بما يتوافق تماماً مع <strong>إرشادات متجر تطبيقات أبل (Apple App Store Review Guidelines - البند 5.1 الخاص بالخصوصية)</strong>، واللائحة العامة لحماية البيانات (<strong>GDPR</strong>)، وقانون خصوصية المستهلك في كاليفورنيا (<strong>CCPA</strong>).
            </p>
            
            <div class="callout gold">
              <svg class="callout-icon" viewBox="0 0 24 24"><path d="M12 1L3 5v6c0 5.55 3.84 10.74 9 12 5.16-1.26 9-6.45 9-12V5l-9-4zm-2 16l-4-4 1.41-1.41L10 14.17l6.59-6.59L18 9l-8 8z"/></svg>
              <div class="callout-body">
                <strong>عهدنا الدائم بحماية خصوصيتك</strong>
                <p>تطبيق آياتك لا يبيع، ولا يؤجر، ولا يشارك أي بيانات تخصك مع شركات الإعلانات أو أطراف خارجية. لا نقوم بتتبعك ولا ننشئ أي ملفات تعريفية عن عباداتك.</p>
              </div>
            </div>
          </section>

          <!-- Section 2 (AR) -->
          <section id="section-collection-ar" class="policy-section">
            <div class="section-header">
              <div class="section-num">٢</div>
              <h2 class="section-title">البيانات التي نتعامل معها وكيفية استخدامها</h2>
            </div>
            <p>
              تم تصميم تطبيق آياتك وفق مبدأ <em>تقليل البيانات إلى الحد الأدنى</em>. نطلب فقط ما هو ضروري لتقديم الخدمات الدينية بدقة:
            </p>

            <h4>
              <svg class="icon" viewBox="0 0 24 24"><path d="M12 2C8.13 2 5 5.13 5 9c0 5.25 7 13 7 13s7-7.75 7-13c0-3.87-3.13-7-7-7zm0 9.5c-1.38 0-2.5-1.12-2.5-2.5s1.12-2.5 2.5-2.5 2.5 1.12 2.5 2.5-1.12 2.5-2.5 2.5z"/></svg>
              أ. بيانات الموقع الجغرافي (أثناء استخدام التطبيق فقط)
            </h4>
            <p>
              عند منح إذن الموقع، يصل التطبيق إلى إحداثيات جهازك (خطوط الطول والعرض) لغايات محددة فقط:
            </p>
            <ul class="feature-list">
              <li>
                <svg class="check-icon" viewBox="0 0 24 24"><path d="M12 2C6.48 2 2 6.48 2 12s4.48 10 10 10 10-4.48 10-10S17.52 2 12 2zm-2 15l-5-5 1.41-1.41L10 14.17l7.59-7.59L19 8l-9 9z"/></svg>
                <span><strong>حساب مواقيت الصلاة بدقة:</strong> لحساب أوقات الفجر، الشروق، الظهر، العصر، المغرب، والعشاء فلكياً وفقاً لموقعك الدقيق وطريقة الحساب المختارة (مثل رابطة العالم الإسلامي، أم القرى، الهيئة المصرية).</span>
              </li>
              <li>
                <svg class="check-icon" viewBox="0 0 24 24"><path d="M12 2C6.48 2 2 6.48 2 12s4.48 10 10 10 10-4.48 10-10S17.52 2 12 2zm-2 15l-5-5 1.41-1.41L10 14.17l7.59-7.59L19 8l-9 9z"/></svg>
                <span><strong>تحديد اتجاه القبلة:</strong> لحساب الزاوية المباشرة نحو الكعبة المشرفة في مكة المكرمة بالاعتماد على بوصلة جهازك.</span>
              </li>
              <li>
                <svg class="check-icon" viewBox="0 0 24 24"><path d="M12 2C6.48 2 2 6.48 2 12s4.48 10 10 10 10-4.48 10-10S17.52 2 12 2zm-2 15l-5-5 1.41-1.41L10 14.17l7.59-7.59L19 8l-9 9z"/></svg>
                <span><strong>المساجد القريبة:</strong> لعرض المساجد المحيطة بك على الخريطة.</span>
              </li>
              <li>
                <svg class="check-icon" viewBox="0 0 24 24"><path d="M12 2C6.48 2 2 6.48 2 12s4.48 10 10 10 10-4.48 10-10S17.52 2 12 2zm-2 15l-5-5 1.41-1.41L10 14.17l7.59-7.59L19 8l-9 9z"/></svg>
                <span><strong>اسم المدينة:</strong> لعرض اسم مدينتك وبلدك (مثل "الدار البيضاء، المغرب") على الواجهة الرئيسية.</span>
              </li>
            </ul>

            <div class="callout info">
              <svg class="callout-icon" viewBox="0 0 24 24"><path d="M12 2C6.48 2 2 6.48 2 12s4.48 10 10 10 10-4.48 10-10S17.52 2 12 2zm1 15h-2v-6h2v6zm0-8h-2V7h2v2z"/></svg>
              <div class="callout-body">
                <strong>معالجة فورية بدون تخزين أو تتبع</strong>
                <p>تتم معالجة بيانات الموقع محلياً على جهازك بشكل فوري. نحن لا نسجل تحركاتك السابقة، ولا نتتبع موقعك في الخلفية، ولا نرسل موقعك لأي جهة إعلانية.</p>
              </div>
            </div>

            <h4>
              <svg class="icon" viewBox="0 0 24 24"><path d="M12 22c1.1 0 2-.9 2-2h-4c0 1.1.89 2 2 2zm6-6v-5c0-3.07-1.64-5.64-4.5-6.32V4c0-.83-.67-1.5-1.5-1.5s-1.5.67-1.5 1.5v.68C7.63 5.36 6 7.92 6 11v5l-2 2v1h16v-1l-2-2z"/></svg>
              ب. الإشعارات وتنبيهات الأذان
            </h4>
            <p>
              يستخدم التطبيق الإشعارات المحلية لرفع الأذان والتنبيه بدخول وقت الصلاة مباشرة من ساعة جهازك. في حال تفعيل الإشعارات العامة، يتم استخدام معرف جهاز مجهول الهوية (APNs / Firebase) لإرسال التذكيرات والتحديثات المهمة.
            </p>

            <h4>
              <svg class="icon" viewBox="0 0 24 24"><path d="M19 3H5c-1.1 0-2 .9-2 2v14c0 1.1.9 2 2 2h14c1.1 0 2-.9 2-2V5c0-1.1-.9-2-2-2zm-6 14H7v-2h6v2zm4-4H7v-2h10v2zm0-4H7V7h10v2z"/></svg>
              ج. حاسبة الزكاة والأرقام المالية
            </h4>
            <p>
              عند استخدام حاسبة الزكاة لحساب النصاب على الذهب والفضة والمدخرات، تتم جميع العمليات الحسابية <strong>محلياً بنسبة 100%</strong> داخل جهازك، ولا يتم إرسال أي أرقام مالية لأي خوادم خارجية.
            </p>
          </section>

          <!-- Section 3 (AR) -->
          <section id="section-apple-ios-ar" class="policy-section">
            <div class="section-header">
              <div class="section-num">٣</div>
              <h2 class="section-title">أذونات نظام iOS ومتطلبات متجر أبل</h2>
            </div>
            <p>
              امتثالاً لمعايير وإرشادات متجر تطبيقات أبل (App Store)، إليك تفاصيل الأذونات التي قد يطلبها تطبيق آياتك:
            </p>

            <div class="data-table-wrap">
              <table class="data-table">
                <thead>
                  <tr>
                    <th>مفتاح الإذن في iOS</th>
                    <th>الغرض ووصف الاستخدام</th>
                    <th>طبيعة الإذن</th>
                  </tr>
                </thead>
                <tbody>
                  <tr>
                    <td><code>NSLocationWhenInUseUsageDescription</code></td>
                    <td>مطلوب لحساب مواقيت الصلاة الدقيقة، وتحديد اتجاه القبلة، واستكشاف المساجد القريبة استناداً إلى موقعك الحالي.</td>
                    <td><span class="table-tag">اختياري (يمكن اختيار المدينة يدوياً)</span></td>
                  </tr>
                  <tr>
                    <td><code>UIBackgroundModes (الإشعارات والجلب)</code></td>
                    <td>لتشغيل تنبيهات الأذان في موعدها وتحديث جدول الصلاة في الخلفية.</td>
                    <td><span class="table-tag">اختياري</span></td>
                  </tr>
                  <tr>
                    <td><code>حساسات البوصلة والحركة</code></td>
                    <td>الوصول لحساس البوصلة المدمج في الهاتف لتوجيه مؤشر القبلة بشكل حي.</td>
                    <td><span class="table-tag">معالجة محلية بالكامل</span></td>
                  </tr>
                </tbody>
              </table>
            </div>

            <div class="callout success">
              <svg class="callout-icon" viewBox="0 0 24 24"><path d="M12 1L3 5v6c0 5.55 3.84 10.74 9 12 5.16-1.26 9-6.45 9-12V5l-9-4zm-2 16l-4-4 1.41-1.41L10 14.17l6.59-6.59L18 9l-8 8z"/></svg>
              <div class="callout-body">
                <strong>عدم وجود أي تتبع إعلاني (No App Tracking)</strong>
                <p>تطبيق آياتك خالٍ تماماً من أي أدوات تتبع إعلاني عبر التطبيقات، ولذلك لا يطلب التطبيق إذن شفافية تتبع التطبيقات (ATT) لعدم وجود أي تتبع أصلاً.</p>
              </div>
            </div>
          </section>

          <!-- Section 4 (AR) -->
          <section id="section-storage-ar" class="policy-section">
            <div class="section-header">
              <div class="section-num">٤</div>
              <h2 class="section-title">التخزين المحلي والعمل دون إنترنت</h2>
            </div>
            <p>
              يعمل التطبيق بفلسفة <strong>التشغيل الذاتي دون إنترنت (Offline-First)</strong>. يتم تخزين البيانات التالية محلياً داخل المساحة الآمنة لجهازك فقط:
            </p>
            <ul class="feature-list">
              <li>
                <svg class="check-icon" viewBox="0 0 24 24"><path d="M12 2C6.48 2 2 6.48 2 12s4.48 10 10 10 10-4.48 10-10S17.52 2 12 2zm-2 15l-5-5 1.41-1.41L10 14.17l7.59-7.59L19 8l-9 9z"/></svg>
                <span>العلامات المرجعية للقراءة في المصحف الشريف، والسور المفضلة، وآخر آية تم الوقوف عندها.</span>
              </li>
              <li>
                <svg class="check-icon" viewBox="0 0 24 24"><path d="M12 2C6.48 2 2 6.48 2 12s4.48 10 10 10 10-4.48 10-10S17.52 2 12 2zm-2 15l-5-5 1.41-1.41L10 14.17l7.59-7.59L19 8l-9 9z"/></svg>
                <span>عدادات التسبيح والأذكار اليومية والأهداف المكتملة.</span>
              </li>
              <li>
                <svg class="check-icon" viewBox="0 0 24 24"><path d="M12 2C6.48 2 2 6.48 2 12s4.48 10 10 10 10-4.48 10-10S17.52 2 12 2zm-2 15l-5-5 1.41-1.41L10 14.17l7.59-7.59L19 8l-9 9z"/></svg>
                <span>تفضيلات المظهر (الوضع الليلي / النهاري) واللغة المختارة (العربية / الإنجليزية).</span>
              </li>
              <li>
                <svg class="check-icon" viewBox="0 0 24 24"><path d="M12 2C6.48 2 2 6.48 2 12s4.48 10 10 10 10-4.48 10-10S17.52 2 12 2zm-2 15l-5-5 1.41-1.41L10 14.17l7.59-7.59L19 8l-9 9z"/></svg>
                <span>طريقة الحساب المعتمدة والمذهب الفقهي (الشافعي / الحنفي) وصوت المؤذن المفضل.</span>
              </li>
            </ul>
            <p>
              هذه البيانات ملكك وحدك ولا تُرفع إلى خوادمنا. عند حذف التطبيق، يتم مسح هذه البيانات من جهازك فوراً.
            </p>
          </section>

          <!-- Section 5 (AR) -->
          <section id="section-third-parties-ar" class="policy-section">
            <div class="section-header">
              <div class="section-num">٥</div>
              <h2 class="section-title">الخدمات الخارجية والواجهات البرمجية (APIs)</h2>
            </div>
            <p>
              لتوفير التلاوات القرآنية، والأحاديث النبوية، ومكتبة الكتب الإسلامية، يتصل التطبيق بمصادر إسلامية موثوقة عبر قنوات مشفرة آمنة (HTTPS):
            </p>

            <div class="data-table-wrap">
              <table class="data-table">
                <thead>
                  <tr>
                    <th>الخدمة / مزود الواجهة البرمجية</th>
                    <th>البيانات المتبادلة</th>
                    <th>سياسة الاستخدام</th>
                  </tr>
                </thead>
                <tbody>
                  <tr>
                    <td><strong>واجهات القرآن الكريم والتلاوات</strong><br><small>quranapi.pages.dev / alquran-api</small></td>
                    <td>جلب نصوص الآيات، التلاوات الصوتية، والتفاسير.</td>
                    <td>طلبات محتوى عامة بدون أي هوية شخصية.</td>
                  </tr>
                  <tr>
                    <td><strong>واجهة الحديث النبوي الشريف</strong><br><small>hadithapi.com</small></td>
                    <td>جلب الأحاديث الصحيحة وشروحاتها.</td>
                    <td>توفير المحتوى الديني فقط.</td>
                  </tr>
                  <tr>
                    <td><strong>موقع دار الإسلام (IslamHouse)</strong><br><small>api3.islamhouse.com</small></td>
                    <td>توفير الكتب والمقالات والمكتبة الإسلامية.</td>
                    <td>مكتبة معرفية مجانية عامة.</td>
                  </tr>
                  <tr>
                    <td><strong>خرائط OpenStreetMap وتحديد المدن</strong></td>
                    <td>إرسال الإحداثيات لمعرفة اسم المدينة وعرض المساجد.</td>
                    <td>لا يتم ربطها بهوية المستخدم.</td>
                  </tr>
                  <tr>
                    <td><strong>خدمة إشعارات أبل (APNs) و Firebase</strong></td>
                    <td>رمز جهاز مجهول لإيصال التنبيهات والأذكار.</td>
                    <td>قنوات مشفرة وفق معايير أبل وجوجل.</td>
                  </tr>
                </tbody>
              </table>
            </div>
          </section>

          <!-- Section 6 (AR) -->
          <section id="section-children-ar" class="policy-section">
            <div class="section-header">
              <div class="section-num">٦</div>
              <h2 class="section-title">حماية خصوصية الأطفال (COPPA)</h2>
            </div>
            <p>
              تطبيق آياتك هو تطبيق ديني وتعليمي آمن تماماً لجميع أفراد الأسرة، ومناسب لجميع الفئات العمرية بما فيها الأطفال دون سن 13 عاماً.
            </p>
            <p>
              نحن نلتزم التزاماً كاملاً بقانون حماية خصوصية الأطفال على الإنترنت (COPPA):
            </p>
            <ul class="feature-list">
              <li>
                <svg class="check-icon" viewBox="0 0 24 24"><path d="M12 2C6.48 2 2 6.48 2 12s4.48 10 10 10 10-4.48 10-10S17.52 2 12 2zm-2 15l-5-5 1.41-1.41L10 14.17l7.59-7.59L19 8l-9 9z"/></svg>
                <span>لا نجمع أي بيانات تعريفية شخصية من الأطفال إطلاقاً.</span>
              </li>
              <li>
                <svg class="check-icon" viewBox="0 0 24 24"><path d="M12 2C6.48 2 2 6.48 2 12s4.48 10 10 10 10-4.48 10-10S17.52 2 12 2zm-2 15l-5-5 1.41-1.41L10 14.17l7.59-7.59L19 8l-9 9z"/></svg>
                <span>لا يحتوي التطبيق على إعلانات تجارية أو تتبع سلوكي.</span>
              </li>
              <li>
                <svg class="check-icon" viewBox="0 0 24 24"><path d="M12 2C6.48 2 2 6.48 2 12s4.48 10 10 10 10-4.48 10-10S17.52 2 12 2zm-2 15l-5-5 1.41-1.41L10 14.17l7.59-7.59L19 8l-9 9z"/></svg>
                <span>جميع المواد والمحتويات القرآنية والدينية مراجعة ومناسبة للأسرة والناشئة.</span>
              </li>
            </ul>
          </section>

          <!-- Section 7 (AR) -->
          <section id="section-gdpr-ccpa-ar" class="policy-section">
            <div class="section-header">
              <div class="section-num">٧</div>
              <h2 class="section-title">حقوقك القانونية (GDPR & CCPA)</h2>
            </div>
            <p>
              أينما كنت في العالم، نضمن لك كامل الحقوق المتعلقة بالخصوصية:
            </p>
            <ul class="feature-list">
              <li>
                <svg class="check-icon" viewBox="0 0 24 24"><path d="M12 2C6.48 2 2 6.48 2 12s4.48 10 10 10 10-4.48 10-10S17.52 2 12 2zm-2 15l-5-5 1.41-1.41L10 14.17l7.59-7.59L19 8l-9 9z"/></svg>
                <span><strong>حق الوصول والتحكم:</strong> جميع بياناتك مخزنة على جهازك ويمكنك إدارتها مباشرة بكل حرية.</span>
              </li>
              <li>
                <svg class="check-icon" viewBox="0 0 24 24"><path d="M12 2C6.48 2 2 6.48 2 12s4.48 10 10 10 10-4.48 10-10S17.52 2 12 2zm-2 15l-5-5 1.41-1.41L10 14.17l7.59-7.59L19 8l-9 9z"/></svg>
                <span><strong>حق المسح والحذف:</strong> يمكنك حذف كل بياناتك بنقرة واحدة بمجرد حذف التطبيق أو مسح بياناته من إعدادات الهاتف.</span>
              </li>
              <li>
                <svg class="check-icon" viewBox="0 0 24 24"><path d="M12 2C6.48 2 2 6.48 2 12s4.48 10 10 10 10-4.48 10-10S17.52 2 12 2zm-2 15l-5-5 1.41-1.41L10 14.17l7.59-7.59L19 8l-9 9z"/></svg>
                <span><strong>حق إلغاء الأذونات:</strong> يمكنك في أي وقت إيقاف إذن الموقع أو الإشعارات عبر <em>إعدادات iOS &gt; آياتك</em>.</span>
              </li>
              <li>
                <svg class="check-icon" viewBox="0 0 24 24"><path d="M12 2C6.48 2 2 6.48 2 12s4.48 10 10 10 10-4.48 10-10S17.52 2 12 2zm-2 15l-5-5 1.41-1.41L10 14.17l7.59-7.59L19 8l-9 9z"/></svg>
                <span><strong>عدم بيع البيانات:</strong> نلتزم بعدم بيع أو مقايضة أي بيانات تحت أي ظرف.</span>
              </li>
            </ul>
          </section>

          <!-- Section 8 (AR) -->
          <section id="section-retention-ar" class="policy-section">
            <div class="section-header">
              <div class="section-num">٨</div>
              <h2 class="section-title">أمن البيانات والاحتفاظ بها</h2>
            </div>
            <p>
              نحن لا نحتفظ بأي قواعد بيانات مركزية لحسابات المستخدمين. يتم تأمين جميع الاتصالات الشبكية بواسطة أحدث بروتوكولات التشفير القياسية <strong>(TLS 1.2 / TLS 1.3)</strong> لضمان حماية اتصالك من أي تنصت أو تلاعب.
            </p>
          </section>

          <!-- Section 9 (AR) -->
          <section id="section-changes-ar" class="policy-section">
            <div class="section-header">
              <div class="section-num">٩</div>
              <h2 class="section-title">تحديثات سياسة الخصوصية</h2>
            </div>
            <p>
              قد نقوم بتحديث هذه السياسة من وقت لآخر لمواكبة التحديثات البرمجية أو المتطلبات القانونية لمتجر أبل. عند إجراء أي تعديل، سيتم تحديث تاريخ السريان أعلى الصفحة. استمرارك في استخدام التطبيق يعتبر موافقة على السياسة المحدثة.
            </p>
          </section>

          <!-- Section 10 (AR) -->
          <section id="section-contact-ar" class="policy-section">
            <div class="section-header">
              <div class="section-num">١٠</div>
              <h2 class="section-title">معلومات الاتصال والدعم</h2>
            </div>
            <p>
              إذا كانت لديك أي استفسارات أو ملاحظات أو طلبات تتعلق بخصوصيتك في تطبيق آياتك، يسعدنا تواصلكم المباشر مع فريق التطوير:
            </p>

            <div class="contact-card">
              <h4>
                <svg class="icon icon-lg" viewBox="0 0 24 24"><path d="M2.01 21L23 12 2.01 3 2 10l15 2-15 2z"/></svg>
                تواصل مع فريق تطبيق آياتك
              </h4>
              <p>نحن حريصون على تقديم أفضل تجربة إسلامية رقمية مع أقصى درجات الأمان والشفافية.</p>
              <a href="mailto:support@elmaallem.com?subject=استفسار%20عن%20خصوصية%20تطبيق%20آياتك" class="contact-btn">
                <svg class="icon" viewBox="0 0 24 24"><path d="M20 4H4c-1.1 0-1.99.9-1.99 2L2 18c0 1.1.9 2 2 2h16c1.1 0 2-.9 2-2V6c0-1.1-.9-2-2-2zm0 4l-8 5-8-5V6l8 5 8-5v2z"/></svg>
                البريد الإلكتروني: support@elmaallem.com
              </a>
              <p style="margin-top: 16px; font-size: 0.85rem; color: var(--text-muted);">
                الموقع الرسمي: <span style="color: var(--accent-gold);">https://ayatika.elmaallem.com</span>
              </p>
            </div>
          </section>

        </div>

      </article>
    </div>
  </main>

  <!-- Site Footer -->
  <footer class="site-footer">
    <div class="container">
      <div class="footer-links">
        <a href="#section-overview">
          <svg class="icon" viewBox="0 0 24 24"><path d="M10 20v-6h4v6h5v-8h3L12 3 2 12h3v8z"/></svg>
          Home
        </a>
        <a href="#section-overview">
          <svg class="icon" viewBox="0 0 24 24"><path d="M12 1L3 5v6c0 5.55 3.84 10.74 9 12 5.16-1.26 9-6.45 9-12V5l-9-4zm-2 16l-4-4 1.41-1.41L10 14.17l6.59-6.59L18 9l-8 8z"/></svg>
          Privacy Policy
        </a>
        <a href="mailto:support@elmaallem.com">
          <svg class="icon" viewBox="0 0 24 24"><path d="M20 4H4c-1.1 0-1.99.9-1.99 2L2 18c0 1.1.9 2 2 2h16c1.1 0 2-.9 2-2V6c0-1.1-.9-2-2-2zm0 4l-8 5-8-5V6l8 5 8-5v2z"/></svg>
          Support
        </a>
      </div>
      <p>© 2026 Ayatika (آياتك). All rights reserved. Developed with care by Elmaallem.</p>
      <p style="margin-top: 6px; font-size: 0.78rem; opacity: 0.7;">Designed for Apple iOS App Store Review Guidelines & Global Privacy Standards.</p>
    </div>
  </footer>

  <!-- Script for Language & Theme Switching & Scrollspy -->
  <script>
    // Theme Switcher
    function toggleTheme() {
      const html = document.documentElement;
      const currentTheme = html.getAttribute('data-theme');
      const newTheme = currentTheme === 'light' ? 'dark' : 'light';
      
      html.setAttribute('data-theme', newTheme);
      localStorage.setItem('ayatika_theme', newTheme);
      updateThemeIcon(newTheme);
    }

    function updateThemeIcon(theme) {
      const wrap = document.getElementById('theme-icon-wrap');
      if (!wrap) return;
      if (theme === 'light') {
        // Moon icon for switching to dark
        wrap.innerHTML = `<svg class="icon" viewBox="0 0 24 24"><path d="M12 3a9 9 0 1 0 9 9c0-.46-.04-.92-.1-1.36a5.389 5.389 0 0 1-4.4 2.26 5.403 5.403 0 0 1-3.14-9.8A9 9 0 0 0 12 3z"/></svg>`;
      } else {
        // Sun icon for switching to light
        wrap.innerHTML = `<svg class="icon" viewBox="0 0 24 24"><path d="M12 7c-2.76 0-5 2.24-5 5s2.24 5 5 5 5-2.24 5-5-2.24-5-5-5zM2 13h2c.55 0 1-.45 1-1s-.45-1-1-1H2c-.55 0-1 .45-1 1s.45 1 1 1zm18 0h2c.55 0 1-.45 1-1s-.45-1-1-1h-2c-.55 0-1 .45-1 1s.45 1 1 1zM11 2v2c0 .55.45 1 1 1s1-.45 1-1V2c0-.55-.45-1-1-1s-1 .45-1 1zm0 18v2c0 .55.45 1 1 1s1-.45 1-1v-2c0-.55-.45-1-1-1s-1 .45-1 1zM5.99 4.58a.996.996 0 0 0-1.41 0 .996.996 0 0 0 0 1.41l1.06 1.06c.39.39 1.03.39 1.41 0s.39-1.03 0-1.41L5.99 4.58zm12.37 12.37a.996.996 0 0 0-1.41 0 .996.996 0 0 0 0 1.41l1.06 1.06c.39.39 1.03.39 1.41 0s.39-1.03 0-1.41l-1.06-1.06zm1.06-10.96a.996.996 0 0 0 0-1.41.996.996 0 0 0-1.41 0l-1.06 1.06c-.39.39-.39 1.03 0 1.41s1.03.39 1.41 0l1.06-1.06zM7.05 18.36a.996.996 0 0 0 0-1.41.996.996 0 0 0-1.41 0l-1.06 1.06c-.39.39-.39 1.03 0 1.41s1.03.39 1.41 0l1.06-1.06z"/></svg>`;
      }
    }

    // Set Saved Theme on load
    (function initTheme() {
      const savedTheme = localStorage.getItem('ayatika_theme') || 'dark';
      document.documentElement.setAttribute('data-theme', savedTheme);
      updateThemeIcon(savedTheme);
    })();

    // Language Switcher
    function setLanguage(lang) {
      const html = document.documentElement;
      const btnEn = document.getElementById('btn-en');
      const btnAr = document.getElementById('btn-ar');
      const contentEn = document.getElementById('content-en');
      const contentAr = document.getElementById('content-ar');
      
      const badgeText = document.getElementById('badge-text');
      const heroTitle = document.getElementById('hero-title');
      const heroSubtitle = document.getElementById('hero-subtitle');
      const tocHeading = document.getElementById('toc-heading');
      
      // Nutrition labels
      const n1Title = document.getElementById('nutri-1-title');
      const n1Desc = document.getElementById('nutri-1-desc');
      const n1Badge = document.getElementById('nutri-1-badge');
      
      const n2Title = document.getElementById('nutri-2-title');
      const n2Desc = document.getElementById('nutri-2-desc');
      const n2Badge = document.getElementById('nutri-2-badge');
      
      const n3Title = document.getElementById('nutri-3-title');
      const n3Desc = document.getElementById('nutri-3-desc');
      const n3Badge = document.getElementById('nutri-3-badge');
      
      const n4Title = document.getElementById('nutri-4-title');
      const n4Desc = document.getElementById('nutri-4-desc');
      const n4Badge = document.getElementById('nutri-4-badge');

      if (lang === 'ar') {
        html.setAttribute('lang', 'ar');
        html.setAttribute('dir', 'rtl');
        btnAr.classList.add('active');
        btnEn.classList.remove('active');
        contentAr.classList.add('active-lang');
        contentEn.classList.remove('active-lang');
        
        badgeText.innerText = 'وثيقة سياسة خصوصية متوافقة مع معايير متجر أبل';
        heroTitle.innerHTML = 'سياسة الخصوصية و<span>حماية البيانات</span>';
        heroSubtitle.innerText = 'رحلتك الإيمانية مقدسة وخاصة بك. تم بناء تطبيق آياتك على أسس صارمة لحماية الخصوصية: لا نبيع بياناتك، ولا نتتبعك، وتتم جميع الحسابات محلياً على هاتفك.';
        tocHeading.innerText = 'فهرس المحتويات';

        n1Title.innerText = 'بدون أي تتبع';
        n1Desc.innerText = 'لا نستخدم المعرف الإعلاني (IDFA) ولا نتتبع نشاطك عبر التطبيقات أو المواقع الأخرى.';
        n1Badge.innerText = 'البيانات المستخدمة للتتبع: صفر';

        n2Title.innerText = 'بدون تسجيل حساب';
        n2Desc.innerText = 'يعمل تطبيق آياتك بحرية تامة دون إجبار على إنشاء حساب. كل مفضلاتك وأذكارك تبقى بجهازك.';
        n2Badge.innerText = 'البيانات المرتبطة بهويتك: لا يوجد';

        n3Title.innerText = 'الموقع محلياً بالجهاز';
        n3Desc.innerText = 'تُستخدم إحداثيات GPS بشكل فوري لحساب مواقيت الصلاة الفلكية وبوصلة القبلة فقط.';
        n3Badge.innerText = 'بيانات غير مرتبطة بك: موقع تقريبي';

        n4Title.innerText = 'اتصال مشفر وآمن';
        n4Desc.innerText = 'جميع الطلبات لجلب التلاوات والأحاديث والكتب مشفرة بأحدث معايير الأمان TLS 1.3.';
        n4Badge.innerText = 'حماية وتشفير عالي المستوى';

        updateArabicToc();
      } else {
        html.setAttribute('lang', 'en');
        html.setAttribute('dir', 'ltr');
        btnEn.classList.add('active');
        btnAr.classList.remove('active');
        contentEn.classList.add('active-lang');
        contentAr.classList.remove('active-lang');

        badgeText.innerText = 'Apple App Store Compliant Privacy Document';
        heroTitle.innerHTML = 'Privacy Policy & <span>Data Protection</span>';
        heroSubtitle.innerText = 'Your spiritual journey is personal. Ayatika is architected with a strict privacy-first foundation: we do not sell your data, do not track you across apps, and perform prayer calculations locally.';
        tocHeading.innerText = 'Table of Contents';

        n1Title.innerText = 'No Tracking';
        n1Desc.innerText = 'We do not use advertising identifiers (IDFA) and never track you across apps or websites owned by other companies.';
        n1Badge.innerText = 'Data Used to Track You: None';

        n2Title.innerText = 'No Account Required';
        n2Desc.innerText = 'Ayatika operates without mandatory sign-ups. Your bookmarks, Dhikr counts, and settings remain solely on your device.';
        n2Badge.innerText = 'Data Linked to You: None';

        n3Title.innerText = 'On-Device Location';
        n3Desc.innerText = 'GPS coordinates are used strictly in real time to calculate astronomical prayer times and Qibla compass direction.';
        n3Badge.innerText = 'Data Not Linked: Coarse Location';

        n4Title.innerText = 'Encrypted & Secure';
        n4Desc.innerText = 'All network requests to fetch Quran recitations, hadiths, and Islamic library resources use strict HTTPS/TLS encryption.';
        n4Badge.innerText = 'Standard TLS 1.3 Security';

        updateEnglishToc();
      }
    }

    function updateEnglishToc() {
      const container = document.getElementById('toc-nav-container');
      container.innerHTML = `
        <a href="#section-overview" class="toc-link active"><svg class="icon" viewBox="0 0 24 24"><path d="M12 2C6.48 2 2 6.48 2 12s4.48 10 10 10 10-4.48 10-10S17.52 2 12 2zm1 15h-2v-6h2v6zm0-8h-2V7h2v2z"/></svg> <span class="toc-text">1. Overview & Commitment</span></a>
        <a href="#section-collection" class="toc-link"><svg class="icon" viewBox="0 0 24 24"><path d="M12 2C6.48 2 2 6.48 2 12s4.48 10 10 10 10-4.48 10-10S17.52 2 12 2zm-1 17.93c-3.95-.49-7-3.85-7-7.93 0-.62.08-1.21.21-1.79L9 15v1c0 1.1.9 2 2 2v1.93z"/></svg> <span class="toc-text">2. Information We Handle</span></a>
        <a href="#section-apple-ios" class="toc-link"><svg class="icon" viewBox="0 0 24 24"><path d="M18.71 19.5c-.83 1.24-1.71 2.45-3.05 2.47-1.34.03-1.77-.79-3.29-.79-1.53 0-2 .77-3.27.82-1.31.05-2.3-1.32-3.14-2.53C4.25 17 2.94 12.45 4.7 9.39c.87-1.52 2.43-2.48 4.12-2.51 1.28-.02 2.5.87 3.29.87.78 0 2.26-1.07 3.81-.91.65.03 2.47.26 3.64 1.98-.09.06-2.17 1.28-2.15 3.81.03 3.02 2.65 4.03 2.68 4.04-.03.07-.42 1.44-1.38 2.83M15.97 6.37c.61-.75 1.04-1.8 0.92-2.87-.93.04-2.03.63-2.67 1.38-.56.65-.99 1.7-0.86 2.73 1.04.08 2.06-.52 2.61-1.24z"/></svg> <span class="toc-text">3. iOS Permissions & Usage</span></a>
        <a href="#section-storage" class="toc-link"><svg class="icon" viewBox="0 0 24 24"><path d="M17 1.01L7 1c-1.1 0-2 .9-2 2v18c0 1.1.9 2 2 2h10c1.1 0 2-.9 2-2V3c0-1.1-.9-1.99-2-1.99zM17 19H7V5h10v14z"/></svg> <span class="toc-text">4. Offline & Local Storage</span></a>
        <a href="#section-third-parties" class="toc-link"><svg class="icon" viewBox="0 0 24 24"><path d="M12 2C6.48 2 2 6.48 2 12s4.48 10 10 10 10-4.48 10-10S17.52 2 12 2zm-1 17.93c-3.95-.49-7-3.85-7-7.93 0-.62.08-1.21.21-1.79L9 15v1c0 1.1.9 2 2 2v1.93z"/></svg> <span class="toc-text">5. Third-Party Services & APIs</span></a>
        <a href="#section-children" class="toc-link"><svg class="icon" viewBox="0 0 24 24"><path d="M12 12c2.21 0 4-1.79 4-4s-1.79-4-4-4-4 1.79-4 4 1.79 4 4 4zm0 2c-2.67 0-8 1.34-8 4v2h16v-2c0-2.66-5.33-4-8-4z"/></svg> <span class="toc-text">6. Children's Privacy (COPPA)</span></a>
        <a href="#section-gdpr-ccpa" class="toc-link"><svg class="icon" viewBox="0 0 24 24"><path d="M12 1L3 5v6c0 5.55 3.84 10.74 9 12 5.16-1.26 9-6.45 9-12V5l-9-4zm-2 16l-4-4 1.41-1.41L10 14.17l6.59-6.59L18 9l-8 8z"/></svg> <span class="toc-text">7. GDPR & CCPA Rights</span></a>
        <a href="#section-retention" class="toc-link"><svg class="icon" viewBox="0 0 24 24"><path d="M6 19c0 1.1.9 2 2 2h8c1.1 0 2-.9 2-2V7H6v12zM19 4h-3.5l-1-1h-5l-1 1H5v2h14V4z"/></svg> <span class="toc-text">8. Data Retention & Deletion</span></a>
        <a href="#section-changes" class="toc-link"><svg class="icon" viewBox="0 0 24 24"><path d="M13 3c-4.97 0-9 4.03-9 9H1l3.89 3.89.07.14L9 12H6c0-3.87 3.13-7 7-7s7 3.13 7 7-3.13 7-7 7c-1.93 0-3.68-.79-4.94-2.06l-1.42 1.42C8.27 19.99 10.51 21 13 21c4.97 0 9-4.03 9-9s-4.03-9-9-9zm-1 5v5l4.28 2.54.72-1.21-3.5-2.08V8H12z"/></svg> <span class="toc-text">9. Policy Updates</span></a>
        <a href="#section-contact" class="toc-link"><svg class="icon" viewBox="0 0 24 24"><path d="M20 4H4c-1.1 0-1.99.9-1.99 2L2 18c0 1.1.9 2 2 2h16c1.1 0 2-.9 2-2V6c0-1.1-.9-2-2-2zm0 4l-8 5-8-5V6l8 5 8-5v2z"/></svg> <span class="toc-text">10. Contact Developer</span></a>
      `;
      setupScrollspy();
    }

    function updateArabicToc() {
      const container = document.getElementById('toc-nav-container');
      container.innerHTML = `
        <a href="#section-overview-ar" class="toc-link active"><svg class="icon" viewBox="0 0 24 24"><path d="M12 2C6.48 2 2 6.48 2 12s4.48 10 10 10 10-4.48 10-10S17.52 2 12 2zm1 15h-2v-6h2v6zm0-8h-2V7h2v2z"/></svg> <span class="toc-text">١. نظرة عامة والالتزام</span></a>
        <a href="#section-collection-ar" class="toc-link"><svg class="icon" viewBox="0 0 24 24"><path d="M12 2C6.48 2 2 6.48 2 12s4.48 10 10 10 10-4.48 10-10S17.52 2 12 2zm-1 17.93c-3.95-.49-7-3.85-7-7.93 0-.62.08-1.21.21-1.79L9 15v1c0 1.1.9 2 2 2v1.93z"/></svg> <span class="toc-text">٢. البيانات واستخدامها</span></a>
        <a href="#section-apple-ios-ar" class="toc-link"><svg class="icon" viewBox="0 0 24 24"><path d="M18.71 19.5c-.83 1.24-1.71 2.45-3.05 2.47-1.34.03-1.77-.79-3.29-.79-1.53 0-2 .77-3.27.82-1.31.05-2.3-1.32-3.14-2.53C4.25 17 2.94 12.45 4.7 9.39c.87-1.52 2.43-2.48 4.12-2.51 1.28-.02 2.5.87 3.29.87.78 0 2.26-1.07 3.81-.91.65.03 2.47.26 3.64 1.98-.09.06-2.17 1.28-2.15 3.81.03 3.02 2.65 4.03 2.68 4.04-.03.07-.42 1.44-1.38 2.83M15.97 6.37c.61-.75 1.04-1.8 0.92-2.87-.93.04-2.03.63-2.67 1.38-.56.65-.99 1.7-0.86 2.73 1.04.08 2.06-.52 2.61-1.24z"/></svg> <span class="toc-text">٣. أذونات نظام iOS</span></a>
        <a href="#section-storage-ar" class="toc-link"><svg class="icon" viewBox="0 0 24 24"><path d="M17 1.01L7 1c-1.1 0-2 .9-2 2v18c0 1.1.9 2 2 2h10c1.1 0 2-.9 2-2V3c0-1.1-.9-1.99-2-1.99zM17 19H7V5h10v14z"/></svg> <span class="toc-text">٤. التخزين المحلي</span></a>
        <a href="#section-third-parties-ar" class="toc-link"><svg class="icon" viewBox="0 0 24 24"><path d="M12 2C6.48 2 2 6.48 2 12s4.48 10 10 10 10-4.48 10-10S17.52 2 12 2zm-1 17.93c-3.95-.49-7-3.85-7-7.93 0-.62.08-1.21.21-1.79L9 15v1c0 1.1.9 2 2 2v1.93z"/></svg> <span class="toc-text">٥. الخدمات والمصادر الخارجية</span></a>
        <a href="#section-children-ar" class="toc-link"><svg class="icon" viewBox="0 0 24 24"><path d="M12 12c2.21 0 4-1.79 4-4s-1.79-4-4-4-4 1.79-4 4 1.79 4 4 4zm0 2c-2.67 0-8 1.34-8 4v2h16v-2c0-2.66-5.33-4-8-4z"/></svg> <span class="toc-text">٦. خصوصية الأطفال (COPPA)</span></a>
        <a href="#section-gdpr-ccpa-ar" class="toc-link"><svg class="icon" viewBox="0 0 24 24"><path d="M12 1L3 5v6c0 5.55 3.84 10.74 9 12 5.16-1.26 9-6.45 9-12V5l-9-4zm-2 16l-4-4 1.41-1.41L10 14.17l6.59-6.59L18 9l-8 8z"/></svg> <span class="toc-text">٧. حقوقك القانونية (GDPR)</span></a>
        <a href="#section-retention-ar" class="toc-link"><svg class="icon" viewBox="0 0 24 24"><path d="M6 19c0 1.1.9 2 2 2h8c1.1 0 2-.9 2-2V7H6v12zM19 4h-3.5l-1-1h-5l-1 1H5v2h14V4z"/></svg> <span class="toc-text">٨. الأمان والاحتفاظ بالبيانات</span></a>
        <a href="#section-changes-ar" class="toc-link"><svg class="icon" viewBox="0 0 24 24"><path d="M13 3c-4.97 0-9 4.03-9 9H1l3.89 3.89.07.14L9 12H6c0-3.87 3.13-7 7-7s7 3.13 7 7-3.13 7-7 7c-1.93 0-3.68-.79-4.94-2.06l-1.42 1.42C8.27 19.99 10.51 21 13 21c4.97 0 9-4.03 9-9s-4.03-9-9-9zm-1 5v5l4.28 2.54.72-1.21-3.5-2.08V8H12z"/></svg> <span class="toc-text">٩. تحديثات السياسة</span></a>
        <a href="#section-contact-ar" class="toc-link"><svg class="icon" viewBox="0 0 24 24"><path d="M20 4H4c-1.1 0-1.99.9-1.99 2L2 18c0 1.1.9 2 2 2h16c1.1 0 2-.9 2-2V6c0-1.1-.9-2-2-2zm0 4l-8 5-8-5V6l8 5 8-5v2z"/></svg> <span class="toc-text">١٠. التواصل والدعم</span></a>
      `;
      setupScrollspy();
    }

    // Scrollspy for Active TOC Highlight
    function setupScrollspy() {
      const links = document.querySelectorAll('.toc-link');
      const sections = document.querySelectorAll('.lang-content.active-lang .policy-section');

      window.addEventListener('scroll', () => {
        let current = '';
        sections.forEach(section => {
          const sectionTop = section.offsetTop - 120;
          if (pageYOffset >= sectionTop) {
            current = section.getAttribute('id');
          }
        });

        links.forEach(link => {
          link.classList.remove('active');
          if (link.getAttribute('href') === '#' + current) {
            link.classList.add('active');
          }
        });
      });
    }

    document.addEventListener('DOMContentLoaded', setupScrollspy);
  </script>
</body>
</html>
