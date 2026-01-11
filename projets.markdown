---
layout: default
title: Mes Réalisations
permalink: /projets/
---

<section id="portfolio">
<h2>MES RÉALISATIONS</h2>

<div class="projects-container">

<div class="project-card" markdown="1">
### GUARDIAN
<img src="/asset/BOBEUUUH.png" alt="Aperçu Klivio">
<div class="project-info" markdown="1">
**Application de prévention face aux catastrophes naturelles.**
<br>
**Stack :** HTML
56.9%
 
CSS
39.9%
 
JavaScript
3.2%
<br>
[Voir le projet](https://adam-latoile.github.io/GUARDIAN/){: .btn-project target="_blank"}
</div>
</div>

<div class="project-card" markdown="1">
### KLIVIO
<img src="/asset/Klivio-logo.png" alt="Aperçu Klivio">
<div class="project-info" markdown="1">
**Plateforme de formation et développement personnel.**
<br>
**Stack :**
HTML
76.2%
 
CSS
22.8%
 
JavaScript
1.0%
<br>
[Voir le projet](https://adam-latoile.github.io/Klivio/){: .btn-project target="_blank"}
</div>
</div>

<div class="project-card" markdown="1">
### GARDEN NEWS
<img src="/asset/garden-news.png" alt="Aperçu Klivio">
<div class="project-info" markdown="1">
**Le premier site d'information 100% consacré aux nains de jardin.**
<br>
**Stack :**JavaScript
54.6%
 
CSS
34.8%
 
HTML
10.6%
<br>
[Voir le projet](https://adam-latoile.github.io/siteactu/){: .btn-project target="_blank"}
</div>
</div>

<div class="project-card" markdown="1">
### 404 NEWS
<img src="/asset/404news.png" alt="Aperçu Klivio">
<div class="project-info" markdown="1">
**Site d'actualités Tech et bons plans web.**
<br>
**Stack :** HTML
61.4%
 
CSS
38.2%
 
JavaScript
0.4%
<br>
[Voir le projet](https://adam-latoile.github.io/404-NEWS/accueil.html){: .btn-project target="_blank"}
</div>
</div>

</div>
</section>

<style>
    #portfolio {
    padding: 4rem 2rem;
    margin: 0 auto;
}

#portfolio h2 {
    text-align: center;
    color: #d3ab82;
    margin-bottom: 3rem;
}

.projects-container {
    display: grid;
    grid-template-columns: repeat(4, 1fr);
    gap: 1.5rem;
}

.project-card {
    background: rgba(0, 0, 0, 0.8);
    border: 1px solid #d3ab8250;
    border-radius: 15px;
    overflow: hidden;
    transition: all 0.3s ease;
}

.project-card h3 {
    justify-self: center;
    font-size: x-large;
    color: #d3ab82;
}

 p {
    place-self: center;
    width: 85%;
}

.project-card:hover {
    transform: translateY(-10px);
    border-color: #d3ab82;
    box-shadow: 0 10px 20px rgba(211, 171, 130, 0.2);
}

.project-card img {
    width: 100%;
    height: 15rem;
    object-fit: cover;
    border-bottom: 1px solid #d3ab8250;
    border-radius: 5%;
}

.project-info h3 {
    color: #d3ab82;
    margin-bottom: 1rem;
}

.project-info p {
       font-size: 0.9rem;
    color: #ccc;
    margin: 0rem 0rem 1rem 0rem;
    display: flex;
    flex-direction: column;
    align-items: center;
    width: 15rem;
    text-align: center;
}

.btn-project {
    display: inline-block;
    padding: 0.5rem 1rem;
    border: 1px solid #d3ab82;
    color: #d3ab82;
    text-decoration: none;
    border-radius: 5px;
    font-size: 0.8rem;
    transition: 0.3s;
}

a.btn-project {
    display: inline-block;
    padding: 0.5rem 1rem;
    border: 1px solid #d3ab82;
    color: #d3ab82;
    text-decoration: none;
    border-radius: 5px;
    font-size: 0.8rem;
    transition: 0.3s;
    display: flex;
    justify-content: center;
    max-width: 6rem;
    place-self: center;
    margin: 1rem 0rem 0rem 0rem;
}
.btn-project:hover {
    background: #d3ab82;
    color: #000;
}
    </style>
