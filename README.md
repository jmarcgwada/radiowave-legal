# RadioWave — Politique de confidentialite

Page unique hebergee par GitHub Pages, qui publie la politique de
confidentialite de l'application mobile **RadioWave**.

- En ligne : <https://jmarcgwada.github.io/radiowave-legal/>
- Contenu : un seul fichier, [index.html](index.html) — texte et styles compris.

## A quoi elle sert

Google Play et l'App Store exigent une politique de confidentialite **accessible
par une adresse publique** avant toute publication. C'est cette adresse qu'on
renseigne dans la fiche du magasin. Elle n'a donc pas vocation a etre jolie : il
faut qu'elle existe, qu'elle soit exacte et qu'elle reste joignable.

## Ce qu'elle affirme

Le fond tient en une phrase : **RadioWave ne collecte, ne stocke ni ne transmet
aucune donnee personnelle.** Le detail couvre :

1. Ce qui n'est pas collecte — aucun compte, aucun outil de suivi, aucune publicite.
2. Ce qui reste **sur l'appareil** — favoris, historique, reveils, enregistrements, preferences.
3. Les **services tiers** reellement appeles : [Radio Browser](https://radio-browser.info)
   pour l'annuaire des stations, [wsrv.nl](https://wsrv.nl) pour redimensionner
   les logos, et les diffuseurs pour les flux audio.
4. Chaque **permission Android** demandee, avec la raison precise de sa presence.
5. Le cas des mineurs, les changements de politique, le contact.

L'application **n'utilise pas le microphone** : les enregistrements proviennent
du flux de la radio, pas du micro. La page le dit explicitement, parce que la
permission d'ecriture audio peut le laisser croire.

## Mettre a jour

Toute modification doit rester **vraie pour la version publiee** de
l'application : si RadioWave se met un jour a collecter quelque chose, c'est
ici que cela doit apparaitre, avant la mise en ligne.

1. Modifier `index.html`.
2. Mettre a jour la ligne « Derniere mise a jour ».
3. Envoyer sur `master` — GitHub Pages republie tout seul.

## Projets lies

- **RadioWave** — l'application mobile elle-meme.
- **radiowave-promo** — la page de presentation.
- **radiowave-listen** — le mini-lecteur web.
