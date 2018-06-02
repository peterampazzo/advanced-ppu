# advanced-ppu

Advanced PPU è un software distribuito con licenza GPLv3 per la gestione informatizzata della progressione personale unitaria dei ragazzi di un reparto in un gruppo Agesci.

> È un programma pensato da scout progettato per scout!

Nasce da una brillante idea di Nicola Corti successivamente ampliata e rivista da Daniele Baschieri, il progetto iniziale è poi stato fortemente modificato diventando questo nuovo progetto A-ppu.

---
## Getting Started

È necessario un ambiente che supporta PHP + MySQL.

Scaricare una copia dell'archivio con il comando:

```git clone https://github.com/peterampazzo/advanced-ppu.git```

A questo punto bisogna importare tutte le tabelle sql su un nuovo database.
Le query si possono trovare dentro la cartella ```database_sql_raw```.

Per impostare i parametri per stabilire una connessione con il DB modificare il file ```query.php``` che si trova dentro la cartella ```php```.

## Generare il primo utente
Aggiungere un nuovo record sulla tabella ```utenti```: inserire utente ed email.

Per la pswd è necessario generarla con HASH1: http://www.sha1-online.com/.

---
## Todo
- [ ] Resettare gli autoincremental (vedi: https://stackoverflow.com/questions/8923114/how-to-reset-auto-increment-in-mysql)
- [ ] Come implementare funzionalità per branco?


