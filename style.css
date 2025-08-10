 :root {
     --primary-color: #4a6fa5;
     --secondary-color: #166088;
     --danger-color: #d33f49;
     --safe-color: #4cb944;
     --warning-color: #ffe74c;
     --scam-color: #ff6b35;
     --theft-color: #8c2d19;
     --light-bg: #f8f9fa;
     --dark-text: #333;
     --light-text: #f8f9fa;
     --dark-bg: #1a1a1a;
     --dark-card: #2d2d2d;
     --dark-border: #444;
 }

 * {
     box-sizing: border-box;
     margin: 0;
     padding: 0;
     font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
     transition: background-color 0.3s, color 0.3s;
 }

 body {
     background-color: var(--light-bg);
     color: var(--dark-text);
     line-height: 1.6;
     min-height: 100vh;
     display: flex;
     flex-direction: column;
 }

 body.dark-mode {
     background-color: var(--dark-bg);
     color: var(--light-text);
 }

 header {
     background-color: var(--primary-color);
     color: white;
     padding: 1rem;
     box-shadow: 0 2px 5px rgba(0, 0, 0, 0.1);
     position: sticky;
     top: 0;
     z-index: 100;
 }

 nav {
     display: flex;
     justify-content: space-between;
     align-items: center;
     flex-wrap: wrap;
 }

 nav ul {
     display: flex;
     list-style: none;
     flex-wrap: wrap;
     justify-content: center;
 }

 nav ul li {
     margin: 0.5rem;
 }

 nav a {
     color: white;
     text-decoration: none;
     font-weight: 500;
     padding: 0.5rem;
     border-radius: 4px;
     transition: background-color 0.3s;
 }

 nav a:hover {
     background-color: rgba(255, 255, 255, 0.2);
 }

 /* Mobile Navigation */
 .mobile-menu-btn {
     display: none;
     background: none;
     border: none;
     color: white;
     font-size: 1.5rem;
     cursor: pointer;
     padding: 0.5rem;
 }

 @media (max-width: 768px) {
     .mobile-menu-btn {
         display: block;
     }

     nav ul {
         display: none;
         flex-direction: column;
         width: 100%;
         padding: 1rem 0;
     }

     nav ul.show {
         display: flex;
     }

     nav ul li {
         margin: 0.5rem 0;
     }
 }

 .container {
     max-width: 1200px;
     margin: 1rem auto;
     padding: 0 1rem;
     flex: 1;
     width: 100%;
 }

 .hero {
     text-align: center;
     padding: 2rem 1rem;
     background-color: #f0f8ff;
     border-radius: 8px;
     margin-bottom: 1rem;
 }


 .hero h1 {
     font-size: clamp(1.5rem, 4vw, 2.5rem);
     margin-bottom: 1rem;
     color: var(--secondary-color);
 }

 .card {
     background: white;
     border-radius: 8px;
     box-shadow: 0 2px 10px rgba(0, 0, 0, 0.1);
     padding: 1.5rem;
     margin-bottom: 1.5rem;
 }



 form label {
     display: block;
     margin: 1rem 0 0.5rem;
     font-weight: 500;
 }

 form input[type="text"],
 form input[type="datetime-local"],
 form input[type="tel"],
 form input[type="url"],
 form select,
 form textarea {
     width: 100%;
     padding: 0.75rem;
     border: 1px solid #ddd;
     border-radius: 4px;
     font-size: 1rem;
     background-color: white;
     color: var(--dark-text);
 }



 form textarea {
     min-height: 100px;
     resize: vertical;
 }

 button {
     background-color: var(--primary-color);
     color: white;
     border: none;
     padding: 0.75rem 1.5rem;
     border-radius: 4px;
     cursor: pointer;
     font-size: 1rem;
     margin-top: 1rem;
     transition: background-color 0.3s;
     width: 100%;
 }

 button:hover {
     background-color: var(--secondary-color);
 }

 .btn-danger {
     background-color: var(--danger-color);
 }

 .btn-danger:hover {
     background-color: #b02a37;
 }

 .btn-warning {
     background-color: var(--scam-color);
 }

 .btn-warning:hover {
     background-color: #e05a2b;
 }

 table {
     width: 100%;
     border-collapse: collapse;
     margin-top: 1rem;
     background: white;
     font-size: clamp(0.8rem, 2vw, 1rem);
 }


 th,
 td {
     padding: 1rem 0.5rem;
     text-align: right;
     border-bottom: 1px solid #ddd;
     vertical-align: middle;
 }


 th {
     background-color: var(--primary-color);
     color: white;
     position: sticky;
     top: 60px;
 }

 tr:nth-child(even) {
     background-color: #f2f2f2;
 }



 .high-risk {
     color: var(--danger-color);
     font-weight: bold;
 }

 .moderate-risk {
     color: var(--warning-color);
     font-weight: bold;
 }

 .low-risk {
     color: orange;
     font-weight: bold;
 }

 .generally-safe {
     color: var(--safe-color);
     font-weight: bold;
 }

 .scam-risk {
     color: var(--scam-color);
     font-weight: bold;
 }

 .theft-risk {
     color: var(--theft-color);
     font-weight: bold;
 }

 .emergency-box {
     background-color: #ffebee;
     border-right: 4px solid var(--danger-color);
     padding: 1rem;
     margin: 1rem 0;
     border-radius: 4px 0 0 4px;
 }

 .scam-box {
     background-color: #fff3e0;
     border-right: 4px solid var(--scam-color);
     padding: 1rem;
     margin: 1rem 0;
     border-radius: 4px 0 0 4px;
 }

 .theft-box {
     background-color: #fbe9e7;
     border-right: 4px solid var(--theft-color);
     padding: 1rem;
     margin: 1rem 0;
     border-radius: 4px 0 0 4px;
 }



 .emergency-box h3 {
     color: var(--danger-color);
     margin-bottom: 0.5rem;
 }

 .scam-box h3 {
     color: var(--scam-color);
     margin-bottom: 0.5rem;
 }

 .theft-box h3 {
     color: var(--theft-color);
     margin-bottom: 0.5rem;
 }

 footer {
     text-align: center;
     padding: 1rem;
     background-color: var(--primary-color);
     color: white;
     margin-top: auto;
 }

 .reports-container {
     max-height: 500px;
     overflow-y: auto;
     margin-top: 1rem;
     border: 1px solid #ddd;
     border-radius: 4px;
     background: white;
 }



 .report-item {
     padding: 1rem;
     border-bottom: 1px solid #eee;
     transition: background-color 0.2s;
 }


 .report-item:hover {
     background-color: #f8f9fa;
 }


 .report-item:last-child {
     border-bottom: none;
 }

 .report-header {
     display: flex;
     justify-content: space-between;
     margin-bottom: 0.5rem;
     flex-wrap: wrap;
 }

 .report-title {
     font-weight: bold;
     color: var(--secondary-color);
 }

 .harassment-report .report-title {
     color: var(--secondary-color);
 }

 .scam-report .report-title {
     color: var(--scam-color);
 }

 .theft-report .report-title {
     color: var(--theft-color);
 }

 .report-meta {
     color: #666;
     font-size: 0.9rem;
 }


 .report-description {
     margin-top: 0.5rem;
 }

 .tabs {
     display: flex;
     margin-bottom: 1rem;
     border-bottom: 1px solid #ddd;
 }


 .tab {
     padding: 0.5rem 1rem;
     cursor: pointer;
     border-bottom: 2px solid transparent;
 }

 .tab.active {
     border-bottom: 2px solid var(--primary-color);
     font-weight: bold;
 }

 .scam-tab.active {
     border-bottom-color: var(--scam-color);
 }

 .theft-tab.active {
     border-bottom-color: var(--theft-color);
 }

 .tab-content {
     display: none;
 }

 .tab-content.active {
     display: block;
 }

 .loading {
     text-align: center;
     padding: 1rem;
     color: #666;
 }



 .toggle-switch {
     position: relative;
     display: inline-block;
     width: 50px;
     height: 24px;
 }

 .toggle-switch input {
     opacity: 0;
     width: 0;
     height: 0;
 }

 .slider {
     position: absolute;
     cursor: pointer;
     top: 0;
     left: 0;
     right: 0;
     bottom: 0;
     background-color: #ccc;
     transition: .4s;
     border-radius: 24px;
 }

 .slider:before {
     position: absolute;
     content: "";
     height: 16px;
     width: 16px;
     left: 4px;
     bottom: 4px;
     background-color: white;
     transition: .4s;
     border-radius: 50%;
 }

 input:checked+.slider {
     background-color: var(--secondary-color);
 }

 input:checked+.slider:before {
     transform: translateX(26px);
 }

 /* Contact page styles */
 .contact-info {
     display: grid;
     grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
     gap: 1.5rem;
     margin-top: 1.5rem;
 }

 .contact-card {
     background: white;
     border-radius: 8px;
     padding: 1.5rem;
     box-shadow: 0 2px 5px rgba(0, 0, 0, 0.1);
 }



 .contact-card h3 {
     color: var(--primary-color);
     margin-bottom: 1rem;
     border-bottom: 2px solid var(--primary-color);
     padding-bottom: 0.5rem;
 }

 .contact-card p {
     margin-bottom: 0.5rem;
 }

 .contact-card a {
     color: var(--secondary-color);
     text-decoration: none;
 }



 .contact-card a:hover {
     text-decoration: underline;
 }

 .social-links {
     display: flex;
     gap: 1rem;
     margin-top: 1rem;
 }

 .social-links a {
     display: inline-block;
     width: 40px;
     height: 40px;
     background-color: var(--primary-color);
     color: white;
     border-radius: 50%;
     text-align: center;
     line-height: 40px;
     transition: background-color 0.3s;
 }

 .social-links a:hover {
     background-color: var(--secondary-color);
 }

 /* Safety tips */
 .safety-tips {
     display: grid;
     grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
     gap: 1.5rem;
     margin-top: 1.5rem;
 }

 .tip-card {
     background: white;
     border-radius: 8px;
     padding: 1.5rem;
     box-shadow: 0 2px 5px rgba(0, 0, 0, 0.1);
     border-top: 4px solid var(--primary-color);
 }


 .tip-card.scam-tip {
     border-top-color: var(--scam-color);
 }

 .tip-card.theft-tip {
     border-top-color: var(--theft-color);
 }

 .tip-card h3 {
     color: var(--primary-color);
     margin-bottom: 1rem;
 }

 .scam-tip h3 {
     color: var(--scam-color);
 }

 .theft-tip h3 {
     color: var(--theft-color);
 }

 .tip-card ul {
     padding-right: 1rem;
 }

 .tip-card li {
     margin-bottom: 0.5rem;
 }

 /* Map container */
 .map-container {
     height: 400px;
     margin: 1rem 0;
     border-radius: 8px;
     overflow: hidden;
     border: 1px solid #ddd;
 }


 /* Statistics cards */
 .stats-container {
     display: grid;
     grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
     gap: 1rem;
     margin: 1rem 0;
 }

 .stat-card {
     background: white;
     border-radius: 8px;
     padding: 1rem;
     text-align: center;
     box-shadow: 0 2px 5px rgba(0, 0, 0, 0.1);
 }



 .stat-card h3 {
     color: var(--primary-color);
     font-size: 1rem;
     margin-bottom: 0.5rem;
 }

 .stat-card p {
     font-size: 1.5rem;
     font-weight: bold;
 }

 .harassment-stat {
     border-top: 4px solid var(--secondary-color);
 }

 .scam-stat {
     border-top: 4px solid var(--scam-color);
 }

 .theft-stat {
     border-top: 4px solid var(--theft-color);
 }

 /* Verification badge */
 .verified-badge {
     display: inline-block;
     background-color: var(--safe-color);
     color: white;
     font-size: 0.7rem;
     padding: 0.2rem 0.5rem;
     border-radius: 10px;
     margin-right: 0.5rem;
     vertical-align: middle;
 }

 @media (max-width: 768px) {
     nav {
         flex-direction: column;
         align-items: stretch;
     }

     nav ul {
         margin-top: 1rem;
         justify-content: space-around;
     }

     nav ul li {
         margin: 0.25rem;
     }

     th {
         top: 100px;
     }

     .stats-container {
         grid-template-columns: 1fr;
     }
 }
