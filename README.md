# The Social-Engineer Toolkit (SET)
* based on the work of 
* Written by: David Kennedy (ReL1K) @HackingDave 
* Company: [TrustedSec](https://www.trustedsec.com)
#TITAN

TITAN ist ein modulares, KI-gestütztes Social-Engineering- und Botnet-Framework, inspiriert 
von Dave Kennedy’s Social-Engineer Toolkit (SET)

und erweitert um Mechaniken und Kompatibilität mit Alien Pimp Botnet sowie moderner
KI- und Visualisierungsfunktionen.

🚀 Features

    Python 3.10+ – Moderne Sprachfeatures und beste Kompatibilität
    Modulare Architektur – Eigene und Community-Module, SET- und Alien Pimp-kompatibel
    Botnet-Mechanik – Verteilter Agentenbetrieb, zentrale Steuerung, verschlüsselte Kommunikation
    Website-Kloning & Credential Harvesting – Automatisiertes Klonen, Anpassen und Bereitstellen von Webinterfaces
    KI-/ML-Analysen – Mit scikit-learn für Mustererkennung, Anomalie-Detektion, Clustering
    Visualisierung – Netzwerk- und Kampagnen-Visualisierung mit matplotlib
    Eigene TUI/GUI – Basierend auf tkinter für einfache Bedienung und Monitoring
    JAN-Integration – Anbindung an das JAN-Framework für weitere Automatisierung und Analyse
    Apache 2.0 Lizenz – Frei, offen, für die Community

🛠️ Voraussetzungen
    Python 3.10 oder neuer
    pip (Python-Paketmanager)
    matplotlib
    tkinter (bei vielen Python-Installationen bereits enthalten)
    scikit-learn
    requests
    jan (dein Framework, ggf. als Submodul oder PyPI-Paket)
    weitere Abhängigkeiten siehe requirements.txt

⚡ Installation

bash
git clone https://github.com/M4tth4ck33/titan
cd titan
pip install -r requirements.txt

🖥️ Starten

bash
python titan.py

Die TUI/GUI (tkinter) öffnet sich, und du kannst TITAN direkt bedienen.

🔌 Module & Erweiterbarkeit
    Eigene Module einfach im Verzeichnis /modules/ ablegen.
    Kompatibel mit SET- und Alien Pimp-Modulen.
    KI-Module können scikit-learn nutzen (z. B. für Phishing-Erkennung, Bot-Verhalten, Netzwerk-Klassifikation).
    Visualisierung und Monitoring via matplotlib und tkinter-Dashboard.

🤖 Botnet-Mechanik
    Controller: Zentrale Steuerung (GUI/TUI, API)
    Agents: Verteilt, leichtgewichtig, empfangen Aufgaben (z. B. Website-Kloning, Payload-Delivery, Scans)
    Kommunikation: Verschlüsselt (z. B. HTTPS, WebSocket)
    Kompatibilität: Alien Pimp-Mechanik und Protokolle werden unterstützt

📊 Visualisierung & KI
    matplotlib: Netzwerkgraphen, Kampagnenverlauf, Cluster-Analysen, Heatmaps
    scikit-learn: ML-Modelle für Anomalieerkennung, Klassifikation, Clustering
    tkinter: Eigene Dashboards und Steuerelemente

🔗 JAN-Integration
    Direkte Anbindung an das JAN-Framework für automatisierte Analysen, Empfehlungen und Reporting.
    Beispiel: Netzwerkdaten an JAN senden, KI-gestützte Scan-Strategien erhalten und direkt visualisieren.

📄 Lizenz
Apache License 2.0 – Open Source, frei nutzbar und erweiterbar.

⚠️ Haftungsausschluss
TITAN ist ausschließlich für legale Sicherheitsforschung, Penetrationstests und Security-Awareness-Trainings gedacht.
Die Nutzung gegen Systeme ohne ausdrückliche Genehmigung ist illegal und wird strafrechtlich verfolgt.
Der Entwickler übernimmt keine Haftung für Missbrauch.

✨ Credits
    Dave Kennedy (TrustedSec) – SET-Inspiration
    Alien Pimp – Botnet-Mechanik
    JAN – KI- und Automatisierungsintegration
    Security Community – für Forschung, Entwicklung und Open Source

💡 Mitmachen
Pull Requests, neue Module und Ideen sind willkommen!


TITAN – The Next Generation Social Engineering, KI & Botnet Framework
„Inspired by Kennedy, powered by the community.“
