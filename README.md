# LeBonResto

Site (React/TypeScript/Tailwind) pour LeBonResto, une alternative locale à
Uber Eats / Deliveroo pour les restaurants lyonnais : page vitrine par
restaurant, commande en click & collect sans commission, et une formule
d'abonnement pour les restaurateurs.

Déployé sur GitHub Pages, servi sur [lebonresto.fr](https://lebonresto.fr).

## Pages

- **Accueil** — pitch, problème/solution, avantages
- **Restaurants** — liste filtrable par quartier et type de cuisine
- **Détail restaurant** — menu, panier, commande en click & collect (mock, aucun paiement réel)
- **Comment ça marche** — parcours client et parcours restaurateur
- **Rejoindre la plateforme** — formules tarifaires et formulaire de contact (mock)

Toutes les données (restaurants, menus) sont statiques et fictives, dans
`src/data/restaurants.ts`.

## Démarrer

```bash
npm install
npm run dev
```

## Build de production

```bash
npm run build
```
