---
layout: page
permalink: /schedule/
title: Programme
---
Vendredi 19 juin 2025

| Horaire      | Orateur              |
|------------- |----------------------|
| 9h30-9h55   | **Accueil**              |
| 9h55-10h    | **Mot d'ouverture**      |
| 10h-10h50   | **Antoine Collas** - Adapting learning models to distribution shifts: the role of normalization|
| 10h50-11h30 | **Pause café + posters** |
| 11h30-12h20 | **Julie Digne** - Implicit Neural Representation for Geometry Processing   |
| 12h20-14h20 | **Buffet + posters**     |
| 14h20-15h10 | **Rodolphe Le Riche**  - Bayesian optimization with derivatives acceleration    |
| 15h10-16h00 | **Romain Vo** - Méthodes d'apprentissage pour la tomographie par rayons X  |


<br>

<div class="speaker-container">
    <div class="speaker-name">Rodolphe Le Riche </div>
    <div class="speaker-title">Bayesian optimization with derivatives acceleration</div>
    
    <div class="speaker-abstract">
Bayesian optimization algorithms form an important class of methods to minimize functions that are costly to evaluate, which is a very common situation. These algorithms iteratively infer Gaussian processes from past observations of the function and decide where new observations should be made through the maximization of an acquisition criterion. Often, in particular in engineering practice, the objective function is defined on a compact set such as in a hyper-rectangle of a d-dimensional real space, and the bounds are chosen wide enough so that the optimum is inside the search domain. In this situation, this work provides a way to integrate in the acquisition criterion the a priori information that these functions, once modeled as GP trajectories, should be evaluated at their minima, and not at any point as usual acquisition criteria do. We propose an adaptation of the widely used Expected Improvement acquisition criterion that accounts only for GP trajectories where the first order partial derivatives are zero and the Hessian matrix is positive definite. The new acquisition criterion keeps an analytical, computationally efficient, expression. This new acquisition criterion is found to improve Bayesian optimization on a test bed of functions made of Gaussian process trajectories in dimensions 2, 3 and 5. The addition of first and second order derivative information is particularly useful for multimodal functions.
This talk corresponds to the paper : Guillaume Perrin and Rodolphe Le Riche Bayesian optimization with derivatives acceleration, Transactions on Machine Learning Research, issn=2835-8856, aug. 2024.
	    </div>
</div>

<div class="speaker-container">
    <div class="speaker-name">Julie Digne</div>
    <div class="speaker-title">Implicit Neural Representation for Geometry Processing</div>
    
    <div class="speaker-abstract">
    Implicit Neural Representations are powerful tools for representing 3D shapes. They encode an implicit field in the parameters of a Neural Network, leveraging the power of auto-differentiation for optimizing the implicit function and avoiding the need for manually crafted basis functions. They can work on single shapes, or be conditioned by a latent shape space. In this talk, I will explain the principles behind implicit neural representation and show several applications for shape analysis skeleton extraction and shape deformation.     
    </div>

</div>

<div class="speaker-container">
    <div class="speaker-name">Antoine Collas</div>
    <div class="speaker-title"> Adapting learning models to distribution shifts: the role of normalization</div>
    
    <div class="speaker-abstract">
       Distribution shifts between source and target datasets pose a major challenge in machine learning. In this talk, I will present recent approaches to adapt models to such shifts, with a particular focus on normalization techniques. I will discuss the often overlooked role of normalization in both generalization and adaptation, showing how appropriate design choices can significantly improve transfer performance. These ideas will be illustrated with concrete examples, notably in neuroscience, where signal characteristics vary greatly across subjects and recording devices.
     </div>
</div>


<div class="speaker-container">
<div class="speaker-name">Romain Vo</div>
<div class="speaker-title">Méthodes d'apprentissage pour la tomographie par rayons X <i>(le titre définitif peut évoluer)</i></div>
    
    <div class="speaker-abstract">
        <i>Abstract à venir.</i>
	    </div>
</div>


