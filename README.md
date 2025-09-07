# phobia-.github.io-
"Phobia Free Hypnotherapy Website"

<!DOCTYPE html>
<html>
<head>
    <title>Phobia Free - Professional Hypnotherapy</title>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <style>
        body { font-family: Arial, sans-serif; margin: 0; padding: 0; }
        .header { background: #2c5aa0; color: white; padding: 20px; text-align: center; }
        .container { max-width: 1200px; margin: 0 auto; padding: 20px; }
        .hero { background: linear-gradient(135deg, #667eea 0%, #764ba2 100%); color: white; padding: 60px 20px; text-align: center; }
        .hero h1 { font-size: 3em; margin-bottom: 20px; }
        .hero p { font-size: 1.2em; margin-bottom: 30px; }
        .btn { background: white; color: #2c5aa0; padding: 15px 30px; border-radius: 25px; text-decoration: none; font-weight: bold; display: inline-block; margin: 10px; }
        .services { padding: 60px 20px; }
        .services h2 { text-align: center; font-size: 2.5em; margin-bottom: 40px; }
        .service-grid { display: grid; grid-template-columns: repeat(auto-fit, minmax(300px, 1fr)); gap: 30px; max-width: 1200px; margin: 0 auto; }
        .service-card { background: white; padding: 30px; border-radius: 10px; box-shadow: 0 5px 15px rgba(0,0,0,0.1); }
        .service-card h3 { color: #2c5aa0; margin-bottom: 15px; }
        .contact { background: #f8f9fa; padding: 60px 20px; }
        .contact h2 { text-align: center; font-size: 2.5em; margin-bottom: 40px; }
        .contact-form { max-width: 600px; margin: 0 auto; }
        .form-group { margin-bottom: 20px; }
        .form-group label { display: block; margin-bottom: 5px; font-weight: bold; }
        .form-group input, .form-group textarea, .form-group select { width: 100%; padding: 12px; border: 2px solid #ddd; border-radius: 5px; font-size: 16px; }
        .submit-btn { background: #2c5aa0; color: white; padding: 15px 30px; border: none; border-radius: 25px; font-size: 16px; cursor: pointer; width: 100%; }
        .footer { background: #2c2c2c; color: white; padding: 40px 20px; text-align: center; }
        @media (max-width: 768px) { .hero h1 { font-size: 2em; } .service-grid { grid-template-columns: 1fr; } }
    </style>
</head>
<body>
    <header class="header">
        <h1>Phobia Free</h1>
        <p>Professional Hypnotherapy Services</p>
    </header>

    <section class="hero">
        <h1>Overcome Your Fears & Live Freely</h1>
        <p>Professional hypnotherapy specialized in phobia treatment. Transform your relationship with fear through proven, gentle techniques that work.</p>
        <a href="#contact" class="btn">Start Your Journey</a>
        <a href="#services" class="btn">Learn More</a>
    </section>

    <section class="services" id="services">
        <h2>Specialized Phobia Treatment</h2>
        <div class="service-grid">
            <div class="service-card">
                <h3>✈️ Flying & Travel Phobias</h3>
                <p>Overcome fear of flying, airports, or traveling. Enjoy vacations and business trips with confidence.</p>
                <ul>
                    <li>Pre-flight anxiety management</li>
                    <li>Turbulence fear elimination</li>
                    <li>Airport confidence building</li>
                    <li>Travel relaxation techniques</li>
                </ul>
            </div>
            <div class="service-card">
                <h3>🕷️ Animal & Insect Phobias</h3>
                <p>Free yourself from fears of spiders, dogs, bees, or other creatures that limit your activities.</p>
                <ul>
                    <li>Gradual exposure therapy</li>
                    <li>Panic response elimination</li>
                    <li>Confidence in nature</li>
                    <li>Home comfort restoration</li>
                </ul>
            </div>
            <div class="service-card">
                <h3>🏢 Heights & Spaces</h3>
                <p>Conquer fear of heights, enclosed spaces, bridges, or elevators for complete freedom of movement.</p>
                <ul>
                    <li>Elevator confidence</li>
                    <li>Bridge crossing comfort</li>
                    <li>Height tolerance building</li>
                    <li>Claustrophobia relief</li>
                </ul>
            </div>
            <div class="service-card">
                <h3>🩺 Medical & Dental Phobias</h3>
                <p>Feel calm and relaxed during medical procedures, dental visits, and health appointments.</p>
                <ul>
                    <li>Injection fear elimination</li>
                    <li>Dental anxiety relief</li>
                    <li>MRI scan comfort</li>
                    <li>Surgery preparation</li>
                </ul>
            </div>
            <div class="service-card">
                <h3>👥 Social & Performance</h3>
                <p>Build confidence in social situations, presentations, and performance scenarios.</p>
                <ul>
                    <li>Public speaking confidence</li>
                    <li>Social anxiety relief</li>
                    <li>Interview preparation</li>
                    <li>Performance enhancement</li>
                </ul>
            </div>
            <div class="service-card">
                <h3>🌐 Online Sessions Available</h3>
                <p>Convenient, secure online hypnotherapy sessions from the comfort of your own home.</p>
                <ul>
                    <li>HIPAA-compliant platform</li>
                    <li>Flexible scheduling</li>
                    <li>Same effective results</li>
                    <li>Recorded sessions available</li>
                </ul>
            </div>
        </div>
    </section>

    <section class="contact" id="contact">
        <h2>Get In Touch</h2>
        <div class="contact-form">
            <h3>Free Consultation Request</h3>
            <form>
                <div class="form-group">
                    <label for="name">Full Name *</label>
                    <input type="text" id="name" name="name" required>
                </div>
                <div class="form-group">
                    <label for="email">Email Address *</label>
                    <input type="email" id="email" name="email" required>
                </div>
                <div class="form-group">
                    <label for="phone">Phone Number</label>
                    <input type="tel" id="phone" name="phone">
                </div>
                <div class="form-group">
                    <label for="phobia">What fear would you like help with? *</label>
                    <input type="text" id="phobia" name="phobia" placeholder="e.g., Fear of flying, spiders, heights..." required>
                </div>
                <div class="form-group">
                    <label for="severity">How would you rate the impact on your daily life? (1-10)</label>
                    <input type="number" id="severity" name="severity" min="1" max="10" placeholder="10 = Severely impacts my life">
                </div>
                <div class="form-group">
                    <label for="preference">Session Preference</label>
                    <select id="preference" name="preference">
                        <option value="">Select an option</option>
                        <option value="online">Online sessions preferred</option>
                        <option value="in-person">In-person sessions preferred</option>
                        <option value="either">Either option is fine</option>
                    </select>
                </div>
                <div class="form-group">
                    <label for="message">Tell me more about your situation (optional)</label>
                    <textarea id="message" name="message" placeholder="Any additional information that might be helpful..."></textarea>
                </div>
                <button type="submit" class="submit-btn">Request Free Consultation</button>
            </form>
        </div>
        
        <div style="margin-top: 40px; text-align: center;">
            <h3>Contact Information</h3>
            <p><strong>Email:</strong> info@phobiafree.co.uk</p>
            <p><strong>Phone:</strong> 020 8940 XXXX</p>
            <p><strong>Location:</strong> Richmond upon Thames, UK</p>
            <p><strong>Hours:</strong> Mon-Fri 9am-8pm, Sat 10am-6pm</p>
        </div>
    </section>

    <footer class="footer">
        <p>&copy; 2024 Phobia Free. All rights reserved.</p>
        <p>Professional hypnotherapy services in Richmond upon Thames and online.</p>
    </footer>

    <script>
        document.querySelector('form').addEventListener('submit', function(e) {
            e.preventDefault();
            alert('Thank you for your request! I will contact you within 24 hours to schedule your free consultation.');
        });
    </script>
</body>
</html>"Launch Phobia Free website"
