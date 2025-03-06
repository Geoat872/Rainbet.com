<!DOCTYPE html>
<html lang="de">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Online Gambling</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <header>
        <h1>Willkommen beim Online Casino!</h1>
    </header>

    <section id="login">
        <h2>Einloggen</h2>
        <form id="login-form">
            <input type="text" id="username" placeholder="Benutzername" required>
            <input type="password" id="password" placeholder="Passwort" required>
            <button type="submit">Einloggen</button>
        </form>
    </section>

    <section id="game-selection">
        <h2>Wähle ein Spiel</h2>
        <button onclick="startGame('slots')">Spielautomaten</button>
        <button onclick="startGame('poker')">Poker</button>
        <button onclick="startGame('roulette')">Roulette</button>
    </section>

    <footer>
        <p>&copy; 2025 Online Casino</p>
    </footer>

    <script src="script.js"></script>
</body>
</html>
2. CSS – Style für die Seite
css
Kopieren
body {
    font-family: Arial, sans-serif;
    background-color: #f4f4f4;
    text-align: center;
}

header {
    background-color: #333;
    color: #fff;
    padding: 20px;
}

section {
    margin: 20px 0;
}

button {
    background-color: #28a745;
    color: white;
    padding: 10px 20px;
    border: none;
    cursor: pointer;
    font-size: 16px;
}

button:hover {
    background-color: #218838;
}
