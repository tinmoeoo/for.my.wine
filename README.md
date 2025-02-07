# My Valentine's Website ❤️  
This is a romantic website for Wainn, created with love. 💕  

## How to View the Website  
1. Open the website link: [GitHub Pages Link](https://your-username.github.io/for-my-wainn/)  
2. Enjoy the lovely surprise! 💖  

---  

## Website Code  
```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Be My Valentine ❤️</title>
    <style>
        body {
            text-align: center;
            background: linear-gradient(to bottom, #ffcccc, #ff99cc);
            font-family: 'Arial', sans-serif;
            position: relative;
        }
        .corner-image {
            position: absolute;
            width: 120px;
            height: 120px;
            border-radius: 0px;
            box-shadow: 0px 4px 8px rgba(0, 0, 0, 0.2);
        }
        .top-left { top: 30px; left: 15px; }
        .top-right { top: 15px; right: 25px; }
        .bottom-left { bottom: 20px; left: 25px; }
        .bottom-right { bottom: 15px; right: 15px; }
        .container {
            margin-top: 50px;
            position: relative;
            display: inline-block;
            animation: fadeIn 2s ease-in-out;
        }
        h1 {
            color: red;
            font-size: 2.5em;
            animation: heartbeat 1.5s infinite;
        }
        .image-container {
            position: relative;
            display: inline-block;
        }
        .image-container img {
            width: 250px;
            height: auto;
            border-radius: 15px;
            margin: 20px;
            box-shadow: 0px 4px 8px rgba(0, 0, 0, 0.2);
            animation: float 3s infinite ease-in-out;
        }
        .buttons button {
            font-size: 20px;
            padding: 10px 20px;
            margin: 10px;
            border: none;
            border-radius: 0px;
            cursor: pointer;
            transition: all 0.3s ease-in-out;
        }
        .yes { background-color: #ff4d4d; color: white; }
        .yes:hover { background-color: #cc0000; transform: scale(1.1); }
        .absolutely { background-color: #ffcc00; color: black; }
        .absolutely:hover { background-color: #e6b800; transform: scale(1.1); }
        .hidden {
            display: none;
            font-size: 1.8em;
            color: red;
            margin-top: 20px;
            animation: fadeIn 1.5s ease-in-out;
        }
        @keyframes floatText {
            0% { transform: translateY(0px); }
            50% { transform: translateY(-10px); }
            100% { transform: translateY(0px); }
        }
    </style>
</head>
<body>
    <img src="https://imgur.com/5P9ybM2.jpg" class="corner-image top-left" alt="Corner Photo">
    <img src="https://imgur.com/E78msMi.jpg" class="corner-image top-right" alt="Corner Photo">
    <img src="https://imgur.com/JbnZhsO.jpg" class="corner-image bottom-left" alt="Corner Photo">
    <img src="https://imgur.com/LVrBvh5.jpg" class="corner-image bottom-right" alt="Corner Photo">
    
    <div class="container">
        <div class="image-container">
            <img src="https://tenor.com/view/please-gif-6115078344733356394.gif" alt="Cute GIF">
        </div>
        <h1 style="font-family: 'Dancing Script', cursive; font-size: 3em; color: #ff3366; animation: floatText 3s infinite ease-in-out;">My Dearest Wainn, Will You Make My Heart The Happiest By Being My Valentine? 💖</h1>
        <div class="buttons">
            <button class="yes" onclick="showLove('yes')">Yes</button>
            <button class="absolutely" onclick="showLove('absolutely')">Absolutely Yes!</button>
        </div>
        <div id="love-message" class="hidden"></div>
    </div>

    <script>
        function showLove(choice) {
            let message = choice === 'absolutely' 
                ? "Congratulations! 🎉 Now you've become the most handsome guy's Valentine! ❤️"
                : "Yay! ❤️ You are my everything, my love! 😘";
            document.getElementById('love-message').innerText = message;
            document.getElementById('love-message').style.display = 'block';
            
            if (choice === 'absolutely') {
                let gif = document.createElement('img');
                gif.src = 'https://tenor.com/view/peach-goma-peach-heart-gif-4275715884831483873.gif';
                gif.alt = 'Peach Goma Heart GIF';
                gif.style.marginTop = '20px';
                document.getElementById('love-message').appendChild(gif);
            }
        }
    </script>
</body>
</html>
```

---  

### 🎉 **Enjoy Your Valentine's Website!**  
Let me know if you need any help! 😊💕  
