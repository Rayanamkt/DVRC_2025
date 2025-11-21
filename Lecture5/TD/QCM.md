✅ QCM – 20 questions (sans réponses)

* Q1. La régression logistique prédit principalement :

    A. Une classe directe (0 ou 1)
    B. Une probabilité entre 0 et 1
    C. Une variable continue
    D. Une transformation polynomiale

Réponse B : la régression logistique calcule une probabilité car son modèle estime la chance d'apartenir à une classe avant de décidé 0 ou 1.

* Q2. La fonction d’activation utilisée dans la régression logistique est :

    A. Softmax
    B. Sigmoïde
    C. ReLU
    D. Lineaire

Réponse B: Le Sigmoïde car elle transforme une valeur réelle en un nombre compris entre 0 et 1

* Q3. Le paramètre C dans LogisticRegression contrôle :

    A. Le taux d’apprentissage
    B. La régularisation (inverse de la force)
    C. Le nombre d’arbres
    D. Le nombre de voisins

Réponse B: La régularisation

* Q4. Dans KNN, le paramètre k contrôle :

    A. La profondeur maximale
    B. Le nombre d’exemples stockés
    C. Le nombre de voisins considérés
    D. Le nombre de features

Réponse C: Le paramétre k indique combien de voisin on regarde quand le KNN classe un point 

* Q5. Le KNN nécessite généralement :

    A. Une standardisation des données
    B. Une réduction de dimension obligatoire
    C. Une normalisation des labels
    D. Aucun prétraitement

Réponse A: KNN se base sur les distances donc on doit avoir des features de meme echelle pour commparé

* Q6. Dans une Random Forest :

    A. Les arbres sont corrélés
    B. Les arbres sont entraînés sur les mêmes données
    C. Les arbres sont entraînés sur des sous-échantillons aléatoires
    D. On a toujours 10 arbres

Réponse C: Random Foret entraine chaque arbre sur un échantillon différent aléatoire

* Q7. Un Decision Tree a tendance à :

    A. Sous-ajuster fortement
    B. Sur-ajuster s’il n’est pas limité
    C. Avoir toujours une faible variance
    D. Avoir un biais élevé

Réponse B: Un arbre peut créer des feuille très spécifique donc il surapprendre facilement

* Q8. Le paramètre max_depth dans un arbre décide :

    A. Le nombre maximum de feuilles
    B. Le nombre de features
    C. La profondeur maximale de l’arbre
    D. Le nombre d’échantillons min pour splitter

Réponse C: La profondeur limite le nombre de divisions et donc la complexité de l'arbre

* Q9. Dans une Random Forest, augmenter le nombre d’arbres :

    A. Augmente toujours l’overfitting
    B. Réduit la variance du modèle
    C. Change complètement le biais
    D. Ne sert à rien

Réponse B: Si on augmente le nombre d'arbre les prédictions se stabilisent car la moyenne réduit l’impact d’un seul arbre trop variable

* Q10. Linear Regression est un modèle :

    A. Supervisé
    B. Non supervisé
    C. De clustering
    D. De détection d’anomalies

Réponse A: Supervisé

* Q11. Le MSE est utilisé dans :

    A. Classification
    B. Clustering
    C. Régression
    D. Détection d’outliers uniquement

Réponse C: Le mse mesure l'erreur entre valeur prédite et réelle

* Q12. Quelle est la métrique la plus adaptée à un jeu déséquilibré ?

    A. Accuracy
    B. F1-score
    C. R²
    D. RMSE

Réponses B: Le F1-score tient compte du déséquilibre contrairement à l'Accuracy

* Q13. Dans LogisticRegression, le solver liblinear permet :

    A. D’utiliser regularisation L1
    B. De calculer une softmax
    C. D’utiliser des arbres
    D. D’entraîner une forêt

Réponse A

* Q14. Dans une matrice de confusion, FN signifie :

    A. Faux négatif
    B. Fait négatif
    C. Fausse normalisation
    D. Feature non utilisée

Réponse A

* Q15. Le modèle KNN est :

    A. Paramétrique
    B. Non paramétrique
    C. Basé sur des arbres
    D. Un réseau de neurones

Réponse B: KNN ne construit aucun modéle il conserve les données et compare les distances seulement

* Q16. Le Random Forest améliore un Decision Tree car :

    A. Il augmente le biais
    B. Il réduit la variance grâce à l’agrégation
    C. Il supprime toute forme d’overfitting
    D. Il fonctionne sans features

Réponse B: Random Forest moyenne les erreurs de plusieur arbres ce qui dimique la variance

* Q17. La régularisation L1 permet :

    A. D’augmenter le nombre de features
    B. D’éliminer certaines features (feature selection)
    C. De réduire la profondeur d’un arbre
    D. De modifier la distribution des labels

Réponse B

* Q18. Le graphe ROC affiche :

    A. FPR vs TPR
    B. F1 vs Recall
    C. Precision vs Recall
    D. Accuracy vs Error rate

Réponse A

* Q19. Le paramètre n_neighbors de KNN influe sur :

    A. Biais/variance
    B. Nombre de features
    C. Nombre d’arbres
    D. Nombre de splits

Réponse A: Un petit k rend le modéle sensible (faible biais, forte variance) et un grand k fait l'inverse

* Q20. La standardisation est essentielle pour :

    A. Logistic Regression
    B. KNN
    C. SVM
    D. Toutes les réponses ci-dessus

Réponse D: Il utilisent tous des distances ou des parametre sensible à l'echelle des données donc la standardisation ameliore leur performances