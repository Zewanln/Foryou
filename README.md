# Rywannftpp
Lol
<!DOCTYPE html><html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Will You Be My Girlfriend?</title>
    <style>
        body {
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh;
            background-color: pink;
            text-align: center;
            font-family: Arial, sans-serif;
        }
        .container {
            background: white;
            padding: 20px;
            border-radius: 10px;
            box-shadow: 0 4px 10px rgba(0, 0, 0, 0.2);
        }
        .buttons {
            margin-top: 20px;
        }
        .buttons button {
            padding: 10px 20px;
            font-size: 18px;
            margin: 10px;
            cursor: pointer;
            border: none;
            border-radius: 5px;
        }
        .yes {
            background-color: lightgreen;
        }
        .no {
            background-color: lightcoral;
            position: absolute;
        }
    </style>
</head>
<body>
    <div class="container">
        <h1>Lia, will you be my girlfriend?</h1>
        <div class="buttons">
            <button class="yes" onclick="alert('Yay! I love you, Lia! ❤️')">Yes</button>
            <button class="no" onmouseover="moveButton(this)">No</button>
        </div>
    </div><script>
    function moveButton(button) {
        const x = Math.random() * (window.innerWidth - button.clientWidth);
        const y = Math.random() * (window.innerHeight - button.clientHeight);
        button.style.left = `${x}px`;
        button.style.top = `${y}px`;
    }
</script>

</body>
</html>
