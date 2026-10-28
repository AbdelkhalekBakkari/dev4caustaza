# Dev4Caustaza

Site vitrine de Dev4Caustaza (Tunisie) — Intelligence Artificielle, Cloud
Computing et Cybersécurité, créateurs de **SUBUL**, la plateforme SaaS
EdTech &amp; JobTech.

- `index.html` — page d'accueil (présentation, expertises, SUBUL, SUBUL XP, contact)
- `lab.html` — formulaire de réservation d'un lab gratuit (résidence tech SUBUL XP)

Avant mise en ligne, personnaliser dans `index.html` et `en/index.html`
(bloc `CONFIGURATION` en bas de chaque fichier) :

- `WHATSAPP` et `EMAIL` — coordonnées de contact.
- `LEAD_ENDPOINT` — URL qui reçoit les demandes entreprises en JSON
  (Formspree, Make, webhook CRM…). Vide : la demande s'ouvre dans WhatsApp.
- `CALENDAR_URL` — lien de prise de rendez-vous (Cal.com, Calendly…).
  Vide : le lien est masqué.
