<html lang="fr">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Apprendre l'Informatique - Seniors</title>
    <style>
        body { font-family: Arial, sans-serif; text-align: center; padding: 20px; background: #eef; }
        nav { margin-bottom: 20px; background: #007BFF; padding: 10px; border-radius: 5px; }
        nav a { margin: 10px; text-decoration: none; font-size: 20px; color: white; font-weight: bold; }
        section { max-width: 700px; margin: auto; padding: 20px; border: 1px solid #ccc; border-radius: 10px; background: #fff; box-shadow: 2px 2px 10px rgba(0,0,0,0.1); }
        h1 { color: #333; }
        button { padding: 10px 20px; font-size: 18px; background: #007BFF; color: white; border: none; border-radius: 5px; cursor: pointer; }
        button:hover { background: #0056b3; }
    </style>
</head>
<body>
    <h1>Bienvenue sur le site d'apprentissage informatique</h1>
    <nav>
        <a href="#accueil">Accueil</a>
        <a href="#cours">Cours</a>
        <a href="#faq">FAQ</a>
        <a href="#contact">Contact</a>
    </nav>
    
    <section id="accueil">
        <h2>Accueil</h2>
        <p>Ce site est conçu pour aider les seniors à apprendre l'informatique facilement et en toute simplicité.</p>
    </section>
    
    <section id="cours">
        <h2>Cours</h2>
        <p>Découvrez des cours adaptés à votre rythme : utiliser un ordinateur, envoyer un email, naviguer sur Internet...</p>
        <button onclick="alert('Accédez aux cours détaillés bientôt !')">Voir les cours</button>
    </section>
    
    <section id="faq">
        <h2>FAQ</h2>
        <p>Retrouvez ici les réponses aux questions les plus courantes sur l'informatique.</p>
    </section>
    
    <section id="contact">
        <h2>Contact</h2>
        <p>Besoin d'aide ? Envoyez-nous un message :</p>
        <form>
            <input type="text" placeholder="Votre nom" required><br><br>
            <input type="email" placeholder="Votre email" required><br><br>
            <textarea placeholder="Votre message" rows="4" required></textarea><br><br>
            <button type="submit">Envoyer</button>
        </form>
    </section>
</body>
</html>
