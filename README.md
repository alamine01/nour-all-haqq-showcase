# Nour All-Haqq — Le Secret du Tahajjud

**Site de vente du livre d'un créateur de contenu**, avec une expérience immersive pilotée par le scroll, un paiement mobile ou par carte, et un back-office de commandes.

[🌐 nourall-haqq.com](https://nourall-haqq.com)

<!-- CAPTURES D'ÉCRAN : crée un dossier "screenshots", ajoute tes images, puis remplace ce commentaire par :
<p align="center">
  <img src="screenshots/accueil.png" width="45%" />
  <img src="screenshots/carnet.png" width="45%" />
</p>
-->

## Aperçu

Site de présentation et de vente du livre *Le Secret du Tahajjud*, destiné à un public francophone au Sénégal et en France. L'accueil propose une visite cinématique : une séquence vidéo qui avance au rythme du scroll.

## Fonctionnalités clés

- **Visite immersive pilotée par le scroll** (séquence de près de 500 images optimisées en WebP)
- Présentation du livre, de son sommaire et de l'auteur
- **Carnet interactif de 60 nuits**, avec une fiche d'accompagnement par nuit
- Commande avec paiement **Mobile Money (PayTech)** ou **carte (Stripe)**
- **E-mails de confirmation** automatiques (Brevo)
- **Back-office** sécurisé : suivi des commandes, renvoi des e-mails
- Pages légales et balises de partage (Open Graph)

## Architecture technique

| Couche | Technologies |
|---|---|
| Front-end | Next.js (App Router), TypeScript |
| Back-end | Routes API Next.js, Firebase (Firestore), Firebase Admin |
| Paiements | Stripe et PayTech, avec webhooks |
| E-mails | Brevo |
| Déploiement | Vercel |

**Point notable** : le prix est toujours recalculé côté serveur, pour qu'il ne puisse pas être modifié depuis le navigateur.

## Mon rôle

Conception et développement full stack du site, de la maquette à la mise en ligne, en freelance.

---

> 🔒 **Projet client : le code source est privé.** Ce dépôt présente le projet. Démonstration du code possible en entretien.
>
> Réalisé par **Al Amine Bah** · [github.com/alamine01](https://github.com/alamine01) · bahmouhamedalamine@gmail.com
