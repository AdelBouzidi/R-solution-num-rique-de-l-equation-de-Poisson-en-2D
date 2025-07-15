# Résolution-numérique-de-l-équation-de-Poisson-en-2D
Ce travail présente l’ensemble des travaux réalisés dans le cadre du TP sur la résolution
numérique de l’équation de Poisson en 2D par la méthode des différences finies. L’objectif
principal était de :
— Résoudre numériquement le problème de Poisson sur le domaine carré unité Ω = 
   (0, 1) × (0, 1) avec conditions de Dirichlet homogènes
— Stocker les résultats de manière structurée et réutilisable avec HDF5
— Générer des fichiers de sortie au format VTK pour visualisation dans ParaView
— Produire des visualisations complémentaires en 2D/3D avec Matplotlib et Plotly
— Étudier la convergence de la méthode et l’erreur numérique

Trois séries de TD ont structuré ce travail :
— TD1 : Résolution numérique avec assemblage du système
— TD2 : Stockage HDF5 et organisation des résultats
— TD3 : Visualisation VTK + analyse de l’erreur et convergence

Chaque section du rapport détaillera le code utilisé, les résultats obtenus, ainsi que les figures
générées. Des explications pédagogiques accompagneront chaque étape pour assurer la
compréhension complète du lecteur.
