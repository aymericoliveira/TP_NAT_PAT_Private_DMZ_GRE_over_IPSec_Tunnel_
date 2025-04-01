# Commandes show les plus utilisées sur un routeur et un switch Cisco.

### 📌 **Commandes `show` pour un routeur Cisco**

| **Commande** | **Description** |
| --- | --- |
| `show version` | Affiche les informations du routeur (modèle, version IOS, uptime, mémoire, etc.). |
| `show running-config` | Affiche la configuration active du routeur. |
| `show startup-config` | Affiche la configuration sauvegardée en NVRAM. |
| `show ip interface brief` | Affiche un résumé des interfaces et leur statut (UP/DOWN, IP assignée). |
| `show interfaces` | Détails complets des interfaces (trafic, erreurs, état, etc.). |
| `show ip route` | Affiche la table de routage. |
| `show arp` | Affiche la table ARP (résolution des adresses MAC <-> IP). |
| `show protocols` | Vérifie l’état des protocoles sur le routeur. |
| `show cdp neighbors` | Affiche les périphériques Cisco voisins via CDP. |
| `show ip nat translations` | Vérifie les translations NAT en cours. |
| `show ip dhcp binding` | Affiche les baux DHCP attribués. |
| `show ip ospf neighbor` | Vérifie l’état des voisins OSPF (si OSPF est activé). |
| `show ip bgp summary` | Vérifie l’état des sessions BGP (si BGP est activé). |

---

### 📌 **Commandes `show` pour un switch Cisco**

| **Commande** | **Description** |
| --- | --- |
| `show version` | Informations sur le switch (modèle, IOS, uptime, mémoire). |
| `show running-config` | Affiche la configuration en cours. |
| `show startup-config` | Affiche la configuration sauvegardée. |
| `show vlan brief` | Liste des VLANs configurés sur le switch. |
| `show interfaces status` | Affiche l’état des interfaces (Up/Down, VLAN, duplex, vitesse). |
| `show interfaces` | Détails sur les interfaces (trafic, erreurs, débit). |
| `show mac address-table` | Affiche la table d’adresses MAC. |
| `show spanning-tree` | Vérifie l’état du protocole STP (Spanning Tree Protocol). |
| `show cdp neighbors` | Liste les appareils Cisco connectés via CDP. |
| `show lldp neighbors` | Liste les appareils connectés via LLDP (équivalent CDP pour non-Cisco). |
| `show etherchannel summary` | Vérifie l’état des ports agrégés (LACP/PAGP). |
| `show power inline` | Affiche la consommation PoE des ports (si switch PoE). |
| `show port-security` | Vérifie l’état de la sécurité des ports. |
| `show ip dhcp snooping binding` | Liste les adresses IP attribuées via DHCP snooping. |