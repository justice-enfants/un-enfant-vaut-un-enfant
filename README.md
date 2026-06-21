# ⚖️ Un enfant vaut un enfant — Simulateur d'Arbitrage Fiscal

> **Accéder directement au simulateur :** [https://justice-enfants.github.io/un-enfant-vaut-un-enfant/](https://justice-enfants.github.io/un-enfant-vaut-un-enfant/)

Ce projet est une initiative citoyenne, transparente et open-source. Elle vise à ouvrir le débat public sur une réforme de la politique familiale française : **le remplacement du quotient familial par une allocation universelle et unique dès le premier enfant.**

---

## 💡 Le Constat : Pourquoi ce simulateur ?

Le système fiscal actuel repose sur le mécanisme du **quotient familial**. En réduisant l'impôt de manière proportionnelle à la tranche marginale d'imposition, l'État accorde indirectement une aide publique par enfant plus élevée aux familles à hauts revenus qu'aux familles modestes ou de la classe moyenne inférieure. 

* **Le modèle actuel :** Plus les revenus sont élevés, plus l'avantage fiscal lié à l'enfant est important (jusqu'au plafond légal).
* **Le modèle proposé :** Chaque enfant donne droit à la même somme directe sous forme d'allocation universelle, peu importe le revenu de ses parents.

Ce simulateur permet à chaque citoyen de calculer instantanément ce qu'il y gagnerait (ou perdrait) si la France adoptait ce principe fondamental : **un enfant vaut un enfant.**

---

## 🛠️ Fonctionnalités du simulateur

* **Calcul personnalisé :** Saisie simplifiée de la configuration familiale (nombre d'enfants, statut marital) et des revenus nets imposables.
* **Modélisation dynamique :** Un curseur ajustable permet de faire varier le montant de l'allocation unique pour tester la viabilité et la neutralité budgétaire du modèle.
* **Transparence algorithmique :** Tous les calculs sont faits côté client. Pas de boîte noire.

---

## 🧮 Sources et Fondations Légales

La précision des calculs est essentielle pour la crédibilité du débat. Ce simulateur s'appuie rigoureusement sur la législation en vigueur :

* **Barème de l'impôt sur le revue 2026 :** Intégration des tranches d'imposition et calculs basés sur l'**Article 197 du Code Général des Impôts (CGI)**.
* **Prestations familiales :** Prise en compte des plafonds de ressources et des montants des allocations de la **CAF** actuellement applicables.
* **Calcul du quotient :** Gestion stricte des demi-parts, parts supplémentaires et plafonnements des effets du quotient familial.

---

## 🔒 Respect de la vie privée (Privacy by Design)

* **Aucune base de données :** Le site est une page statique hébergée de manière transparente.
* **Zéro tracking :** Vos données fiscales, vos revenus et votre situation familiale ne quittent jamais votre navigateur. Aucune donnée n'est collectée, enregistrée ou transmise à un tiers.

---

## 💻 Stack Technique

Le projet a été conçu pour être ultra-léger, rapide à charger et facilement hébergeable :

* **HTML5 / JavaScript (Vanilla ES6)** pour la logique de calcul fiscal.
* **Tailwind CSS** pour une interface utilisateur moderne, réactive et mobile-first.
* Déploiement automatisé via **GitHub Pages**.

---

## 🚀 Lancer le projet en local

Vous souhaitez auditer le code ou faire tourner le simulateur hors ligne ? C'est très simple :

1. Clonez le dépôt :
```bash
git clone [https://github.com/justice-enfants/un-enfant-vaut-un-enfant.git](https://github.com/justice-enfants/un-enfant-vaut-un-enfant.git)
```

2. Accédez au dossier :
```bash
cd un-enfant-vaut-un-enfant
```

3. Ouvrez simplement le fichier `index.html` dans votre navigateur web. Aucun serveur ni installation de dépendances (`npm`) n'est requis.

---

## 🤝 Contributions et Audit

La solidité mathématique de cet outil est sa meilleure arme. Si vous êtes fiscaliste, développeur, ou simplement citoyen et que vous constatez :
* Une divergence de calcul avec le site officiel des impôts sur une situation spécifique,
* Une coquille dans l'application des règles de l'Article 197 du CGI,
* Une idée d'amélioration de l'accessibilité ou du design UI,

N'hésitez pas à **ouvrir une Issue** ou à proposer une **Pull Request**. Les contributions constructives sont les bienvenues pour enrichir le débat public.

---

## 📄 Licence

Ce projet est placé sous licence **MIT**. Vous êtes libre de le copier, de le modifier et de le redistribuer.
