## Activité 3 : Comptabilisation

Contenu:

* [A. Fiche Pédagogique](#A-fiche-pédagogique)
    - [1. Objectifs spécifiques](#1-objectifs-spécifiques)
    - [2. Supports](#2-supports)
    - [3. Méthodes et Techniques](#3-méthodes-et-techniques)
    - [4. Durée](#4-durée)
    - [5. Déroulement de l'activité](#5-déroulement-de-l'activité)
* [B. Fiche Technique](#B-fiche-technique)
    - [1. Notions](#1-notions)


### A. **Fiche Pédagogique**


#### 1.  **Objectifs spécifiques** :

Au terme de cette activité, le participant sera capable de (d') :

-   Expliquer les notions de la comptabilisation à l'aide du logiciel comptable ;

-   Distinguer les types d'écritures dans le logiciel comptable ;

-   Utiliser la comptabilité en partie double avec TVA.

#### 2.  **Supports** :

-   OHADA, Acte uniforme relatif au droit comptable et à l'information financière et système comptable OHADA, Yaoundé le 15 février 2017 ;

-   Guide d'application OHADA ;

-   EPSP, DIPROMAD, *Curriculum des Humanités Techniques Commerciales*, Commerciale et Gestion, Kinshasa 2014 ;

-   SERNAFOR Technique, module de formation sur le système comptable OHADA niveau 4, 2018 ;

-   [La documentation du logiciel Banana](https://www.banana.ch/fr/documentation)

#### 3.  **Méthodes et techniques** :

Exposé, discussion dirigée, brainstorming et travail de groupe.

#### 4.  **Durée** : 

120 minutes

#### 5.  **Déroulement de l'activité** :

|     N°    |     Tâches                                                                                                                                                                              |     Méthodes et Techniques    |     Durée      |
|-----------|-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|-------------------------------|----------------|
|     1     |     Présenter   l’activité et ses objectifs                                                                                                                                             |     Exposé                    |     5 min.     |
|     2     |     expliquer les notions de la comptabilisation à l’aide du logiciel   comptable                                                                                                       |     Brainstorming             |     15 min.    |
|     3     |     Constituer des   sous-groupes pour :     <ul><li>distinguer les types d’écritures;</li><li>utiliser la comptabilité en partie double avec TVA.</li></ul>                                           |     Travail en   groupe       |     70 min.    |
|     4     |     En plénière : le rapporteur de chaque sous-groupe présente la   production de son équipe suivie de mise en commun avec les membres des autre   sous-groupes et du facilitateur.     |     Discussion   dirigée      |     20 min.    |
|     5     |     Questions de   synthèse     <ul><li>citer les types d’écritures utilisés dans logiciel comptable;</li>   <li>expliquer la comptabilité en partie double avec TVA.</li></ul>                             |     Discussion dirigée        |     10 min.    |



### B. **Fiche Technique**

#### 1. Notions

##### 1.1 Soldes d'ouvertures

Quand on utilise Banana Comptabilité pour la première fois, il est
nécessaire d'insérer les soldes initiaux manuellement pour créer le
bilan d'ouverture. Le **solde d'ouverture** d'un compte est indiqué
dans la colonne **Ouverture**:

a. Se positionner dans le tableau **Comptes**, vue **Base**,
    colonne **Ouverture**;

b. Reporter manuellement les soldes initiaux des comptes Actifs et
    Passifs. **Les soldes débiteurs sont indiqués normalement. Les soldes créditeurs sont indiqués avec le signe moins (en négatif)**;

c. Contrôler que le total Actifs est égal au total Passifs pour avoir l'équilibre comptable. Dans le cas qu'il y a des différences dans les soldes d'ouverture, il faut [**contrôler et corriger**](https://www.banana.ch/doc9/fr/node/7220).

Pour reporter automatiquement les soldes d'ouverture pour l'année
suivante, cliquer sur menu compta 2 puis cliquer sur créer une nouvelle
année.

##### 1.2 Mise à jour des soldes d'ouverture

La commande **Mettre à jour Soldes d'ouverture :**

-   Reprend les données de clôture du fichier indiqué.

-   Copie les données de l\'année précédente dans le fichier courant (voir commande [Créer nouvelle année](https://www.banana.ch/doc9/fr/node/3398#2))

La commande n'influence pas les écritures déjà insérées. En fait, c'est comme si on crée une nouvelle année et on enregistre dans l'année courante.

La commande **Mettre à jour Soldes d'ouverture**est nécessaire dans les cas suivants :

- Si on a créé une nouvelle année et par après on a fait d'ultérieures écritures ou corrections dans l'année précédente ;

- Quand le bénéfice ou la perte de l'exercice n'a pas été reparti.

La procédure de mise à jour est la suivante :

- Ouvrir le fichier de l'année courante et du menu **Compta2**, cliquer sur la commande **Mettre à jour soldes d'ouverture**

- Spécifier le fichier de l'année précédente, avec le bouton **Parcourir**

- Suivre les mêmes instructions que celles pour la commande **Créer nouvelle année**.

![Image Parcourir](images/activity3b_1.jpg)

##### 1.3 Écritures de l'année

Il s'agit d'insérer les écritures dans le journal. Les écritures doivent être insérées dans le **Tableaux Écritures**.

![Tableau Écritures](images/activity3b_2.jpg)

##### 1.4 Commentaire sur les colonnes du tableau d'Écritures

a. **Date :** La date doit être située dans la période comptable définie dans les [Données de base](https://www.banana.ch/doc9/fr/node/2864) de la comptabilité. Dans les [options](https://www.banana.ch/doc9/fr/node/2865) on peut indiquer que la date est obligatoire, autrement la valeur peut être vide. S'il y a des [écritures bloquées](https://www.banana.ch/doc9/fr/node/3168), le programme signale une erreur quand on insère une date inférieure ou égale à la date du bloc. 

b. **Pièce :** Le numéro du justificatif qui est la base pour l'écriture comptable. En introduisant les écritures, il est conseillé d'indiquer un numéro progressif sur le document, de façon à ce que l'on peut facilement retrouver la pièce comptable. La fonction de saisie semi-automatique suggère des valeurs progressives et des codes d'écriture définis précédemment dans le tableau Écritures répétées. Le programme propose le numéro suivant du document, qui peut être repris avec la touche **F6**.

- Numérotation numérique, le programme incrémente simplement la valeur plus élevée trouvée dans la **colonne Doc ;**

- Numérotation alphanumérique, le programme incrémente la partie numérique finale ; cette fonction est utile si l'on veut tenir des numérotations séparées pour la caisse ou la banque.

    -   Si précédemment C-01a été inséré, et on commence à taper C, le
        programme propose C-02.

    -   Si précédemment B104 a été inséré, et on commence à taper B, le
        programme propose B105.

    -   Si précédemment D10-04 a été inséré, et on commence à taper D,
        le programme propose D10-05.

Dans les écritures répétées vous pouvez prédisposer des groupes d'écritures qui seront reprises au moyen d'un code.

Pour ajouter une grande quantité de numéros, vous pouvez éventuellement
profiter d'Excel. Créez dans Excel la quantité désirée de numéros de
pièces et copier et coller dans la colonne **Pièce** du tableau Ecritures de Banana Comptabilité.

c. **Numéro de la facture :** Un numéro de facture émise ou payée qui est utilisé avec la fonction de contrôle-factures pour clients et fournisseurs.

d. **Lien à fichier externe :** Sert à insérer un lien à un fichier externe, habituellement le justificatif comptable. Avec la petite flèche en haut, le programme ouvre le document. Cette colonne est utilisée avec la commande **Lien à un document**

e. **Libellé :** Le texte de l'écriture. La fonction de saisie semi-automatique suggère le texte d'une écriture déjà insérée, ou insérée l'année précédente si l'option appropriée est active. En pressant la touche **F6**, le programme reprend les données de la ligne précédente avec le même libellé et complète les champs de la ligne actuelle.

f. **Compte Débit :** Le compte qui sera débité.

g. **Compte Débit Description :** La description du compte inséré, reprise du plan comptable

h. **Compte Crédit :** Le compte qui sera crédité. Pour le reste, nous renvoyons l'utilisateur à l'explication sous "**Compte Débit**".

i. **Compte Crédit Description**: La description de ce compte, reprise du plan comptable

j. **Montant :** Le montant qui sera inséré sur le compte Débit et le compte Crédit.

#### 2. Types d'écritures

Avec le logiciel banana comptabilité, vous avez la possibilité de tenir :

-   La Comptabilité en partie double mono-devise sans ou avec TVA ;

-   La Comptabilité en partie double multidevise sans ou avec TVA

-   La Comptabilité en partie double mono-devise sans TVA ;

Il y a généralement deux types d'écritures :

-   Ecritures simples

-   Ecritures composées

##### 2.1 Comptabilité en partie double sans TVA

a. **Écritures simples**

L'écriture simple celle qu'inclue deux comptes qui sont insérés chacun sur une seule ligne. Le numéro de pièce est différent pour chaque écriture.

![Écritures simples](images/activity3b_3.jpg)

b. **Écritures composées**

L'écriture composée est celle qui fait intervenir au moins deux comptes
enregistrés sur plusieurs lignes. Le numéro de document reporté sur les
différentes lignes est le même car il s'agit de la même écriture.

**N.B. :** Dans les écritures composées, les dates des lignes de l'écriture doivent être les mêmes, sinon, en cas de calculs par période, il pourrait y avoir des différences comptables.

![Écritures composées](images/activity3b_4.jpg)

##### 2.2 Comptabilité en partie double mono devise avec TVA

Les plans comptables de Banana Comptabilité 9 sont déjà configurés avec
les comptes pour la TVA. Si vous n'utilisez pas les plans comptables
préconfigurés de Banana, il est nécessaire de vous assurer que dans
votre plan comptable personnel les comptes TVA soient présents.

Néanmoins, il est possible de convertir généralement un fichier existant
en un autre avec des propriétés différentes. Notamment passer d'un
fichier de plan de comptes sans la déclaration TVA à un autre plan de
comptes avec la déclaration TVA. Pour ce faire, on procède de la manière
suivante :

-   Aller dans la barre de menus puis cliquer sur outils ;

-   Commande convertir fichier ;

![convertir](images/activity3b_5.jpg)

-   Enregistrer et indiquer le nom du nouveau fichier.

![enregistrer](images/activity3b_6.jpg)

**N.B.** : Lors de la conversion, il sied de rappeler que les données du
fichier existant restent inchangées. Quand un fichier, contenant plus
d'éléments, est converti dans un fichier avec moins d'informations, une
partie des données sera perdue pendant la conversion. Par exemple, si on
veut convertir une comptabilité avec TVA dans une comptabilité sans TVA,
les données relatives aux colonnes de la TVA seront perdues dans la
conversion.

a.  **Tableau codes TVA**

Les configurations dans le tableau Codes TVA permettent de définir tous
les paramètres nécessaires pour gérer les modalités des écritures avec
TVA. Ces configurations concernent : la TVA due ou à récupérer, le
montant de l'écriture au brut, au net ou montant TVA au 100% (TVA à la
douane), le pourcentage TVA à appliquer, le compte sur lequel la TVA
doit être enregistrée, l'arrondi spécifique pour chaque code ou la
méthode de regroupement et de totalisation.

b.  **Modalité de calcul**

Les paramètres indiqués dans le tableau TVA sont utilisés pour calculer
la TVA des écritures individuelles.

Dans les écritures, on ne peut pas changer les paramètres établis dans
le tableau Codes TVA. Cette modalité assure que les calculs TVA soient
corrects et uniformes.

**N.B:** Si la valeur d'un code TVA, qui a déjà été utilisé dans les
écritures, est modifiée, les modifications ne sont pas directement
reportées, mais il est nécessaire d'activer la commande pour
recontrôler la comptabilité (Menu **Compta1 -> Contrôler comptabilité)**.

Quand on modifie le tableau TVA, par prudence, le programme affiche un
message dans la fenêtre d'information qui invite l'utilisateur à
procéder à un recontrôle complet.

**Le tableau qui suit se réfère aux codes utilisés selon les normes Congolaises**.

![normes congolaise](images/activity3b_7.jpg)

c. **Description détaillée des colonnes**

Dans les colonnes suivantes, insérez les données suivantes :

-   **Groupe** : un sigle ou un numéro qui indique le groupe
    d'appartenance.

-   **Cod. TVA** : il y a un code TVA approprié pour chaque type
    d'écriture. Au moment de l'écriture il suffit d'actionner ce code,
    la TVA est comptabilisée automatiquement.

-   **Libellé** : un texte pour la description du code TVA ou du Groupe.

-   **Gr** : sigle du Groupe dans lequel la ligne doit être totalisée.

-   **Gr1** : dans l'image sont présents les regroupements pour la
    codification qui représente les chiffres de la déclaration TVA de la
    Direction Générale des Impôt de la RDC.

-   **TVA due (collectée) :** si dans la cellule de cette colonne
    **Oui** est insérée, ceci veut dire que la TVA est due ou collectée.
    Si rien n'est indiqué, ceci veut dire que la TVA est récupérable.

-   **Montant type** : le code indique comment doit être compris le
    montant de l'écriture.
    
    - (0) Lorsque c'est zéro, la cellule reste vide : la TVA est incluse
    dans le montant de l'écriture ;

    - (1) Le montant de l'écriture est le montant net de la TVA.
    C'est-à-dire c'est le montant hors TVA.

    - (2) Montant TVA le montant de l'écriture est considéré comme
    montant TVA à 100% TVA **%**

-   **Non déd. :** la partie de la TVA qui n'est pas déductible en
    pourcentage. A être utilisé quand la déduction de la TVA n'est pas
    applicable complètement. Les modifications pour ce champ ne sont
    reprises que pour de nouvelles écritures.

-   **% au brut** : d'habitude, cette colonne reste vide. Dans des cas
    particuliers, on doit y insérer **Oui** seulement si le taux TVA
    doit être appliqué sur le montant brut (TVA comprise) et non sur
    l'imposable (par exemple lors de taux de TVA forfaitaires).

-   **Compte TVA** : le numéro de compte sur lequel la TVA calculée est
    enregistrée automatiquement.

Quand les écritures avec TVA sont insérées, en appliquant le code TVA
dans la colonne **Cod. TVA**, le programme calcule automatiquement tous
les montants relatifs à la TVA et les transfère dans le compte TVA.

##### 2.3 Comptabilité multidevise sans TVA

La comptabilité multidevise est basée sur la méthode de la comptabilité
en partie double, mais permet de gérer les comptes et mouvements en
devise étrangère.

a. **Caractéristiques**

-   Gère aussi les comptes en devise étrangère ;

-   Calcule automatiquement le change, selon le change inséré dans le
    tableau Changes ;

-   Calcule automatiquement les différences de change ;

-   Bilans, Comptes de résultat et rapports également dans une deuxième
    devise.

Pour passer d'une comptabilité mono à une avec la multidevise, procède
de la manière suivante :

-   Aller dans la barre de menus puis cliquer sur outils ;

-   Commande convertir fichier ;

![convertir fichier](images/activity3b_8.jpg)

La boite de dialogue ci-dessous apparaitra ; cliquer sur comptabilité en partie double avec multidevises.

![enregistrer](images/activity3b_9.jpg)

Enregistrer et indiquer le nom du nouveau fichier.

b. **Plan comptable, Propriétés fichier et tableau Changes.**

Il est conseillé de choisir un plan comptable, en partant d'un exemple
de Banana Comptabilité déjà configuré et en le modifiant selon vos
propres besoins. Il est fondamental que dans le plan comptable
des **Comptes en devise étrangère** et des **Comptes pour le bénéfice et
la perte de change** soient configurés.

c. **Le plan comptable multidevise**

Le plan des comptes de la comptabilité multidevise est le même que ceux
de la comptabilité avec une seule devise, à l'exception des facteurs
spécifiques indiqués ci-dessous.

d. **Devise de base**

Dans les **Propriétés fichier,** menu **Fichier**, vous devez définir la
devise de base et dans le tableau Changes, il vous faut définir les
devises étrangères.

Dans l'exemple qui suit, la devise de base est le CDF qui, comme vous
pouvez le voir, apparaît dans les en-têtes des colonnes avec les
montants en devise de base.

e. **Devise du compte**

Chaque compte possède un sigle de devise, qui peut être celui de la
devise de base, ou celui d'une devise étrangère, indiqué dans le
tableau Changes.

**Les comptes Actifs et Passifs, en plus de la devise de base peuvent être définis en plusieurs devises.**

![comptes actifs](images/activity3b_10.jpg)

**Les comptes des Charges et Produits en plus de la devise de base (dans l'exemple le CDF), peuvent être définis en plusieurs devises étrangères**

![comptes actifs](images/activity3b_11.jpg)

f. **Explication des colonnes de la Comptabilité multidevise**

-   **Devise** : Insérez le sigle de la devise du compte. Pour les comptes en devise étrangère, le sigle doit être présent aussi dans le tableau Changes.

-   **Ouverture Devise :** Pour chaque compte il faut insérer le solde initial, que ce soit un pour un compte en devise de base que pour un compte en devise étrangère.

-   **Ouverture (devise de base)**: nous avons dans cette colonne :

    - Colonne protégée utilisée par le programme ;
    
    - Le solde initial de la devise de base est calculé par le programme ;

    - Pour les comptes en devise de base, le solde d'ouverture est celui de la colonne Ouverture devise ;

    - Pour les comptes en devise étrangère, le solde présent dans la colonne Ouverture devise est reporté ici, converti selon le taux de change en vigueur dans le tableau de changes, dans la ligne sans date, colonne Ouverture.

-   **Solde devise :**

    - Colonne protégée utilisée par le programme ;

    - Le solde provient du solde d'ouverture et de l'importation des écritures en devise de base et étrangères ; pour les comptes en devise étrangère, le solde est converti en devise de base selon les taux de change en vigueurs dans le tableau **Changes**.

-   **Solde :**

    - Colonne protégée utilisée par le programme ;

    - Le solde est calculé par le programme et est le résultat de la somme du solde d'ouverture (pour les comptes en devise étrangère c'est le solde converti en devise de base) et de l'importation des écritures en devise de base et devise étrangère (montants convertis selon un taux de change, présent dans le tableau Changes).

-   **Solde calculé**

    - Colonne protégée utilisée par le programme ;

    - C'est le solde en devise du compte converti au taux de changes actuel (taux de changes du tableau Changes de la ligne sans date) ;

    - Dans cette colonne, les soldes des comptes en devise, convertis en devise de base peuvent différer de ceux de la colonne Solde, en raison des différences de change.

-   **Les soldes d'ouverture**

    - Avant d'insérer les soldes d'ouverture, il faut indiquer le change d'ouverture pour les différentes devises dans le tableau Changes. Le change d'ouverture est celui indiqué dans la colonne Change Ouverture dans la ligne de change sans date. Les changes d'ouverture doivent être égaux à ceux de la clôture de l'année précédente ;

    - Les soldes d'ouverture doivent être insérés dans le tableau **Comptes**, colonne **Ouverture Devise**, vue **Base**, pour ceux qui se réfèrent à la devise de base ainsi que pour ceux en devise étrangère ;

    - La colonne **Ouverture (**devise de base) est protégée. Le programme calcule automatiquement la contrevaleur en devise de base selon le change d'ouverture indiqué dans le tableau Changes ;

    - Les soldes créditeurs doivent être insérés avec le signe moins (-) devant le montant ;

    - Les soldes d'ouverture des actifs et des passifs doivent être en> équilibre. Il est conseillé de consulter la leçon suivante: **Contrôler la comptabilité**

g. **Comptes gain et perte de change**

Dans le plan comptable, il faut insérer les comptes prédéfinis pour le gain (bénéfice) et la perte de change, qui seront ensuite indiqués dans les **Propriétés fichier**.

![gain et perte change](images/activity3b_12.jpg)

Les comptes pour les différences de change doivent contenir la BClasse 3
(Charges - pertes de change) ou 4 (Produits - gains de change).

h. **Tableau Changes**

Avant de commencer d'enregistrer des opérations multidevises, il faut
d'abord spécifier les paramètres des devises utilisées pour la
comptabilité, dans le tableau Changes.

![tableau change](images/activity3b_13.jpg)

i. **Explication des Colonnes du tableau Changes**

Les colonnes sont visibles dans la Vue Complète.

-   **Date :** La date du change : Nous avons ici 2 cas, à savoir :

    - **Ligne change sans date** : Le taux de change actuel et d'ouverture. Pour chaque devise étrangère utilisée, il faut absolument avoir une ligne avec le taux de change et sans date : **le change** est celui qui est considéré le plus récent et aussi celui de la clôture. Il est utilisé pour le calcul de la colonne solde calculé dans le tableau des comptes et toujours s'il n'y a pas de taux de change historique tandis que le **change ouverture** est utilisé pour convertir le montant d'ouverture de la devise étrangère en celui de l'ouverture de la devise de base de la comptabilité.

    - **Lignes change avec dates** **(taux de change historiques)**: Dans les cas indiqués ci-dessous le programme choisit le taux de change avec une date égale ou inférieure la plus proche de la date de la ligne d'écriture :



