<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Sha's Biography</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #a67b5b; /*  Dark nude background tengah*/
            color: #333; /* Dark text color */
        }

        header {
            background-color: #a67b5b; /*  Dark nude background atas*/
            color: #fff;
            padding: 20px;
            text-align: center; /* Center align header text */
        }

        nav ul {
            list-style-type: none;
            margin: 0;
            padding: 0;
            text-align: center; /* Center align navigation links */
        }

        nav ul li {
            display: inline;
            margin-right: 20px;
        }

        nav ul li a {
            color: #333; /*Tulisan bawah welcome*/
            text-decoration: none;
            font-size: 18px; /* Increase font size */
            transition: color 0.3s; /* Smooth color transition */
        }

        nav ul li a:hover {
            color: #fff; /* Change text color on hover */
        }

        section {
            padding: 30px;
            margin-bottom: 30px;
            background-color: #f5f5dc; /* beige background besar tengah */
            border-radius: 10px; /* Rounded corners for sections */
            box-shadow: 0px 0px 10px rgba(0, 0, 0, 0.1); /* Drop shadow effect */
        }

        .container {
            display: flex;
            align-items: center;
            justify-content: space-between;
        }

        .description {
            flex: 1;
            padding-right: 20px; /* Add some spacing between description and image */
            text-align: justify;
        }

        .image {
            flex: 1;
            text-align: center;
        }

        .image img {
            width: 60%; /* Adjusted width to 80% */
            height: auto;
            border-radius: 10px; /* Rounded corners for the image */
            margin-bottom: 10px;
        }

        footer {
            background-color: #ddc0b4; /* Pink nude background paling bawah */
            color: #333;
            padding: 20px;
            position: fixed;
            bottom: 0;
            width: 100%;
            text-align: center;
        }

        /* Larger title */
        h1 {
            font-size: 32px;
            margin-bottom: 10px;
        }

        /* Grid for introduction images */
        .introduction-grid {
            display: grid;
            grid-template-columns: repeat(2, 1fr);
            gap: 20px;
        }

        /* Grid item */
        .introduction-item {
            display: flex;
            flex-direction: column;
            align-items: center;
            text-align: center;
        }

        /* Contact form styles */
        form {
            margin-top: 20px;
            text-align: center;
        }

        label {
            display: block;
            margin-bottom: 5px;
            font-weight: bold;
        }

        input[type="text"],
        input[type="email"],
        textarea {
            width: 50%;
            padding: 10px;
            margin-bottom: 10px;
            border-radius: 5px;
            border: 1px solid #ccc;
            box-sizing: border-box;
        }

        textarea {
            resize: vertical;
        }

        input[type="submit"] {
            background-color: #a67b5b; /*caffe latte block*/
            color: #fff;
            border: none;
            padding: 10px 20px;
            border-radius: 5px;
            cursor: pointer;
            transition: background-color 0.3s;
        }

        input[type="submit"]:hover {
            background-color: #6f4e37; /*roasted cocoa bayang-bayang block*/
        }

        /* Styling for 3 social media buttons */
        button {
            background-color: #a67b5b; /*caffe latte block*/
            color: #fff;
            border: none;
            padding: 10px 20px;
            border-radius: 5px;
            cursor: pointer;
            transition: background-color 0.3s;
        }

        button:hover {
            background-color: #6f4e37; /*roasted cocoa bayang-bayang block*/

        }
    </style>
</head>
<body>
    <header>
        <h1>B I O G R A P H Y</h1>
        <nav>
            <ul>
                <li><a href="#" onclick="showSection('about')">About Me</a></li>
                <li><a href="#" onclick="showSection('activity')">Activities</a></li>
                <li><a href="#" onclick="showSection('people')">People</a></li>
                <li><a href="#" onclick="showSection('contact')">Contact</a></li>
            </ul>
        </nav>
    </header>



<section id="about">
   <div class="container">
       <div class="description">
           <h2>Me</h2>
           <p>Welcome to my world!<p> 
My name is Nurul Umi Natasha Binti Md.Saudi. I'm 23 years old. I'm Ubianese from Kota Belud, Sabah. I pursued a degree in Vocational Education (Creative Multimedia) with honors at Universiti Tun Hussein Onn Malaysia. I am the fifth child of six siblings. I am a third-year student and i'll be leaving from uni soon. Wish me luck to become a teacher in thefuture!</p>

            <!-- Add Instagram, Facebook, and TikTok buttons -->
            <div>
              <a href="https://www.instagram.com/natashasaudi?igsh=anFiNnN4bnVhODBy&utm_source=qr" target="_blank"><button>Instagram</button></a>

              <a href="https://www.facebook.com/natashasaudi/" target="_blank"><button>Facebook</button></a>

              <a href="https://www.tiktok.com/@ntshsdi?_t=8o818lkGF3B&_r=1"_blank"><button>TikTok</button></a>
        </div>
           </div>
             <div class="image">
             <img src="profile picture.jpg" alt="Profile Picture">
           </div>
        </div>
<br><br><br>

    </section>


<section id="activity">
    <h2>Activities</h2>
    <p>These are my usual activities when i'm free.</p>
<hr>

<p><br>
    <img src="singing.jpg" align="centre" height="200" width="200"/> 
<p> I love to singing. I have a few songs i have covered and posted it on my social media. </p>

<!-- Embedding the audio player for the MP3 file -->
<p> So, this is one of my cover song i covered during MCO. I was bored that time, so i try to sang this song and i did it! So enjoy! <3 </p>

    <audio controls>
        <source src="Heather_Sri.mp3" type="audio/mp3">
        Your browser does not support the audio element.
    </audio>
<br><br><hr>

<!-- Embedding the audio player for the MP3 file -->
<audio controls>
        <source src="Anji.mp3" type="audio/mp3">
        Your browser does not support the audio element.
    </audio>
<br><br><hr>


<br><p>
    <img src="drawing.jpg" align="centre" height="200" width="200"/>
<img src="drawing 1.jpg" align="centre" height="300" width="200"/>
<p> I also love to draw some picture randomly but it depends on my mood. I draw the doodle last year and all four picture i draw 2 years ago.
</p>
<br><hr>

<br><p>
    <img src="editing.jpg" align="centre" height="200" width="200"/>
<p> Editing is my favourite activity too. I'll edit my photos or videos when i have a free time. In the picture above, i attended my 3D class, we have to make a 3D plane using a 3Ds Max Software. This is very exciting and i love it!
</p>
<br><hr>

<br><p>
    <img src="music.jpg" align="centre" height="200" width="200"/>
<p> One good thing about music is when it hits you, you feel no pain. The music also reminds us of the past. This is a reason why i love to listening to music. It had it's own story.
</p>
<br><hr>

    <p>Acting is my favourite activity. Why? Because ii teach me to understand other people feeling. Such as, if I take on the role of a victim, I can feel and understand the soul of a victim. Here, I can identify and empathize the others feelings. <br><br>
So, here is my short video i've made 2 semester ago. Do watch it! </p><br>

    <title>Embedded YouTube Video</title>
	<iframe width="500" height="315"
	src="https://www.youtube.com/embed/02z3dNzoMDg">
</iframe>

	<br><br>
Don't forget to like, share and subscribe my youtube channel :<a href="page1.html">
<img src="Youtube.png" width="50" height="32" align="bottom"/></a> 
<br><br><br><br><br>


</section>


    <section id="people">
        <h2>People</h2>
        <p>Family, friends and love are the foundation of a happy life. They are our backbone who are keep supporting us when we fall down.  </p><hr>

<p><br>
    <img src="family.jpg" align="centre" height="300" width="400"/>
<p>First family photo with complete members in 2019. After that, Abang Sopy has faced to His Creator. Al-Fatihah.
<br><br><hr>

<p><br><br>
    <img src="family 2.jpg" align="centre" height="300" width="400"/>
<p>This is our family photo with incomplete members. We took this picture on Hari Raya last year.
<br><br><hr>

<p><br><br>
    <img src="love 2.jpg" align="centre" height="400" width="400"/>
<p>My soulmate. InsyaAllah. Do pray the best for us. Hehe
<br><br><hr>

<p><br><br>
    <img src="friends.jpg" align="centre" height="400" width="500"/>
<p>My lovely friends. We have another year and half together before we seperate with our respective journeys. Hopefully, we can survive until the end. Aminnn. <p>
<br><br><br>

    </section>

    <section id="contact">
        <h2>Contact</h2>
        <p>Please contact me via the form below or through email.</p>
        <form action="contact.php" method="POST">
            <label for="name">Name:</label>
            <input type="text" id="name" name="name"required><br>
            <label for="email">Email:</label>
            <input type="email" id="email" name="email"required><br>
            <label for="message">Message:</label><br>
            <textarea id="message" name="message" rows="4" required></textarea><br>
            <input type="submit" value="Send">
        </form>
    </section>


    <footer>
        <p>&copy; 2024 Sha's Biography.</p>
    </footer>

    <script>
        // Function to toggle section visibility
        function showSection(sectionId) {
            // Hide all sections
            var sections = document.getElementsByTagName('section');
            for (var i = 0; i < sections.length; i++) {
                sections[i].style.display = 'none';
            }
            // Show the selected section
            var selectedSection = document.getElementById(sectionId);
            if (selectedSection) {
                selectedSection.style.display = 'block';
            }
        }

        // Show the about section by default
        window.onload = function() {
            showSection('about');
        };
    </script>
</body>
</html>
