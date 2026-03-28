Q1 : Classez ces sélecteurs par spécificité croissante : p, .text, #main, p.text, #main .text p
1. p 
2. .text
3. p.text
4. #main
5. #main .text p

Q2 : Si deux règles ont la même spécificité, laquelle gagne ?
Si deux règles ont la même spécificité, c'est la "dernière règle définie" dans le fichier CSS qui l'emporte.

Q3 : Pourquoi faut-il éviter !important ?
Il est fortement déconseillé d'utiliser "!important" car :
- Il brise la hiérarchie naturelle de la spécificité et de la cascade.
- Il rend le code difficile à maintenir et à déboguer.
- Il peut entraîner des conflits insolubles lorsqu'on travaille avec des bibliothèques externes.