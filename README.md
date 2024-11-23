# chess-events-app
Frontend:
Pagine:
Home (lista eventi).
Dettaglio evento.
Profilo utente.
Creazione evento (per organizzatori).
Backend:
API RESTful:
/events (GET: lista eventi, POST: crea evento).
/users (GET: profilo, POST: registrazione).
/subscriptions (POST: iscrizione a un evento).
Autenticazione: OAuth2 o JWT.
Database:
Tabelle principali:
users: per memorizzare gli utenti.
events: per gli eventi di scacchi.
subscriptions: per tracciare chi si iscrive agli eventi.
