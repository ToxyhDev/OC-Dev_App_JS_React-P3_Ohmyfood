# Projet 3 - Dynamisez une page web avec des animations CSS

- **ANNEXE - Ressources projets**

  🔗 [Lien dossier projet google drive](https://drive.google.com/drive/folders/1iEnE9L4YCTxl5JXHhrj1Q9R8RIcqZc-F?usp=drive_link)

  🖌️ [Maquette Figma](<https://www.figma.com/file/ZuQApbbsI4OBRGc1aesRcF/Maquettes-Ohmyfood-(mobile-et-desktop)-(Copy)?type=design&mode=design&t=oWcduZquHYSTQyuN-0>)

  📄 [Brief creatif](https://course.oc-static.com/projects/D%C3%A9veloppeur+Web/IW_P4+Animations+CSS+Ohmyfood/Brief+cr%C3%A9atif+site+Ohmyfood.pdf)

  💻 [Github](https://github.com/ToxyhDev/OC-Dev_App_JS_React-P3_Ohmyfood)

---

## ⏳ Timing

**Date début :** 27/08/23 16:00

**Date de fin :** 01/09/23

**Date de fin réel :** 01/09/23 18:15

---

## 🎯 Objectifs :

**Objectifs :**

- Créer une structure de code efficace avec SASS
- Respecter le timing

---

## 📑 Etapes :

➡️ [Guide étape](https://course.oc-static.com/projects/D%C3%A9veloppeur+Web/IW_P4+Animations+CSS+Ohmyfood/Guide+d%E2%80%99e%CC%81tapes+cle%CC%81s+%E2%80%93+Ame%CC%81liorez+l'interface+d'un+site+mobile+avec+des+animations+CSS.pdf)

- [x] **Étape n° 1 : Mettez en place votre environnement de développement**
- [x] **Étape n°2 : Intégrez la version mobile de la page d’accueil**
- [x] **Étape n° 3 : Ajoutez les animations à la page d’accueil**
- [x] **Étape n° 4 : Réalisez le responsive de la page d’accueil**
- [x] **Étape n° 5 : Intégrez le HTML et le CSS d’une page de restaurant**
- [x] **Étape n° 6 : Copiez la page de restaurant et adaptez le contenu aux restaurants restants**
- [x] **Étape n° 7 : Faites une revue complète du projet**

---

## 🤔 Conclusion :

### Problèmes rencontrés :

- Problème au niveau de l’animation pour validé sont plat. J’avais mis dans un label toute les div mais ce n’était pas valide au validateur W3C. J’ai du placer ma div en absolute au dessus de l’élément pour activer la checkbox
- `text-overflow: ellipsis;` problème pour l’ajouter à mon code le conteneur dépassé du parent il fallait que je mette un overflow hidden au parent du texte en question.
- Problème au niveau bouton like de la page d’accueil le label du bouton était dans une balise, j’ai du le déplacer dans le conteneur et le mettre en absolute.

### Point négatif 👎

- Tout a été fait comme il peut être pas optimisé en manière d’accesibilité, à cause des checkbox pour une gestion en css car le JS était interdit.

### Point positif 👍

- Mise en place d’une bonne architecture SASS avec l’utilisation de @for, placeholder, variable, composant.
- Mise en place de la Github Pages que je ne connaissais pas avant.

---
