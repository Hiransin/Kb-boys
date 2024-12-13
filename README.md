<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>KB Boys - Friends Forever</title>
    <style>
        body {
            font-family: 'Arial', sans-serif;
            margin: 0;
            padding: 0;
            background: linear-gradient(135deg, #ff6b6b, #f7b731);
            color: #333;
        }
        header {
            background-color: #2c3e50;
            color: white;
            text-align: center;
            padding: 30px 0;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.2);
        }
        header h1 {
            font-family: 'Roboto', sans-serif;
            font-size: 3em;
            margin: 0;
        }
        header p {
            font-size: 1.2em;
            margin: 10px 0;
        }
        nav {
            background-color: #34495e;
            padding: 15px;
            text-align: center;
        }
        nav a {
            color: white;
            text-decoration: none;
            margin: 0 20px;
            font-size: 1.2em;
            font-weight: bold;
            transition: color 0.3s ease, transform 0.3s ease;
        }
        nav a:hover {
            color: #1abc9c;
            transform: scale(1.1);
        }
        section {
            padding: 40px;
            text-align: center;
            background: #ecf0f1;
        }
        .card-container {
            display: flex;
            flex-wrap: wrap;
            justify-content: center;
            gap: 20px;
            margin-top: 20px;
        }
        .card {
            background: #fff;
            border-radius: 15px;
            box-shadow: 0 6px 12px rgba(0, 0, 0, 0.2);
            width: 230px;
            padding: 20px;
            text-align: center;
            transition: transform 0.3s ease, box-shadow 0.3s ease;
        }
        .card:hover {
            transform: translateY(-10px);
            box-shadow: 0 10px 20px rgba(0, 0, 0, 0.3);
        }
        .card img {
            border-radius: 50%;
            width: 220px;
            height: 220px;
            border: 4px solid #f39c12;
            margin-bottom: 15px;
        }
        .card h3 {
            font-size: 2.4em;
            color: #34495e;
            margin: 10px 0;
        }
        .card p {
            font-size: 1.1em;
            color: #7f8c8d;
        }
        footer {
            background-color: #2c3e50;
            color: white;
            text-align: center;
            padding: 20px 0;
            margin-top: 40px;
            font-size: 1.1em;
        }

        /* Mobile responsiveness */
        @media (max-width: 600px) {
            nav a {
                font-size: 1em;
                margin: 0 15px;
            }
            .card {
                width: 180px;
                padding: 15px;
            }
            .card h3 {
                font-size: 1.2em;
            }
            .card p {
                font-size: 1em;
            }
        }
    </style>
</head>
<body>
    <header>
        <h1>Welcome to KB Boys</h1>
        <p>Friends Forever, Memories Together</p>
    </header>
    <nav>
        <a href="#about">About Us</a>
        <a href="#members">Our Members</a>
        <a href="#contact">Contact</a>
    </nav>

    <section id="about">
        <h2>About Us</h2>
        <p>We are the KB Boys, a group of friends who share a bond of laughter, fun, and endless memories. This page is dedicated to celebrating our friendship!</p>
    </section>
    <section id="members">
        <h2>Our Members</h2>
        <div class="card-container">
            <div class="card">
                <img src="profile1.jpg" alt="Portrait of Soham, the Techie">
                <h3>Soham Ghosh</h3>
                <p>The Techie</p>
            </div>
            <div class="card">
                <img src="profile2.jpg" alt="Portrait of Subham, the Allrounder">
                <h3>Subham Singh</h3>
                <p>The Allrounder</p>
            </div>
            <div class="card">
                <img src="profile3.jpg" alt="Portrait of Hiran Singh Babu, the Editor">
                <h3>Hiran Singh Babu</h3>
                <p>The Editor</p>
            </div>
            <div class="card">
                <img src="profile4.jpg" alt="Portrait of Rabi Shankar Das, the skillful guy">
                <h3>Rabi Shankar Das</h3>
                <p>The skillful guy</p>
            </div>
            <div class="card">
                <img src="profile5.jpg" alt="Portrait of Himangshu Dey, the smiling guy">
                <h3>Himangshu Dey</h3>
                <p>The smiling guy </p>
            </div>
            <div class="card">
                <img src="profile6.jpg" alt="Portrait of Uday Mahato, the victim">
                <h3>Uday Mahato</h3>
                <p>The victim</p>
            </div>
            <div class="card">
                <img src="profile7.jpg" alt="Portrait of Somnath Mahato, the Footballer">
                <h3>Somnath Mahato</h3>
                <p>The Footballer</p>
            </div>
            <div class="card">
                <img src="profile8.jpg" alt="Portrait of Suraj Mahato, the tallest guy">
                <h3>Suraj Mahato</h3>
                <p>The tallest guy</p>
            </div>
            <div class="card">
                <img src="profile9.jpg" alt="Portrait of Arnab Mahato, the ultimate Gamer">
                <h3>Arnab Mahato</h3>
                <p>The ultimate Gamer</p>
            </div>
            <div class="card">
                <img src="profile10.jpg" alt="Portrait of Abhijeet Mahato, the tech gadgets guy">
                <h3>Abhijeet Mahato</h3>
                <p>The tech gadgets guy</p>
            </div>
            <div class="card">
                <img src="profile11.jpg" alt="Portrait of Faizan Ansari, the Entertainer">
                <h3>Faizan Ansari</h3>
                <p>The Entertainer</p>
            </div>
            <div class="card">
                <img src="profile12.jpg" alt="Portrait of Nayyar Ansari, the video guy">
                <h3>Nayyar Ansari</h3>
                <p>The  video guy</p>
            </div>
            <div class="card">
                <img src="profile13.jpg" alt="Portrait of Neel Paul, the badmosh">
                <h3>Neel Paul</h3>
                <p>The badmosh</p>
            </div>
            <div class="card">
                <img src="profile14.jpg" alt="Portrait of Bhawiswat Lal Gope, the class leader">
                <h3>Bhawiswat Lal Gope</h3>
                <p>The class leader</p>
            </div>
            <div class="card">
                <img src="profile15.jpg" alt="Portrait of Ayush Lalbegi, the Topper">
                <h3>Ayush Lalbegi</h3>
                <p>The Topper</p>
            </div>
            <div class="card">
                <img src="profile16.jpg" alt="Portrait of Jay Chourasia, the Cricketer">
                <h3>Jay Chourasia</h3>
                <p>The Cricketer</p>
            </div>
            <div class="card">
                <img src="profile17.jpg" alt="Portrait of Sejan Hasmi, the Dreamer">
                <h3>Sejan Hasmi</h3>
                <p>The guy with dreams</p>
            </div>
            <div class="card">
                <img src="profile18.jpg" alt="Portrait of Ayush Chandra, the Artist">
                <h3>Ayush Chandra</h3>
                <p>The Artist</p>
            </div>
        </div>
    </section>
<section id="contact">
        <h2>contact</h2>
        <p>for contact call 7001637175 or email at hiransinghbabu72@gmail.com
    </section>
    <footer>
        <p>&copy; 2024 KB Boys. All rights reserved.</p>
    </footer>
</body>
</html>
