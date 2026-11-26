
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

