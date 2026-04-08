# Patient Journey Portal - Sistema Integrato Sanitario

Il progetto **Patient Journey Portal** è una soluzione Full-Stack progettata per aggregare e visualizzare il percorso diagnostico-terapeutico di un paziente in tempo reale. 

## 🏥 Visione del Progetto
L'obiettivo è superare la frammentazione dei dati sanitari (LIS, RIS, PACS) fornendo al paziente un'interfaccia unica, chiara e interattiva.

## 🛠️ Architettura Tecnica
Il sistema è costruito seguendo i moderni standard di sviluppo software:

* **Backend:** Sviluppato in **Java (Spring Boot)**. Gestisce l'orchestrazione dei microservizi, la sicurezza del dato e la logica di business.
* **Frontend:** Sviluppato in **React**. Offre una timeline interattiva per la visualizzazione degli appuntamenti e la gestione dei referti.
* **Infrastruttura:** Completamente containerizzata con **Docker**, garantendo portabilità e scalabilità tra ambienti di sviluppo e produzione (Render/Vercel).
* **Database:** PostgreSQL per la persistenza sicura dei dati clinici.

## 🚀 Guida Rapida
Il progetto è configurato per essere avviato interamente tramite Docker Compose:

```bash
docker-compose up --build