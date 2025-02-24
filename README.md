# Observateur-d-v-nements-windows
# 📌 Explication du fichier  

Ce fichier XML est une configuration pour l'Event Viewer de Windows, spécifiquement pour surveiller les événements liés aux services DNS.  

## 🎯 Objectif  
Il définit une requête pour capturer des événements de journaux Windows liés au DNS.  

## 📂 Journaux ciblés  
Il surveille plusieurs journaux d'événements :  
- **DNS Server**  
- **Microsoft-Windows-DNS-Client/Operational**  
- **Microsoft-Windows-DNSServer/Analytical**  
- **Microsoft-Windows-DNSServer/Audit**  
- **System**  

## 🔍 Sources surveillées  
Les événements sont générés par plusieurs sources :  
- `Microsoft-Windows-DNS-Client`  
- `Microsoft-Windows-DNS-Client-DiagTrack`  
- `Microsoft-Windows-DNSServer`  
- `Microsoft-Windows-DNS-Server-Service`  

## 🎯 Filtres appliqués  
### **🆔 ID des événements surveillés**  
- `2`, `4`, `409`  
- Plages d'IDs : `501-502` et `6001-6002`  

### **⚠️ Niveaux de gravité (Level)**  
- `1` (Critique)  
- `2` (Erreur)  
- `3` (Avertissement)  
- `4` (Information)  
- `0` (Non défini)  

---

## 🛠 Utilité de cette configuration  
✅ **Détecter les erreurs DNS** sur un serveur Windows.  
✅ **Suivre l'activité** du client et du serveur DNS.  
✅ **Avoir une vue centralisée** sur les logs DNS critiques.  
