[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/HlDpWB5G)
# zbx7-auto-reg

The independent work - Vagrant and Zabbix Agent2 7.0 LTS - Auto-registration to
[Zabbix pfSense](https://enceladus.pfsense.cz)

# Zabbix pfSense monitoring - Linux distribution by Agent2

Vytvořil jsem složku Zabbix, do které jsem umístil funkční Ubuntu 24.04 server nasazený pomocí Vagrantu.
Součástí projektu jsou dva skripty, které automaticky nainstalují a nakonfigurují Zabbix Agent 2.

## Popis složky

Vagrantfile – vytváří virtuální stroj s Ubuntu 24.04, nastaví síť, SSH klíč a spustí instalační skripty

installzabbix.sh – stáhne repozitář Zabbix, nainstaluje balíčky zabbix-agent2 a příslušné pluginy

confzabbix.sh – upraví konfiguraci Zabbix agenta (hostname, server, metadata, timeout) a restartuje službu

zbx_export_hosts.yaml - export meho hosta "kucheriavyi" from zabbix, ve formatu yaml

![Ubuntu Zabbix Agent2](./photo.jpg)
