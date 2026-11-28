
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
                SI  une_annee DIV 400 = nombreEntier ET une_annee MOD 400 > 0 OU < 0 ALORS
                    anneeBissextile <- VRAI 
                    ECRIRE anneBissextile
                SINON 
                    anneeBissextile <- FAUX
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

* 
