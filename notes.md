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
                Heures <- TotalMinutes DIV 60
                Minutes <- TotalMinutes MOD 60
                Durée <- Heures, "h", Minutes, "min"
                ECRIRE TotalMinutes donne "Durée"
            FIN
    -> 4. 

* Prix TTC. Demander un prix hors taxes et un taux de TVA en pourcentage. Afficher le montant de la taxe et le prix TTC.
    -> 1. Ce qui entre : prix hors taxes et taux de TVA en pourcentage ; ce qui sort : la taxe et le prix TTC.
    -> 2. 

    -> 3.   ALGORITHME Prix TTC
            VARIABLES
                prixHorsTaxes : REEL
                tauxTVA : REEL
                montantTVA : REEL
                prixTTC : REEL
            DEBUT
                LIRE prixHorsTaxes
                LIRE tauxTVA
                montantTVA <- prixHorsTaxes * tauxTVA
                prixTTC <- prixHorsTaxes + montantTVA
                ECRIRE tauxTVA
                ECRIRE prixTTC
            FIN
        -> 4.

* Rendu de monnaie. Un montant entier en euros est saisi. Afficher le nombre minimal de billets de 10 €, de billets de 5 €, de pièces de 2 € et de pièces de 1 € pour le composer.
    -> 1. Ce qui entre : un montant entier en euros ; ce qui sort : le nombre minimal de billets de 10 €, le nombre minimal de billets de 5 €, le nombre minimal de pièces de 2 €, et le nombre minimal de pièces de 1 €.

    -> 2.

    -> 3.   ALGORITHME Rendu de monnaie
            VARIABLES
                montantEnt : ENTIER
                nbrmin10 : ENTIER
                nbrmin5 : ENTIER
                nbrmin2 : ENTIER
                nbrmin1 : ENTIER
            DEBUT
                LIRE montantEnt
            **PASSSS FINIIIIIIIIIIIIII**
            FIN

## Série 2 -- Conditions

* Majorité. Demander un âge, afficher "majeur" ou "mineur".
    -> 1. Ce qui entre : un âge ; Ce qui sort : "majeur" ou "mineur".

    -> 2. 

    -> 3.   ALGORITHME Majorité
            VARIABLES
                age : ENTIER
                majeur : ENTIER
                mineur : ENTIER
            DEBUT
                SI age >= 18 ALORS
                    ECRIRE "majeur"
                SINON 
                    ECRIRE "mineur"
                FIN SI
            FIN
    
    -> 4.

* Parité. Demander un entier, afficher "pair" ou "impair".
    -> 1. Ce qui entre : un entier ; ce qui sort : "pair" ou "impair"

    -> 2.

    -> 3.   ALGORITHME Parité
            VARIABLES
                unEntier : ENTIER
                pair : ENTIER
                impair : ENTIER
            DEBUT
                LIRE unENTIER
                SI unEntier = 
                **PASSSS FINIIIIIIIIIIIIII**
            FIN

* Le plus grand. Demander deux nombres, afficher le plus grand. Que faites-vous s'ils sont égaux ?
    -> 1. Ce qui entre : deux nombres ; ce qui sort : un nombre .......

    -> 2.

    -> 3.   ALGORITHME Le plus grand
            VARIABLES
                nombreUn : REEL
                nombreDeux : REEL
            DEBUT
                LIRE nombreUn
                LIRE nombreDeux
                SI nombreUn > nombreDeux ALORS
                    ECRIRE nombreUn
                SINON nombreDeux
                FIN SI
            FIN

* Tarif d'une sortie. Le tarif dépend de l'âge : moins de 12 ans, 5 € ; de 12 à 25 ans, 8 € ; de 26 à 64 ans, 12 € ; 65 ans et plus, 7 €. Demander l'âge, afficher le tarif.
    -> 1. Ce qui entre : un âge ; ce qui sort : le tarif.

    -> 2.

    -> 3.   ALGORITHME Tarif d'une sortie
            VARIABLES
                âge : ENTIER
                moins12 : ENTIER
                12_25 : ENTIER
                26_64 : ENTIER
                65_Plus : ENTIER
                tarifM12 : ENTIER
                tarif12_25 : ENTIER
                tarif26_64 :  ENTIER
                tarif65_Plus : ENTIER
            DEBUT
                tarifsM12 <- 5
                tarif12_25 <- 8
                tarif26_64 <- 12
                tarif65_Plus <- 7
                LIRE âge
                SI âge < 12 ALORS
                ECRIRE tarifsM12
                SINON SI âge >= 12 ET âge < 26 ALORS
                ECRIRE tarif12_25
                SINON SI âge >= 26 ET âge <64 ALORS
                ECRIRE tarif26_64
                SINON SI âge >= 65 ALORS
                ECRIRE tarif65_Plus
                FIN SI
            FIN

* Difficulté d'un sentier. On saisit la durée en heures et le dénivelé en mètres. Le sentier est "difficile" si la durée dépasse 6 h **ou** si le dénivelé dépasse 1000m ; "facile" si la durée est d'au plus 3 h **et** le dénivelé d'au plus 300 m ; "moyen"" dans les autres cas.
    -> 1. Ce qui entre : durée en heures et le dénivelé en mètres ; ce qui sort : les difficultés "difficile", "facile" et "moyen".

    -> 2. 

    -> 3.   ALGORITHME Difficulté d'un sentier
            VARIABLES
                duree_Heures : REEL
                denivele : REEL
                difficile : REEL
                moyen : REEL
                facile : REEL
            DEBUT
                SI durée_Heures > 6 OU denivele > 1000 ALORS
                    ECRIRE difficile
                SINON SI duree_heures <= 3 ET denivele <= 300 ALORS
                    ECRIRE facile
                SINON 
                    ECRIRE moyen
                FIN SI
            FIN
    
    -> 4.

* Année bissextile. Une année est bissextile si elle est divisible par 4 mais pas par 100, ou si elle est divisible par 400. Demander une année, afficher la réponse. À tester avec 2024, 2026, 1900, 2000.
    -> 1. Ce qui entre : une année ; ce qui sort : oui ou non.

    -> 2.

    -> 3.   ALGORITHME Année bissextile
            VARIABLES
                une_annee : ENTIER
                anneeBissextile : BOOLEEN
                nombreEntier : ENTIER
            DEBUT
                    nombreEntier <- 
                        LIRE une_annee
                SI      une_annee MOD 4 = 0 ET une_annee MOD 100 = 0 ALORS
                        anneeBissextile <- FAUX
                        ECRIRE anneebissextile
                SINON SI une_annee MOD 4 = 0 ET une_annee MOD 100 > 0 OU < 0 ALORS
                        anneeBissextile <- VRAI 
                        ECRIRE anneeBissextile
                SINON SI une_annee MOD 4 = 0 ET une_annee MOD 100 = 0 ET une_année MOD 400 = 0 
                        anneeBissextile <- VRAI
                        ECRIRE anneeBissextile
                FIN SI
            FIN
    
    -> 4.

* Remise et livraison. On saisit le montant d'un panier. Remise de 10 % à partir de 100 €, de 5 % à partir de 50 €, aucune en dessous. La livraison coûte 6 €, offerte si le montant **après remise** atteint 80 €. Afficher la remise, les frais de livraison et le total à payer.
    -> 1.

    -> 2.

    -> 3.

    -> 4.

## Série 3 -- Boucles

* Compter. Afficher les entiers de 1 à 10, puis de 10 à 1.
    -> 1. Ce qui entre : les entiers de 1 à 10 ; ce qui sort : les entiers de 1 à 10.

    -> 2.

    -> 3.   ALGORITHME Compter
            VARIABLES
                i : ENTIER
            DEBUT
                POUR i DE 1 à 10 FAIRE
                    ECRIRE i
                FIN POUR
                POUR i DE 10 à 1 PAS -1 FAIRE
                    ECRIRE i
                FIN POUR
            FIN

    -> 4.

* Table de multiplication. Demander un entier, afficher sa table de 1 à 10 sous la forme "7 x 3 = 21".
    -> 1. Ce qui entre : un entier ; ce qui sort : une table de multiplication sous la forme "7 x 3 = 21".

    -> 2.

    -> 3.   ALGORITHME Table de multiplication
            VARIABLES
                un_entier : ENTIER
                i : ENTIER
            DEBUT
                LIRE un_entier
                POUR i DE 1 à 10 FAIRE
                ECRIRE un_entier, "x", i, "=", un_entier * i
                FIN POUR
    -> 4.

* Somme. Demander un entier N, afficher la somme des entiers de 1 à N.
    -> 1. Ce qui entre : un entier N ; ce qui sort : somme des entiers de 1 à N.

    -> 2.

    -> 3.   ALGORITHME Somme
            VARIABLES
                N : ENTIER
                i : ENTIER
                somme_des_entiers : ENTIER
            DEBUT
                    LIRE N
                    somme_des_entiers <- 0
                POUR i de 1 à N FAIRE
                    somme_des_entiers <- somme_des_entiers + i
                FIN POUR
                    ECRIRE somme_des_entiers
            FIN

* Saisie controlée. Demander une note entre 0 et 20, et la redemander tant qu'elle n'est pas valide. Afficher la note retenue.
    -> 1. Ce qui entre : une note entre 0 et 20 ; ce qui sort : une note valide.

    -> 2.

    -> 3.   ALGORITHME Saisie contrôlée
            VARIABLES
                note : ENTIER
                note_valide : ENTIER
            DEBUT
                LIRE note
            TANT QUE note < 0 OU note > 20 FAIRE
                ECRIRE "note invalide. Recommencez (entre 0 et 20)"
                LIRE note
            FIN TANT QUE
                ECRIRE "La note retenue est : ", note
            FIN
    
    -> 4.

* Moyenne. L'utilisateur saisit des notes, une par une, et tape -1 pour terminer. Afficher le nombre de notes et leur moyenne. Que se passe-t-il s'il tape -1 tout de suite ?
    -> 1. Ce qui entre : des notes ; ce qui sort : le nombre de notes et leur moyenne.

    -> 2.

    -> 3.   ALGORITHME Moyenne
            VARIABLES
                note : REEL
                nombre_de_notes : ENTIER
                moyenne : REEL
                somme : REEL
            DEBUT
                somme <- 0
                nombre_de_notes <- 0
                LIRE note
            TANT QUE note <> -1 FAIRE
                somme <- somme + note
                nombre_de_notes <- nombre_de_notes + 1
                ECRIRE "Entrez une autre note (-1 pour terminer)"
                LIRE note
            FIN TANT QUE
            SI nombre_de_notes > 0 ALORS
                moyenne <- somme / nombre_de_notes
                ECRIRE "nombre_de_notes : ", nombre_de_notes
                ECRIRE "moyenne : ", moyenne
            SINON
                ECRIRE "aucune note saisie"
            FIN SI
            FIN

    -> 4.

* Nombre mystère. Le nombre à deviner vaut 42. L'utilisateur propose des nombres ; le programme répond "trop grand" ou "trop petit" jusqu'à ce qu'il trouve, puis affiche le nombre d'essais.
    -> 1. Ce qui entre : des nombres ; ce qui sort : le nombre d'essais.

    -> 2.

    -> 3.   ALGORITHME Nombre mystère
            VARIABLES
                nombre : ENTIER
                nombre_essais : ENTIER
                bon_nombre : ENTIER
            DEBUT
                        bon_nombre <- 42
                        nombre_essais <- 0
                        LIRE nombre
                        nombre_essais <- nombre_essais + 1
                TANT QUE nombre <> bon_nombre FAIRE
                    SI nombre < bon_nombre ALORS
                        ECRIRE "Trop petit"
                    SINON 
                        ECRIRE "Trop grand"
                    FIN SI
                        ECRIRE "Essayez encore"
                        LIRE nombre
                        nombre_essais <- nombre_essais + 1
                FIN TANT QUE
                        ECRIRE "Bravo ! Le bon nombre était bien ", bon_nombre
                        ECRIRE "Nombre_essais : ", nombre_essais
                FIN

    -> 4.

* Factorielle. Demander un entier N positif ou nul, afficher N! (le produit des entiers de 1 à N ; par convention 0! vaut 1).
    -> 1. Ce qui entre : un entier N positif ou nul ; ce qui sort : N!.

    -> 2.

    -> 3.   ALGORITHME Factorielle
            VARIABLES
                N : ENTIER
                fact : ENTIER
                i : ENTIER
            DEBUT
                    ECRIRE "un entier positif ou nul"
                    LIRE N
                TANT QUE N < 0 FAIRE
                    ECRIRE "N doit être positif ou nul. Recommencez."
                    LIRE N
                FIN TANT QUE
                    fact <- 1
                POUR i de 1 à N FAIRE
                    fact <- fact * i
                FIN POUR
                    ECRIRE N, "! = ", fact
            FIN
    
    -> 4.

* Nombre premier. Demander un entier supérieur à 1, dire s'il est premier.
    -> 1. Ce qui entre : un entier supérieur à 1 ; ce qui sort : s'il est premier.

    -> 2.

    -> 3.   

    -> 4.

* 