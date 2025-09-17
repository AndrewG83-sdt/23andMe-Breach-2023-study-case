# # Credential Stuffing Breach su 23andMe (2023)

## Descrizione
Questo repository contiene la mia analisi tecnica del data breach che ha colpito 23andMe nell’ottobre 2023.  
L’attacco, basato su **credential stuffing**, ha compromesso milioni di account, sfruttando la funzione “DNA Relatives” e il riuso di credenziali già esposte in altri leak.

## Contenuto
- `REPORT.md` → Report tecnico completo con sezioni: introduzione, timeline, tecniche (TTP), dati compromessi, impatto, lezioni apprese, azioni correttive e preventive, conclusione, fonti.  
- `fonti.txt` → Elenco dei link diretti alle fonti ufficiali e articoli usati per la ricerca.

## Punti chiave del report
- Attacco basato su **riuso password** e assenza di MFA obbligatoria.  
- ~14.000 account compromessi direttamente.  
- Esposizione di dati di **~6,9 milioni di utenti** tramite funzioni social.  
- Impatti legali: **class action** e multa da **£2,3 milioni** dal UK ICO.  
- **Azioni preventive proposte**: MFA obbligatoria, rate limiting, monitoraggio dark web, revisione funzioni social, bug bounty.

##  Fonti principali
- [Arxiv.org – Anatomy of the 23andMe Credential Stuffing Attack](https://arxiv.org/pdf/2502.04303)  
- [California Attorney General – Data Breach Notification](https://oag.ca.gov/system/files/CA%20AG%20-%20CA%20Notification%20Letters.pdf)  
- [Wired – 23andMe Hack Exposed Genetic Data](https://www.wired.com/story/23andme-hack-genetic-data/)  
- [TechCrunch – Hackers Access Millions of 23andMe Accounts](https://techcrunch.com/2023/10/09/23andme-hackers-breach-data/)  
- [HIPAA Journal – 23andMe User Data Stolen](https://www.hipaajournal.com/23andme-user-data-stolen-credential-stuffing-campaign/)  
- [UK ICO – Enforcement Action on 23andMe](https://ico.org.uk/action-weve-taken/enforcement/23andme-enforcement-notice/)  

---

✍Autore: **Andrea Giovannoni**  
 [LinkedIn](https://www.linkedin.com/in/andrea-giovannoni-253b1b54/) | [GitHub](https://github.com/AndrewG83-sdt)  
