[index.html](https://github.com/user-attachments/files/28951268/index.html)
```html
<!DOCTYPE html>
<html lang="fr">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Miguiwaras eSports</title>

<link href="https://fonts.googleapis.com/css2?family=Orbitron:wght@400;700;900&display=swap" rel="stylesheet">

<style>
*{
    margin:0;
    padding:0;
    box-sizing:border-box;
}

body{
    font-family:'Orbitron',sans-serif;
    background:#0a0a0a;
    color:white;
    overflow-x:hidden;
}

header{
    height:100vh;
    background:
    linear-gradient(rgba(0,0,0,.7),rgba(0,0,0,.7)),
    url('https://images.unsplash.com/photo-1542751371-adc38448a05e?auto=format&fit=crop&w=1920&q=80');
    background-size:cover;
    background-position:center;
    display:flex;
    justify-content:center;
    align-items:center;
    text-align:center;
}

.hero h1{
    font-size:5rem;
    color:#ff004c;
    text-shadow:0 0 20px #ff004c;
}

.hero p{
    margin-top:20px;
    font-size:1.3rem;
    color:#ccc;
}

.btn{
    display:inline-block;
    margin-top:30px;
    padding:15px 35px;
    background:#ff004c;
    color:white;
    text-decoration:none;
    border-radius:8px;
    transition:.3s;
}

.btn:hover{
    transform:scale(1.1);
    box-shadow:0 0 25px #ff004c;
}

section{
    padding:100px 10%;
}

.section-title{
    text-align:center;
    font-size:3rem;
    margin-bottom:50px;
    color:#ff004c;
}

.about{
    text-align:center;
    max-width:900px;
    margin:auto;
    line-height:1.8;
}

.cards{
    display:grid;
    grid-template-columns:repeat(auto-fit,minmax(250px,1fr));
    gap:25px;
}

.card{
    background:#111;
    padding:30px;
    border-radius:15px;
    border:1px solid #222;
    transition:.3s;
}

.card:hover{
    transform:translateY(-10px);
    border-color:#ff004c;
    box-shadow:0 0 20px rgba(255,0,76,.5);
}

.card h3{
    margin-bottom:15px;
    color:#ff004c;
}

.recruitment{
    background:#111;
    border-radius:20px;
    padding:50px;
}

.requirements{
    display:grid;
    grid-template-columns:1fr 1fr;
    gap:30px;
    margin-top:30px;
}

.requirement-box{
    background:#181818;
    padding:25px;
    border-radius:15px;
}

.requirement-box h3{
    color:#ff004c;
    margin-bottom:15px;
}

.contact{
    text-align:center;
    margin-top:40px;
}

.contact a{
    color:#ff004c;
    text-decoration:none;
    font-size:1.2rem;
}

.stats{
    display:grid;
    grid-template-columns:repeat(auto-fit,minmax(220px,1fr));
    gap:20px;
    text-align:center;
}

.stat{
    background:#111;
    padding:30px;
    border-radius:15px;
}

.stat h2{
    color:#ff004c;
    font-size:3rem;
}

footer{
    text-align:center;
    padding:30px;
    background:#050505;
    border-top:1px solid #222;
}

@media(max-width:768px){

.hero h1{
    font-size:3rem;
}

.requirements{
    grid-template-columns:1fr;
}

}
</style>
</head>

<body>

<header>
<div class="hero">
<h1>MIGUIWARAS</h1>
<p>Valorant eSports Team</p>
<a href="#recrutement" class="btn">Nous Rejoindre</a>
</div>
</header>

<section>
<h2 class="section-title">À Propos</h2>

<div class="about">
<p>
Les Miguiwaras sont une équipe eSport Valorant ambitieuse.
Notre objectif est de progresser ensemble, participer à des compétitions
et construire une structure sérieuse autour de la performance,
de la discipline et de l'esprit d'équipe.
</p>
</div>
</section>

<section>
<h2 class="section-title">Nos Valeurs</h2>

<div class="cards">
<div class="card">
<h3>Compétition</h3>
<p>Nous cherchons constamment à nous améliorer.</p>
</div>

<div class="card">
<h3>Respect</h3>
<p>Chaque membre est traité avec respect et professionnalisme.</p>
</div>

<div class="card">
<h3>Esprit d'équipe</h3>
<p>La réussite passe avant tout par le collectif.</p>
</div>

<div class="card">
<h3>Progression</h3>
<p>Chaque joueur est encouragé à évoluer continuellement.</p>
</div>
</div>
</section>

<section>
<h2 class="section-title">Statistiques</h2>

<div class="stats">

<div class="stat">
<h2>5</h2>
<p>Joueurs titulaires</p>
</div>

<div class="stat">
<h2>1</h2>
<p>Coach recherché</p>
</div>

<div class="stat">
<h2>∞</h2>
<p>Ambition</p>
</div>

<div class="stat">
<h2>100%</h2>
<p>Motivation</p>
</div>

</div>
</section>

<section id="recrutement">

<h2 class="section-title">Recrutement</h2>

<div class="recruitment">

<div class="requirements">

<div class="requirement-box">
<h3>Recherche Joueurs</h3>
<ul>
<li>Rang minimum : Silver 1</li>
<li>Actif et motivé</li>
<li>Bon mental</li>
<li>Travail en équipe</li>
</ul>
</div>

<div class="requirement-box">
<h3>Recherche Coach</h3>
<ul>
<li>Rang minimum : Diamant</li>
<li>Âge : 14 à 18 ans</li>
<li>Connaissances tactiques Valorant</li>
<li>Analyse des matchs</li>
</ul>
</div>

</div>

<div class="contact">
<h3>Postuler</h3>

<p>
Pour rejoindre les Miguiwaras en tant que joueur ou coach :
</p>

<br>

<a href="mailto:lmgwr.contact.team@gmail.com">
lmgwr.contact.team@gmail.com
</a>

</div>

</div>

</section>

<footer>
<p>© 2026 Miguiwaras eSports - Valorant Team</p>
</footer>

</body>
</html>
```
