# Dev4Caustaza

Site vitrine de Dev4Caustaza (Tunisie) — Intelligence Artificielle, Cloud
Computing et Cybersécurité, créateurs de **SUBUL**, la plateforme SaaS
EdTech &amp; JobTech.

- `index.html` — page d'accueil : deux parcours (je recrute / je veux apprendre),
  à propos, équipe, technologie, SUBUL XP, formulaire entreprises
- `lab.html` — formulaire candidat·e de réservation d'un lab gratuit (SUBUL XP)
- `en/` — versions anglaises des deux pages

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
