# Git Branching Strategie

## Übersicht

Für die Zusammenarbeit im Team wird eine vereinfachte Git Flow Strategie verwendet.  
Diese Strategie stellt sicher, dass neue Features, Bugfixes und Releases sauber getrennt entwickelt werden.

## Branches

### main
Der main Branch enthält immer den stabilen und produktionsbereiten Code.  
Direkte Commits auf main sind nicht erlaubt. Änderungen werden nur über Pull Requests integriert.

### feature Branches
Neue Funktionen werden in separaten Feature Branches entwickelt.

Beispiel:

feat/Login  
feat/Website  
feat/Strategie

Feature Branches werden vom aktuellen main Branch erstellt und nach Fertigstellung per Pull Request in main gemerged.

### bugfix Branches
Fehler werden in eigenen Bugfix Branches behoben.

Beispiel:

fix/login-error

Diese Branches werden ebenfalls über Pull Requests in main integriert.

## Workflow

1. Entwickler erstellt einen neuen Feature Branch
2. Änderungen werden mit sinnvollen Commit Messages erstellt
3. Branch wird auf Github gepusht
4. Pull Request wird erstellt
5. Code Review
6. Merge in main

## Vorteile dieser Strategie

- Klare Trennung zwischen stabiler Version und Entwicklung
- Keine direkten Änderungen auf main
- Änderungen werden über Pull Requests geprüft
- Bessere Zusammenarbeit im Team