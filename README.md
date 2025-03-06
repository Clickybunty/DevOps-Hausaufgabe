# DevOps Beispiel!

# Inhaltsverzeichnis

## DevOps-Erfolgsgeschichte von GitHub
1. [1. IT-Organisation vor der DevOps-Transformation](#it-organisation-vor-der-devops-transformation)
2. [Transformationsschritte](#transformationsschritte)
3. [Messbare Erfolge](#messbare-erfolge)
4. [Herausforderungen und Bewältigungsstrategien](#herausforderungen-und-bewältigungsstrategien)
5. [Erkenntnisse für die Praxis](#erkenntnisse-für-die-praxis)

## Historische Wurzeln von DevOps
1. [Vorläufer und Einflüsse](#vorläufer-und-einflüsse)
2. [Wichtige Vordenker und Pioniere](#wichtige-vordenker-und-pioniere)
3. [Schlüsselereignisse zur Verbreitung von DevOps](#schlüsselereignisse-zur-verbreitung-von-devops)

## Visuelle Zeitleiste der DevOps-Meilensteine
1. [2001 – Agile Manifesto veröffentlicht](#2001--agile-manifesto-veröffentlicht)
2. [2009 – Patrick Debois organisiert erste DevOpsDays](#2009--patrick-debois-organisiert-erste-devopsdays)
3. [2010–2015 – Netflix, Amazon & Google treiben DevOps voran](#2010–2015--netflix-amazon--google-treiben-devops-voran)
4. [2016 – DevOps als Standard in vielen Unternehmen](#2016--devops-als-standard-in-vielen-unternehmen)
5. [2020+ – DevSecOps & Platform Engineering als neue Entwicklungen](#2020--devsecops--platform-engineering-als-neue-entwicklungen)

## DevOps Lifecycle
1. [PLAN (Planung)](#plan-planung)
2. [CODE (Entwicklung)](#code-entwicklung)
3. [BUILD (Build-Prozess)](#build-build-prozess)
4. [TEST (Tests)](#test-tests)
5. [RELEASE (Veröffentlichung)](#release-veröffentlichung)
6. [DEPLOY (Bereitstellung)](#deploy-bereitstellung)
7. [OPERATE (Betrieb)](#operate-betrieb)
8. [MONITOR (Überwachung)](#monitor-überwachung)


**DevOps-Erfolgsgeschichte von GitHub**

### 1. IT-Organisation vor der DevOps-Transformation
GitHub war bereits als Plattform für Softwareentwicklung etabliert, aber vor der vollständigen DevOps-Integration gab es einige Herausforderungen:
- **Langsame Bereitstellungen durch manuelle Prozesse**  
  *Neue Features wurden erst nach wochenlangen Tests ausgerollt, was Innovationen verzögerte.*
- **Hohe Abhängigkeit von zentralisierten Teams**  
  *Entwickler mussten auf Freigaben von separaten Betriebsteams warten, bevor sie Änderungen bereitstellen konnten.*
- **Eingeschränkte Skalierbarkeit und Effizienzprobleme**  
  *Eine steigende Anzahl von Nutzern führte zu langen Ladezeiten, weil die Infrastruktur nicht dynamisch skaliert wurde.*
- **Fehlende Standardisierung bei Deployments und Infrastrukturmanagement**  
  *Unterschiedliche Teams nutzten verschiedene Deployment-Methoden, was zu Fehlern in der Produktionsumgebung führte.*
- **Schwierigkeiten bei der schnellen Bereitstellung neuer Funktionen**  
  *Ein Feature-Update für Issues verzögerte sich um Monate, da die Freigabeprozesse umständlich waren.*

### 2. Transformationsschritte
GitHub hat eine Reihe von Maßnahmen ergriffen, um DevOps vollständig zu integrieren:
- **Einführung von ChatOps**  
  *Entwickler konnten mit einem einfachen Chat-Befehl (`/deploy featureX`) einen neuen Code in die Produktion bringen.*
- **Nutzung von Kubernetes zur Container-Orchestrierung**  
  *Wenn viele Nutzer gleichzeitig auf GitHub zugriffen, wurden automatisch neue Serverinstanzen bereitgestellt.*
- **Implementierung von GitHub Actions für CI/CD**  
  *Jeder neue Code-Commit löste automatisch eine Testpipeline aus, die fehlerhaften Code verhinderte.*
- **Förderung einer DevOps-Kultur mit mehr Verantwortung für Entwickler**  
  *Entwickler übernahmen selbst die Verantwortung für den Betrieb ihrer Anwendungen.*
- **Verstärkter Einsatz von Infrastructure as Code (IaC)**  
  *Anstatt manuell Server einzurichten, wurden Konfigurationsdateien wie Terraform genutzt.*
- **Einführung eines Observability-Stacks**  
  *GitHub setzte Prometheus und Grafana ein, um Echtzeit-Metriken über die Systemleistung zu überwachen.*

### 3. Messbare Erfolge
Durch diese Maßnahmen erzielte GitHub signifikante Verbesserungen:
- **Schnellere Deployments**  
  *Features konnten nun täglich oder sogar stündlich bereitgestellt werden.*
- **Geringere Ausfallzeiten**  
  *Dank automatischer Fehlererkennung wurde ein Serverausfall in Minuten statt Stunden behoben.*
- **Höhere Entwicklerproduktivität**  
  *Entwickler verbrachten weniger Zeit mit Deployment-Prozessen und mehr mit Code-Entwicklung.*
- **Reduzierte technische Schulden**  
  *Durch kontinuierliche Integration wurde veralteter Code schneller erkannt und ersetzt.*
- **Verbesserte Sicherheit durch DevSecOps-Ansätze**  
  *Automatisierte Sicherheits-Scans verhinderten, dass Schwachstellen in den Code gelangten.*

### 4. Herausforderungen und Bewältigungsstrategien
Während der Umstellung gab es einige Hürden:
- **Widerstand gegen Veränderung**  
  *Einige Teams befürchteten, dass Automatisierung ihre Jobs ersetzen würde.*
- **Komplexität der Migration**  
  *Die Umstellung von monolithischen Anwendungen auf Microservices dauerte Monate.*
- **Sicherheitsbedenken**  
  *Ein automatisches Deployment könnte versehentlich unsicheren Code freigeben.*

### 5. Erkenntnisse für die Praxis
- **Automatisierung ist essenziell für eine erfolgreiche DevOps-Transformation**  
  *Ohne CI/CD wären die schnellen Deployment-Zyklen nicht möglich gewesen.*
- **Eine DevOps-Kultur erfordert eine enge Zusammenarbeit zwischen Entwicklern und Betrieb**  
  *Wöchentliche Meetings zwischen Entwicklung und Ops verbesserten den Austausch.*
- **Iterative Verbesserungen sind effektiver als große Umstellungen**  
  *GitHub führte DevOps schrittweise ein, statt das gesamte System auf einmal umzustellen.*
- **Monitoring und Observability helfen, Probleme frühzeitig zu erkennen**  
  *Echtzeit-Dashboards zeigten Engpässe, bevor sie kritisch wurden.*
- **Sicherheit muss von Anfang an integriert werden**  
  *GitHub führte automatisierte Sicherheitsprüfungen in jeder Pipeline ein.*

---

**Historische Wurzeln von DevOps**

### 1. Vorläufer und Einflüsse
- **Agile Softwareentwicklung (2001)**  
  *Scrum ermöglichte schnellere Software-Releases mit enger Kundeninteraktion.*
- **Lean Manufacturing**  
  *Toyota’s Just-in-Time-Produktion inspirierte DevOps-Prozesse zur Effizienzsteigerung.*
- **Kontinuierliche Integration (CI, seit 1990er Jahren)**  
  *Entwickler konnten ihre Codeänderungen mehrmals täglich einspielen und testen.*

### 2. Wichtige Vordenker und Pioniere
- **Patrick Debois (2009)**  
  *Organisierte die erste DevOpsDays-Konferenz.*
- **Gene Kim**  
  *Schrieb das Buch "The Phoenix Project", das DevOps-Prinzipien anschaulich erklärt.*
- **Jez Humble & David Farley**  
  *Entwickelten Continuous Delivery als Standardpraktik für DevOps.*

### 3. Schlüsselereignisse zur Verbreitung von DevOps
- **2009: Erste DevOpsDays-Konferenz in Belgien**  
  *Entwickler und Ops tauschten sich erstmals über Automatisierung und Zusammenarbeit aus.*
- **2010–2015: Verbreitung durch Unternehmen wie Netflix, Amazon und Google**  
  *Netflix entwickelte Chaos Monkey, um Resilienz zu testen.*
- **2016: DevOps als Mainstream-Ansatz in Unternehmen weltweit**  
  *Große Banken wie ING setzten DevOps für schnellere Releases ein.*
- **2020+: DevSecOps und Platform Engineering als neue Strömungen**  
  *DevSecOps integriert Sicherheitsprüfungen direkt in die CI/CD-Pipeline.*

---

**Visuelle Zeitleiste der DevOps-Meilensteine**
1. **2001** – Agile Manifesto veröffentlicht  
   *Teams arbeiteten iterativ an Features statt in monolithischen Projekten.*
2. **2009** – Patrick Debois organisiert erste DevOpsDays  
   *Entwickler und IT-Betriebsteams arbeiteten enger zusammen.*
3. **2010–2015** – Netflix, Amazon & Google treiben DevOps voran  
   *Netflix setzte Microservices für resiliente Architekturen ein.*
4. **2016** – DevOps als Standard in vielen Unternehmen  
   *Firmen wie Adidas optimierten ihre Softwarebereitstellung.*
5. **2020+** – DevSecOps & Platform Engineering als neue Entwicklungen  
   *Sicherheitsprüfungen wurden automatisch in den Entwicklungsprozess integriert.*

---

# DevOps Lifecycle

![image](https://github.com/user-attachments/assets/29d2bb2e-609c-4f4d-8475-d33aefd80e72)


## 1️⃣ PLAN (Planung) 📝
### Erklärung:
In der Planungsphase wird der gesamte Entwicklungsprozess vorbereitet. Es werden Anforderungen erfasst, Ziele definiert und eine Strategie für die Umsetzung erarbeitet. Dabei kommen agile Methoden wie Scrum oder Kanban zum Einsatz.

### Beschreibung: Definieren der Anforderungen, Ziele und Roadmap für die Softwareentwicklung.
### Beispiel: Ein Scrum-Team erstellt ein Product Backlog mit User Stories in Jira.
### Verbindung: Liefert die Grundlage für das Coding.

### Planungsphase

**Methoden**:
**Agile Entwicklung (Scrum, Kanban)**:
- Iterative und flexible Entwicklungsansätze, die eine schnelle Anpassung an Änderungen ermöglichen.
  
**User Story Mapping**:
- Eine Technik zur Visualisierung von Nutzeranforderungen in Form von Geschichten, um den Entwicklungsprozess besser zu strukturieren.

**Impact Mapping**:
- Eine strategische Planungstechnik, die hilft, Geschäftsziele mit den richtigen Entwicklungsmaßnahmen zu verknüpfen.

**Verhaltensgetriebene Entwicklung (BDD)**:
- Ein Testansatz, der sich auf die Beschreibung des gewünschten Verhaltens der Software in natürlicher Sprache konzentriert.

**Werkzeuge**:
**Jira, Asana, Trello (Projektmanagement)**:
- Tools zur Planung, Verwaltung und Organisation von Aufgaben innerhalb von Entwicklerteams.

**Confluence, Notion (Dokumentation)**:
- Plattformen zur zentralen Speicherung und Bearbeitung von Dokumentationen und Wissen innerhalb eines Unternehmens.

**Miro, Lucidchart (Visualisierung)**:
- Anwendungen zur Erstellung von Diagrammen, Mindmaps und Flowcharts für bessere Teamkommunikation.

**GitLab, GitHub Issues (Ticketsysteme)**:
- Systeme zur Verwaltung und Nachverfolgung von Entwicklungsaufgaben und Fehlerberichten im Softwareentwicklungsprozess.


---

## 2️⃣ CODE (Entwicklung) 💻
### Erklärung:
Hier schreiben Entwickler den eigentlichen Code der Anwendung. Dabei setzen sie auf Best Practices wie Test-Driven Development (TDD) oder Pair Programming, um qualitativ hochwertigen Code zu gewährleisten. Versionskontrollsysteme wie Git helfen bei der Zusammenarbeit und Verwaltung des Codes.

### Beschreibung: Entwickler schreiben den Quellcode für die Anwendung oder ein Feature.
### Beispiel: Ein Entwickler nutzt GitHub oder GitLab, um Code für ein neues Feature zu committen.
### Verbindung: Der Code wird anschließend gebaut und getestet.

### Entwicklungsphase

**Methoden**:
**Test-Driven Development (TDD)**:
- Ein Entwicklungsansatz, bei dem Tests vor dem eigentlichen Code geschrieben werden, um Fehler frühzeitig zu erkennen.

**Pair Programming**:
- Zwei Entwickler arbeiten gleichzeitig an einem Code-Abschnitt, um die Code-Qualität zu verbessern und Wissen zu teilen.

**Code Reviews**:
- Eine Methode zur Überprüfung von Code durch Kollegen, um Fehler zu reduzieren und Best Practices sicherzustellen.

**Trunk-Based Development**:
- Ein Entwicklungsmodell, bei dem alle Entwickler regelmäßig Code in den Hauptzweig (`trunk`) einpflegen, um Konflikte zu minimieren.

**Werkzeuge**:
**Git, GitLab, GitHub, Bitbucket (Versionskontrolle)**:
- Plattformen zur Verwaltung von Code, die Änderungen nachvollziehbar machen und eine kollaborative Entwicklung ermöglichen.

**IDEs: VS Code, IntelliJ, Eclipse**:
- Entwicklungsumgebungen, die Entwicklern Funktionen wie Debugging, Autovervollständigung und Syntaxprüfung bieten.

**SonarQube (Code-Qualitätsanalyse)**:
- Ein Tool zur statischen Code-Analyse, das hilft, Sicherheitslücken und schlechte Code-Praktiken zu identifizieren.

**Docker (Containerisierung)**:
- Eine Plattform zur Erstellung und Verwaltung von Containern, um Software in isolierten Umgebungen bereitzustellen.


---

## 3️⃣ BUILD (Build-Prozess) 🏗
### Erklärung:
Der Build-Prozess konvertiert den geschriebenen Code in ein ausführbares Programm. Dabei werden Abhängigkeiten aufgelöst, Transpilation durchgeführt und das Ergebnis in einem Paket zusammengefasst, das für die nächsten Phasen bereitsteht. CI/CD-Pipelines übernehmen oft diesen Schritt automatisiert.

### Beschreibung: Der Quellcode wird in ein ausführbares Programm kompiliert und mit Abhängigkeiten verbunden.
### Beispiel: Eine CI/CD-Pipeline mit Jenkins oder GitHub Actions erstellt automatisch ein Docker-Image.
### Verbindung: Das fertige Artefakt wird für Tests bereitgestellt.

### Build

Der **Build**-Prozess wandelt Quellcode in ausführbare Artefakte um.

**Transpilierung des React-Codes**:
- Umwandlung von JSX und modernem JavaScript (ES6+) in browserfähiges JavaScript.

**Abhängigkeitsmanagement**:
- Installation aller erforderlichen npm-Pakete für Frontend und Backend mit `npm install`.

**Paketierung**:
**Frontend**:
- Webpack bündelt React-Komponenten, CSS und Assets in optimierte statische Dateien im `build`-Verzeichnis.

**Backend**:
- Express-Server-Code wird in ein Verzeichnis kopiert, oft wird `node_modules` für Produktion optimiert.

**Versionierung**:
- Setzen der Versionsnummer in `package.json`, eventuell Generierung von Build-Hashes für Cache-Busting.

**Qualitätsprüfungen**:
- ESLint für JavaScript/TypeScript-Codequalität, Jest für automatisierte Tests.

**Beispiel**:
- Der Build-Prozess für eine Full-Stack-JavaScript-Anwendung umfasst das Ausführen von `npm run build`, was die React-App für Produktion bundelt und optimiert, dann die Express-API-Dateien verarbeitet und schließlich alles in ein Docker-Image packt für ein konsistentes Deployment.


---

## 4️⃣ TEST (Tests) ✅
### Erklärung:
In dieser Phase wird der Code intensiv geprüft. Automatisierte Unit-, Integrations- und UI-Tests helfen, Fehler frühzeitig zu erkennen. Auch Sicherheitstests und Lasttests sind wichtige Bestandteile, um eine hohe Softwarequalität sicherzustellen.

### Beschreibung: Automatisierte Tests prüfen die Software auf Fehler und Schwachstellen.
### Beispiel: Unit-Tests mit Jest für JavaScript oder JUnit für Java, dazu Security-Scans mit SonarQube.
### Verbindung: Nach erfolgreichem Test wird die Software für den Release vorbereitet.

### Testphase

**Methoden**:
**Automatisierte Testpyramide**:
- Strukturierte Teststrategie mit Fokus auf Unit-Tests, Integrationstests und UI-Tests.

**Shift-Left Testing**:
- Frühes Testen im Entwicklungsprozess, um Fehlerkosten zu minimieren.

**Chaos Engineering**:
- Gezieltes Einbringen von Fehlern in das System, um die Resilienz zu testen.

**Contract Testing**:
- Validierung von API-Schnittstellen, um Kompatibilitätsprobleme zwischen Diensten zu vermeiden.

**Werkzeuge**:
**JUnit, pytest, Jest (Unit Testing)**:
- Frameworks zur Automatisierung von Unit-Tests für verschiedene Programmiersprachen.

**Selenium, Cypress (UI-Tests)**:
- Tools zur Automatisierung von End-to-End-Tests in Webanwendungen.

**Postman, REST Assured (API-Tests)**:
- Werkzeuge zur Validierung von API-Schnittstellen.

**JMeter, Gatling (Lasttests)**:
- Plattformen zur Simulation von Last- und Performancetests.

**OWASP ZAP, SonarQube (Sicherheitstests)**:
- Tools zur Analyse von Sicherheitslücken und Code-Qualität.


---

## 5️⃣ RELEASE (Veröffentlichung) 🚀
### Erklärung:
Nach erfolgreichem Testen wird die Software für die Bereitstellung freigegeben. Das beinhaltet das Setzen von Versionen, das Schreiben von Release Notes und das Definieren von Strategien für den Rollout.

### Beschreibung: Die getestete Software wird für das Deployment freigegeben.
### Beispiel: GitHub Actions oder GitLab CI/CD pusht ein neues Release-Tag in das Repository.
### Verbindung: Der Code wird nun in Produktionsumgebungen deployed.

### Release

Ein **Release** ist die finale Vorbereitung für die Bereitstellung.

**Schritte im Release-Prozess**:

**Versionierung** und Kennzeichnung des Releases:
- Definiert die eindeutige Versionsnummer und dokumentiert Änderungen.

**Änderungsdokumentation (Release Notes)**:
- Beschreibt neue Funktionen, Bugfixes und Änderungen für Nutzer und Entwickler.

**Genehmigungsprozesse (falls erforderlich)**:
- Unternehmen mit strengen Compliance-Vorgaben benötigen Freigaben für den Release.

**Bereitstellungsplanung (Zeitpunkt, Strategie)**:
- Entscheidet, wann und wie das Release ausgerollt wird.

**Rollback-Planung für den Fehlerfall**:
- Stellt sicher, dass im Problemfall eine frühere Version schnell wiederhergestellt werden kann.

**Release-Strategien**:
**Big Bang Release**:
- Alles wird auf einmal bereitgestellt – geeignet für kleinere Anwendungen oder wenig frequentierte Systeme.

**Phased Roll-out**:
- Neue Versionen werden schrittweise an Nutzer ausgerollt, um potenzielle Fehler frühzeitig zu erkennen.

**Canary Release**:
- Eine kleine Benutzergruppe erhält die neue Version vor der vollständigen Bereitstellung.

**Blue-Green Deployment**:
- Zwei parallele Produktionsumgebungen ermöglichen risikofreie Updates.

**Feature Flags**:
- Bestimmte Funktionen können zur Laufzeit aktiviert oder deaktiviert werden, ohne den gesamten Code neu bereitzustellen.



---

## 6️⃣ DEPLOY (Bereitstellung) 📦
### Erklärung:
In dieser Phase wird die Anwendung in einer Produktions- oder Staging-Umgebung bereitgestellt. Dabei kommen Tools wie Kubernetes oder Terraform zum Einsatz, um die Bereitstellung effizient und automatisiert zu gestalten.

### Beschreibung: Der Release-Code wird in verschiedenen Umgebungen (Staging/Produktion) bereitgestellt.
### Beispiel: Kubernetes orchestriert die Bereitstellung einer neuen Microservices-Version auf AWS oder Azure.
### Verbindung: Nach dem Deployment beginnt die Überwachung der Anwendung.

### Bereitstellungsphase

**Methoden**:

**Continuous Delivery/Deployment**:
- Softwareänderungen werden kontinuierlich automatisiert bereitgestellt, wodurch Updates jederzeit sicher veröffentlicht werden können.

**GitOps**:
- Infrastruktur und Deployments werden über Git-Repositories verwaltet, um Änderungen nachvollziehbar und reproduzierbar zu machen.

**Infrastructure as Code**:
- Infrastruktur wird über Code definiert und automatisiert bereitgestellt, um konsistente Umgebungen zu gewährleisten.

**Immutable Infrastructure**:
- Infrastrukturkomponenten werden bei Änderungen neu erstellt, statt aktualisiert, um Konfigurationsdrift zu vermeiden.

**Werkzeuge**:
**Jenkins, GitLab CI/CD, GitHub Actions, CircleCI (CI/CD-Plattformen)**:
- Automatisierungs-Tools für den Build-, Test- und Deployment-Prozess.

**ArgoCD, Flux (GitOps)**:
- Kubernetes-native Tools zur Verwaltung von Deployments über Git-Repositorys.

**Terraform, CloudFormation (Infrastructure as Code)**:
- Tools zur automatisierten Bereitstellung und Verwaltung von Cloud-Ressourcen.

**Ansible, Chef, Puppet (Konfigurationsmanagement)**:
- Automatisierungstools zur Verwaltung und Konfiguration von Servern und Anwendungen.

**Kubernetes, Docker Swarm (Container-Orchestrierung)**:
- Plattformen zur Verwaltung und Skalierung von containerisierten Anwendungen.


---

## 7️⃣ OPERATE (Betrieb) ⚙️
### Erklärung:
Nachdem die Software live gegangen ist, wird sie verwaltet, gewartet und skaliert. Hier spielen Automatisierung und Cloud-Technologien eine große Rolle, um eine hohe Verfügbarkeit sicherzustellen und manuelle Eingriffe zu minimieren.

### Beschreibung: Die Anwendung wird live genutzt, verwaltet und skaliert.
### Beispiel: Ein Cloud-Administrator nutzt Terraform oder Ansible, um Infrastrukturänderungen automatisiert durchzuführen.
### Verbindung: Es wird sichergestellt, dass das System stabil läuft und überwacht wird.

### Betriebsphase

**Methoden**:
**Site Reliability Engineering (SRE)**:
- Ein Ansatz, der Softwareentwicklung mit IT-Betrieb kombiniert, um zuverlässige und skalierbare Systeme zu gewährleisten.

**Incident Management**:
- Prozesse zur schnellen Identifikation, Analyse und Behebung von Vorfällen, um Betriebsunterbrechungen zu minimieren.

**Capacity Planning**:
- Vorausschauende Planung von Ressourcen, um sicherzustellen, dass Infrastruktur und Systeme mit steigenden Anforderungen skalieren können.

**Automatische Skalierung**:
- Dynamische Anpassung der Ressourcen je nach Last, um Effizienz und Performance zu maximieren.

**Werkzeuge**:
**Kubernetes, Nomad (Orchestrierung)**:
- Plattformen zur Verwaltung und Skalierung von containerisierten Anwendungen.

**Helm (Kubernetes-Paketmanagement)**:
- Tool zur Verwaltung von Kubernetes-Anwendungen mit vordefinierten Charts.

**AWS, Azure, GCP (Cloud-Plattformen)**:
- Cloud-Dienste zur Bereitstellung und Skalierung von Infrastruktur und Anwendungen.

**PagerDuty, OpsGenie (Incident Management)**:
- Plattformen zur Alarmierung und Koordination von Reaktionsmaßnahmen bei Betriebsstörungen.


---

## 8️⃣ MONITOR (Überwachung) 🔍
### Erklärung:
Überwachungstools wie Prometheus und Grafana sammeln Metriken über die Anwendung und Infrastruktur. Bei Anomalien oder Fehlern werden Teams sofort benachrichtigt, um frühzeitig reagieren zu können. Monitoring sorgt für Stabilität und Performanceoptimierung.

### Beschreibung: Die Leistung und Sicherheit der Anwendung werden kontinuierlich überwacht.
### Beispiel: Prometheus und Grafana tracken Fehlerraten, CPU-Auslastung und Antwortzeiten.
### Verbindung: Falls Fehler auftreten, wird das Team benachrichtigt und startet einen neuen Planungszyklus.

### Überwachungsphase

**Methoden**:
**Observability (Logs, Metriken, Traces)**:
- Kombination aus Logging, Metriken und verteiltem Tracing, um Systemverhalten zu analysieren.

**Synthetics Monitoring**:
- Automatisierte Tests, die Benutzeraktionen simulieren, um die Verfügbarkeit und Performance zu überprüfen.

**Real User Monitoring (RUM)**:
- Erfassung und Analyse echter Nutzerinteraktionen, um die User Experience zu verbessern.

**Anomalieerkennung**:
- Algorithmen zur Identifikation ungewöhnlicher Muster oder Abweichungen im Systemverhalten.

**Werkzeuge**:
**Prometheus, Grafana (Metriken)**:
- Open-Source-Tools zur Überwachung und Visualisierung von Systemmetriken.

**ELK Stack, Loki (Logging)**:
- Plattformen zur zentralisierten Protokollierung und Analyse von Log-Daten.

**Jaeger, Zipkin (Tracing)**:
- Tools zur Analyse und Visualisierung von Anfragen innerhalb verteilter Systeme.

**Datadog, New Relic (APM)**:
- Application Performance Monitoring für die Messung und Optimierung der Anwendungsperformance.

**Sentry (Fehlerüberwachung)**:
- Tool zur automatisierten Fehlerverfolgung und -benachrichtigung.


---
