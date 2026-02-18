# KI-Workflows, Qualitaetssicherung und Risikomanagement im Journalismus

> Recherche-Dokument fuer den Workshop "AI im Journalismus"
> Stand: Februar 2026

---

## Inhaltsverzeichnis

1. [KI-Integration in redaktionelle Workflows](#1-ki-integration-in-redaktionelle-workflows)
2. [Qualitaetssicherung bei KI-gestuetztem Journalismus](#2-qualitaetssicherung-bei-ki-gestuetztem-journalismus)
3. [Risiken von KI im Journalismus](#3-risiken-von-ki-im-journalismus)
4. [Auditing und Monitoring von KI-Nutzung](#4-auditing-und-monitoring-von-ki-nutzung)
5. [Weiterbildung und Upskilling fuer Journalist:innen](#5-weiterbildung-und-upskilling-fuer-journalistinnen)
6. [Prompt Engineering im journalistischen Kontext](#6-prompt-engineering-im-journalistischen-kontext)
7. [Deepfake-Erkennung: Methoden und Tools](#7-deepfake-erkennung-methoden-und-tools)
8. [Wie KI die Rolle von Journalist:innen veraendert](#8-wie-ki-die-rolle-von-journalistinnen-veraendert)

---

## 1. KI-Integration in redaktionelle Workflows

### Schrittweiser Integrationsprozess

Die Integration von KI in Redaktionen folgt typischerweise einem mehrstufigen Prozess:

**Phase 1: Bestandsaufnahme und Planung**
- Einrichtung eines **KI-Boards** mit Expert:innen aus IT, Recht, HR und verschiedenen Redaktionsabteilungen
- Bedarfsanalyse: Was brauchen die Menschen in der Redaktion? Was wollen die Leser:innen?
- Bewertung vorhandener Infrastruktur und Ressourcen

**Phase 2: Pilotprojekte und Tests**
- Start mit kleinen, risikoarmen Pilotprojekten (z.B. Metadaten-Tagging, Audio-Produktion)
- Einrichtung von **Sandbox-Umgebungen** zum sicheren Testen von Tools
- Gemeinsames Prompt Engineering mit Autor:innen anhand realer Artikel

**Phase 3: Operative Einfuehrung**
- Drei Viertel der KI-Ausgaben fliessen in redaktionelle Arbeit und Content-Erstellung
- Schrittweise Ausweitung auf weitere Anwendungsbereiche

**Phase 4: Governance und Transparenz**
- Nur 13% der Redaktionen haben formale KI-Richtlinien etabliert -- hier besteht grosser Nachholbedarf
- Festlegung von Offenlegungspflichten, Autorenschaftsregeln und Urheberrechtsrichtlinien

### Konkrete Einsatzbereiche in Redaktionen

| Anwendung | Beschreibung | Beispiel |
|-----------|-------------|---------|
| **Automatisierte Berichterstattung** | KI generiert Entwuerfe aus strukturierten Daten (Pressemitteilungen, Boersendaten) | Reporter:innen pruefen und ueberarbeiten, koennen so mehrere Stories gleichzeitig betreuen |
| **SEO und Tagging** | KI-gestuetzte Verschlagwortung und Suchmaschinenoptimierung | Automatische Kategorisierung von Inhalten |
| **Community-Management** | KI erkennt relevante Leserkommentare und leitet sie weiter | Weiterleitung ueber Teams/Slack an die Redaktion |
| **Recherche-Unterstuetzung** | KI-gestuetzte Themensuche und Quellenrecherche | dpa "Story-Radar" durchsucht soziale Netzwerke nach Themen |
| **Transkription und Uebersetzung** | Automatische Verschriftlichung von Interviews und Pressekonferenzen | Echtzeit-Transkription mit Whisper oder aehnlichen Tools |

### Beispiel: Deutsche Presseagentur (dpa)

Die dpa hat seit Januar 2025 ein eigenes KI-Team unter Yannick Franke. Das Projekt **"Wegweiser KI"** (April 2024 -- Maerz 2025) unterstuetzte deutsche Redaktionen durch praxisorientierte Schulungen. Die dpa nutzt u.a. das "Story-Radar", das Reporter:innen auf interessante Geschichten aufmerksam macht, indem es soziale Netzwerke nach relevanten Themen durchsucht.

> **Quellen:**
> - [WAN-IFRA: How to integrate AI into your newsroom](https://wan-ifra.org/2025/05/how-to-integrate-ai-into-your-newsroom-not-just-as-a-tool-but-as-a-transformative-force/)
> - [Nieman Lab: AI will rewrite the architecture of the newsroom](https://www.niemanlab.org/2025/12/ai-will-rewrite-the-architecture-of-the-newsroom/)
> - [Twipe: 12 Ways Journalists Use AI Tools](https://www.twipemobile.com/12-ways-journalists-use-ai-tools-in-the-newsroom/)
> - [dpa Innovation: Wegweiser KI](https://www.dpa.com/de/wegweiser-ki)
> - [dpa Innovation: KI-Recherche fuer den Newsroom](https://innovation.dpa.com/2024/11/04/ki-recherche-zukunft-der-nachrichtenrecherche/)

---

## 2. Qualitaetssicherung bei KI-gestuetztem Journalismus

### Das Vier-Augen-Prinzip und redaktionelle Pruefung

Der Grundsatz lautet: **Journalismus ist eine menschengetriebene Taetigkeit** -- KI kann unterstuetzen, aber nicht das Urteilsvermoegen, die Kreativitaet und die Verantwortlichkeit ersetzen, die Qualitaetsjournalismus ausmachen.

**Human-in-the-Loop-Prinzip:**
- Jeder KI-generierte Inhalt wird vor Veroeffentlichung von menschlichen Redakteur:innen geprueft
- KI-generiertes Material wird wie eine Quelle behandelt, die menschliche Bearbeitung und Faktencheck erfordert (Praxis bei MinnPost)
- Menschliche Redakteur:innen haben immer das letzte Wort bei wichtigen redaktionellen Entscheidungen

### Governance-Strukturen

Eine Analyse redaktioneller Stylebooks und interner KI-Richtlinien von **45 journalistischen Organisationen** zeigt:

- Medieninstitutionen entwickeln aktiv Regeln zur Begrenzung des Einsatzes generativer KI in der Content-Erstellung
- Schwerpunkte: menschliche Aufsicht, Verifizierung, Urheberrechtsschutz und Transparenz
- **Reuters** bietet interne Richtlinien fuer verantwortungsvollen und transparenten KI-Einsatz
- Die **BBC** wahrt menschliche Aufsicht ueber KI-generierte Inhalte und kennzeichnet KI-gestuetzte Berichterstattung klar

### Transparenz und Kennzeichnung

- Rund **90% der untersuchten Richtlinien** schreiben vor, dass KI-Einsatz in einer Story offengelegt werden muss
- **The Guardian** und **CBC** fordern vollstaendige Offenlegung; CBC verfolgt das Prinzip "keine Ueberraschungen" fuer das Publikum
- **AP** legt fest: KI "darf nicht zur Erstellung publizierbarer Inhalte und Bilder fuer den Nachrichtendienst verwendet werden"
- Herausforderung: Wie die Transparenz in der Praxis konkret umgesetzt wird, bleibt oft unklar

### Qualitaetssicherungs-Checkliste fuer KI-gestuetzte Inhalte

1. **Faktencheck**: Alle KI-generierten Aussagen gegen Originalquellen pruefen
2. **Quellenverifikation**: Sind die genannten Quellen real und korrekt zitiert?
3. **Bias-Pruefung**: Einseitige Darstellungen oder systematische Verzerrungen identifizieren
4. **Tonalitaet**: Entspricht der Stil den redaktionellen Standards?
5. **Kennzeichnung**: KI-Einsatz gemaess Richtlinien offenlegen
6. **Versionierung**: Dokumentation der verwendeten Prompts und KI-Tools

> **Quellen:**
> - [Frontiers: Digital transformation in journalism](https://www.frontiersin.org/journals/communication/articles/10.3389/fcomm.2025.1535156/full)
> - [Digital Content Next: Journalists confront the reality of media use of AI](https://digitalcontentnext.org/blog/2025/03/17/journalists-confront-the-reality-of-media-use-of-ai/)
> - [CNTI: Artificial Intelligence in Journalism](https://cnti.org/issue-primers/artificial-intelligence-in-journalism/)
> - [Journalists Resource: Researchers compare AI policies at 52 news organizations](https://journalistsresource.org/home/generative-ai-policies-newsrooms/)
> - [Springer: Guiding the way -- AI guidelines in global media](https://link.springer.com/article/10.1007/s00146-024-01973-5)

---

## 3. Risiken von KI im Journalismus

### 3.1 Halluzinationen

KI-Chatbots weisen **Halluzinationsraten von bis zu 79%** auf. Eine Studie des Tow Center for Digital Journalism ergab, dass **ueber 60% der Antworten von KI-gestuetzten Suchmaschinen ungenau** waren. Dies ist besonders problematisch, da LLM-basierte Suchmaschinen zunehmend in Journalismus und Faktenpruefung Einzug halten.

**Auswirkungen auf den Journalismus:**
- Erfundene Zitate, falsche Statistiken, nicht existierende Quellen
- Plausibel klingende aber faktisch falsche Zusammenhaenge
- Besonders gefaehrlich bei Echtzeit-Berichterstattung unter Zeitdruck

### 3.2 Bias und Verzerrungen

- Trainingsdaten koennen **voreingenommen, ungenau oder absichtlich manipuliert** sein
- Staatliche und nichtstaatliche Akteure koennen Narrative in Trainingsdaten einschleusen
- Systematische Unterrepraesentation bestimmter Perspektiven und Bevoelkerungsgruppen
- Verstaerkung bestehender gesellschaftlicher Vorurteile

### 3.3 Deepfakes und synthetische Medien

- Rund **500.000 Deepfake-Videos** wurden 2023 in sozialen Medien geteilt; Prognosen zeigen **bis zu 8 Millionen bis 2025**
- KI-Tools ermoeglichen die Erstellung realistischer multimodaler Inhalte -- einschliesslich Deepfakes, KI-generierter Stimmaufnahmen und ueberzeugender synthetischer Texte
- Deepfake-Technologie wird als Werkzeug fuer **geschlechtsspezifische Gewalt** eingesetzt, was die demokratische Teilhabe von Frauen und Minderheiten gefaehrdet

### 3.4 Quellenschutz und Desinformation

- Die russisch-ausgerichtete Kampagne **"Operation Overload"** (Januar--Maerz 2025) imitierte ueber 80 Organisationen mittels manipulierter Logos und Stimmen
- KI erweitert **Umfang, Skalierung und Personalisierung von Desinformation**
- Gefaehrdung der Vertraulichkeit journalistischer Quellen durch KI-gestuetzte Analyse-Tools
- Risiko der De-Anonymisierung von Whistleblowern durch Mustererkennung

### 3.5 Urheberrecht und geistiges Eigentum

- Ungeklaerte Rechtslage bei KI-generierten Inhalten
- Risiko der unbeabsichtigten Urheberrechtsverletzung durch Uebernahme geschuetzter Textpassagen
- Fragen der Autorenschaft bei KI-gestuetzten Artikeln

### Risikomatrix

| Risiko | Wahrscheinlichkeit | Schweregrad | Gegenmassnahme |
|--------|-------------------|-------------|----------------|
| Halluzinationen | Sehr hoch | Hoch | Systematischer Faktencheck, Vier-Augen-Prinzip |
| Bias | Hoch | Hoch | Diversitaetspruefung, Sensitivitaetstraining |
| Deepfakes | Mittel | Sehr hoch | Detektionstools, Quellenverifikation |
| Quellenschutz | Mittel | Sehr hoch | Verschluesselung, minimale Datenweitergabe |
| Urheberrecht | Hoch | Mittel | Rechtliche Pruefung, klare Richtlinien |

> **Quellen:**
> - [CJR: What Journalists Should Know About Deepfake Detection in 2025](https://www.cjr.org/tow_center/what-journalists-should-know-about-deepfake-detection-technology-in-2025-a-non-technical-guide.php)
> - [UNRIC: Artificial Intelligence and the Future of Journalism](https://unric.org/en/artificial-intelligence-and-the-future-of-journalism-risks-and-opportunities/)
> - [Frontiers: AI-driven disinformation](https://www.frontiersin.org/journals/artificial-intelligence/articles/10.3389/frai.2025.1569115/full)
> - [EU-Parlament: Briefing zu KI und Desinformation](https://www.europarl.europa.eu/RegData/etudes/BRIE/2025/779259/EPRS_BRI(2025)779259_EN.pdf)
> - [TIME: What the Numbers Show About AI's Harms](https://time.com/7346091/ai-harm-risk/)

---

## 4. Auditing und Monitoring von KI-Nutzung

### Aktueller Stand in Redaktionen

Eine Umfrage unter 28 Redaktionen im Jahr 2025 zeigt:
- **Ca. 50%** arbeiten an KI-Nutzungsrichtlinien
- Vier haben oeffentliche KI-Nutzungsrichtlinien veroeffentlicht
- Drei haben interne Richtlinien
- Sechs weitere sind im Entwurfsstadium

### Best Practices fuer KI-Auditing

**Kontinuierliches Monitoring:**
- Regelmaessige Ueberpruefung der Inputs, Datenerfassung und Outputs von KI-Tools
- Laufende Beobachtung auf Updates und Aenderungen durch die Entwickler
- Benennung einer verantwortlichen Person fuer das Monitoring

**Policy-Entwicklung:**
- Zusammenarbeit zwischen redaktionellen, juristischen und Audience-Teams
- Orientierung an bestehenden Richtlinien (AP "Standards around generative AI", SPJ "Ethics of using AI")
- Regelmaessige Aktualisierung der Richtlinien

**Governance-Rahmenwerk:**
- Verantwortungsvolle Beschaffung und Nutzung von KI-Tools
- Sicherstellung der angemessenen Nutzung und Ueberwachung ueber den gesamten Lebenszyklus eines KI-Tools
- Zusammenarbeit zwischen Journalist:innen, Redakteur:innen und Organisationsleitung

### Audit-Checkliste fuer Redaktionen

1. **Tool-Inventar**: Welche KI-Tools werden in der Redaktion eingesetzt?
2. **Datenfluss**: Welche Daten werden an KI-Dienste uebermittelt?
3. **Output-Qualitaet**: Wie oft muessen KI-Ergebnisse korrigiert werden?
4. **Compliance**: Werden alle internen Richtlinien eingehalten?
5. **Transparenz**: Wird der KI-Einsatz gegenueber dem Publikum offengelegt?
6. **Datenschutz**: Werden personenbezogene Daten und Quelleninformationen geschuetzt?
7. **Kosteneffizienz**: Stehen Aufwand und Nutzen in einem sinnvollen Verhaeltnis?

### Deutschsprachiger Kontext

Im deutschen Sprachraum gilt: KI-Einsatz wird als **redaktionelle, nicht rein technische oder oekonomische Angelegenheit** verstanden. Journalist:innen behalten die endgueltige Entscheidungsgewalt, waehrend KI-Systeme nur unterstuetzend eingesetzt werden. KI-generierte oder KI-gestuetzte Inhalte muessen nachvollziehbar und auf ihre Quellen rueckfuehrbar sein.

> **Quellen:**
> - [American Journalism Project: Developing an AI usage policy](https://www.theajp.org/news-insights/insights/developing-an-ai-usage-policy-in-your-news-organization/)
> - [Partnership on AI: AI Adoption for Newsrooms -- A 10-Step Guide](https://partnershiponai.org/ai-for-newsrooms/)
> - [EJO: Zwischen Leitlinien und Redaktionstisch](https://de.ejo-online.eu/in-eigener-sache/zwischen-leitlinien-und-redaktionstisch-verantwortungsvoller-ki-einsatz-im-journalismus)
> - [dpa Innovation: Fuenf Guidelines fuer Kuenstliche Intelligenz](https://innovation.dpa.com/2023/04/03/kuenstliche-intelligenz-fuenf-guidelines-der-dpa/)

---

## 5. Weiterbildung und Upskilling fuer Journalist:innen

### Internationale Programme

| Programm | Anbieter | Format | Details |
|----------|---------|--------|---------|
| **JournalismAI Skills Lab** | POLIS/LSE | 12 Wochen, virtuell, kostenlos | Praktische Implementierung von LLMs und GenAI im Redaktionsalltag |
| **JournalismAI Academy** | POLIS/LSE | 5 Wochen, ab Feb. 2026 | Masterclasses mit Expert:innen an der Schnittstelle von Journalismus und KI |
| **AI Journalism Lab: Leaders** | CUNY Newmark J-School | Mehrteilig | Fokus auf Fuehrungskraefte und KI-Strategie in Redaktionen |
| **AI Journalism Lab: Adoption** | CUNY Newmark J-School | Mehrteilig | Praktische KI-Einfuehrung in Redaktionen |
| **Prompt Engineering 101 for Journalists** | Knight Center | Online-Kurs | Grundlagen des Prompt Engineering fuer journalistische Arbeit |
| **Google AI Tools for Journalists** | Knight Center | 4 Wochen, kostenlos, EN/ES | Optimierung von Workflows, Content-Erstellung, Audience Engagement |
| **AI for Journalists** | NCTJ | Modular | Fuer Journalist:innen, PR-Fachleute, Dozent:innen, Freelancer:innen |
| **CJS2030 AI Initiative** | Columbia J-School | Integriert ins Studium | Langfristiges Programm zur KI-Integration in die Journalistenausbildung |

### Reichweite

JournalismAI plant fuer 2025 die Schulung von mindestens **4.500 Journalist:innen aus 100 Laendern in 5 Sprachen**. Zusaetzlich bietet die "AI Academy for Small Newsrooms" praktische Schulungen fuer 200 Nachrichtenorganisationen weltweit.

### Deutschsprachige Angebote

- **dpa "Wegweiser KI"**: Praxisorientiertes Trainingsprogramm fuer deutsche Redaktionen (2024-2025)
- **dpa Fortbildung**: Digitale Recherche, Verification und KI-Tools -- Trainingsprogramm fuer Redaktionen
- **BJV (Bayerischer Journalisten-Verband)**: Schulungen zum Einsatz von KI in Redaktionen

### Kernkompetenzen fuer die Zukunft

Journalist:innen benoetigen zunehmend:

1. **Datenkompetenz**: Interpretation und Analyse grosser Datensaetze, KI-gestuetzte Analytik
2. **Technische Grundlagen**: Verstaendnis von KI-Plattformen, NLP und Automatisierungstools
3. **Kritisches Denken**: Bewertung und Einordnung von KI-Outputs
4. **Prompt Engineering**: Faehigkeit, praezise Anweisungen an KI-Systeme zu formulieren
5. **Ethische Kompetenz**: Verstaendnis von Urheberrecht, Attribution, Bias und Transparenz

> **Quellen:**
> - [JournalismAI Skills Lab](https://www.journalismai.info/programmes/skillslab)
> - [JournalismAI Academy](https://www.journalismai.info/programmes/academy)
> - [CUNY AI Journalism Labs](https://www.journalism.cuny.edu/j-plus/ai-journalism-labs/)
> - [Knight Center: Prompt Engineering 101 for Journalists](https://journalismcourses.org/product/prompt-engineering-101-for-journalists/)
> - [NCTJ: AI for Journalists](https://www.nctj.com/professional-development/artificial-intelligence-ai-for-journalists/)
> - [dpa Presseportal: Trainingsprogramm](https://www.presseportal.de/pm/8218/6004014)

---

## 6. Prompt Engineering im journalistischen Kontext

### Grundprinzipien

Prompt Engineering ist 2025 nicht mehr nur das Stellen von Fragen -- es geht um das **Entwerfen von Fragetypen**, die Modelle zu genauen, relevanten und umsetzbaren Outputs fuehren.

### Wichtige Techniken fuer Journalist:innen

| Technik | Beschreibung | Journalistisches Beispiel |
|---------|-------------|--------------------------|
| **Zero-Shot Prompting** | Direkte Aufgabe ohne Beispiele | "Fasse diesen Bericht in 3 Saetzen zusammen" |
| **Few-Shot Prompting** | Aufgabe mit Beispielen | "Hier sind 3 Beispiel-Teaser. Schreibe einen aehnlichen fuer diesen Artikel" |
| **Chain-of-Thought** | Schrittweises Durchdenken | "Analysiere diese Statistik Schritt fuer Schritt und pruefe auf Unstimmigkeiten" |
| **Role Prompting** | Zuweisung einer Rolle | "Du bist ein erfahrener Faktenpruefer. Bewerte diese Behauptungen" |
| **Prompt Chaining** | Verkettung mehrerer Prompts | Recherche -> Zusammenfassung -> Faktencheck -> Entwurf |

### Best Practices fuer den Redaktionsalltag

**Spezifisch sein:**
```
Schlecht: "Schreib einen Artikel ueber Klimawandel"
Besser: "Erstelle einen 300-Woerter-Nachrichtenbeitrag ueber die Ergebnisse
         der COP29 fuer ein deutsches Regionalpublikum. Fokus auf konkrete
         Beschluesse mit Relevanz fuer kommunale Klimapolitik.
         Stil: sachlich-informativ, keine Meinungsaeusserung."
```

**Kontext bereitstellen:**
```
"Basierend auf dem folgenden Pressebericht [Text einfuegen], erstelle eine
Zusammenfassung mit den 5 wichtigsten Punkten. Kennzeichne Stellen, die
einer unabhaengigen Verifizierung beduerfen."
```

**Gewuenschtes Output-Format definieren:**
```
"Erstelle aus diesen Interviewnotizen [Text] einen strukturierten Bericht:
- Ueberschrift (max. 70 Zeichen)
- Vorspann (2 Saetze)
- 3-5 Abschnitte mit Zwischenueberschriften
- Keine direkten Zitate erfinden, nur vorhandene verwenden"
```

**Iterativ arbeiten:**
- Prompts testen, Variationen ausprobieren
- Ergebnisse bewerten und Input verfeinern
- Wiederverwendbare Templates fuer wiederkehrende Aufgaben erstellen

### Journalismus-spezifische Prompt-Templates

**Faktencheck-Prompt:**
```
"Pruefe die folgenden Behauptungen auf ihre Plausibilitaet. Liste fuer jede
Behauptung auf: (1) die Behauptung, (2) bekannte Fakten, die dafuer/dagegen
sprechen, (3) moegliche Quellen zur Verifizierung, (4) Konfidenz-Einschaetzung."
```

**Recherche-Prompt:**
```
"Erstelle einen Rechercheplan zum Thema [X]. Identifiziere: (1) Kernfragen,
(2) relevante Expert:innen und Institutionen, (3) moegliche Datenquellen,
(4) alternative Perspektiven, die beruecksichtigt werden sollten."
```

> **Quellen:**
> - [Knight Center: Prompt Engineering 101 for Journalists](https://journalismcourses.org/product/prompt-engineering-101-for-journalists/)
> - [CodeSignal: Prompt Engineering Best Practices 2025](https://codesignal.com/blog/prompt-engineering-best-practices-2025/)
> - [DigitalOcean: Prompt Engineering Best Practices](https://www.digitalocean.com/resources/articles/prompt-engineering-best-practices)

---

## 7. Deepfake-Erkennung: Methoden und Tools

### Verfuegbare Tools

| Tool | Schwerpunkt | Geeignet fuer |
|------|------------|---------------|
| **InVID/WeVerify** | Video-Verifikation, Metadatenanalyse | Journalist:innen, Faktenpruefer:innen |
| **Hive Moderation** | KI-generierte Bild-/Videoerkennung | Plattformen, Redaktionen |
| **Deepware Scanner** | Deepfake-Ersterkennung | Schnelles Screening |
| **DeepFake-o-Meter** | Akademisches Erkennungstool | Forschung, vertiefende Analyse |
| **Optic** | Multimodale Erkennung | Breit einsetzbar |
| **Content Credentials (C2PA)** | Provenienz-Standard | Medienproduktion, Verifikation |

### Erkennungsmethoden

**Visuelle Forensik:**
- Gesichtsinkonsistenzen (unnatuerliche Augenbewegungen, Lippensynchronisations-Fehler)
- Biometrische Muster (Blutflussanalyse, Stimmtonvariationen)
- Metadaten und digitale Fingerabdruecke

**Audio-Analyse:**
- Stimmton-Variationen und unnatuerliche Muster
- Hintergrundgeraeusch-Inkonsistenzen

**Cross-modale Konsistenzpruefung:**
- Abgleich zwischen Audio und Video
- Ueberpruefung von Provenienz-Signalen (Content Credentials/C2PA)

### Kritische Einschraenkungen

- Die Zuverlaessigkeit von Erkennungstools haengt stark von der **Art des Mediums und der Art der Manipulation** ab
- Eine Studie von 2024 zeigte: Journalist:innen mit Zugang zu Deepfake-Erkennungstools **verliessen sich manchmal zu stark** auf diese, besonders wenn die Ergebnisse ihre anfaenglichen Instinkte bestaetigten
- Ergebnisse koennen schwierig zu interpretieren sein

### Empfohlener Verifikations-Workflow

1. **Erstscreening**: Automatisierte Analyse mit Detektionstools (z.B. Deepware Scanner)
2. **Metadaten-Pruefung**: EXIF-Daten, Dateieigenschaften, C2PA-Credentials pruefen
3. **Visuelle Inspektion**: Manuelle Pruefung auf Artefakte und Inkonsistenzen
4. **Quellenverifikation**: Rueckverfolgung zum Ursprung, Gegenrecherche
5. **Expert:innen-Konsultation**: Bei Zweifeln forensische Expert:innen einbeziehen
6. **Redaktionelle Entscheidung**: Menschliche Reviewer:innen bestaetigten Befunde vor Veroeffentlichung

> **Quellen:**
> - [CJR/Tow Center: What Journalists Should Know About Deepfake Detection in 2025](https://www.cjr.org/tow_center/what-journalists-should-know-about-deepfake-detection-technology-in-2025-a-non-technical-guide.php)
> - [Nieman Lab: What journalists should know about deepfake detection](https://www.niemanlab.org/reading/what-journalists-should-know-about-deepfake-detection-in-2025/)
> - [SOCRadar: Top 10 AI Deepfake Detection Tools](https://socradar.io/blog/top-10-ai-deepfake-detection-tools-2025/)
> - [Deep Media: Why Media Companies Need Deepfake Detection in 2025](https://deepmedia.ai/blog/media-2025)

---

## 8. Wie KI die Rolle von Journalist:innen veraendert

### Der "hybride Profi"

Journalist:innen der Zukunft werden **"hybride Professionals"** sein, die traditionelle Faehigkeiten mit technologischen Kompetenzen verbinden. Statt Journalist:innen vollstaendig zu ersetzen, verschieben KI-Tools die Rolle hin zu **Analyse, Verifikation und multimedialem Storytelling**.

### Veraenderung der Kernaufgaben

| Traditionell | Mit KI-Unterstuetzung |
|-------------|----------------------|
| Manuelle Recherche | KI-unterstuetzte Recherche und Datenanalyse |
| Routinemaessige Berichterstattung | Automatisierte Erstfassung, menschliche Verfeinerung |
| Einzelne Medienformate | Multimediales Storytelling (Text, Audio, Video, Interaktiv) |
| Lineare Workflows | Parallelisierte, KI-gestuetzte Workflows |
| Intuitive Themenauswahl | Datengestuetzte Trendanalyse und Themenidentifikation |

### Zahlen und Fakten

- **81,7%** der Journalist:innen nutzen KI-Tools in ihrer Arbeit
- **49,4%** nutzen KI taeglich
- **72%** der Medienunternehmen planen bis 2025 mehr KI-Technologien einzusetzen
- Nachfrage nach Journalist:innen mit KI-Kenntnissen stieg um **ueber 30%**
- Journalist:innen mit KI-Expertise verdienen durchschnittlich **12% mehr** als Kolleg:innen ohne diese Faehigkeiten

### Neue Kompetenzen

Faehigkeiten, die KI **nicht ersetzen** kann:
- Kritisches Denken und Einordnung
- Menschliche Empathie und Einfuehlungsvermoegen
- Ethische Urteilsfaehigkeit
- Kreative Narrative und Storytelling
- Beziehungsaufbau mit Quellen
- Kontextualisierung komplexer Zusammenhaenge

Faehigkeiten, die Journalist:innen **neu entwickeln** muessen:
- Datenanalyse und -interpretation
- KI-Tool-Management und Prompt Engineering
- Technische Grundlagen (Grundlagen des Programmierens, Verstaendnis digitaler Plattformen)
- Multimedia-Storytelling in verschiedenen Formaten
- KI-Ethik und verantwortungsvoller Umgang mit Technologie

### Herausforderungen

- Nur **13%** der Redaktionen haben formale KI-Richtlinien
- KI-Nutzung bleibt oft den einzelnen Journalist:innen ueberlassen, was zu **Inkonsistenzen und ethischen Bedenken** fuehrt
- Gefahr der Abhaengigkeit von KI-Tools bei gleichzeitigem Verlust traditioneller Faehigkeiten
- Notwendigkeit kontinuierlicher Weiterbildung in einem sich schnell veraendernden Feld

> **Quellen:**
> - [Frontiers: Digital transformation in journalism](https://www.frontiersin.org/journals/communication/articles/10.3389/fcomm.2025.1535156/full)
> - [Boston Institute of Analytics: The Future of Journalism](https://bostoninstituteofanalytics.org/blog/the-future-of-journalism-how-ai-is-transforming-newsrooms-worldwide/)
> - [Reuters Institute: AI and the Future of News](https://reutersinstitute.politics.ox.ac.uk/ai-journalism-future-news)
> - [UNESCO: WPFD 2025 -- Future of journalism in an AI-Driven World](https://www.unesco.org/en/articles/wpfd-2025-exploring-future-journalism-ai-driven-world)
> - [Research.com: AI, Automation, and the Future of Journalism](https://research.com/advice/ai-automation-and-the-future-of-journalism-degree-careers)

---

## Fazit und Handlungsempfehlungen

### Fuer den Workshop

1. **Workflows etablieren**: KI-Integration ist ein schrittweiser Prozess -- mit Pilotprojekten beginnen, Vertrauen aufbauen, dann skalieren
2. **Qualitaet sichern**: Das Vier-Augen-Prinzip und Human-in-the-Loop sind nicht optional, sondern Grundvoraussetzung
3. **Risiken kennen**: Halluzinationen, Bias und Deepfakes sind reale Gefahren -- systematische Gegenmassnahmen sind notwendig
4. **Transparenz leben**: KI-Einsatz muss gegenueber dem Publikum offengelegt werden
5. **Kompetenzen aufbauen**: Kontinuierliche Weiterbildung in Prompt Engineering, Datenanalyse und KI-Ethik
6. **Richtlinien entwickeln**: Formale KI-Policies sind die Ausnahme, sollten aber die Regel werden
7. **Kritisch bleiben**: KI ist ein Werkzeug, kein Ersatz fuer journalistische Urteilskraft

---

*Dieses Dokument wurde im Rahmen der Vorbereitung des Workshops "AI im Journalismus" erstellt. Alle Quellen wurden im Februar 2026 abgerufen.*
