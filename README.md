# Einführung in Git & GitHub

## Übersicht

In dieser Lektion habe ich den Teilnehmenden erklärt:
- **Was Git und GitHub sind.**
- **Wofür sie verwendet werden.**
- **Wie man Git und GitHub praktisch einsetzt**, einschließlich der Erstellung, Verwaltung und Klonung von Projekten.

---

## Was ist Git?

**Git** ist ein verteiltes Versionskontrollsystem, das von Linus Torvalds entwickelt wurde. Es wird hauptsächlich für die Verwaltung von Quellcode in Softwareentwicklungsprojekten verwendet.

### Hauptfunktionen von Git:
1. **Versionskontrolle und Sicherung von Daten:**  
   Git ermöglicht die effiziente Verfolgung von Änderungen am Quellcode und anderen Dateien.

2. **Commits:**  
   Ein Commit ist eine Gruppe von Änderungen, die zu einem Zeitpunkt in die Versionsgeschichte aufgenommen werden.

3. **Branches:**  
   Branches sind separate Entwicklungslinien, die von der Hauptentwicklungslinie (z. B. "Main") abzweigen können.

4. **Merge und Pull Requests:**  
   Änderungen in einem Branch können durch Merge in den Hauptcode integriert werden. Pull Requests erlauben es, Änderungen vorzuschlagen und von anderen Entwicklern überprüfen zu lassen.

5. **Konfliktlösung:**  
   Konflikte entstehen, wenn mehrere Entwickler gleichzeitig Änderungen an derselben Datei vornehmen. Git hilft, diese Konflikte zu lösen.

6. **Remote-Repositories:**  
   Projekte können auf remote gehosteten Git-Servern gespeichert werden, um die Zusammenarbeit zu erleichtern. Beispiele:  
   - GitLab  
   - Bitbucket

---

## Was ist GitHub?

**GitHub** ist eine webbasierte Plattform, die von Entwicklern genutzt wird, um Code zu hosten, zu verwalten und gemeinsam daran zu arbeiten. Sie bietet eine Umgebung, in der Projekte mit Versionskontrolle gespeichert und überprüft werden können.

### Hauptfunktionen von GitHub:
1. **Repositories:**  
   Repositories sind Projekte, in denen der Quellcode und andere Dateien aufbewahrt werden.

2. **Versionskontrolle:**  
   GitHub verwendet Git, um Änderungen zu verfolgen und zu verwalten.

3. **Branches:**  
   Branches ermöglichen es, verschiedene Versionen des Codes zu entwickeln, ohne sich gegenseitig zu stören.

4. **Pull Requests:**  
   Pull Requests erlauben es Entwicklern, Änderungen vorzuschlagen. Andere können diese Änderungen überprüfen und genehmigen oder ablehnen.

---

## GitHub: Die Vorgehensweise

### Ein neues Repository erstellen:
1. Repository auf GitHub erstellen.
2. Projektordner lokal erstellen und in VS Code öffnen.
3. Terminal in VS Code öffnen (`command + j`).

**Befehle für ein neues Projekt:**
```bash
git init               # Initialisiert ein neues Git-Repository
git add .              # Fügt alle Dateien hinzu
git commit -m "first commit"  # Speichert die Änderungen mit einem Kommentar
git branch -m main     # Setzt den Branch auf "main"
git remote add origin URL   # Verknüpft das Repository mit dem Remote-Repository
git push -u origin main  # Schiebt die Änderungen ins Remote-Repository