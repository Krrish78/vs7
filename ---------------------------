<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>A.I VOICE SINGER</title>
    <style>
        body {
            margin: 0;
            padding: 0;
            background-color: #fff; /* White background */
            color: #000; /* Black text */
            overflow: hidden; /* Prevent scrolling */
        }

        /* Header */
        h1 {
            margin: 20px 0;
            text-align: center;
            font-size: 2rem;
            z-index: 2;
            position: absolute;
            top: 10px;
            width: 100%;
        }

        /* Main container with iframe */
        .main-container {
            display: flex;
            justify-content: center;
            align-items: flex-start; /* Align iframe to the top */
            height: 100vh;
            padding-top: 100px; /* Padding to keep space between header and iframe */
        }

        iframe {
            display: block;
            width: 80vw; /* Adjusted to make iframe a little smaller */
            height: 75vh; /* Adjusted height to make iframe smaller */
            border: none;
            border-radius: 10px;
            box-shadow: 0 4px 10px rgba(0, 0, 0, 0.2); /* Subtle shadow */
        }

        /* Falling music logos */
        .music-logo {
            position: absolute;
            width: 30px;
            height: 30px;
            background: url('https://upload.wikimedia.org/wikipedia/commons/7/73/Music-note.svg') no-repeat center;
            background-size: contain;
            animation: fall linear infinite;
        }

        @keyframes fall {
            0% {
                transform: translateY(-100px);
                opacity: 1;
            }
            100% {
                transform: translateY(100vh);
                opacity: 0.2;
            }
        }
    </style>
</head>
<body>
    <h1>A.I VOICE SINGER</h1>
    <div class="main-container">
        <iframe
            src="https://krish778-singerai4.hf.space"
            frameborder="0"
            width="850"
            height="450">
        </iframe>
    </div>

    <script>
        // Generate falling music logos
        function createMusicLogo() {
            const logo = document.createElement('div');
            logo.classList.add('music-logo');
            logo.style.left = Math.random() * 100 + 'vw';
            logo.style.animationDuration = Math.random() * 5 + 5 + 's'; // Random speed
            logo.style.opacity = Math.random() * 0.7 + 0.3; // Random opacity
            document.body.appendChild(logo);

            // Remove the logo after animation
            logo.addEventListener('animationend', () => {
                logo.remove();
            });
        }

        // Create multiple logos every 300ms
        setInterval(createMusicLogo, 300);
    </script>
</body>
</html>
