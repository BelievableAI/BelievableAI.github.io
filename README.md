<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Believable AI</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }
        
        body {
            font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Oxygen, Ubuntu, Cantarell, sans-serif;
            line-height: 1.6;
            color: #333;
            background-color: #ffffff;
        }
        
        .container {
            max-width: 1200px;
            margin: 0 auto;
            padding: 0 20px;
        }
        
        header {
            text-align: center;
            padding: 80px 0 60px;
            border-bottom: 1px solid #eee;
        }
        
        .logo {
            font-size: 3rem;
            margin-bottom: 10px;
        }
        
        h1 {
            font-size: 2.5rem;
            font-weight: 300;
            margin-bottom: 20px;
            color: #2c3e50;
        }
        
        .tagline {
            font-size: 1.2rem;
            color: #7f8c8d;
            font-weight: 300;
            max-width: 600px;
            margin: 0 auto;
        }
        
        .team-section {
            padding: 80px 0;
        }
        
        .section-title {
            text-align: center;
            font-size: 2rem;
            font-weight: 300;
            margin-bottom: 60px;
            color: #2c3e50;
        }
        
        .team-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(280px, 1fr));
            gap: 40px;
            margin-top: 40px;
        }
        
        .member-card {
            text-align: center;
            padding: 30px 20px;
            border-radius: 8px;
            transition: transform 0.3s ease, box-shadow 0.3s ease;
            background: #ffffff;
            border: 1px solid #f0f0f0;
        }
        
        .member-card:hover {
            transform: translateY(-5px);
            box-shadow: 0 10px 30px rgba(0,0,0,0.1);
        }
        
        .member-photo {
            width: 120px;
            height: 120px;
            border-radius: 50%;
            object-fit: cover;
            margin: 0 auto 20px;
            border: 3px solid #f8f9fa;
        }
        
        .member-name {
            font-size: 1.3rem;
            font-weight: 500;
            margin-bottom: 8px;
            color: #2c3e50;
        }
        
        .member-affiliation {
            color: #7f8c8d;
            font-size: 0.95rem;
            margin-bottom: 8px;
        }
        
        .member-email {
            color: #3498db;
            font-size: 0.9rem;
            text-decoration: none;
        }
        
        .member-email:hover {
            text-decoration: underline;
        }
        
        .corresponding {
            font-size: 0.8rem;
            color: #e74c3c;
            margin-top: 5px;
        }
        
        footer {
            text-align: center;
            padding: 40px 0;
            border-top: 1px solid #eee;
            color: #7f8c8d;
            font-size: 0.9rem;
        }
        
        @media (max-width: 768px) {
            h1 {
                font-size: 2rem;
            }
            
            .tagline {
                font-size: 1.1rem;
            }
            
            .team-grid {
                grid-template-columns: 1fr;
                gap: 30px;
            }
            
            header {
                padding: 60px 0 40px;
            }
        }
    </style>
</head>
<body>
    <div class="container">
        <header>
            <div class="logo">🤙</div>
            <h1>Believable AI</h1>
            <p class="tagline">We aim to build AI that people can believe.</p>
        </header>
        
        <section class="team-section">
            <h2 class="section-title">Our Team</h2>
            <div class="team-grid">
                <div class="member-card">
                    <img src="pictures/hoki.jpg" alt="Hoki Kim" class="member-photo">
                    <h3 class="member-name">Hoki Kim</h3>
                    <p class="member-affiliation">Chung-Ang University</p>
                    <a href="mailto:hokikim@cau.ac.kr" class="member-email">hokikim@cau.ac.kr</a>
                    <p class="corresponding">Corresponding Author</p>
                </div>
                
                <div class="member-card">
                    <img src="pictures/keonwoo.jpg" alt="Keonwoo Kim" class="member-photo">
                    <h3 class="member-name">Keonwoo Kim</h3>
                    <p class="member-affiliation">NAVER Cloud</p>
                    <a href="mailto:keonwoo.kim97@navercorp.com" class="member-email">keonwoo.kim97@navercorp.com</a>
                </div>
                
                <div class="member-card">
                    <img src="pictures/sungwon.jpg" alt="Sungwon Chae" class="member-photo">
                    <h3 class="member-name">Sungwon Chae</h3>
                    <p class="member-affiliation">Seoul National University</p>
                    <a href="mailto:csw0815@snu.ac.kr" class="member-email">csw0815@snu.ac.kr</a>
                </div>
                
                <div class="member-card">
                    <img src="pictures/sangwon.jpg" alt="Sangwon Yoon" class="member-photo">
                    <h3 class="member-name">Sangwon Yoon</h3>
                    <p class="member-affiliation">Ministry of Justice, Republic of Korea</p>
                    <a href="mailto:asd01075272750@gmail.com" class="member-email">asd01075272750@gmail.com</a>
                </div>
            </div>
        </section>
        
        <footer>
            <p>&copy; 2024 Believable AI. Building trustworthy artificial intelligence.</p>
        </footer>
    </div>
</body>
</html>