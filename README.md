# 🌿 WorkEase - Portail RH & Management

Application web moderne et intuitive de gestion des congés, des absences et du planning d'équipe pour salariés et managers RH.

---

## 🧭 Structure des Pages (Format Desktop)

Le projet est désormais scindé en deux espaces dédiés avec une passerelle directe :

1. **[index.html](file:///d:/projects/WorkEase/index.html)** :
   - Portail d'accueil d'entreprise permettant de sélectionner l'espace de travail.

2. **[employe.html](file:///d:/projects/WorkEase/employe.html)** :
   - **Espace Salarié / Collaborateur (Thomas Leroy)** :
     - Synthèse des soldes disponibles en grille Bento (18.5 CP, 6 RTT, 2 Ancienneté).
     - Compte à rebours du prochain départ en vacances.
     - Calendrier mensuel interactif avec alertes d'absences de l'équipe.
     - Modal de dépôt de nouvelle demande de congé avec estimation de durée.
     - Suivi et annulation des demandes récentes (Pont de l'Ascension, congés d'été, etc.).
     - Bouton direct pour basculer vers l'espace RH.

3. **[rh.html](file:///d:/projects/WorkEase/rh.html)** :
   - **Espace Manager & RH (Sophie Laurent)** :
     - Tableau de bord des arbitrages prioritaires (Approbation / Refus instantané).
     - Matrice complète de présence hebdomadaire de l'équipe (Présentiel, TT, Congés).
     - Répartition graphique des types d'absences (CP, RTT, Maladie).
     - Suivi des quotas conventionnels Syntec et exports paie normalisés DSN.
     - Bouton direct pour basculer vers l'espace Salarié.

---

## 🚀 Lancement & Test Local

```bash
# Lancement du serveur local
npm start
# ou
npx serve .
```

Ouvrez ensuite l'un des liens dans votre navigateur :
- **Portail d'accueil** : `http://localhost:3000/index.html`
- **Espace Salarié** : `http://localhost:3000/employe.html`
- **Espace Manager RH** : `http://localhost:3000/rh.html`

---

## 👤 Auteur

- GitHub : [@ridaSoulaim](https://github.com/ridaSoulaim)
