# phobia-.github.io-

</html>"Launch Phobia Free website"
<!DOCTYPE html>
<html>
<head>
    <title>Phobia Free - Professional Hypnotherapy</title>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <style>
        body { 
            font-family: Arial, sans-serif; 
            margin: 0; 
            padding: 0; 
            line-height: 1.6;
        }
        .header { 
            background: #2c5aa0; 
            color: white; 
            padding: 20px; 
            text-align: center; 
        }
        .container { 
            max-width: 1200px; 
            margin: 0 auto; 
            padding: 20px; 
        }
        .hero { 
            background: linear-gradient(135deg, #667eea 0%, #764ba2 100%); 
            color: white; 
            padding: 60px 20px; 
            text-align: center; 
        }
        .hero h1 { 
            font-size: 3em; 
            margin-bottom: 20px; 
        }
        .hero p { 
            font-size: 1.2em; 
            margin-bottom: 30px; 
            max-width: 600px;
            margin-left: auto;
            margin-right: auto;
        }
        .btn { 
            background: white; 
            color: #2c5aa0; 
            padding: 15px 30px; 
            border-radius: 25px; 
            text-decoration: none; 
            font-weight: bold; 
            display: inline-block; 
            margin: 10px; 
            transition: all 0.3s ease;
        }
        .btn:hover {
            transform: translateY(-2px);
            box-shadow: 0 5px 15px rgba(0,0,0,0.2);
        }
        .about {
            padding: 60px 20px;
            background: #f8f9fa;
        }
        .about h2 {
            text-align: center;
            font-size: 2.5em;
            margin-bottom: 40px;
            color: #2c5aa0;
        }
        .about h3 {
            color: #2c5aa0;
            margin-bottom: 20px;
            margin-top: 30px;
        }
        .about-content {
            max-width: 800px;
            margin: 0 auto;
            line-height: 1.7;
            font-size: 1.1em;
        }
        .expectations-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
            gap: 20px;
            margin: 30px 0;
        }
        .expectation-card {
            background: white;
            padding: 20px;
            border-radius: 10px;
            box-shadow: 0 3px 10px rgba(0,0,0,0.1);
        }
        .quote-box {
            font-size: 1.2em;
            color: #2c5aa0;
            text-align: center;
            font-weight: bold;
            margin: 30px 0;
            padding: 20px;
            background: white;
            border-radius: 10px;
            box-shadow: 0 3px 10px rgba(0,0,0,0.1);
        }
        .final-quote {
            font-style: italic;
            text-align: center;
            margin-top: 30px;
            padding: 20px;
            background: #2c5aa0;
            color: white;
            border-radius: 10px;
        }
        .services { 
            padding: 60px 20px; 
        }
        .services h2 { 
            text-align: center; 
            font-size: 2.5em; 
            margin-bottom: 40px; 
            color: #2c5aa0;
        }
        .service-grid { 
            display: grid; 
            grid-template-columns: repeat(auto-fit, minmax(300px, 1fr)); 
            gap: 30px; 
            max-width: 1200px; 
            margin: 0 auto; 
        }
        .service-card { 
            background: white; 
            padding: 30px; 
            border-radius: 10px; 
            box-shadow: 0 5px 15px rgba(0,0,0,0.1); 
            transition: transform 0.3s ease;
        }
        .service-card:hover {
            transform: translateY(-5px);
        }
        .service-card h3 { 
            color: #2c5aa0; 
            margin-bottom: 15px; 
            font-size: 1.3em;
        }
        .service-card ul {
            padding-left: 20px;
        }
        .service-card li {
            margin-bottom: 8px;
        }
        .testimonials {
            padding: 60px 20px;
            background: #f8f9fa;
        }
        .testimonials h2 {
            text-align: center;
            font-size: 2.5em;
            margin-bottom: 40px;
            color: #2c5aa0;
        }
        .testimonial-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
            gap: 30px;
            max-width: 1200px;
            margin: 0 auto;
        }
        .testimonial {
            background: white;
            padding: 30px;
            border-radius: 10px;
            box-shadow: 0 5px 15px rgba(0,0,0,0.1);
            position: relative;
        }
        .testimonial::before {
            content: '"';
            font-size: 4em;
            color: #2c5aa0;
            opacity: 0.3;
            position: absolute;
            top: -10px;
            left: 20px;
        }
        .testimonial-text {
            font-style: italic;
            margin-bottom: 20px;
            padding-top: 20px;
        }
        .testimonial-author {
            font-weight: bold;
            color: #2c5aa0;
        }
        .contact { 
            background: #f8f9fa; 
            padding: 60px 20px; 
        }
        .contact h2 { 
            text-align: center; 
            font-size: 2.5em; 
            margin-bottom: 40px; 
            color: #2c5aa0;
        }
        .contact-grid {
            display: grid;
            grid-template-columns: 1fr 1fr;
            gap: 40px;
            max-width: 1200px;
            margin: 0 auto;
        }
        .contact-info h3 {
            color: #2c5aa0;
            margin-bottom: 20px;
        }
        .contact-info p {
            margin-bottom: 15px;
        }
        .contact-form { 
            max-width: 600px; 
            margin: 0 auto; 
        }
        .contact-form h3 {
            color: #2c5aa0;
            margin-bottom: 20px;
        }
        .form-group { 
            margin-bottom: 20px; 
        }
        .form-group label { 
            display: block; 
            margin-bottom: 5px; 
            font-weight: bold; 
        }
        .form-group input, 
        .form-group textarea, 
        .form-group select { 
            width: 100%; 
            padding: 12px; 
            border: 2px solid #ddd; 
            border-radius: 5px; 
            font-size: 16px; 
            font-family: Arial, sans-serif;
        }
        .form-group input:focus,
        .form-group textarea:focus,
        .form-group select:focus {
            border-color: #2c5aa0;
            outline: none;
        }
        .submit-btn { 
            background: #2c5aa0; 
            color: white; 
            padding: 15px 30px; 
            border: none; 
            border-radius: 25px; 
            font-size: 16px; 
            cursor: pointer; 
            width: 100%; 
            transition: background 0.3s ease;
        }
        .submit-btn:hover {
            background: #1e3f73;
        }
        .footer { 
            background: #2c2c2c; 
            color: white; 
            padding: 40px 20px; 
            text-align: center; 
        }
        .footer p {
            margin-bottom: 10px;
        }
        
        /* Mobile Responsive */
        @media (max-width: 768px) { 
            .hero h1 { 
                font-size: 2em; 
            } 
            .service-grid { 
                grid-template-columns: 1fr; 
            }
            .contact-grid {
                grid-template-columns: 1fr;
            }
            .expectations-grid {
                grid-template-columns: 1fr;
            }
            .testimonial-grid {
                grid-template-columns: 1fr;
            }
        }
    </style>
</head>
<body>
    <!-- Header -->
    <header class="header">
        <h1>Phobia Free</h1>
        <p>Professional Hypnotherapy Services</p>
    </header>

    <!-- Hero Section -->
    <section class="hero">
        <h1>Overcome Your Fears & Live Freely</h1>
        <p>Professional hypnotherapy specialized in phobia treatment. Transform your relationship with fear through proven, gentle techniques that work.</p>
        <a href="#contact" class="btn">Start Your Journey</a>
        <a href="#about" class="btn">Learn More</a>
    </section>

    <!-- About Section with Your Profile -->
    <section class="about" id="about">
        <div class="container">
            <h2>About Me - Your Guide to Freedom from Fear</h2>
            
            <div class="about-content">
                <h3>A Lifetime of Helping Others Transform Their Lives</h3>
                
                <p>Throughout my career, I've had the privilege of working with people during some of their most challenging moments. As a former children's services manager, I've supported vulnerable young people, managed complex family situations, and led teams dedicated to keeping families together. From running children's homes to managing outreach programs that prevented children from entering care, I've witnessed firsthand the incredible resilience of the human spirit.</p>
                
                <p>My journey has taken me from managing secure units where I worked with young people facing their deepest struggles, to traveling extensively and experiencing diverse cultures and perspectives. These experiences have taught me that transformation is always possible, no matter how overwhelming the challenge may seem.</p>
                
                <h3>Why I Chose Phobia Treatment</h3>
                
                <p>What drew me to hypnotherapy was seeing how fear can limit people's potential – just as I'd witnessed with the young people I worked with. Whether it's a child afraid to trust again or an adult avoiding flights that could connect them with loved ones, fear has a way of building walls around our lives.</p>
                
                <p>I understand what it's like to feel stuck, overwhelmed, or afraid. My background in crisis management and working with complex emotional situations has given me a unique perspective on how fear operates – and more importantly, how it can be overcome.</p>
                
                <h3>My Approach: Compassionate, Professional, Real</h3>
                
                <p>Working in children's services taught me that every person's story matters. I don't believe in one-size-fits-all solutions. Instead, I take time to understand your specific situation, your triggers, and your goals.</p>
                
                <p>Having managed teams and supported families through crisis, I know how to remain calm under pressure and create safe spaces where people feel heard and understood. I've learned that lasting change happens when someone feels truly supported – not judged.</p>
                
                <p>My extensive travel has shown me that courage comes in many forms, and that stepping outside our comfort zones, while scary, opens up worlds of possibility.</p>
                
                <h3>What You Can Expect</h3>
                
                <p>When we work together, you'll find someone who:</p>
                
                <div class="expectations-grid">
                    <div class="expectation-card">
                        <strong style="color: #2c5aa0;">Listens without judgment</strong><br>
                        My years in social services taught me that everyone has a story worth understanding
                    </div>
                    <div class="expectation-card">
                        <strong style="color: #2c5aa0;">Stays calm in difficult moments</strong><br>
                        Managing crisis situations has given me the ability to remain steady when emotions run high
                    </div>
                    <div class="expectation-card">
                        <strong style="color: #2c5aa0;">Believes in your potential</strong><br>
                        I've seen people overcome seemingly impossible obstacles, and I know you can too
                    </div>
                    <div class="expectation-card">
                        <strong style="color: #2c5aa0;">Uses practical, proven techniques</strong><br>
                        My approach combines professional training with real-world experience helping people through tough times
                    </div>
                </div>
                
                <h3>Your Journey Starts Here</h3>
                
                <p>I didn't come to hypnotherapy by accident. Every challenging situation I've navigated, every person I've supported, and every place I've traveled has prepared me for this work.</p>
                
                <p>I know that taking the first step to address your phobia takes courage. That's why I offer a free consultation – so you can get to know me, ask questions, and feel completely comfortable before we begin.</p>
                
                <div class="quote-box">
                    Your fear doesn't define you. It's simply something we'll work through together, one step at a time.
                </div>
                
                <div class="final-quote">
                    "Having worked with people in their most vulnerable moments, I understand that healing happens in an environment of safety, respect, and genuine care. Let me help you write your next chapter – one free from the limitations fear has placed on your life."
                </div>
            </div>
        </div>
    </section>

    <!-- Services Section -->
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
                    <li<valid semver> ::= <version core>
                 | <version core> "-" <pre-release>
                 | <version core> "+" <build>
                 | <version core> "-" <pre-release> "+" <build>

<version core> ::= <major> "." <minor> "." <patch>

<major> ::= <numeric identifier>

<minor> ::= <numeric identifier>

<patch> ::= <numeric identifier>

<pre-release> ::= <dot-separated pre-release identifiers>

<dot-separated pre-release identifiers> ::= <pre-release identifier>
                                          | <pre-release identifier> "." <dot-separated pre-release identifiers>

<build> ::= <dot-separated build identifiers>

<dot-separated build identifiers> ::= <build identifier>
                                    | <build identifier> "." <dot-separated build identifiers>

<pre-release identifier> ::= <alphanumeric identifier>
                           | <numeric identifier>

<build identifier> ::= <alphanumeric identifier>
                     | <digits>

<alphanumeric identifier> ::= <non-digit>
                            | <non-digit> <identifier characters>
                            | <identifier characters> <non-digit>
                            | <identifier characters> <non-digit> <identifier characters>

<numeric identifier> ::= "0"
                       | <positive digit>
                       | <positive digit> <digits>

<identifier characters> ::= <identifier character>
                          | <identifier character> <identifier characters>

<identifier character> ::= <digit>
                         | <non-digit>

<non-digit> ::= <letter>
              | "-"

<digits> ::= <digit>
           | <digit> <digits>

<digit> ::= "0"
          | <positive digit>

<positive digit> ::= "1" | "2" | "3" | "4" | "5" | "6" | "7" | "8" | "9"

<letter> ::= "A" | "B" | "C" | "D" | "E" | "F" | "G" | "H" | "I" | "J"
           | "K" | "L" | "M" | "N" | "O" | "P" | "Q" | "R" | "S" | "T"
           | "U" | "V" | "W" | "X" | "Y" | "Z" | "a" | "b" | "c" | "d"
           | "e" | "f" | "g" | "h" | "i" | "j" | "k" | "l" | "m" | "n"
           | "o" | "p" | "q" | "r" | "s" | "t" | "u" | "v" | "w" | "x"
           | "y" | "z"
