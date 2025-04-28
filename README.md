# Universal Agent Chain Builder 🤖

Eine flexible Anwendung zum Erstellen und Ausführen von KI-Agenten-Ketten mit GPT-4. Entwickle deine eigenen Agenten-Ketten mit 2 bis 99 Agenten, die nacheinander arbeiten und aufeinander aufbauen.

## Features

- 🔗 Flexible Agenten-Ketten mit 2-99 Agenten
- 🎯 Individuelle System-Prompts für jeden Agenten
- 📊 Live-Fortschrittsanzeige
- 📝 Markdown-Export der Ergebnisse
- 🌐 Benutzerfreundliche Streamlit-Oberfläche
- 🚀 Einfache Installation mit setup.bat

## Installation

### Automatische Installation (Windows)

1. Klone das Repository
2. Führe `setup.bat` aus
3. Gib deinen OpenAI API Key ein, wenn du dazu aufgefordert wirst
4. Fertig! Die App erstellt automatisch Desktop-Verknüpfungen

### Manuelle Installation

1. Klone das Repository
2. Installiere die Abhängigkeiten:
   
   ```bash
   pip install -r requirements.txt
   ```
3. Erstelle eine `.env` Datei mit deinem OpenAI API Key:
   
   ```
   OPENAI_API_KEY=dein-api-key-hier
   ```
4. Starte die App:
   
   ```bash
   streamlit run agent_chain_app.py
   ```

## Verwendung

1. **Konfiguration**
   
   - Gib deinen OpenAI API Key ein
   - Gib Name und Website des zu untersuchenden potenziellen Kunden ein

2. **Agenten-Setup**
   
   - Die System Prompts der Agents sind vordefiniert, können aber manuell verändert werden

3. **Ausführung**
   
   - Drucke auf "Prozess starten"

4. **Ergebnisse**
   
   - Lade die kompletten Ergebnisse als Markdown-Datei herunter

## ## Lizenz

MIT License - Siehe LICENSE Datei

## Beitragen

Beiträge sind willkommen! Bitte erstelle einen Pull Request oder öffne ein Issue für Vorschläge und Verbesserungen.

made by Dirk Wonhoefer, AI Engineering, 2025

https://ai-engineering.ai