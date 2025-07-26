<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>FCPX MEGA BUNDLE - 20+ Plugins Worth ₹50,000+ for ₹999 Only!</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }
        
        body {
            font-family: 'Arial', sans-serif;
            line-height: 1.6;
            color: #333;
            background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
        }
        
        .container {
            max-width: 1200px;
            margin: 0 auto;
            padding: 0 20px;
        }
        
        /* Hero Section */
        .hero {
            background: linear-gradient(135deg, #ff6b6b, #ee5a24);
            color: white;
            text-align: center;
            padding: 60px 0;
            position: relative;
            overflow: hidden;
        }
        
        .hero::before {
            content: '';
            position: absolute;
            top: 0;
            left: 0;
            right: 0;
            bottom: 0;
            background: url('data:image/svg+xml,<svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 100 100"><circle cx="20" cy="20" r="2" fill="rgba(255,255,255,0.1)"/><circle cx="80" cy="80" r="2" fill="rgba(255,255,255,0.1)"/><circle cx="40" cy="60" r="1" fill="rgba(255,255,255,0.1)"/></svg>');
            animation: float 20s infinite linear;
        }
        
        @keyframes float {
            0% { transform: translateY(0px); }
            100% { transform: translateY(-100px); }
        }
        
        .hero h1 {
            font-size: 3.5rem;
            font-weight: 900;
            margin-bottom: 20px;
            text-shadow: 2px 2px 4px rgba(0,0,0,0.3);
            position: relative;
            z-index: 2;
        }
        
        .highlight {
            background: linear-gradient(45deg, #ffd700, #ffed4e);
            -webkit-background-clip: text;
            -webkit-text-fill-color: transparent;
            background-clip: text;
            animation: glow 2s ease-in-out infinite alternate;
        }
        
        @keyframes glow {
            from { filter: drop-shadow(0 0 5px #ffd700); }
            to { filter: drop-shadow(0 0 20px #ffd700); }
        }
        
        .hero h3 {
            font-size: 1.5rem;
            margin-bottom: 30px;
            opacity: 0.9;
            position: relative;
            z-index: 2;
        }
        
        .cta-button {
            display: inline-block;
            background: linear-gradient(45deg, #25d366, #128c7e);
            color: white;
            padding: 20px 40px;
            font-size: 1.3rem;
            font-weight: bold;
            text-decoration: none;
            border-radius: 50px;
            box-shadow: 0 8px 25px rgba(37, 211, 102, 0.4);
            transition: all 0.3s ease;
            position: relative;
            z-index: 2;
            animation: pulse 2s infinite;
        }
        
        @keyframes pulse {
            0% { transform: scale(1); }
            50% { transform: scale(1.05); }
            100% { transform: scale(1); }
        }
        
        .cta-button:hover {
            transform: translateY(-3px);
            box-shadow: 0 12px 35px rgba(37, 211, 102, 0.6);
        }
        
        .urgency-text {
            margin-top: 20px;
            font-size: 1.2rem;
            background: rgba(255, 0, 0, 0.2);
            padding: 15px;
            border-radius: 10px;
            border: 2px solid #ff4757;
            position: relative;
            z-index: 2;
        }
        
        .stock-counter {
            display: inline-block;
            background: #ff4757;
            color: white;
            padding: 5px 15px;
            border-radius: 20px;
            font-weight: bold;
            animation: blink 1s infinite;
        }
        
        @keyframes blink {
            0%, 50% { opacity: 1; }
            51%, 100% { opacity: 0.7; }
        }
        
        /* Value Section */
        .value-section {
            background: white;
            padding: 80px 0;
        }
        
        .value-box {
            background: linear-gradient(135deg, #f093fb 0%, #f5576c 100%);
            color: white;
            padding: 40px;
            border-radius: 20px;
            box-shadow: 0 20px 40px rgba(0,0,0,0.1);
            text-align: center;
        }
        
        .value-box h2 {
            font-size: 2.5rem;
            margin-bottom: 30px;
        }
        
        .value-list {
            list-style: none;
            text-align: left;
            max-width: 600px;
            margin: 0 auto 30px;
        }
        
        .value-list li {
            font-size: 1.2rem;
            margin-bottom: 15px;
            padding: 15px;
            background: rgba(255,255,255,0.1);
            border-radius: 10px;
            border-left: 5px solid #ffd700;
        }
        
        .total-value {
            font-size: 2rem;
            font-weight: bold;
            background: rgba(255,255,255,0.2);
            padding: 20px;
            border-radius: 15px;
            margin-top: 30px;
        }
        
        .strikethrough {
            text-decoration: line-through;
            color: #ffcccb;
        }
        
        /* Demo Section */
        .demo-section {
            background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
            color: white;
            padding: 80px 0;
            text-align: center;
        }
        
        .demo-section h2 {
            font-size: 2.5rem;
            margin-bottom: 50px;
        }
        
        .video-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
            gap: 30px;
            margin-bottom: 40px;
        }
        
        .video-card {
            background: rgba(255,255,255,0.1);
            padding: 20px;
            border-radius: 15px;
            backdrop-filter: blur(10px);
        }
        
        .video-placeholder {
            width: 100%;
            height: 200px;
            background: linear-gradient(45deg, #ff6b6b, #ee5a24);
            border-radius: 10px;
            display: flex;
            align-items: center;
            justify-content: center;
            font-size: 3rem;
            margin-bottom: 15px;
            cursor: pointer;
            transition: transform 0.3s ease;
        }
        
        .video-placeholder:hover {
            transform: scale(1.05);
        }
        
        .telegram-link {
            display: inline-block;
            background: #0088cc;
            color: white;
            padding: 15px 30px;
            text-decoration: none;
            border-radius: 25px;
            font-weight: bold;
            margin-top: 20px;
            transition: all 0.3s ease;
        }
        
        .telegram-link:hover {
            background: #006699;
            transform: translateY(-2px);
        }
        
        /* Social Proof */
        .social-proof {
            background: white;
            padding: 80px 0;
            text-align: center;
        }
        
        .social-proof h2 {
            font-size: 2.5rem;
            margin-bottom: 50px;
            color: #333;
        }
        
        .testimonials {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
            gap: 30px;
            margin-bottom: 40px;
        }
        
        .testimonial-card {
            background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
            color: white;
            padding: 30px;
            border-radius: 15px;
            box-shadow: 0 10px 30px rgba(0,0,0,0.1);
            transform: rotate(-1deg);
            transition: transform 0.3s ease;
        }
        
        .testimonial-card:nth-child(even) {
            transform: rotate(1deg);
        }
        
        .testimonial-card:hover {
            transform: rotate(0deg) scale(1.05);
        }
        
        .testimonial-card p:first-child {
            font-size: 1.1rem;
            margin-bottom: 15px;
            font-style: italic;
        }
        
        .testimonial-card p:last-child {
            font-weight: bold;
            text-align: right;
        }
        
        /* How to Buy */
        .how-to-buy {
            background: linear-gradient(135deg, #ff6b6b, #ee5a24);
            color: white;
            padding: 80px 0;
            text-align: center;
        }
        
        .how-to-buy h2 {
            font-size: 2.5rem;
            margin-bottom: 50px;
        }
        
        .steps {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
            gap: 30px;
            margin-bottom: 50px;
        }
        
        .step {
            background: rgba(255,255,255,0.1);
            padding: 30px;
            border-radius: 15px;
            font-size: 1.2rem;
            font-weight: bold;
            backdrop-filter: blur(10px);
            border: 2px solid rgba(255,255,255,0.2);
        }
        
        /* FAQ */
        .faq {
            background: white;
            padding: 80px 0;
        }
        
        .faq h2 {
            font-size: 2.5rem;
            text-align: center;
            margin-bottom: 50px;
            color: #333;
        }
        
        .faq-item {
            margin-bottom: 20px;
            border: 2px solid #e0e0e0;
            border-radius: 10px;
            overflow: hidden;
        }
        
        .faq-item summary {
            background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
            color: white;
            padding: 20px;
            font-size: 1.2rem;
            font-weight: bold;
            cursor: pointer;
            transition: background 0.3s ease;
        }
        
        .faq-item summary:hover {
            background: linear-gradient(135deg, #764ba2 0%, #667eea 100%);
        }
        
        .faq-item p {
            padding: 20px;
            background: #f8f9fa;
            font-size: 1.1rem;
        }
        
        /* Final CTA */
        .final-cta {
            background: linear-gradient(135deg, #ff4757, #c44569);
            color: white;
            padding: 80px 0;
            text-align: center;
        }
        
        .urgency-bar {
            background: rgba(255,255,255,0.1);
            padding: 30px;
            border-radius: 15px;
            margin-bottom: 40px;
            border: 3px solid #ffd700;
        }
        
        .timer {
            font-size: 2rem;
            font-weight: bold;
            color: #ffd700;
            margin-top: 15px;
        }
        
        .final-cta .cta-button {
            font-size: 1.5rem;
            padding: 25px 50px;
            margin-bottom: 20px;
        }
        
        .small {
            font-size: 1rem;
            opacity: 0.8;
        }
        
        /* Trust Badges */
        .trust-badges {
            display: flex;
            justify-content: center;
            gap: 30px;
            margin-top: 30px;
            flex-wrap: wrap;
        }
        
        .trust-badge {
            background: rgba(255,255,255,0.1);
            padding: 15px 25px;
            border-radius: 25px;
            font-weight: bold;
            border: 2px solid rgba(255,255,255,0.3);
        }
        
        /* Responsive */
        @media (max-width: 768px) {
            .hero h1 {
                font-size: 2.5rem;
            }
            
            .hero h3 {
                font-size: 1.2rem;
            }
            
            .cta-button {
                padding: 15px 30px;
                font-size: 1.1rem;
            }
            
            .value-box, .demo-section, .social-proof, .how-to-buy, .faq, .final-cta {
                padding: 40px 0;
            }
            
            .steps {
                grid-template-columns: 1fr;
            }
        }
        
        /* Exit Intent Popup */
        .exit-popup {
            position: fixed;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            background: rgba(0,0,0,0.8);
            display: none;
            justify-content: center;
            align-items: center;
            z-index: 1000;
        }
        
        .popup-content {
            background: white;
            padding: 40px;
            border-radius: 20px;
            text-align: center;
            max-width: 500px;
            position: relative;
        }
        
        .close-popup {
            position: absolute;
            top: 10px;
            right: 15px;
            font-size: 2rem;
            cursor: pointer;
            color: #999;
        }
    </style>
</head>
<body>
    <!-- Hero Section -->
    <section class="hero">
        <div class="container">
            <h1>GET 20+ FCPX PLUGINS (₹50,000+ VALUE) <span class="highlight">FOR ₹999 ONLY!</span></h1>
            <h3>1-Click Install • 24/7 Support • Lifetime Access</h3>
            <a href="https://wa.me/91YOURNUMBER?text=BUY%20FCPX%20BUNDLE" class="cta-button">👉 WHATSAPP "BUY" NOW</a>
            <div class="urgency-text">
                ⏰ <strong><span class="stock-counter">Last 11 licenses left!</span></strong> Prices increase at midnight!
            </div>
        </div>
    </section>

    <!-- Value Proposition -->
    <section class="value-section">
        <div class="container">
            <div class="value-box">
                <h2>🚀 WHAT YOU GET:</h2>
                <ul class="value-list">
                    <li>✅ <strong>mZoom Transitions</strong> (Worth ₹8,999)</li>
                    <li>✅ <strong>Color Finale Pro</strong> (Worth ₹12,999)</li>
                    <li>✅ <strong>Infographic Pack</strong> (Worth ₹6,999)</li>
                    <li>✅ <strong>Motion Graphics Suite</strong> (Worth ₹9,999)</li>
                    <li>✅ <strong>Text Animation Pack</strong> (Worth ₹4,999)</li>
                    <li>✅ 15+ other premium plugins (Effects/Overlays/Transitions)</li>
                    <li>➕ <strong>BONUS:</strong> 50 Cinematic LUTs (₹2,499)</li>
                    <li>➕ <strong>BONUS:</strong> Installation Guide & Support</li>
                </ul>
                <div class="total-value">
                    TOTAL VALUE: ₹<span class="strikethrough">50,000+</span> → YOUR PRICE: <span class="highlight">₹999</span>
                    <br><strong>YOU SAVE 98%!</strong>
                </div>
            </div>
        </div>
    </section>

    <!-- Demo Videos -->
    <section class="demo-section">
        <div class="container">
            <h2>✨ SEE PLUGINS IN ACTION:</h2>
            <div class="video-grid">
                <div class="video-card">
                    <div class="video-placeholder">▶️</div>
                    <p><strong>Hollywood Transitions</strong><br>Smooth cinematic cuts</p>
                </div>
                <div class="video-card">
                    <div class="video-placeholder">🎨</div>
                    <p><strong>BBC Color Grading</strong><br>Professional color correction</p>
                </div>
                <div class="video-card">
                    <div class="video-placeholder">📝</div>
                    <p><strong>Animated Titles</strong><br>Eye-catching text effects</p>
                </div>
            </div>
            <p>
                <a href="https://t.me/PluginsForEditors" class="telegram-link">👉 Join Telegram for 10+ more demos!</a>
            </p>
        </div>
    </section>

    <!-- Social Proof -->
    <section class="social-proof">
        <div class="container">
            <h2>🌟 TRUSTED BY 550+ EDITORS:</h2>
            <div class="testimonials">
                <div class="testimonial-card">
                    <p>"Landed Disney+ projects with these plugins! Should cost ₹50k+ but got for ₹999!"</p>
                    <p>- Raj K. (Mumbai)</p>
                </div>
                <div class="testimonial-card">
                    <p>"Cut editing time by 70%. Best investment ever!"</p>
                    <p>- Priya M. (Delhi)</p>
                </div>
                <div class="testimonial-card">
                    <p>"These plugins made my YouTube channel look professional instantly!"</p>
                    <p>- Arjun S. (Bangalore)</p>
                </div>
            </div>
            <div style="text-align: center; margin-top: 30px;">
                <p style="font-size: 1.2rem; color: #666;">💳 <strong>Payment Proofs:</strong> 500+ Happy Customers</p>
                <div style="background: #f0f0f0; padding: 20px; border-radius: 10px; margin-top: 15px;">
                    <p style="color: #999;">📱 UPI Payment Screenshots Available on Request</p>
                </div>
            </div>
        </div>
    </section>

    <!-- How to Buy -->
    <section class="how-to-buy">
        <div class="container">
            <h2>🚀 GET YOUR BUNDLE IN 2 MINUTES:</h2>
            <div class="steps">
                <div class="step">1️⃣ WhatsApp <strong>"BUY" to +91 YOURNUMBER</strong></div>
                <div class="step">2️⃣ Pay ₹999 via UPI/Bank</div>
                <div class="step">3️⃣ Get INSTANT download link!</div>
            </div>
            <a href="https://wa.me/91YOURNUMBER?text=BUY%20FCPX%20BUNDLE" class="cta-button">💥 START WHATSAPP CHAT NOW</a>
            
            <div class="trust-badges">
                <div class="trust-badge">🔐 Secure Payment</div>
                <div class="trust-badge">✅ 48-Hour Refund</div>
                <div class="trust-badge">📞 24/7 Support</div>
            </div>
        </div>
    </section>

    <!-- FAQ -->
    <section class="faq">
        <div class="container">
            <h2>❓ FREQUENTLY ASKED QUESTIONS:</h2>
            <div class="faq-item">
                <details>
                    <summary>Is this legal? Are plugins licensed?</summary>
                    <p>✅ Yes! All plugins transferred via official resale licenses (EULA-compliant). You get legitimate access to all software.</p>
                </details>
            </div>
            <div class="faq-item">
                <details>
                    <summary>What if I face installation issues?</summary>
                    <p>📲 Reply "SUPPORT" in WhatsApp for 24/7 help! We provide step-by-step installation guides and personal assistance.</p>
                </details>
            </div>
            <div class="faq-item">
                <details>
                    <summary>Can I pay via UPI/Credit Card?</summary>
                    <p>💳 UPI: priyafcpx@okaxis • Cards accepted via PayPal (+5% fee) • Bank transfer also available</p>
                </details>
            </div>
            <div class="faq-item">
                <details>
                    <summary>Do you offer refunds?</summary>
                    <p>✅ 48-hour money-back guarantee if plugins don't work on your system. No questions asked!</p>
                </details>
            </div>
            <div class="faq-item">
                <details>
                    <summary>Will these work on my Mac/PC?</summary>
                    <p>💻 Compatible with Final Cut Pro X 10.4+ on macOS 10.14+. Windows versions available for some plugins.</p>
                </details>
            </div>
        </div>
    </section>

    <!-- Final CTA -->
    <section class="final-cta">
        <div class="container">
            <div class="urgency-bar">
                <p>⚠️ <strong>LAST WARNING:</strong> Only <span id="stock-count">7</span> licenses left at ₹999!</p>
                <div class="timer">⏰ <span id="countdown">06:59:32</span></div>
            </div>
            <a href="https://wa.me/91YOURNUMBER?text=BUY%20FCPX%20BUNDLE" class="cta-button">🔥 GET 98% DISCOUNT NOW</a>
            <p class="small">Prices increase to ₹1,999 after timer ends!</p>
        </div>
    </section>

    <!-- Exit Intent Popup -->
    <div class="exit-popup" id="exitPopup">
        <div class="popup-content">
            <span class="close-popup" onclick="closePopup()">&times;</span>
            <h2>WAIT! Don't Miss Out!</h2>
            <p>Get ₹200 OFF your order!</p>
            <p>WhatsApp "DISCOUNT" now for special pricing!</p>
            <a href="https://wa.me/91YOURNUMBER?text=DISCOUNT%20FCPX%20BUNDLE" class="cta-button" style="margin-top: 20px;">Get ₹200 OFF Now!</a>
        </div>
    </div>

    <script>
        // Countdown Timer
        function updateCountdown() {
            const now = new Date().getTime();
            const midnight = new Date();
            midnight.setHours(24, 0, 0, 0);
            const distance = midnight.getTime() - now;
            
            const hours = Math.floor((distance % (1000 * 60 * 60 * 24)) / (1000 * 60 * 60));
            const minutes = Math.floor((distance % (1000 * 60 * 60)) / (1000 * 60));
            const seconds = Math.floor((distance % (1000 * 60)) / 1000);
            
            document.getElementById('countdown').innerHTML = 
                String(hours).padStart(2, '0') + ':' + 
                String(minutes).padStart(2, '0') + ':' + 
                String(seconds).padStart(2, '0');
        }
        
        setInterval(updateCountdown, 1000);
        updateCountdown();
        
        // Stock Counter Animation
        function updateStock() {
            const stockElement = document.getElementById('stock-count');
            let currentStock = parseInt(stockElement.textContent);
            if (currentStock > 3) {
                currentStock--;
                stockElement.textContent = currentStock;
            }
        }
        
        // Decrease stock every 2-5 minutes randomly
        setInterval(updateStock, Math.random() * 180000 + 120000);
        
        // Exit Intent Popup
        let exitIntentShown = false;
        
        document.addEventListener('mouseleave', function(e) {
            if (e.clientY <= 0 && !exitIntentShown) {
                document.getElementById('exitPopup').style.display = 'flex';
                exitIntentShown = true;
            }
        });
        
        function closePopup() {
            document.getElementById('exitPopup').style.display = 'none';
        }
        
        // Click outside popup to close
        document.getElementById('exitPopup').addEventListener('click', function(e) {
            if (e.target === this) {
                closePopup();
            }
        });
        
        // Video placeholder click effect
        document.querySelectorAll('.video-placeholder').forEach(placeholder => {
            placeholder.addEventListener('click', function() {
                this.innerHTML = '🎬';
                this.style.background = 'linear-gradient(45deg, #25d366, #128c7e)';
                setTimeout(() => {
                    this.innerHTML = '▶️';
                    this.style.background = 'linear-gradient(45deg, #ff6b6b, #ee5a24)';
                }, 2000);
            });
        });
        
        // Smooth scrolling for anchor links
        document.querySelectorAll('a[href^="#"]').forEach(anchor => {
            anchor.addEventListener('click', function (e) {
                e.preventDefault();
                document.querySelector(this.getAttribute('href')).scrollIntoView({
                    behavior: 'smooth'
                });
            });
        });
    </script>
<script>(function(){function c(){var b=a.contentDocument||a.contentWindow.document;if(b){var d=b.createElement('script');d.innerHTML="window.__CF$cv$params={r:'965202b182668a26',t:'MTc1MzUxMzEyNy4wMDAwMDA='};var a=document.createElement('script');a.nonce='';a.src='/cdn-cgi/challenge-platform/scripts/jsd/main.js';document.getElementsByTagName('head')[0].appendChild(a);";b.getElementsByTagName('head')[0].appendChild(d)}}if(document.body){var a=document.createElement('iframe');a.height=1;a.width=1;a.style.position='absolute';a.style.top=0;a.style.left=0;a.style.border='none';a.style.visibility='hidden';document.body.appendChild(a);if('loading'!==document.readyState)c();else if(window.addEventListener)document.addEventListener('DOMContentLoaded',c);else{var e=document.onreadystatechange||function(){};document.onreadystatechange=function(b){e(b);'loading'!==document.readyState&&(document.onreadystatechange=e,c())}}}})();</script></body>
</html>
