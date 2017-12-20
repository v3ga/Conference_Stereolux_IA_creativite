# Intelligence artificielle et créativité
Keynotes et tables rondes à [Stereolux](https://www.stereolux.org/) le 13 décembre 2017 dans le cadre d'une journée thématique « créativité et émotions à l'heure de l'intelligence artificielle ».

https://www.stereolux.org/agenda/matinee-keynotes-et-tables-rondes-batiment-b

Avec : 
* Cyrille Chaudoit, directeur du développement / [TheLINKS](http://thelinks.fr).
* Lionel Oisel, Principal Scientist, Technicolor.
* Luis Galarraga del Prado, chercheur à l'INRIA.
* [Elisa Braün](https://twitter.com/elisabraun?lang=fr), journaliste.

## Présentation
[Andrew Ng](http://www.andrewng.org/), professeur à Standford et spécialiste de l’IA, parle de l’intelligence artificielle comme étant la *« nouvelle électricité »*. Comment ces algorithmes qui façonnent les industries de demain peuvent-ils être transposés aux champs de la création artistique et quelles en sont les limites ? Julien Gachadoat apportera quelques éléments de réponses en se basant sur ses propres recherches.

### Contexte de l’IA aujourd’hui : apprentissage supervisé
<img src="https://imgs.xkcd.com/comics/self_driving.png" width="400"/>
J’ai sélectionné cette première image car elle montre de façon humoristique (et critique) sur quoi repose aujourd’hui les algorithmes de deep learning. Ces algorithmes utilisent une masse importante de données «étiquetées» par des humains, dans un mode d’apprentissage supervisé. Les algorithmes apprennent aujourd’hui à reconnaitre des éléments qu’on a bien voulu leur montrer et nous participons à cet apprentissage parfois à notre insu.

<img src="http://www.v3ga.net/_temp/ConfIA/Images/02_AI_Google_ReCaptcha.png" width="200px" />

### Ce que ne peut pas faire l’IA aujourd’hui
<img src="http://www.aaronkoblin.com/work/thesheepmarket/grid.jpg" width="100%" />
Ce mode d’apprentissage m’a rappelé un travail d'Aaron Koblin, « The Sheep Market » qui a astucieusement utilisé les mechanical turks d'Amazon, plateforme qui permet de demander à des travailleurs humains de réaliser des tâches répétitives qui ne sont pas facilement réalisables par une machine. Son utilisation a été détournée pour créer cette composition, et montrer les diversités d’interprétation à partir d’une consigne (« input ») simple : dessiner un mouton.

Ce travail montre à mon sens la créativité de l’être humain et ce que ne peuvent pas vraiment produire ces algorithmes pour l’instant. C’est une instruction simple qui fait appel à l’imagination, à la mémoire, à la culture, des attributs dont ne sont pas dotés les algorithmes d’intelligence artificielle aujourd’hui même si les recherches se tournent dans ce sens ( unsupervised learning notamment )

*Ce projet fait écho aussi aux « manufactures de logarithmes », aux «computers» (calculateurs humains) de l’après révolution française, qui ont précédé la création des machines de Babagge.*

### Créativité et réseaux de neurones
<img src="https://world4jason.gitbooks.io/research-log/content/deepLearning/CNN/img/lenet.png" width="100%" />
Les algorithmes de l'intelligence articielle et de deep learning en particulier reposent sur une architecture de réseaux de neurones à plusieurs couches.

Je vous montre ici un réseau de neurones « historique », le réseau LeNet-5 qui a été construit pour reconnaitre des chiffres manuscrits par [Yann LeCun](http://yann.lecun.com/). Mes recherches m’ont conduit à penser qu’il fallait une bonne dose d’intuition et de créativité pour composer les différentes couches d’un tel réseau.

Une intelligence artificielle pourra-t-telle créer ses propres réseaux de neurone ou peut-être mieux modifier sa propre structure pour être plus performante sur une tâche donnée ? Un petit peu à la manière de notre cerveau qui recycle des neurones *[cas de l’apprentissage de la lecture chez l’enfant par exemple]* Une architecture comme celle-ci pourra-t-elle avoir conscience d’elle-même en quelque sorte ?

<img src="http://www.v3ga.net/_temp/ConfIA/Images/dl.demo2x800.jpg" width="400px" />

*Image tirée de l'article « Visualizing and Understanding
Convolutional Networks » de Matthew D. Zeiler and Rob Fergus, NYU*

### Génération d’images
<img src="https://images.vice.com/vice/images/articles/meta/2015/07/29/no-they-dream-of-puppy-slugs-0000703-v22n8-1438186190.jpg?crop=1xw:0.42674278846153846xh;center,center&resize=0" width="400px" />
Les réseaux de neurones utilisés pour la classification peuvent être aussi détournés (en quelque sorte) pour produire des images générées. C'est le cas avec Deep Dream de Google qui a été entraîné ici à reconnaître des chiens et qui amplifie ensuite tout signal dans les couches intermédiaires où il croit en reconnaître dans une photo quelconque.

La majorité des productions artistiques détourne ce type de réseaux de neurones, et la créativité réside dans le domptage de ces algorithmes ou le choix des bons «ingrédients» (*training sets*, *hyperparamètres*).
Il existe d'autres types de réseaux de neurone détournés ainsi, notamment avec la technique de «neural style transfer» qui consiste à appliquer à une photo quelconque le style d'une œuvre d'art.
Il me semble qu'il existe un potentiel créatif certain en laissant travailler la machine à réaliser des représentations dans des espaces mathématiques difficilement imaginables pour nous laisser ensuite combiner ou détourner ces entités (pas que dans le domaine de l'image).

Il sera possible aussi d'utiliser l'intelligence artificielle « plus discrètement » dans le sens où une œuvre interactive pourrait capter les réactions de ses spectacteurs pour moduler sa propre composition par exemple.

### Créativité et apprentissage du vivant
<img src="https://assets.letemps.ch/sites/default/files/media/2017/07/04/file6v6691ctw6h1dzhb593z.jpg" width="400px" />
Je voulais terminer cette présentation avec cette image, celle d’un blob. C’est un organisme unicellulaire qui peut apprendre à « contourner » des obstacles pour aller chercher de la nourriture et se développer (décrire brièvement l’expérience avec le pont de sel) Et tout cela sans neurones ! Mais encore mieux, il peut fusionner avec d’autres blobs pour partager de l’information.

## Références
Ce paragraphe présente les liens et références dont je me suis servi pour préparer cette keynote et la table ronde. Certaines références ne sont pas toutes directement reliées à l'intelligence artificielle (enjeux et techniques) mais aussi à la biologie, aux neurosciences et à l'histoire de l'informatique.

### Sites / artistes
* [prosthetic knowledge / neural networks](http://prostheticknowledge.tumblr.com/tagged/neural-networks)
* [nips4creativity](http://nips4creativity.com/) — collection of art, music and design using machine learning.
* [nips2017creativity.github.io](https://nips2017creativity.github.io/)
* [Luba Elliot](http://elluba.com) — curator, artist and researcher specialising in artificial intelligence in the creative industries.
  * [The creative AI newsletter](http://mailchi.mp/e42fc9825362/the-creative-ai-newsletter-195661)

### Vidéos
* [Do machines make art ?](https://www.youtube.com/watch?v=FqrHmKo-cm4)
* Lynn Cherry
  * [Conference at KIKK Festival 2017](https://vimeo.com/242926369)
* Kyle McDonald
  * [A return to machine learning](https://www.youtube.com/watch?v=POrPIABj2MI)
* Stanislas Dehane
  * [Les grands principes de l'apprentissage](https://www.youtube.com/watch?v=4NYAuRjvMNQ)
  * [Les neurones de la lecture](https://www.youtube.com/watch?v=ptABRBcdI0c)
  * [Le code de la conscience](https://www.youtube.com/watch?v=mSqX_dwLA40)
 
### Podcasts
* France Culture
  * [L'intelligence peut-elle devenir artificielle ?](https://www.franceculture.fr/emissions/la-conversation-scientifique/lintelligence-peut-elle-devenir-artificielle) / Entretien avec Yann LeCun.
  * [Les neurosciences émotionnelles d'Antonio Damasio](https://www.franceculture.fr/emissions/la-grande-table-2eme-partie/la-grande-table-2eme-partie-mercredi-22-novembre-2017)
* France Inter
  * [Le Blob par Audrey Dussutour](https://www.franceinter.fr/emissions/une-journee-particuliere/une-journee-particuliere-01-octobre-2017), « organisme unicellulaire qui n'a pas de cerveau *[mais qui apprend](http://www2.cnrs.fr/presse/communique/4837.htm)* » — fascinant !

### Articles
* [Artist + AI = Creativity²: Humans and machines will create prize-winning art](https://www.nesta.org.uk/2018-predictions/humans-and-machines-will-win-prize-winning-art)
* Slate
  * [These Stunning A.I. Tools Are About to Change the Art World](http://www.slate.com/articles/technology/future_tense/2017/12/a_i_neural_photo_and_image_style_transfer_will_change_the_art_world.html?utm_content=buffer924bd&utm_medium=social&utm_source=twitter.com&utm_campaign=buffer)
* Olivier Ezratty
  * [L'IA est-elle vraiment créative?](http://www.oezratty.net/wordpress/2017/ia-est-elle-vraiment-creative/)
* Kyle McDonald
  * [Comparing artificial artists](https://medium.com/@kcimc/comparing-artificial-artists-7d889428fce4)
  * [Finding Gogh](https://medium.com/@kcimc/finding-gogh-76ff90cbd408)
  * [A return to machine learning](https://medium.com/@kcimc/a-return-to-machine-learning-2de3728558eb)
* Grégory Chatonsky
  * [Intelligence ou imagination (artificielles)?](http://chatonsky.net/imagination-intelligence/)
  * [L'imagination (de l') artificielle](http://chatonsky.net/imaginaton-artificielle/)
* François Chollet
  * [The impossibility of intelligence explosion](https://medium.com/@francois.chollet/the-impossibility-of-intelligence-explosion-5be4a9eda6ec)
* Shubhang Desai
  * [Neural Artistic Style Transfer: A Comprehensive Look](https://medium.com/artists-and-machine-intelligence/neural-artistic-style-transfer-a-comprehensive-look-f54d8649c199)
* Harish Narayanan
  * [Convolutional neural networks for artistic style transfer](https://harishnarayanan.org/writing/artistic-style-transfer/)
* Céline Henne (Le Monde)
  * [Le cerveau est une machine comme une autre](http://www.lemonde.fr/livres/article/2017/11/18/le-cerveau-est-une-machine-comme-une-autre_5216868_3260.html)
* Olivier Ertzscheid
  * [Google, Andromaque et l'algorithme](http://affordance.typepad.com//mon_weblog/2017/11/google-andromaque-algorithme.html)
* Mark Riedl
  * [Introduction to neural nets without the brain metaphor](https://medium.com/@mark_riedl/introduction-to-neural-nets-without-the-brain-metaphor-874e7950bca0)
* Thomas McMullan
  * [The Work of Art in the Age of Algorithmic Reproduction](https://medium.com/@thomas_mac/the-work-of-art-in-the-age-of-algorithmic-reproduction-bd3bd9b4e236)

### Cours en ligne
* Pierre Lévy
  * [La pyramide algorithmique](http://www.sens-public.org/article1275.html?lang=en)
* Gérard Verroust
  * [Histoire, épistémologie de l'informatique 
et Révolution technologique](http://hypermedia.univ-paris8.fr/Verroust/cours/TABLEFR.HTM)
* Coursera
  * [Deep learning specialization](https://www.coursera.org/specializations/deep-learning)
* 3Blue1Brown — deep learning
  * [Chapter 1, But what *is* a Neural Network?](https://www.youtube.com/watch?v=aircAruvnKk)
  * [Chapter 2, Gradient descent, how neural networks learn](https://www.youtube.com/watch?v=IHZwWFHWa-w)
  * [Chapter 3, What is backpropagation really doing?](https://www.youtube.com/watch?v=Ilg3gGewQ5U)
* Stanislas Dehane
  * [Psychologie cognitive expérimentale](http://www.college-de-france.fr/site/stanislas-dehaene/_course.htm), cours au Collège de France.
* Yann Lecun
  * [L'apprentissage profond](https://www.college-de-france.fr/site/yann-lecun/course-2015-2016.htm), cours au Collège de France et [leçon inaugurale](https://www.college-de-france.fr/site/yann-lecun/inaugural-lecture-2016-02-04-18h00.htm).
* Jean-Gabriel Ganascia
  * [Mooc Intelligence artificielle](http://moocdigitalmedia.paris/cours/intelligence-artificielle/) 
  
### Conférences, évènements
* [NIPS 2017](https://nips.cc/)
* [Intelligence et bêtise artificielle](https://www.ensadlab.fr/fr/francais-conference-intelligence-et-betise-artificielle-au-centre-pompidou/), Centre Pompidou, 17/11/2017 avec [Warren Sack](https://people.ucsc.edu/~wsack/)

### Le coin geek
* Gene Kogan
  * [Machine Learning for artists](http://ml4a.github.io/) — guides / demos / classes / code
* Daniel Shiffman
  * [Coding train / Machine learning](https://github.com/CodingTrain/Machine-Learning), beaucoup de références, excellente ressource.
  * [Neural-Network-p5](https://github.com/shiffman/Neural-Network-p5)
* NVIDIA
  * [pix2pixHD : Synthesizing and manipulating 2048x1024 images with conditional GANs](https://github.com/NVIDIA/pix2pixHD)
* [YOLO : Real-time object detection](https://pjreddie.com/darknet/yolo/)
