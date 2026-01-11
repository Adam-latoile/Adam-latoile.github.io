---
layout: about
title: About
permalink: /about/
---

<section id="formations">
<h2>Mon Parcours</h2>

<div class="formations-container">

<div class="formation-box" markdown="1">
<i class="fa-solid fa-graduation-cap"></i>
### 2023 - Aujourd'hui
**Web@cademie by Epitech**
*Titre Architecte Web (Niveau 5)*

Formation intensive basée sur la pédagogie par projets. Apprentissage des langages web modernes, de l'architecture logicielle et du travail en équipe.

</div>

<div class="formation-box" markdown="1">
<i class="fa-solid fa-school"></i>
### 2018 - 2019 (Exemple)
**Nom de ton Lycée / École**
*Baccalauréat / Autre diplôme*

Spécialité ou option suivie. Mention ou détails pertinents si tu le souhaites.

</div>

</div>
</section>

<style>
#formations {
    padding: 2rem;
    max-width: 800px;
    margin: 0 auto;
}

#formations h2 {
    text-align: center;
    color: #d3ab82;
    margin-bottom: 2rem;
    text-shadow: 0 0 5px #000;
}

.formations-container {
    display: flex;
    flex-direction: column;
    gap: 1.5rem;
}

.formation-box {
    background: rgba(0, 0, 0, 0.6);
    border-left: 4px solid #d3ab82;
    border-radius: 5px;
    padding: 1.5rem;
    color: #fff;
    box-shadow: 0 4px 6px rgba(0,0,0,0.3);
    transition: transform 0.3s ease;
    position: relative;
}

.formation-box:hover {
    transform: translateX(10px);
    background: rgba(255, 255, 255, 0.05);
}

.formation-box h3 {
    color: #d3ab82;
    margin-top: 0;
    margin-bottom: 0.5rem;
    font-size: 1.1rem;
}

.formation-box i {
    position: absolute;
    top: 1.5rem;
    right: 1.5rem;
    font-size: 2rem;
    color: #d3ab8250;
}

.formation-box strong {
    display: block;
    font-size: 1.2rem;
    margin-bottom: 0.2rem;
    color: #fff;
}

.formation-box em {
    display: block;
    color: #ccc;
    font-size: 0.9rem;
    margin-bottom: 1rem;
    font-style: italic;
}
</style>
