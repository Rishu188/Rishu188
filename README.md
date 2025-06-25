<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Rishu | Portfolio</title>
    <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@400;600&display=swap" rel="stylesheet" />
    <style>
         :root {
            --primary-color: #6c63ff;
            --bg-color: #f4f7ff;
            --text-color: #333;
        }
        
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }
        
        body {
            font-family: 'Poppins', sans-serif;
            background: var(--bg-color);
            color: var(--text-color);
        }
        
        .hero {
            display: flex;
            flex-direction: column;
            align-items: center;
            text-align: center;
            padding: 100px 20px;
        }
        
        .hero h1 {
            font-size: 3rem;
            color: var(--primary-color);
            margin-bottom: 10px;
        }
        
        .hero h2 {
            font-size: 1.5rem;
            margin-bottom: 20px;
            color: #555;
        }
        
        .hero p {
            font-size: 1.1rem;
            max-width: 600px;
            line-height: 1.6;
            margin-bottom: 30px;
        }
        
        .btn {
            display: inline-block;
            background-color: var(--primary-color);
            color: white;
            padding: 12px 30px;
            border-radius: 30px;
            text-decoration: none;
            font-weight: 600;
            transition: background 0.3s ease;
        }
        
        .btn:hover {
            background-color: #574fe0;
        }
        
        @media (max-width: 768px) {
            .hero h1 {
                font-size: 2.2rem;
            }
            .hero h2 {
                font-size: 1.2rem;
            }
        }
    </style>
</head>

<body>
    <section class="hero">
        <h1>Hi, I'm Rishu 👋</h1>
        <h2>A Curious Learner & Aspiring Developer</h2>
        <p>
            I enjoy exploring new technologies, writing code in C++, Python, and crafting websites with HTML/CSS. I’m passionate about building cool things, solving problems, and working with others to bring ideas to life.
        </p>
        <a href="#projects" class="btn">View My Work</a>
    </section>
</body>

</html>
