# Aufgabe 1: Theorie

1. Was ist Ansible und welche Rolle spielt es in der IT-Infrastrukturverwaltung?
* Ansible ist ein Open-Source-Tool für die Automatisierung von IT-Umgebungen und wird häufig für das Configuration Management verwendet. Es ermöglicht die effiziente Verwaltung der IT-Infrastruktur.

2. Was versteht man unter Configuration Management und warum ist es wichtig?
* Configuration Management bezieht sich auf die Verwaltung und Kontrolle von Systemkonfigurationen in einer IT-Umgebung. Es ist wichtig, da es die Konsistenz und Wiederherstellbarkeit von Systemkonfigurationen gewährleistet und hilft, Fehler und Ineffizienzen durch menschliche Fehler zu vermeiden.

3. Welche Herausforderungen können bei der manuellen Einrichtung von Systemen auftreten?
* Manuelle Systemeinrichtungen können zeitaufwändig sein und zu Inkonsistenzen und Fehlern führen.

4. Wie unterscheidet sich Configuration Management von Bash-Skripten?
* Im Gegensatz zu Bash-Skripten, die sequenzielle Befehle ausführen, ermöglicht das Configuration Management eine deklarative Definition des gewünschten Systemzustands und nimmt automatisch die notwendigen Änderungen vor, um diesen Zustand zu erreichen.

5. Warum ist Configuration Management eine effiziente Möglichkeit, Systeme einzurichten?
* Configuration Management ist effizient, da es die Automatisierung von Routineaufgaben ermöglicht, wodurch Zeit und Ressourcen gespart und Fehler minimiert werden.

6. Was ist der Unterschied zwischen einem Agent und einer agentenlosen Architektur im Kontext von Configuration Management?
* Im Kontext des Configuration Managements bezeichnet ein Agent eine Software, die auf dem Zielsystem installiert ist und Aufgaben ausführt. Eine agentenlose Architektur hingegen führt Aufgaben remote aus, ohne dass eine Software auf dem Zielsystem installiert werden muss.

7. Welche Aufgaben erfüllt ein Agent auf einem Zielsystem?
* Software, die Aufgaben im Zielsystem ausführt und auf diesem installiert ist.

8. Warum ist Ansible ein agentenloses Configuration-Management-Tool?
* Ansible ist ein agentenloses Configuration-Management-Tool, was bedeutet, dass es keine Agenten auf den Zielsystemen installiert.

9. Welches Protokoll verwendet Ansible, um Befehle und Konfigurationen auf Zielsystemen auszuführen?
* Ansible verwendet das SSH-Protokoll, um Befehle und Konfigurationen auf Zielsystemen auszuführen.

10. Was ist das Inventory in Ansible und wie wird es definiert?
* Das Inventory in Ansible ist eine Liste von Zielsystemen, auf denen Aufgaben ausgeführt werden sollen. Es wird in einer Textdatei definiert.

11. Was sind Tasks in Ansible und wie werden sie in Playbooks strukturiert?
* Tasks in Ansible sind Einzelaufgaben, die in Playbooks strukturiert sind. Ein Playbook ist eine Sammlung von Tasks.

12. Was ist ein Recipe in Ansible und wie ist es in Playbooks organisiert?
* Ein Recipe in Ansible ist ein veralteter Begriff und wird üblicherweise als Playbook bezeichnet. 

13. Was sind Ansible-Rollen und wie können sie zur Strukturierung von Playbooks verwendet werden?
* Ansible-Rollen sind wiederverwendbare und universelle Komponenten, die zur Strukturierung von Playbooks verwendet werden können.

14. Was sind Ansible-Module und welche Funktion erfüllen sie bei der Ausführung von Aufgaben?
* Ansible-Module sind die Bausteine für Playbooks. Sie führen bestimmte Aufgaben aus und können in Tasks verwendet werden.