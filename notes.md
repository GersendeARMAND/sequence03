# Algorithmes débranchés -- le robot idiot
## Manche 1 -- La tartine

* Ecrire, étape par étape, comment préparer une tartine beurrée à partir de :
    + un sachet de pain de mie fermé, 
    + une plaquette de beurre emballée, 
    + un couteau posé sur la table.

    1. Ouvrir le sachet de pain de mie
    2. Ouvrir la plaquette de beurre emballée
    3. Prendre une tranche de pain de mie
    4. Saisir le couteau posé sur la table
    5. Récupérer du beurre avec le couteau en faisant glisser le couteau au-dessus de la plaquette de beurre déballée
    6. Etaler le beurre qui est sur le couteau, sur la tranche de pain de mie

-> tartine beurrée préparée.

Blocage observé : il manque des étapes, et utilisation de verbes qui n'étaient pas dans la liste.

Ce qui manquait dans l'instruction : rien. 

## Manche 2 -- Le dessin dicté

**Figure géométrique :**
1. Dessiner un carré d'environ 4 cm de côté
2. Au-dessus du carré, faire un cercle d'environ 2.5 cm de diamètre, coincident au milieu du côté haut du carré
3. En bas à droite du carré, coincide un triangle rectangle isocèle (il a deux côtés de même longueur). Le côté qui coincide avec le carré est l'un de ses deux côtés égaux. L'autre côté égaux (qui n'est donc pas l'hypoténuse) se trouve sur la même ligne du côté bas du carré. L'hypoténuse forme deux angles de 45 degrès avec les deux autres côtés.

Les deux dessinateurs avaient le même texte. Ont-ils obtenu le même dessin ? Qu'est-ce-qui, dans le texte, laissait le choix ?

Oui, ils ont obtenu le même dessin.

## Manche 3 -- Décider et répéter

Ecrire en français structuré, avec les mots "Si... ALORS... SINON" et "TANT QUE... FAIRE" : 

1. **Le feu tricolore** : ce que fait un piéton devant un feu, selon sa couleur.  
-> **SI** le feu tricolore est rouge **ALORS** le piéton traverse **SINON** il patiente.

2. **Le distributeur** : rendre la monnaie sur un billet de 10 € pour un article à 6 €, avec des pièces de 2 € et de 1 €.

    -> **SI** le distributeur reçoit un billet de 10 € pour un article à 6 € **ALORS** il rend la monnaie avec deux pièces de 2 € **SINON** avec une pièce de 2 € et deux pièces de 1 €.

3. **Le tri de cartes** : vous tenez dix cartes numérotées, mélangées, face cachée ; vous ne pouvez en retourner que deux à la fois. Décrire comment trouver la plus grande.

    -> **SI** en retournant les deux premières cartes, la carte 1 est supérieure à la carte 2, **ALORS** je retourne face cachée la deuxième carte, **SINON** la première carte.
    **TANT QUE** je n'ai pas trouvé la carte la plus grande des dix cartes, **FAIRE** le tirage de la carte suivante et, retourner face cachée la carte inférieure jusqu'à trouver la plus grande des cartes.

Faire exécuter chaque texte par le robot du trio voisin, avec de vraies cartes pour le troisième.

## Manche 4 -- Ce qu'on retient

+ Définition d'un algorithme, en une phrase : une suite d'instructions à exécuter, dans le but de résoudre un problème donné.

+ Trois qualités d'une bonne instruction : simplicité, exactitude, exécutable.

+ Les trois "briques" (je n'en vois que deux) qu'on a utilisées dans la manche 3. Donnez-leur un nom : 
    * "SI... ALORS... SINON..." : condition,
    * "TANT QUE... FAIRE..." : boucle en continu tant que condition reste vraie. Dès qu'elle devient fausse, le programme passe à la suite.

Définition commune retenue : une suite d'instructions à exécuter, dans le but de résoudre un problème donné.

## Pour finir :

**Dix instructions au plus, l'algorithme d'un geste de mon ancien métier ou d'un loisir :**

Le geste d'une activité de mon ancien métier : conditionner des bocaux de caramel beurre salée à l'aide d'une doseuse :


1. Préparer 20 bocaux vides (car série choisie : 20) sur la partie gauche de la table, deux par deux, prêts à être déplacer, un à un, sous la doseuse.
2. Préparer les couvercles des bocaux sur la partie droite de la table.
3. Se placer en face de la doseuse, qui se situe au milieu de la table.
4. Mettre un premier bocal sous la doseuse.
5. Appuyer sur le bouton de mise en route d'une série.
6. La doseuse mesure et verse 210g de caramel beurre salé par bocal.
7. Dès que le premier bocal a été rempli ; refermer ce bocal avec un couvercle ; déplacer ce même bocal au plus loin sur la partie droite de la table (pour laisser place aux 19 autres bocaux de la série) et placer le prochain bocal vide sous la doseuse.
8. Répéter l'étape 7 jusqu'à la pose du couvercle du 20e bocal.
9. Lorsque les 20 bocaux sont remplis, les peser : si le bocal à un poids net inférieur à 210g, alors remplir à l'aide d'une cuillère, la différence. 
10. Pour commencer une autre série : répéter toutes les étapes, depuis la première jusque la septième inclus.
11. Lorsque tous les bocaux sont remplis (en général, il y en avait 180 à remplir au total par production), nettoyer la machine. 


# Tickets d'algorithmique -- séries 1 à 5

**Méthode pour chaque ticket :** 
1. Reformuler : qu'est-ce-qui entre, qu'est-ce-qui sort ?
2. Résoudre un exemple à la main.
3. Ecrire le pseudo-code.
4. Prévoir un jeu d'essai de trois cas (normal, limite, erreur) et le dérouler.
5. Faire relire par mon binôme.

## Série 1 -- Variables, saisie, affichage

* Bonjour. Demander son prénom à l'utilisateur et afficher "Bonjour" suivi du prénom.
    -> 1. Ce qui entre : prénom de l'utilisateur ; ce qui sort : "Bonjour + prénom"

    -> 2.

    -> 3.   ALGORITHME Bonjour
            VARIABLE
                    Prénom : TEXTE
            DEBUT
                LIRE Prénom 
                ECRIRE "Bonjour", Prénom
            FIN 

    -> 4.

* Surface. Demander la longueur et la largeur d'une pièce, afficher sa surface.
    -> 1. Ce qui entre : longueur et largeur d'une pièce ; ce qui sort : surface.

   -> 2. 

   -> 3.    ALGORITHME Surface
            VARIABLES
                Longueur : REEL
                Largeur : REEL
                Surface : REEL
            DEBUT
                LIRE Longueur
                LIRE Largeur
                Surface <- Longueur * Largeur
                ECRIRE Surface
            FIN
    -> 4.

* Echange. Deux variables a et b contiennent chacune un nombre saisi. Echanger leurs valeurs, puis les afficher.
    -> 1. Ce qui entre : deux variables ; ce qui sort : deux nombres ;

    -> 2.

    -> 3.   ALGORITHME Echange
            VARIABLES
                a : REEL
                b : REEL
                c : REEL
            DEBUT
                c <- a
                a <- b
                b <- c
                ECRIRE a 
                ECRIRE b 
            FIN
    -> 4.   

* Durée de randonnée. Une durée est saisie en minutes. L'afficher en heures et minutes. Exemple : 135 donne "2 h 15 min".
    -> 1. Ce qui entre : durée en minutes ; ce qui sort : heures et minutes.

    -> 2.

    -> 3.   ALGORITHME Durée de randonnée
            VARIABLE
                TotalMinutes : ENTIER
                Heures : ENTIER
                Minutes : ENTIER
                Durée : TEXTE
            DEBUT
                LIRE Minutes
                TotalMinutes DIV 60 = Heures
                TotalMinutes MOD 60 = Minutes
                Durée <- Heures, "h", Minutes, "min"
                ECRIRE TotalMinutes donne "Durée"
            FIN
    -> 4. 

