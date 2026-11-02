## Progetto Pratico SOC Analyst: Monitoraggio e Analisi di Sicurezza con Splunk
## Descrizione Generale: Simuliamo un scenario reale dove investighiamo, monitoriamo e analisiamo la gestione degli incidenti di sicurezza.

# Step 1: Configurazione dell'Ambiente e Dati
In questa prima parte, ho configurato Splunk e poi nella query della ricerca con index="soc_project" source="accesslog.json" abbiamo analizzato e visualizzato i log di accesso web.
<img width="1502" height="726" alt="1parteWEB" src="https://github.com/user-attachments/assets/75b4cd44-3923-45a8-a531-cf9fb373610f" />

## Step 2: Rilevamento e analisi delle attività sospette
# Analisi degli accessi VPN falliti
Ho filtrato i log VPN utilizzando action=failed e identificato:
274 eventi di accesso fallito
Utente: Simon
Indirizzo IP di origine: 172.201.60.191
Intervallo: 11 gennaio 2022, dalle ore 07:28:47 alle ore 07:35🈹
<img width="1506" height="709" alt="raporto" src="https://github.com/user-attachments/assets/3ce37c3e-13cb-4180-932c-2f9933352d8a" />
