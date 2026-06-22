[![Shipping files](https://github.com/neuefische/ds-linear-regression/actions/workflows/workflow-02.yml/badge.svg?branch=main&event=workflow_dispatch)](https://github.com/neuefische/ds-linear-regression/actions/workflows/workflow-02.yml)
# Lineare Regression

Dieses Repository behandelt verschiedene Themen rund um lineare Regression:

* Einfache und multiple lineare Regression mit scikit-learn
* Einfache und multiple lineare Regression mit statsmodels
* Grenzen der linearen Regression
* Umgang mit kategorialen Variablen

## Richte deine Umgebung ein
Bitte stelle sicher, dass du das Repo geforkt und eine neue virtuelle Umgebung eingerichtet hast. Dafür kannst du die folgenden Befehle verwenden:
Die beigefügte [requirements-Datei](requirements.txt) enthält alle Bibliotheken und Abhängigkeiten, die wir zur Ausführung der Lineare-Regression-Notebooks benötigen.
### **`macOS`** gib folgende Befehle ein:
- Installiere die virtuelle Umgebung und die benötigten Pakete mit folgenden Befehlen:

    ```BASH
    pyenv local 3.11.3
    python -m venv .venv
    source .venv/bin/activate
    pip install --upgrade pip
    pip install -r requirements.txt
    ```
### **`WindowsOS`** gib folgende Befehle ein:
- Installiere die virtuelle Umgebung und die benötigten Pakete mit folgenden Befehlen.

   Für `PowerShell` CLI:
   
    ```PowerShell
    pyenv local 3.11.3
    python -m venv .venv
    .venv\Scripts\Activate.ps1
    python -m pip install --upgrade pip
    pip install -r requirements.txt
    ```
    
    Für `Git-Bash` CLI:
    
    ```
    pyenv local 3.11.3
    python -m venv .venv
    source .venv/Scripts/activate
    python -m pip install --upgrade pip
    pip install -r requirements.txt
    ```
## Daten
Die Datensätze für die Notebooks sind im `data.zip`-Ordner gespeichert. Um den Daten-Ordner direkt im Terminal zu entpacken, führe aus:

```sh
unzip data.zip
```
## Lernziele
Am Ende dieses Repos solltest du
* wissen, wie man scikit-learn verwendet, um ein lineares Regressionsmodell zu trainieren.
* ein Verständnis für die Anwendung und Grenzen der linearen Regression haben.
* wissen, wie man die statsmodels-Bibliothek für OLS verwendet.
