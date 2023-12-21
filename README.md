verranno utilizzati java e Spring per questo progetto seguendo il modello MVC (model-view-controller) :

Entity: Classi o oggetti.

Service: contiene la logica.

Controller : gestisce interazioni tra utente e sistema, prende i metodi del service e testa le api tramite un uri.

Repository: contenitore di dati e collegamento al DB.

avrò un user, un calendar e un id.

User avrà :  id,name, una lista di eventi e una lista degli eventi a cui si ha aderito.

Calendar avrà : id, nome, un user e una lista di eventi.

Event avrà : un id, data di inizio ,una data di fine, un titolo e una lista di partecipanti 

Inizialmente creando le varie entità, poi le repository ed service e controller implementando inizialmente le CRUD operations



