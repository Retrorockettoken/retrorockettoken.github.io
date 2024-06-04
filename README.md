# retrorockettoken.github.io
No iremos a la Luna llegaremos a Martes 
### HTML (index.html)

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Preventa Retro Rocket Token</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <h1>Retro Rocket Token - Preventa</h1>
    </header>

    <main>
        <section class="about">
            <h2>¿Qué es Retro Rocket Token?</h2>
            <p>Retro Rocket Token es un memecoin diseñado para llevarnos de vuelta a los días más nostálgicos de la era espacial. Únete a la preventa exclusiva y sé parte de esta emocionante aventura.</p>
        </section>

        <section class="presale-form">
            <h2>Únete a la Preventa</h2>
            <form id="presaleForm">
                <label for="walletAddress">Dirección de Cartera:</label>
                <input type="text" id="walletAddress" name="walletAddress" required>
                
                <label for="amount">Cantidad a Comprar (ETH):</label>
                <input type="number" id="amount" name="amount" required min="0.1" step="0.1">
                
                <button type="submit">Participar en la Preventa</button>
            </form>
        </section>
    </main>

    <footer>
        <p>&copy; 2023 Retro Rocket Token. Todos los derechos reservados.</p>
    </footer>

    <script src="script.js"></script>
</body>
</html>
```
