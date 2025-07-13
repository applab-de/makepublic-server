# MakePublic Server
Self-hosted Reverse Proxy Gateway

Dieses Repository enthält die zentrale Server-Komponente für sichere, dynamische Reverse-Proxies auf Basis von FRP.  
Der Server ermöglicht es, beliebige lokale Dienste von internen Rechnern aus über öffentliche Subdomains oder Ports im Internet bereitzustellen – ohne Firewall-Änderungen oder komplexe Netzwerkkonfiguration.

---

## Features

- **Ein zentraler Endpoint für alle Clients**  
  – Empfängt Verbindungen von beliebig vielen Clients (frpc)  
  – Ermöglicht dynamische Vergabe von Subdomains oder Ports  
  – Ideal für temporäre oder dauerhafte Tunnels
- **Unterstützt zahlreiche Protokolle:**  
  – HTTP, HTTPS  
  – TCP & UDP  
  – SNI-basiertes Routing, Subdomain-Support 
- **Skalierbar und performant**  
  – Geringer Ressourcenverbrauch  
  – Stabil auch bei vielen gleichzeitigen Tunnels

---

## Installation

...
