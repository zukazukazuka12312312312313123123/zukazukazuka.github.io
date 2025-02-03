<!DOCTYPE html>
<html lang="ka">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>გამაოცებელი HTML საიტი</title>
</head>
<body style="background-color: black; color: white; font-family: Arial, sans-serif; text-align: center;">

    <!-- მბზინავი ანიმაცია (მარტივი marquee) -->
    <marquee style="font-size: 50px; font-weight: bold; color: #ff1493;">გამაოცებელი HTML საიტი!</marquee>

    <!-- ბრწყინვალე ტექსტი, რომელიც ელვარებს -->
    <h1 style="font-size: 60px; font-weight: bold; text-shadow: 0 0 10px #ff1493, 0 0 20px #ff1493; animation: glowing 1.5s infinite alternate;">
        HTML მაგია
    </h1>

    <!-- ტექსტი, რომელიც ცვალებადი იქნება -->
    <p style="font-size: 20px;">გპირდები, რომ ეს მხოლოდ დასაწყისია!</p>

    <!-- ბრწყინვალე ტექსტი -->
    <blink>🔮</blink>

    <script>
        // JavaScript-ის მოკლე სკრიპტი, რომ ტექსტი გადამორთვას
        setTimeout(function() {
            document.querySelector("h1").innerHTML = "თქვენი HTML საიტი მუშაობს!";
        }, 3000); // 3 წამში ტექსტი შეიცვლება
    </script>

</body>
</html>
