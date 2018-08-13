## Setup d'un site R&R "Phase 1" -  la checklist des taches a faire pour tout site R&R
* Recherche de mots cles a faible competition, choix de la methode de rentabilisation a priori
  * Volume min. de 200-300 recherches par mois
  * CPC aussi haut que possible
  * KGR le plus faible possible https://www.humanproofdesigns.com/kgr-for-high-volume-keywords/
  * Au moins 2-3 domaines avec un DR <30 dans le top 10 des resultats
    * 1 ou 2 sites niche dans le top 10 est un bon indicateur, plus de 3 veut dire que la competition va etre potentiellement rude
* Trouver un domaine exact match avec TLD approprie. Exact match ideal:
  * Exactement les mots cles, sans rien de plus
  * Dans le bon ordre
  * Eviter les tirets autant que possible
  * Choisir le bon TLD, par exemple offshoresoftwaredevelopment.net est meilleur que le .com, parce que c'est lie au sujet IT. De meme aspirateursansfil.fr est meilleur que le .com si la france est ciblee: [details.](https://www.searchenginejournal.com/how-to-choose-domain-name/252285/)
  * Nouveau domaine ou domaine expire? [Details.](https://marketever.com/how-to-choose-the-right-domain-name-niche-site/)
* Contenu:
  * Contenu simple qui est en lien avec le mot cle, unique, idealement ~1000 mots ou plus
  * Le faire ecrire
  * ou chercher du contenu abandonne sur un domaine expire 
    * rechercher des sites abandonnes sur archive.org, 
    * verifier qu'il n'a pas ete reutilise quelque part
* Tracking
  * Ouvrir un compte clicky.com
  * Creer un tracking pour le domaine
* Hebergement
  * Creer une repo github et lui choisir un theme par defaut
  * Pour ne pas tjs utiliser le mm theme, en prendre un dans la librairie de [themes Jekyll](http://jekyllthemes.org/), et le mettre dans le fichier de configuration yml (parametre remote_theme au lieu de theme)
  * https://github.com/adam-p/markdown-here/wiki/Markdown-Here-Cheatsheet => comment formater le contenu de la page pour le rendre un peu moins moche qu'un sale copier/coller de texte 
  * Ajouter le code de tracking clicky just avant la balise de fermeture *</body>*
  * Bien renseigner le titre des pages et les meta, verifier qu'il y a bien un H1 et qu'il correspond au titre
  * Copier dans la repo les fichier de layout que tu veux modifier, et faire les modifs
  * Ajouter une page 404
  * Ajouter une page contact et liu mettre un lien sur la homepage
  * Faire pointer le domaine
    * Ajouter 3 A records dans les parametres DNS du domaine vers les serveurs IP de Github
    * Rediriger le sous domaine www vers la racine du domaine
* Link building
  * Ajouter dans un repertoire web un lien vers le site pour qu'il soit index par Google, si possible en nofollow
  * ou n'importe quel lien depuis un site indexe fera l'affaire, le mieux est en nofollow pour eviter de prendre une penalite si le site est spammy
  
**Tadaa, le domaine est accessible et il ne reste plus qu'a attendre l'indexation!**


## Une liste de lecture:

### Pour preparer la phase 2 (rien de tout ca ne doit etre implemente pour le moment):
* [Comment structurer un site une fois qu'il a montre du potentiel](https://rileyx.com/rank-and-rent/)
* [Pareil, en plus detaille avec d'autres methodes](https://chasereiner.com/blog/local-seo/rank-and-rent-guide/)
* [Comment creer du contenu qui cible des sous-mots cles avec le moins de competition possible](http://tao-mmo.com/kgr-guide/)
* [Pareil, avec d'autres details](https://nichesiteproject.com/keyword-golden-ratio-best-keyword-research-rank-google/)
* [Anatomie d'une page parfaite d'un point de vue SEO](https://backlinko.com/on-page-seo)
* [Une introduction a schema et a son implementation](https://www.contentkingapp.com/academy/schema/)

### Des connaissance plus generales, qui seont toujours utiles 
* Qq cours pour apprendre les bases de l'html/css:
  * [https://fr.slideshare.net/SamuelRobert2/les-bases-de-lhtml-css](https://fr.slideshare.net/SamuelRobert2/les-bases-de-lhtml-css)
  * [https://fr.khanacademy.org/computing/computer-programming/html-css/intro-to-html/p/html-basics](https://fr.khanacademy.org/computing/computer-programming/html-css/intro-to-html/p/html-basics)
  * [https://developer.mozilla.org/fr/docs/Apprendre/Commencer_avec_le_web/Les_bases_HTML](https://developer.mozilla.org/fr/docs/Apprendre/Commencer_avec_le_web/Les_bases_HTML)
* Apprendre git et github (en particulier le versioning):
  * [https://medium.com/quick-code/top-tutorials-to-learn-git-for-beginners-622289ffdfe5](https://medium.com/quick-code/top-tutorials-to-learn-git-for-beginners-622289ffdfe5)
  * [https://lab.github.com](https://lab.github.com)
