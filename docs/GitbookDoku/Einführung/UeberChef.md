# Ziel dieses Buches

Industrie 4.0, IoT, CI/CD, dockerized... Kein anderes Fachgebiet scheint über die Jahre hinweg so vielen Buzzwords ausgesetzt wie die Informatik. Allein in einem Teammeeting innerhalb des IT Bereichs kann ein normalsterblicher, so scheint es, schon keiner Konversation folgen, ohne einen Thesaurus bei der Hand zu haben, der ihm in die Magie der Thematik einzuführen vermag.

Ziel dieses Buches ist es anhand einer Studienarbeit einen möglichst großen Querschnitt über alle Themengebiete zu geben.

## Ausgangssituation

*"Fortbildungszentren besitzen Seminarräume, in denen sich viele Computer befinden, welche von
den Teilnehmern zur Bearbeitung ihrer Aufgaben verwendet werden. Je nachdem was in dem ak-
tuellen Seminar vermittelt wird, müssen die Computer mit der entsprechenden Software versehen
sowie vorkonfiguriert werden. In diesem Szenario geht es darum, einen Seminarraum bzgl. einer
Webentwicklungsfortbildung vorzubereiten."*

## Zielstellung
Das Resultat aus diesem Beleg, soll ein Chef-Cookbook sein, welches alle in der folgenden Sektion genannten Anforderungen abdeckt. Zudem soll das Cookbook exemplarisch auf einer Client-VM (PC eines Teilnehmers) ausgerollt werden.

Das Betriebssystem worauf das Cookbook ausgerichtet sein soll, ist eine Ubuntu Desktop Distribution. Die nachstehende Auflistung umfasst eine Beschreibung aller Aufgaben, die im Rahmen
dieses Belegs zu erledigen sind.
  
* Einrichten der Chef-Server-Umgebung
* Anlegen eines Nutzers für das Labor
  * Name: labornutzer“
  * Passwort: nutzer@labor123“
  * Gruppe: users“
  * Home directory: /home/labornutzer
* Konfigurieren des Proxy-Servers (http    proxy/https proxy/HTTP PROXY/HTTPS PROXY)
  * /etc/environment
  * in /home/labornutzer/.bashrc (Alternativ: /home/student/.bashrc)
* Installation der Konsolenanwendungen vim und htop
* Installation eines Apache Web-Servers
* Installation einer normalen Eclipse-Umgebung
* Installation einer MySQL Datenbank (Alternativ MariaDB)
* Installation Firefox sowie Google Chrome oder Chromium
* Entfernen von LibreOffice
* Installation einer Firewall
  * – Installation der Firewall
  * – Erlauben der Ports: 80, 443, 22
  * – Sperren der Ports: 3389




