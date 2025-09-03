# Lab 01 – Pierwsza sieć

To jest moja pierwsza sieć stworzona w Packet Tracerze.  
Zawiera:
- dwa komputery podłączone do switcha,  
- podstawową konfigurację adresów IP,  
- udane testy ping pomiędzy urządzeniami.  

## Plik
- [01_first_network](01_first_network)

---


# Lab 02 – VLAN 4PC i 2 Switchy

**Opis projektu:**  
- Topologia: 4 PC (PC1–PC4), 2 Switch (Switch0, Switch1), 1 Router (Router0), 1 Server (Server0)  
- VLAN10 → PC1, PC2 + Server0  
- VLAN20 → PC3, PC4  
- Router obsługuje routing między VLANami  
- Kabel: Copper Straight-Through  

**Problemy w projekcie:**  
- DHCP w Packet Tracer nie działa (PC używają APIPA 169.254.x.x)  
- Wszystkie VLANy i porty fizycznie podłączone i ustawione poprawnie  

**Cel projektu:**  
- Pokazanie konfiguracji VLANów, portów switcha i routing między VLANami  
- Gotowa topologia do nauki DHCP i sieci wielopodsieciowych  

## Plik
- [02_vlan_network](02_vlan_network)
