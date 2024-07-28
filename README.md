<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Display Numbers</title>
</head>
<body>
    <script src="script.js"></script>
    
    <div id="numberList"></div>

    <script>
        const numberListDiv = document.getElementById('numberList');

        for (let i = 1; i <= 100; i++) {
            const p = document.createElement('p');
            p.textContent = i;
            numberListDiv.appendChild(p);
        }
    </script>
</body>
</html>
