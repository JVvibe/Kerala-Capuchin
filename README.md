# Kerala Capuchin
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Kerala Capuchin</title>
    <style>
        body {
            background-image: url("background-image.jpg");
            background-size-fit-screen: cover;
            background-position: center;
        }
    </style>
</head>
<body>
    <nav>
        <ul>
            <li><a href="#home">Home</a></li>
            <li><a href="#about">About</a></li>
            <li><a href="#result">Result</a></li>
            <li><a href="#directory">Directory</a></li>
        </ul>
    </nav>

    <div id="home">
        <h1>Welcome to Kerala Capuchin</h1>
        <p>History of Kerala Capuchin:</p>
        <p>The Kerala Capuchin is a unique and fascinating species native to the beautiful region of Kerala, India. They have a rich history that dates back centuries...</p>

        <p>Different Provinces:</p>
        <p>Kerala is divided into several provinces, each with its distinct features and habitats. These provinces are home to different groups of capuchins, each adapting to...</p>

        <p>Aim of Kerala Capuchin:</p>
        <p>The Kerala Capuchin aims to promote conservation efforts for the species, protect their natural habitats, and raise awareness about their ecological importance...</p>

        <p>Ministries of Kerala Capuchin:</p>
        <p>The Kerala Capuchin is governed by various ministries that oversee research, conservation projects, and educational initiatives. These ministries collaborate...</p>
    </div>

    <div id="about">
        <!-- About section content goes here -->
    </div>

    <div id="result">
        <!-- Result section content goes here -->
    </div>

    <div id="directory">
        <!-- Directory section content goes here -->
    </div>

    <!-- Image Carousel -->
    <div class="carousel">
        <img src="slide1.jpg" alt="Slide 1">
        <img src="slide2.jpg" alt="Slide 2">
        <img src="slide3.jpg" alt="Slide 3">
        <!-- Add more images as needed -->
    </div>

    <script>
        // JavaScript for the image carousel
        const carousel = document.querySelector(".carousel");
        const images = carousel.querySelectorAll("img");
        let currentSlide = 0;

        function showSlide(slideIndex) {
            images.forEach((image, index) => {
                if (index === slideIndex) {
                    image.style.display = "block";
                } else {
                    image.style.display = "none";
                }
            });
        }

        function nextSlide() {
            currentSlide = (currentSlide + 1) % images.length;
            showSlide(currentSlide);
        }

        // Set the interval for automatic slide change (adjust duration as needed)
        const interval = 3000; // 3 seconds
        setInterval(nextSlide, interval);

        // Show the first slide initially
        showSlide(currentSlide);
    </script>

</body>
</html>
![background-image](https://github.com/JVvibe/keralacapuchin.com/assets/139759474/c4cf2124-8168-4dba-9269-448a0caa3423)
![slide3](https://github.com/JVvibe/keralacapuchin.com/assets/139759474/918c25a2-e9a3-4154-99f9-a36f6a5902b8)
![slide2](https://github.com/JVvibe/keralacapuchin.com/assets/139759474/ccbae4e8-7b8c-4cad-a8d7-7850f8812acb)
![slide1](https://github.com/JVvibe/keralacapuchin.com/assets/139759474/027f6443-a6bd-4c8e-83d6-298dbb4bc15d)
