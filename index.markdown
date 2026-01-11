---
layout: default
title: Accueil
---

<section id="introduction">
<div class="bloc-gauche" markdown="1">

## Developpeur Web/Graphiste

Actuellement étudiant à Epitech, j'ai appris à penser différemment plutôt qu'à simplement coder. Je vois le code comme un terrain de jeu où je transforme des défis techniques en interfaces soignées qui ne se consultent pas, mais se vivent.

[Télécharger mon CV](ADAM_BECHIKH.pdf){: .button}

</div>
</section>

---

<section id="competences">

<div class="competence" markdown="1">

<i class="fa-solid fa-pen-nib fa-shake" style="color: #000000;"></i>

### Créativité

Curieux et imaginatif, j’aime trouver des idées nouvelles et explorer des approches innovantes pour résoudre les problèmes et donner vie à des projets uniques.

</div>

<div class="competence" markdown="1">

<i class="fa-solid fa-stairs fa-bounce" style="color: #000000;"></i>

### Persévérance

Je fais preuve de détermination et de résilience pour surmonter les défis, en gardant un engagement constant jusqu’à la réussite des objectifs fixés.

</div>

<div class="competence" markdown="1">
<i class="fa-solid fa-fire fa-beat-fade" style="color: #000000;"></i>

### Motivation

Ma motivation me pousse à donner le meilleur de moi-même. Curieux et persévérant, je reste concentré sur mes objectifs et transforme les défis en opportunités d’apprentissage et de croissance.

</div>

</section>

---

<section id="stacks">
<h2>Mes Stacks Techniques</h2>

<div class="stacks-container">

<div class="stack-box" markdown="1">
<i class="fa-solid fa-code"></i>

### Front-End

- **Langages :** HTML5, CSS3, JavaScript
- **Frameworks :** Jekyll, **Bootstrap**
- **Animation :** CSS Animations

</div>

<div class="stack-box" markdown="1">
<i class="fa-solid fa-server"></i>

### Back-End & Data

- **Langages :** PHP, Node.js
- **Frameworks :** Express.js
- **Bases de données :** MySQL / SQL

</div>

<div class="stack-box" markdown="1">
<i class="fa-solid fa-palette"></i>

### Design & Outils

- **Design :** Figma, UX/UI Design
- **No-Code :** Webflow
- **Organisation :** Notion, Pack Office

</div>

<div class="stack-box" markdown="1">
<i class="fa-solid fa-terminal"></i>

### Système & Env.

- **OS :** Windows & **WSL**, Linux Ubuntu
- **Shell :** **Bash**
- **Versionning :** Git / GitHub
- **IA :** Prompt Engineering

</div>

</div>
</section>

<style>
body {
    margin: 0;
    font-family: Arial, sans-serif;
    line-height: 1.6;
    color: #fff;
    background-image: url(/asset/pexels-njeromin-14558623.jpg);
    background-size: cover;
    background-attachment: fixed;
}

ul {
    list-style: none;
    padding: 0;
}

a {
    text-decoration: none;
    color: inherit;
}

img {
    max-width: 100%;
    height: auto;
}

main {
    background-color: rgba(0, 0, 0, 0.85); 
    padding: 2rem;
    min-height: 100vh;
}

nav {
    display: flex;
    justify-content: space-between;
    align-items: center;
    background: #000000;
    color: #d3ab82;
    padding: 1rem 2rem;
}

nav .logo {
    font-size: 1.5rem;
    font-weight: bold;
}

nav ul {
    display: flex;
    gap: 1.5rem;
}

nav ul li a {
    color: #d3ab82;
    transition: color 0.3s;
}

nav ul li a:hover {
    color: #fff;
}

nav img {
    width: 90px;
}

#introduction {
    display: flex;
    align-items: center;
    justify-content: space-between;
    padding: 4rem 2rem;
    max-width: 1000px;
    margin: 0 auto;
}

#introduction .bloc-gauche {
    width: 100%;
    max-width: 700px;
}

#introduction h2 {
    font-size: 2.5rem;
    margin-bottom: 1rem;
    color: #d3ab82;
    text-shadow: 0 0 5px #000, 0 0 10px #000;
}

#introduction p {
    margin-bottom: 1.5rem;
    line-height: 1.8;
    color: #fff;
    font-size: 1.2rem;
    text-shadow: 1px 1px 2px #000;
}

.button {
    display: inline-block;
    padding: 0.75rem 1.5rem;
    background: #000000;
    color: #d3ab82 !important;
    border: 1px solid #d3ab82;
    border-radius: 5px;
    transition: background 0.3s;
    text-shadow: 0 0 1px #d3ab82;
    margin-top: 15px;
}

.button:hover {
    background: #d3ab82;
    color: #000 !important;
}

#competences {
    padding: 2rem;
    display: flex;
    gap: 2rem;
    justify-content: center;
    flex-wrap: wrap;
    color: #fff;
}

.competence {
    padding: 1.5rem;
    border-radius: 10px;
    text-align: center;
    box-shadow: 0 2px 10px rgba(0,0,0,0.5);
    width: 300px;
    background: rgba(255, 255, 255, 0.05); 
    border: 1px solid #d3ab8250;
}

.competence h3 {
    margin-bottom: 1rem;
    color: #d3ab82;
    text-transform: uppercase;
}

#portfolio {
    padding: 2rem;
    text-align: center;
}

#portfolio h2 {
    margin-bottom: 2rem;
    color: #d3ab82;
    text-shadow: 0 0 5px #000;
}

.projects {
    display: flex;
    gap: 2rem;
    justify-content: center;
    flex-wrap: wrap;
}

.project {
    padding: 1rem;
    border-radius: 10px;
    text-align: center;
    width: 300px;
    background: rgba(0,0,0,0.5);
}

.project img {
    margin-bottom: 1rem;
    border-radius: 10px;
    border: 1px solid #d3ab82;
    transition: transform 0.3s;
}

.project img:hover {
    transform: scale(1.05);
}

.project h2 {
    color: #fff;
    font-size: 1.5rem;
}

footer {
    padding: 2rem;
    background: #000000;
    color: #d3ab82;
    display: flex;
    justify-content: center;
    align-items: center;
    text-align: center;
}

#stacks {
    padding: 2rem;
    max-width: 1000px;
    margin: 0 auto;
    text-align: center;
}

#stacks h2 {
    color: #d3ab82;
    margin-bottom: 2rem;
    text-shadow: 0 0 5px #000;
}

.stacks-container {
    display: grid;
    grid-template-columns: repeat(4, 1fr);
    justify-content: center;
    flex-wrap: wrap;
    gap: 1.5rem;
}

.stack-box {
    background: rgba(0, 0, 0, 0.6);
    border: 1px solid #d3ab82;
    border-radius: 10px;
    padding: 1.5rem;
    width: 200px;
    text-align: left;
    box-shadow: 0 4px 6px rgba(0,0,0,0.3);
    transition: transform 0.3s ease;
}

.stack-box:hover {
    transform: translateY(-5px);
    background: rgba(211, 171, 130, 0.1);
}

.stack-box i {
    font-size: 2rem;
    color: #d3ab82;
    display: block;
    text-align: center;
    margin-bottom: 1rem;
}

.stack-box h3 {
    text-align: center;
    margin-top: 0;
    border-bottom: 1px solid #d3ab8250;
    padding-bottom: 0.5rem;
    margin-bottom: 1rem;
    font-size: 1.2rem;
}

.stack-box ul {
    list-style-type: none;
    padding: 0;
    margin: 0;
}

.stack-box li {
    margin-bottom: 0.5rem;
    font-size: 0.95rem;
    color: #fff;
}

.stack-box strong {
    color: #d3ab82;
}
</style>
