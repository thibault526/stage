# stage

## fichier qui décrit le stage dans l'entreprise "Antidot" du 15 décembre au 19 décembre:

### Jour 1:

```python
def thales(a: int|None, b: int|None, c: int|None):
    if a is not None and b is not None:    # si a et b sont definis
        b = a + b
        print(a, b, c, d)    # affiche les valeurs pour suivre le fonctionnement
        return (d*c)/a    # résoudre le quotient de a par le produit de d par c



```

Tout d'abord, je suis allé à l'entreprise Antidot en vélo avec Olivier. En arrivant aux bureaux, Olivier (mon tuteur de stage) m'a mis sur un bureau à côté de lui. durant cette première matinée, il m'avait préparé des petites activitées de codages sur le logiciel informatique Python. Sur Python j'ai progammé un code pour résoudre des théorêmes de mathématiques (Pythagore et Thalès). Le midi j'ai mangé avec 5-6 personnes de l'entreprise,  en discutant de sujets diverses. À 14h, j'ai eu une réunion avec l'agente marketing pour qu'elle m'explique son métier, qu'est ce qu'il apporte à l'entreprise ce qu'elle fait pendant la journée, et enfin le produit que Antidot vend aux grandes entreprises. Le produit  s'appelle Fluid Topics, c'est un portail de documentation.C'est à dire que  juste en tapant des "Keyswords", des blogs Linkedin apparaissent en rapport avec ton mot. Ce portail de documentation sert pour les sites internets  de grandes entreprises comme "Konne" pour les ascenseurs. Pour finir, derrière Fluid Topics, qui n'est qu'une espèce de moteur de recherche, il y a tous les développeurs qui construisent des lignes de codes pour pouvoir faire fonctionner Fluid Topics. Pour continué l'après-midi, j'ai enchainé avec une deuxième réunion cette fois à distance avec une développeuse d'une certaine équipe "Search".  Pareil, elle m'a présenté son métier de développeur/développeuse. Enfin, vers 17h30  avec Olivier,nous sommes rentrés en vélo car oui, le soir je dorschez lui et  je passe la semaine avec lui et sa famille.

### Jour 2:

```python
def paire(l):    # définit la fonction "paire" (l)
    result = []    # result est une liste vide: []
    for i in l:    # pour i dans l 
        if i % 2 == 0:    # si i est divisible par 2:
            result.append(i)    # ajouter i dans la liste result
    return result  


def impaire(l):
    result = []
    for i in l:
        if i % 2 == 1:
            result.append(i)
    return result
```

Le matin, je suis allé à l'entreprise en métro car il pleuvait, mais au fur et à mesure de la journée, il a fait beau. Ensuite j'ai eu une réunion avec l'assisstante RH (Ressources Humaines) qui, pendant 1h, m'a expliqué son métier. l'assisstante RH de l'entreprise s'occupe des liens entre les salariés .Elle vérifie si il n'y a pas de tensions au sein de l'entreprise ou bien autre chose de grave. Elle vérifie aussi les droits du travail (si les salariés sont assez payés ou alors si les conditions de travail sont conformes aux lois, elle s'occupe aussi des recrutements et des  licienciements...). Après, il était midi. Alors Olivier et moi sommes partis  nous chercher à manger. Puisque j'ai adoré le sandwich de la veille, j'ai repris le même. Vers 13h, je me suis retrouvé avec un petit groupe de salariés pour jouer à des jeux de sociétés d'ambiances assez rapides. Pendant l'après-midi, Olivier m'a appris à faire des dictionnaires avec une clé, des codes pour dire si un chiffre est pair/impair ou bien des listes de chiffres dans le but d'ordonner les informations. Au début, je ne comprenais absolument rien. J'étais vraiment perdu et plus extrèmement fatigué. mais quand Olivier m'a donné un exercice, plutôt que de m'expliquer trop de choses, tout s'est éclairci et j'ai réussi l'exercice le lendemain car j'y avais un peu réfléchi la nuit. 

### Jour 3:

```python
class Parallelepiped:    # modèle pour créer des objets, tous définis dans la class

    def __init__(self, l, L):    # définis les états initiaux de l et L
        self.l = l
        self.L = L

    def perimeter(self):    # définis la fonction "perimeter"
        return self.l * 2 + self.L * 2    #résouds la somme du produit de du produit de 2 fois l et du produit de 2 fois L

    def area(self):    # définis la fonction "area"
        return self.l * self.L

p = Parallelepiped (6, 7)
print(p.perimeter())    # affiche les valeurs contenues dans la fonction perimeter
print('perimetre parallelepiped')    # affiche perimetre parallelepiped
print(p.area())
print('aire parallelepiped')
```

Ce matin, j'ai continué mon programme Python avec un code de calcul pour calculer l'aire et le périmètre d'une figure géométrique. Puis de 11h à 12h, j'ai assissté à une réunion avec plein de membres qui venaient d'équipes différentes. Je me suis présenté à eux puis, durant toute la réunion, ils ont parlé de sujets différents (ce qui va ou ne va pas dans l'entreprise). Ensuite, chaque membre devait présenter l'avancée de son/ses projet(s) enfin, la réunion s'est terminée. Le midi j'ai déjeuné dans un restaurant:  "the Jungle". La décoration était particulièrement acceuillante et te donnait l'impression d'être dans une jungle. De plus, le burger et les frites de patates douces étaient exellents. de retour au bureau, L'arpès-midi, j'ai continué mon programme Python mais cette fois-ci avec des formes géométriques plus compliquées: le cercle, le parallélépipède et le trapèze, jusqu'à la fin de journée cela m'a pris beaucoup de temps à comprendre le système de codes pour calculer un cercle car il fallait trouver le nombre PI que l'on ne pouvait pas déduire. Cependant, quand j'ai terminé mon programme, j'ai sauté de joie dans tous les bureaux (non, j'abuse peut-être un peu) mais quand même trop content. J'adore cette sensation où je me creuse la tête toute l'après-midi et finalement après 2h d'acharnement j'y arrive enfin. Ce soir-là, moi et Olivier sommes rentrés à la maison en vélo après une grosse journée assez éprouvantes.

### Jour 4:

Durant cette matinée, j'ai découvert le site de github. C'est un logiciel qui te permet d'écrire tout ce que tu veux, n'importe comment. Dessus, j'ai écrit le journal de bord pour mon rapport de stage. Ensuite, Olivier m'a crée un dossier  github me permettant d'écrire mon rapport ou bien qqch d'autre et puis après, github retranscrit mon texte avec une plus belle présentation. De 10h à 12h, plusieurs personnes m'ont expliqué leur métier:

-Benoit est un membre de l'équipe SER. En gros, il s'occupe et surveille à longueur de journée l'état des data centers disposés à Singapour, Ohio et Vitry. L'équipe SER essaye aussi d'automatiser tout le système de vérification. ils utilisent des scripts pour contrôler l'état des ordinateurs à distance comme ça ils n'auront pas à aller les réparer sur place et du coup faire du chemin. Pour vérifier si l'ordinateur est éteint ou pas, ils envoient un PING (message rapide demandant à l'ordinateur si il est éteint ou pas) à l'ordinateur.

-Alain est un membre de l'organisation PS (Professionnal Services) dans le pôle TECH. Lui et son équipe s'occupent notamment d'exécuter et de faire ce que le client demande. Parfois ceux-ci demandent qqch de très compliqué ou même parfois carrément impossible. Alors c'est à ce moment là que Alain et son équipe entre en scène: ils proposent au client une solution plus possible pour eux ou bien pour le logiciel. La plupart du temps le client comprend et accepte les conseils mais des fois le client n'accepte pas et donc alain et son équipe sont obligés de suivre ce que le client demande. Ensuite, le pôle CAP s'occupe de l'aspect accompagnateur des clients et adapte le logiciel Fluid Topics en fonction des préférences du/des clients. 

Dès 13h, j'ai refais des petites parties de jeu de société avec 3 autres personnes. C'était super sympathique.
De retour à mon bureau, j'ai continué d'écrire tout ce texte sur Github. Je me suis assez habitué au rythme du travail car je suis de moins en moins fatigué mais malheureusement le stage se finit déjà demain. De retour à la maison, le soir, je pense à comment serait le métier d'informaticien 10 ans plus tard. Je me divertit aussi en lisant Da Vinci Code. 
