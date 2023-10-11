<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Samprati Didi :)</title>

    <style>
        body {
            font-family: 'Arial', sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f0f0f0;
            font-size: 20px;
            font-weight: bold;
        }

                /* Dark mode */
                body.dark-mode {
            background-color: #1f1f1f;
            color: white;
        }

        header {
            text-align: center;
            background-color: #ae00ff;
            color: black, white, blue, green, yellow, red,orangered, purple, skyblue, pink;
            padding: 15px;
        }
        h1 {
            /* color: #ffffff; */
            color: linear-gradient(to right, violet, indigo, blue, green, yellow, orange, red);
            text-align: center;
            border-radius: 5px;
            box-shadow: 0 2px 5px rgb(0, 0, 0);
            transition: background 0.5s ease, transform 0.3s ease;
            /* animation: pulse 1s infinite ease-in-out; */
            text-shadow: rgb(255, 255, 255);

        }

        section {
            margin: 20px;
            text-align: center;
        }


        img {
             border-radius: 0.3cm;
            }
                .card {
                --background: linear-gradient(to left, #2bf0f7 10%, #f700ff 100%);
                width: 170px;
                height: 256px;
                padding: 6px;
                border-radius: 1rem;
                overflow: visible;
                background: transparent;
                /* background: var(--background); */
                /* position: relative; */
                z-index: 1;
                margin: 0 auto; /* Center the card horizontally */

               }
               
               .card::after {
                position: absolute;
                content: "";
                top: 30px;
                left: 0;
                right: 0;
                z-index: -1;
                height: 100%;
                width: 100%;
                transform: scale(1.0);
                filter: blur(100px);
                background: #2bdff7, red;
                background: red;
                background: var(--background);
                transition: opacity .5s;
               }
               
               .card-info {
                --color: #ffffff;
                background: var(--color);
                color: var(--color);
                display: flex;
                justify-content: center;
                align-items: center;
                width: 100%;
                height: 100%;
                overflow: visible;
                border-radius: .7rem;
               }
               
               
               /*Hover*/
               .card:hover::after {
                opacity: 0;
               }
               
               .card:hover .card-info {
                color: #1100ff;
                color: red;
                transition: color 1s;
               }

            video {
            max-width: 80%;
            height: auto;
            border-radius: 10px;
            --background: linear-gradient(to left, #2bf0f7 10%, #f700ff 100%);
            .card {
                --background: linear-gradient(to left, #2bf0f7 10%, #f700ff 100%);
                width: 170px;
                height: 256px;
                padding: 6px;
                border-radius: 1rem;
                overflow: visible;
                background: transparent;
                /* background: var(--background); */
                /* position: relative; */
                z-index: 1;
                margin: 0 auto; /* Center the card horizontally */

               }
               
               .card::after {
                position: absolute;
                content: "";
                top: 30px;
                left: 0;
                right: 0;
                z-index: -1;
                height: 100%;
                width: 100%;
                transform: scale(1.0);
                filter: blur(100px);
                background: #2bdff7, red;
                background: red;
                background: var(--background);
                transition: opacity .5s;
               }
               
               .card-info {
                --color: #ffffff;
                background: var(--color);
                color: var(--color);
                display: flex;
                justify-content: center;
                align-items: center;
                width: 100%;
                height: 100%;
                overflow: visible;
                border-radius: .7rem;
               }
               
               
               /*Hover*/
               .card:hover::after {
                opacity: 0;
               }
               
               .card:hover .card-info {
                color: #1100ff;
                color: red;
                transition: color 1s;
               }
        }

        audio {
            width: 100%;
            height: 54px;
            margin-top: 20px;
        }

        #poem {
            text-align: center;
            /*Hover*/
            .card:hover::after {
                opacity: 0;
               }
            text-align: center;
            border-radius: 10px;
            box-shadow: 0 20px 50px #ea00ff, rgb(0, 238, 255);
            box-shadow: 0 20px 50px #00ccff;

            transition: background 0.5s ease, transform 0.3s ease;
            text-shadow: rgb(204, 0, 255);
            animation: colorChange1 5s infinite alter

        }

        .colorfulButton {
            background: linear-gradient(to right, violet, indigo, blue, green, yellow, orange, red);
            border: 2px solid transparent;
            color: rgb(73, 71, 71);
            padding: 15px 32px;
            text-align: center;
            text-decoration: none;
            display: inline-block;
            font-size: 20px;
            margin: 4px 2px;
            cursor: pointer;
            border-radius: 5px;
            box-shadow: 0 2px 5px rgba(0, 0, 0, 0.2);
            transition: background 0.5s ease, transform 0.3s ease;
            animation: pulse 1s infinite ease-in-out;
        }

        .colorfulButton:hover {
            transform: scale(1.05);
        }

        @keyframes pulse {
            0% {
                transform: scale(1);
            }
            50% {
                transform: scale(1.1);
            }
            100% {
                transform: scale(1);
            }
        }

        /* Add styling for the Change Color button */
        #changeColorButton {
            position: fixed;
            top: 10px;
            right: 10px;
            background-color: #4CAF50;
            border: none;
            color: white;
            padding: 10px 20px;
            font-size: 14px;
            cursor: pointer;
            border-radius: 5px;
            box-shadow: 0 2px 5px rgba(0, 0, 0, 0.2);
            transition: background-color 0.2s ease-in-out;
        }

        #changeColorButton:hover {
            background-color: #00eeff;
        }
        
        
        body {
            font-family: 'Arial', sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f0f0f0;
            font-size: 20px;
            font-weight: bold;
        }

        header {
            text-align: center;
            background-color: #ae00ff;
            color: white;
            padding: 15px;
        }

        /* Define keyframes for different colors */
        @keyframes colorChange1 {
            5% { color: violet; }
            5% { color: indigo; }
            15% { color: blue; }
            10% { color: green; }
            10% { color: yellow; }
            100% { color: orangered; }
            5% { color: violet; }
            2% { color: indigo; }
            25% { color: blue; }
            10% { color: green; }
            15% { color: yellow; }
            1% { color: purple; }
            15% { color: orangered; }
            10% {color:rgb(0, 217, 255); }
            30% {color:rgb(174, 0, 255); }
            5% {color:rgb(255, 0, 170); }
            15% {color:rgb(51, 255, 0); }
            5% {color:red; }
            15% {color:rgb(255, 38, 0); }
            30% {color:rgb(255, 255, 255); }
            1% {color:rgb(0, 0, 0); }
            
        }

        @keyframes colorChange2 {
            50% { color: violet; }
            50% { color: rgb(195, 0, 255); }
            50% { color: blue; }
            50% { color: green; }
            50% { color: yellow; }
            50% { color: purple; }
            50% { color: orangered; }
            50% {color:rgb(0, 217, 255); }
            50% {color:rgb(174, 0, 255); }
            50% {color:rgb(255, 0, 170); }
            50% {color:rgb(51, 255, 0); }
            50% {color:red; }
            50% {color:rgb(255, 38, 0); }
            1% {color:rgb(255, 255, 255); }
            
        }

        h1 {
            text-align: center;
            border-radius: 5px;
            box-shadow: 0 2px 5px rgb(0, 0, 0);
            transition: background 0.5s ease, transform 0.3s ease;
            text-shadow: rgb(102, 100, 100);
            animation: colorChange1 5s infinite alternate;
        }

        #image-section h1 {
            animation: colorChange2 5s infinite alternate;
        }
    
        /* Dark mode button styles */
        #darkModeButton {
            position: fixed;
            top: 10px;
            left: 10px;
            background-color: #000000;
            border: none;
            color: white;
            padding: 10px 20px;
            font-size: 14px;
            cursor: pointer;
            border-radius: 5px;
            box-shadow: 0 2px 5px rgba(0, 0, 0, 0.2);
            transition: background-color 0.2s ease-in-out;
        }

        #darkModeButton:hover {
            background-color: #555;
        }

        /* Dark mode icon styles */
        .dark-mode-icon {
            font-size: 24px;
        }

    </style>
</head>
<body>
    <header>
        <h1><span id="typing-text-1">धन्यवाद😊 :)</span></h1>
    </header>
    <nav>
        <ul>
            <li><a href="#image-section">Image</a></li>
            <li><a href="#smile-please-section">Smile Please😊</a></li>
            <li><a href="Naan Pizhai.mp3">Audio</a></li>
            <li><a href="#video-section">Video</a></li>
            <li><a href="#poem-section">Poem</a></li>
        </ul>
    </nav>
<Style>
    /* Navigation menu styles */
nav ul {
    list-style-type: none;
    margin: 0;
    padding: 0;
    text-align: center;
}

nav ul li {
    display: inline;
    margin: 0 15px;
}

nav ul li a {
    text-decoration: none;
    color: #050505;
    font-weight: bold;
    font-size: 18px;
    transition: color 0.3s ease-in-out;
}

nav ul li a:hover {
    color: #00c3ff; /* Change the color on hover */
}
/* Common styles for body and header */
body, header {
    font-family: 'Arial', sans-serif;
    margin: 0;
    padding: 0;
    font-size: 20px;
    font-weight: bold;
}

header {
    text-align: center;
    background-color: #ae00ff;
    color: white;
    padding: 15px;
}
</Style>

    <section id="image-section">
      <h1><span id="typing-text-2">Samprati Didi😊🥰 :)</span></h1>        
      




      <button id="PlayButton" class="colorfulButton">Smile Please😊</button>

        <div class="sister">
            <div class="card">
                <div class="card-info">
                  <img id="image" src="Samprati Didi.png" width="1000" height="255">
            <style>
                
               </style>
               </div>
              </div>
            
            <p>My sister Samprati Didi. She is the best sister anyone could ask for.</p>
        </div>
    </section>

    <!-- Audio player section -->
    <audio src="TEST AUDIO.mp3" controls autoplay loop></audio>

    <section id="video-section">
        <video autoplay controls loop width="600">
            <source src="Didi.mp4" type="video/mp4">
        </video>
    </section>

    <section id="poem-section">
        <div id="poem">
            <p>Sisters are the second version of mother. She will give you advice, protect you and Scold you, but will never tolerate if Someone hurts you.</p>
            <p><b>Radhe Radhe My Sister😊🥰</b></p>
        </div>
        <button class="changeColorButton" id="changeColorButton">Change Color</button>
    </section>

        <!-- Dark mode button -->
        <button id="darkModeButton" onclick="toggleDarkMode()">
            <span class="dark-mode-icon">&#127771;</span> Dark Mode
        </button>

    <script>
        // Function to simulate computer typing effect
        function typeText(element, text, delay) {
            let index = 0;
            const typingInterval = setInterval(function () {
                if (index < text.length) {
                    const currentText = text.slice(0, index + 1);
                    document.getElementById(element).textContent = currentText;
                    index++;
                } else {
                    clearInterval(typingInterval); // Stop typing animation
                    setTimeout(function () {
                        // Reset the text and start typing again
                        document.getElementById(element).textContent = '';
                        index = 0;
                        typeText(element, text, delay);
                    }, 1000); // Adjust the delay before restarting the animation (1 second in this example)
                }
            }, delay);
        }

        // Call the typing effect function for your h1 elements
        window.onload = function () {
            typeText('typing-text-1', 'स्वागतम् 😊 :)', 100); // Adjust the delay as needed
            typeText('typing-text-2', 'Samprati Didi😊🥰 :)', 100); // Adjust the delay as needed
        };
        alert("राधे कृष्ण संप्राति दीदी :)");
        document.addEventListener('DOMContentLoaded', function () {
            const header = document.querySelector('header');
            const changeColorButton = document.getElementById('changeColorButton');

            // Add a click event listener to the header
            header.addEventListener('click', function () {
                alert('एक अद्भुत दीदी होने के लिए धन्यवाद बहना :)');
            });

            // Pop-up
            document.getElementById('PlayButton').addEventListener('click', function () {
                // Create a new pop-up window
                var popupWindow = window.open('', '_blank', 'width=400,height=300');
                // Write the video HTML to the pop-up window
                popupWindow.document.write('<video src="Muskurao- By Nayab Midha.mp4" autoplay controls width="100%" height="100%">Play</video>');
            });

            // Add a click event listener to the button
            changeColorButton.addEventListener('click', function () {
                // Generate a random color
                const randomColor = getRandomColor();

                // Change the background color of the body
                document.body.style.backgroundColor = randomColor;

                // Display a personalized message
                alert('आशा करता की यह रंग आपको पसंद आएगा दीदी :)');
            });

            // Function to generate a random color
            function getRandomColor() {
                const letters = '0123456789ABCDEF';
                let color = '#';
                for (let i = 0; i < 6; i++) {
                    color += letters[Math.floor(Math.random() * 16)];
                }
                return color;
            }
        });

        // Toggle dark mode
        function toggleDarkMode() {
            const body = document.body;
            body.classList.toggle('dark-mode');
        }
    </script>
</body>
</html>
