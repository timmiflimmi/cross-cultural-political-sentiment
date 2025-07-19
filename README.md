# 🌍 Cross-Cultural Political Sentiment Analysis

## ⚠️ **WICHTIGER HINWEIS: SIMULATIONSSTUDIE**

**Diese Studie verwendet SIMULIERTE DATEN, nicht echte Social Media Posts.**

**Zweck:** Framework-Demonstration und Methodenvalidierung für zukünftige empirische Forschung mit echten Datenquellen.

---

## 📊 Überblick

Entwicklung und Demonstration einer wissenschaftlich fundierten Methodik zur Analyse politischer Stimmungen in sozialen Medien verschiedener Länder und deren Korrelation mit Demokratie-Indizes.

## 🎯 Projektziel

**METHODISCHE ENTWICKLUNG** einer reproducible research pipeline für:
- Sentiment-Analyse von Social Media Posts
- Korrelation mit Democracy Index Scores
- Ländervergleichende Visualisierungen
- Framework für echte empirische Studien

## ⚠️ **DATENGRUNDLAGE - VOLLSTÄNDIGE TRANSPARENZ**

### ✅ **ECHTE WISSENSCHAFTLICHE KOMPONENTEN:**
- **EIU Democracy Index 2024**: Authentische Werte von [Our World in Data](https://ourworldindata.org/grapher/democracy-index-eiu)
- **Peer-reviewed Literatur**: Systematische Review von 10+ wissenschaftlichen Studien
- **Statistische Methoden**: Validierte Korrelationsanalyse und Visualisierungen
- **Code-Framework**: Professional Data Science Pipeline

### ⚠️ **SIMULIERTE KOMPONENTEN:**
- **Social Media Daten**: KEINE echten Tweets oder Posts verwendet
- **Sentiment Scores**: Mathematisch generiert basierend auf Democracy Scores + Rauschen
- **Zeitreihen**: Simulierte 365-Tage-Trends mit realistischen Parametern
- **User Engagement**: Population-basierte Schätzungen

### 🔢 **WIE DIE SIMULATION FUNKTIONIERT:**
```python
# Basis-Sentiment mathematisch vom Democracy Score abgeleitet
base_sentiment = (democracy_score - 5) / 10

# Plus realistische Faktoren:
# + Länderspezifische Trends
# + Saisonale politische Zyklen  
# + Wochentag-Effekte
# + Stochastisches Rauschen
```

**ERGEBNIS:** Die hohe Korrelation (r = 0.992) ist ein **Artefakt der Simulation**, nicht empirisch validiert.

---

## 🛠️ Tech Stack

- **Python**: Pandas, NumPy, Scikit-learn
- **Visualisierung**: Plotly, Matplotlib, Seaborn
- **Web-App**: Streamlit
- **NLP-Framework**: VADER Sentiment (für zukünftige echte Daten)
- **Datenquellen**: EIU Democracy Index, wissenschaftliche Literatur

## 📊 Analysierte Länder

**8 Länder mit unterschiedlichen Demokratie-Klassifikationen:**

### Full Democracies (EIU 2024):
- **Schweden**: 9.2/10
- **Deutschland**: 8.7/10  
- **UK**: 8.3/10
- **Frankreich**: 8.1/10

### Flawed Democracies (EIU 2024):
- **USA**: 7.8/10
- **Italien**: 7.5/10
- **Brasilien**: 6.9/10
- **Polen**: 6.8/10

## 📁 Projektstruktur

```
cross-cultural-political-sentiment/
├── src/                           # Haupt-Analysecode
│   └── sentiment_analysis.py      # Wissenschaftlich fundierte Simulation
├── docs/                          # Wissenschaftliche Dokumentation
│   └── scientific_sources.md      # Vollständige Literaturverweise
├── results/                       # Simulationsergebnisse
│   ├── sentiment_analysis_scientific.html
│   ├── scientific_insights_report.md
│   └── scientific_methodology.json
├── data/                          # (Zukünftig: echte Datenquellen)
├── app/                           # (Zukünftig: Streamlit Dashboard)
└── tests/                         # Unit Tests
```

## 🚀 Quick Start

```bash
# Repository klonen
git clone https://github.com/timmiflimmi/cross-cultural-political-sentiment.git
cd cross-cultural-political-sentiment

# Virtual Environment
python -m venv venv
source venv/bin/activate  # Mac/Linux

# Dependencies installieren
pip install -r requirements.txt

# Simulation ausführen
python src/sentiment_analysis.py

# Ergebnisse anschauen
open results/sentiment_analysis_scientific.html
```

## 📈 Simulationsergebnisse

**⚠️ WICHTIG: Diese Ergebnisse basieren auf SIMULIERTEN DATEN**

### Haupterkenntnisse der Simulation:
- **Democracy-Sentiment Korrelation**: r = 0.992 (durch Design!)
- **Full Democracies**: Ø 0.371 Sentiment (simuliert)
- **Flawed Democracies**: Ø 0.204 Sentiment (simuliert)
- **Volatilität**: Höher in weniger demokratischen Ländern (modelliert)

### Was diese Zahlen BEDEUTEN:
1. **Demonstration der Methodik** ✅
2. **Framework-Validierung** ✅  
3. **Code-Pipeline funktioniert** ✅
4. **NICHT: Empirische Evidenz** ❌

---

## 🔬 Wissenschaftliche Fundierung

### Peer-Reviewed Literaturgrundlage:
1. **EIU Democracy Index**: [Our World in Data](https://ourworldindata.org/grapher/democracy-index-eiu)
2. **Sentiment Analysis Systematic Review**: [Sistia et al. (2019)](https://www.sciencedirect.com/science/article/pii/S187705091931885X)
3. **Political Text Analysis**: [Steinert-Threlkeld (2018)](https://www.cambridge.org/core/journals/political-analysis/article/sentiment-is-not-stance-targetaware-opinion-classification-for-political-text-analysis/743A9DD62DF3F2F448E199BDD1C37C8D)
4. **Social Media Analytics Framework**: [Stieglitz & Dang-Xuan (2013)](https://www.researchgate.net/publication/235632721_Social_Media_and_Political_Communication_-_A_Social_Media_Analytics_Framework)

**Vollständige Referenzen**: [docs/scientific_sources.md](docs/scientific_sources.md)

---

## 🎯 Verwendungszweck & Zielgruppe

### **Ideal für:**
- **Data Science Portfolio**: Demonstration wissenschaftlicher Arbeitsweise
- **Methodische Studien**: Framework für echte Forschung
- **Educational Purposes**: Lernen von reproduce research
- **Proof-of-Concept**: Für zukünftige empirische Studien

### **NICHT geeignet für:**
- ❌ Policy-Entscheidungen
- ❌ Akademische Publication (ohne echte Daten)
- ❌ Kausal-Inferenz
- ❌ Empirische Validierung von Theorien

---

## 🔄 Roadmap für echte Forschung

### Phase 1: Framework (✅ ABGESCHLOSSEN)
- [x] Methodische Grundlagen
- [x] Code-Pipeline
- [x] Visualisierungs-Framework
- [x] Literatur-Integration

### Phase 2: Echte Datenintegration (🚧 ZUKÜNFTIG)
- [ ] Twitter Academic API Integration
- [ ] Echte Sentiment-Analyse mit BERT/VADER
- [ ] Longitudinale Datensammlung (6+ Monate)
- [ ] Multi-Language NLP Pipeline

### Phase 3: Empirische Validierung (📅 GEPLANT)
- [ ] Causal Inference Design
- [ ] Cross-validation mit anderen Democracy Indices
- [ ] Peer Review Submission
- [ ] Policy Impact Assessment

---

## ⚖️ Wissenschaftliche Ethik & Limitationen

### **Methodische Stärken:**
- ✅ Vollständig dokumentierte Pipeline
- ✅ Peer-reviewed Literaturgrundlage
- ✅ Reproducible Research Standards
- ✅ Transparente Datengeneration

### **Klare Limitationen:**
- ⚠️ **Simulierte Daten**: Keine echten Social Media Posts
- ⚠️ **Designed Correlation**: Hohe Korrelation ist Artefakt
- ⚠️ **Keine Kausalität**: Korrelation ≠ Kausalität
- ⚠️ **Zeitliche Begrenzung**: 1-Jahres-Simulation nur

### **Ethische Überlegungen:**
- 🔒 **Privacy by Design**: Keine echten User-Daten verwendet
- 📖 **Vollständige Transparenz**: Simulation klar kommuniziert
- 🔬 **Scientific Integrity**: Limitationen explizit benannt
- 🎯 **Educational Purpose**: Framework für echte Forschung

---

## 🤝 Beitragen

Dieses Projekt dient als **Grundlage für echte empirische Forschung**. Contributions willkommen für:

- **Echte API-Integration** (Twitter Academic, Reddit, etc.)
- **Advanced NLP Models** (BERT, GPT-basierte Sentiment)
- **Causal Inference Methods** 
- **Multi-Language Support**
- **Longitudinal Study Design**

---

## 📄 Lizenz

MIT License - Siehe [LICENSE](LICENSE) für Details.

---

## 🔗 Kontakt & Referenzen

**GitHub**: [@timmiflimmi](https://github.com/timmiflimmi)  
**Projekt**: Cross-Cultural Political Sentiment Analysis Framework

```

---

## ⚠️ **ABSCHLIESSENDER HINWEIS**

**Diese Studie ist eine METHODISCHE DEMONSTRATION mit simulierten Daten. Alle Ergebnisse dienen der Framework-Validierung, nicht der empirischen Erkenntnisgewinnung. Für echte wissenschaftliche Schlussfolgerungen sind empirische Studien mit authentischen Datenquellen erforderlich.**

**Wissenschaftliche Integrität erfordert vollständige Transparenz. Dieses Projekt demonstriert Best Practices für reproducible research und dient als Grundlage für zukünftige empirische Validierung.**

---

*Letzte Aktualisierung: Juli 2025 | Framework Version 1.0*