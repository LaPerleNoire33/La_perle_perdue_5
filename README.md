
<html lang="fr">

<head>

<meta charset="UTF-8">

<title>Indice Secret – Bunker</title>

<style>

body {

    font-family: 'Georgia', serif; /* Police type “lettre” */

    background-color: #f3e4d0; /* Fond beige clair / marron clair */

    color: #3e2f1c; /* Couleur texte foncée */

    padding: 40px;

}

#secret {

    display: none;

    font-style: italic; /* Texte en italique pour effet lettre */

    line-height: 1.8;

    max-width: 600px;

    margin: auto;

    border: 1px solid #cbb79b;

    padding: 20px;

    background-color: #fff3e0; /* Fond légèrement plus clair pour la lettre */

}

#login {

    text-align: center;

    max-width: 400px;

    margin: auto;

}

input {

    padding: 10px;

    font-size: 16px;

    margin-top: 10px;

}

button {

    padding: 10px 15px;

    font-size: 16px;

    margin-top: 10px;

    cursor: pointer;

}

</style>

<script>

function checkPassword() {

    var pass = document.getElementById("password").value;

    if(pass === "LAPERLENOIRE") { // Remplace MONCODE par ton mot de passe

        document.getElementById("secret").style.display = "block";

        document.getElementById("login").style.display = "none";

    } else {

        alert("Mot de passe incorrect !");

    }

}

</script>

</head>

<body>



<div id="login">

<h2>Entrez le code pour accéder à l'indice</h2>

<input type="password" id="password" placeholder="Votre code">

<br>

<button onclick="checkPassword()">Valider</button>

</div>



<div id="secret">

<h2>Le bunker</h2>

<p>Quel paysage, n’est-ce pas ?
Une vue immense, un horizon sans fin. Pas étonnant que les Allemands aient voulu s’approprier ce lieu et dresser leurs fortifications.
Je me souviens… c’est ici que je t’ai vu pour la première fois, mon amour.Nous n’étions encore que des enfants, réquisitionnés malgré nous pour aider à la construction de ces bunkers. La faim régnait partout, nos parents n’avaient plus la liberté d’exercer leur métier, et chaque journée semblait plus lourde que la précédente.
Et pourtant, c’est dans ces moments de peur, de fatigue et de faim que notre histoire a démarré.
Quel autre endroit aurais-je pu choisir pour cacher ce bien si précieux, cette perle qui fera notre fortune ? Elle reposera là où nous avions l’habitude de nous étendre, là où nous partagions nos instants volés, à l’abri des regards et pourtant si accessible: il suffisait juste de prendre un peu de hauteur.
</p>
