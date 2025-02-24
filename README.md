# Observateur-d-v-nements-windows
Ce fichier XML est une configuration pour l'Event Viewer de Windows, spécifiquement pour surveiller les événements liés aux services DNS. Voici ce qu'il fait :

📌 Explication du fichier
Il définit une requête pour capturer des événements de journaux Windows liés au DNS.

Il cible plusieurs journaux d'événements, notamment :

DNS Server
Microsoft-Windows-DNS-Client/Operational
Microsoft-Windows-DNSServer/Analytical
Microsoft-Windows-DNSServer/Audit
System
Il surveille les événements générés par plusieurs sources, dont :

Microsoft-Windows-DNS-Client
Microsoft-Windows-DNS-Client-DiagTrack
Microsoft-Windows-DNSServer
Microsoft-Windows-DNS-Server-Service
Il filtre les événements ayant certains ID spécifiques :

2, 4, 409
Une plage d'IDs : 501-502 et 6001-6002
Il capture aussi les événements de différents niveaux de gravité (Level) :

1 (Critique), 2 (Erreur), 3 (Avertissement), 4 (Information) et 0 (non défini).
🛠 Utilité de cette configuration
Ce type de fichier est utile pour :
✅ Détecter les erreurs DNS sur un serveur Windows.
✅ Suivre l'activité du client et du serveur DNS.
✅ Avoir une vue centralisée sur les logs DNS critiques.
