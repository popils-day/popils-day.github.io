---
layout: page
permalink: /schedule/
title: Programme
---
Jeudi 10 juin 2026

| Horaire      | Orateur              |
|------------- |----------------------|
| 9h30-9h55   | **Accueil**              |
| 9h55-10h    | **Mot d'ouverture**      |
| 10h-10h50   | **Emilie Morvant** - Mini-tutoriel PAC-Bayes : Des bornes de généralisation à des fonctions objectives |
| 10h50-11h30 | **Pause café + posters** |
| 11h30-12h20 | **Stéphane Chrétien** - Tukey-Median of Means-Gradients for Langevin Dynamics   |
| 12h20-14h20 | **Buffet + posters**     |
| 14h20-15h10 | **Ammar Mian**  - TBC    |
| 15h10-16h00 | **Valentin Debarnot** - Learning in tomography imaging |


<br>

<div class="speaker-container">
    <div class="speaker-name">Emilie Morvant</div>
    <div class="speaker-title">Mini-tutoriel PAC-Bayes : Des bornes de généralisation à des fonctions objectives</div>
    
    <div class="speaker-abstract">
En apprentissage statistique, la théorie PAC-Bayésienne offre une approche flexible et puissante pour analyser la généralisation des modèles d’apprentissage automatique, en combinant probabilités (via les inégalités de concentration), théorie de l’information et théorie de l’apprentissage. Contrairement aux bornes classiques, souvent peu informatives dans les régimes modernes surparamétrés, l’analyse PAC-Bayésienne permet d’obtenir des garanties dépendantes des données, précises et exploitables en pratique.
Ce mini-tutoriel débutera par un bref panorama des outils standards de généralisation, avant de présenter les principes fondamentaux menant à la dérivation des bornes PAC-Bayésiennes. Les résultats clés seront exposés à l’aide de preuves simples, afin de mettre en lumière les mécanismes essentiels sous-jacents à ces bornes.
Au-delà de la théorie, nous insisterons sur leur portée algorithmique. Plutôt que de considérer les bornes PAC-Bayésiennes comme de simples outils d’analyse a posteriori, nous montrerons comment les transformer en véritables objectifs d’apprentissage. Cette perspective conduit à des algorithmes auto-certifiés : les modèles sont appris en minimisant directement une borne de généralisation, intégrant ainsi leurs propres garanties.
	    </div>
</div>

<div class="speaker-container">
    <div class="speaker-name">Stéphane Chrétien</div>
    <div class="speaker-title">Tukey-Median of Means-Gradients for Langevin Dynamics</div>
    
    <div class="speaker-abstract">
Median-of-Means (MoM) estimators have emerged as powerful tools for robust learning when data are corrupted by outliers or exhibit heavy-tailed distributions. However, incorporating MoM principles to design robust loss functions typically renders the underlying optimization problem highly non-convex, posing significant challenges for the design of efficient, polynomial-time algorithms. In this work, we apply MoM principle at the gradient level using Tukey median to robustly estimate the uncorrupted gradient. More precisely, we propose a novel Tukey MoM-based variant of Stochastic Gradient Langevin Dynamics (TMoM-SGLD) which enjoys strong theoretical guarantees, including hitting-time bounds showing convergence to approximate stationary points of the underlying uncorrupted loss. Contrary to prior MoM estimators, our results hold in broad non-convex settings, making TMoM-SGLD particularly relevant to modern machine learning tasks.
	    </div>
</div>
<div class="speaker-container">
    <div class="speaker-name">Ammar Mian</div>
    <div class="speaker-title">TBC</div>
    
    <div class="speaker-abstract">
TBC
	    </div>
</div>
<div class="speaker-container">
    <div class="speaker-name">Valentin Debarnot</div>
    <div class="speaker-title">Learning in tomography imaging</div>
    
    <div class="speaker-abstract">
Electron tomography reconstructs three-dimensional volumes from a limited number of projection images acquired along fixed directions. Because the range of accessible angles is restricted, the associated reconstruction problem is highly ill-posed: the acquisition operator has a large kernel, meaning that significant information about the volume is missing. In addition, the observations are extremely noisy (often with a negative signal-to-noise ratio) and the volumes to reconstruct are very large. These challenges make the design of appropriate reconstruction algorithms essential. 

In this presentation, we will show how self-supervised learning can be used to recover information lying in the kernel of the acquisition operator and to effectively remove noise. This is achieved by exploiting the specific structure of the tomography problem together with equivariance-based priors. 

Finally, we will show how these self-supervised approaches can be used to develop supervised learning methods that achieve comparable reconstruction quality while drastically reducing computation time (approximately 5 minutes instead of 12 hours).
	    </div>
</div>



