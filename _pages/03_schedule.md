---
layout: page
permalink: /schedule/
title: Programme
---
Vendredi 16 Février 2024

| Horaire      | Orateur              |
|------------- |----------------------|
| 9h30-9h55   | **Acceuil**              |
| 9h55-10h    | **Mot d'ouverture**      |
| 10h-10h50   | **Yohann De Castro** - Convex regularization on measures for GMMs     |
| 10h50-11h30 | **Pause café + posters** |
| 11h30-12h20 | **Loïc Denis**  - Parcimonie, optimisation et problèmes inverses en observation de la Terre et de l'Univers          |
| 12h20-14h20 | **Buffet + posters**     |
| 14h20-15h10 | **Nicolas Ducros** - Computational hyperspectral SPIM for quantitative multicolor imaging      |
| 15h10-16h00 | **Elisa Riccietti** - IML FISTA: A Multilevel Framework for Inexact and Inertial Forward-Backward. Application to large scale Image Restoration       |


<br>



<div class="speaker-container">
    <div class="speaker-name">Yohann De Castro</div>
    <div class="speaker-title">Convex regularization on measures for GMMs</div>
    
    <div class="speaker-abstract">
The Gaussian mixture model (GMM) is an important model in unsupervised machine learning. It allows you to obtain a partition of a point cloud. In this talk, we will present a new way to solve this problem based on a parsimonious regression model on the measurement space. This point of view will allow us to remove a barrier in MMG: the selection of the size of the model, here the number of mixing components. We will give theoretical guarantees to this approach. We will show that our approach is compatible with dimension reduction techniques, such as “sketching”. In the context of GMM this amounts to projecting the point cloud into a dimensional space not depending on the number of points but on the size of the model to be estimated (within log factors). In practice this allows the MMG to be scaled up to significant scales, understood here as a significant number of points. Hoping that I will not be too long on these first aspects, I will discuss an algorithm to solve the regression problem on the space of measurements that we will have considered. This algorithm, called particle gradient descent on the cone, is compatible with the “sketching” mentioned above. We will show that it is possible to give theoretical guarantees to the stochastic version of this gradient descent.

The results presented are the fruit of contributions on very similar subjects from several researchers including Claire Boyer, Cathy Maugis, Clément Marteau, Sébastien Gadat, Vincent Duval, Rémi Gribonval, Gabriel Peyré, Clarice Poon, Nicolas Jouvin, Lénaïc Chizat, Francis Bach, and Gilles Blanchard. An article introducing this new method is “SuperMix: Sparse Regularization for Mixtures”, with S. Gadat & C. Marteau & C. Maugis-Rabusseau, Annals of Statistics, 2021, Vol. 49, No. 3, 1779-1809.
	    </div>
</div>



<div class="speaker-container">
    <div class="speaker-name">Loïc Denis</div>
    <div class="speaker-title">Parcimonie, optimisation et problèmes inverses en observation de la Terre et de l'Univers</div>
    
    <div class="speaker-abstract">
La résolution de problèmes inverses avec des a priori de parcimonie conduit à des problèmes d'optimisation nécessitant des méthodologies adaptées.

Au travers d'exemples en observation de la Terre et de l'Univers, plusieurs approches seront présentées: les modèles de décomposition (composante étendue + composante ponctuelle), l'estimation aveugle de paramètres instrumentaux (restauration d'un flou variable dans le champ), la détection de sources ponctuelles (exoplanètes) ou de changements (apparition/disparition de forts rétro-diffuseurs en imagerie radar à synthèse d'ouverture).
	    </div>
</div>


<div class="speaker-container">
    <div class="speaker-name">Nicolas Ducros</div>
    <div class="speaker-title">Computational hyperspectral SPIM for quantitative multicolor imaging</div>
    
    <div class="speaker-abstract">
By allowing fast 3D imaging of fluorescent samples, selective plane illumination microscopy (SPIM) has become an invaluable tool in life science, in particular in developmental biology. Recently, several groups proposed strategies for hyperspectral SPIM, where the full emission spectrum of the fluorescence signal is measured in each voxel of the sample. Coupled with dedicated algorithms, hyperspectral SPIM opens the way to the study of multicolor samples in a quantitative manner.

Here, we will describe a computational strategy based on structured light for achieving hyperspectral SPIM. In a transgenic zebrafish that expresses both green and red fluorescent proteins, we will exhibit autofluorescence removal, as well as the discrimination of two red proteins with very similar emission spectra.
	    </div>
</div>

<div class="speaker-container">
    <div class="speaker-name">Elisa Riccietti</div>
    <div class="speaker-title">IML FISTA: A Multilevel Framework for Inexact and Inertial Forward-Backward. Application to large scale Image Restoration</div>
    
    <div class="speaker-abstract">
	In this talk I'll introduce a multilevel framework for inertial and inexact proximal algorithms, referred as IML FISTA, which includes multilevel adaptations of classical algorithms like forward-backward (FB) and FISTA.

	The proposed IML FISTA is supported by strong theoretical guarantees: we establish both the convergence rate and the convergence of the iterates, a critical outcome for addressing ill-posed problems. We propose a particular instance of IML FISTA, based on the use of the Moreau envelope to build efficient and useful coarse corrections, fully adapted to solve image restoration problems.

	We evaluate our approach on several image reconstruction problems including hyperspectral image restoration. We show that it considerably accelerates the convergence of the corresponding one-level (i.e. FB or FISTA) version of the methods.

	In the context of hyperspectral image restoration, two methods for approximating the objective function dedicated to this problem are proposed. In both cases, the associated convergence guarantees are equivalent to state-of-the-art approaches. These two methods are compared to FISTA, demonstrating the relevance of the proposed approach for very large volumes of data.
	    </div>
</div>

