# glpi

Docker-Compose File mit folgenden Services:
- fametec/glpi:mariadb
- fametec/glpi:latest
- fametec/glpi:crond

Erreichbar über
- http://[IP-Adresse]:30080
- user: glpi
- password: glpi

In laufende Docker-Umgebung integrieren mit:
- download yaml-file
- erstellen eines Ordners und verschieben des yaml-files
- wechseln in den Ordner
- docker compose run

   resp. um ihn als Service zu starten:
- docker compose run -d
