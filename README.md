# Dev4Caustaza

Site vitrine de Dev4Caustaza (Tunisie) — Intelligence Artificielle, Cloud
Computing et Cybersécurité, créateurs de **SUBUL**, la plateforme SaaS
EdTech &amp; JobTech.

- `index.html` — page d'accueil : deux parcours (je recrute / je veux apprendre),
  à propos, équipe, technologie, SUBUL XP, formulaire entreprises
- `lab.html` — formulaire candidat·e de réservation d'un lab gratuit (SUBUL XP)
- `confidentialite.html`, `conditions.html` — politique de confidentialité
  (avec la section cookies) et mentions légales
- `en/` — versions anglaises (`index.html`, `lab.html`, `privacy.html`, `terms.html`)
- `fonts/` — polices Geist, Geist Mono et Instrument Serif hébergées sur le site
  (licence SIL OFL 1.1) : aucune page n'appelle de service tiers au chargement

Les pages légales sont des **projets** : elles portent la balise `noindex` et un
encadré « Projet en cours de relecture », et les mentions surlignées (`<mark>`)
restent à compléter. Après relecture par une personne au fait de la loi
organique n° 2004-63 : compléter les mentions, retirer l'encadré et la balise
`noindex`, puis ajouter les quatre pages à `sitemap.xml`.

Avant mise en ligne, personnaliser dans `index.html` et `en/index.html`
(bloc `CONFIGURATION` en bas de chaque fichier) :

- `WHATSAPP` et `EMAIL` — coordonnées de contact.
- `LEAD_ENDPOINT` — URL qui reçoit les demandes entreprises en JSON
  (Formspree, Make, webhook CRM…). Vide : la demande s'ouvre dans WhatsApp.
- `CALENDAR_URL` — lien de prise de rendez-vous (Cal.com, Calendly…).
  Vide : le lien est masqué.

Et dans `lab.html` et `en/lab.html` :

- `WHATSAPP` — numéro qui reçoit les demandes de lab.
- `EMAIL` — adresse proposée aux candidat·es sans WhatsApp.
- `ENDPOINT` — URL qui reçoit une copie JSON de chaque demande (facultatif).
