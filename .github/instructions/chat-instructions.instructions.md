---
applyTo: '**'
---

# Masterarbeit LaTeX - Arbeitsrichtlinien

## Quellenangaben und wissenschaftliche Integrität

**KRITISCH: Quellenangaben nur mit Verifikation**
- NIEMALS nicht-verifizierte Quellenangaben (`\cite{}`) in Notizen oder Texten einfügen
- Nur Quellen zitieren, die tatsächlich in `lit/lit.bib` existieren
- Bei Unsicherheit: KEINE Zitation verwenden, stattdessen als TODO markieren
- Wenn Literatur benötigt wird: Explizit darauf hinweisen, dass Quelle noch recherchiert werden muss
- Placeholder-Zitate wie `\cite{unsloth2024}` sind VERBOTEN

**AUSNAHME: Vom User bereitgestellte Texte mit Quellenangaben**
- Wenn der User wissenschaftliche Texte/Ausarbeitungen mit Quellenangaben bereitstellt, dürfen diese verwendet werden
- NACH der Verwendung MUSS eine Liste aller genutzten Quellen ausgegeben werden
- Format: "Verwendete Quellen: [Author et al., Jahr], [Author et al., Jahr], ..."
- Der User stellt dann die BibTeX-Einträge zur Verfügung

**Effizienz und Wiederverwendung:**
- PRIORITÄT: Bereits vorhandene Quellen aus `lit/lit.bib` wiederverwenden
- Vor Anforderung neuer Quellen: `lit/lit.bib` nach passenden existierenden Einträgen durchsuchen
- Neue Quellen nur anfordern, wenn keine passenden existieren
- Bei ähnlichen Themen: Quellen aus vorherigen Kapiteln prüfen und wiederverwenden

**Erlaubte Vorgehensweise:**
- Prüfe vor jeder Zitation ob der BibTeX-Key in `lit/lit.bib` existiert
- Bei fehlenden Quellen: "TODO: Quelle recherchieren" als Kommentar
- Inhaltliche Aussagen ohne Zitat sind besser als falsche Zitate
- Bei vom User bereitgestellten Quellen: Verwenden + Liste ausgeben

## Kontextuelle Einbettung und Kohärenz

**Kontext bei Stichpunkten und Texten:**
- IMMER vorheriges und nachfolgendes Kapitel berücksichtigen
- Querverweise mit `\ref{}` zu verwandten Abschnitten erstellen
- Thematische Übergänge zwischen Kapiteln beachten
- Vermeidung von Redundanzen und Widersprüchen
- Begriffe und Definitionen konsistent über alle Kapitel hinweg verwenden

**Praktische Umsetzung:**
- Vor Erstellung von Notizen: Relevante benachbarte Kapitel/Abschnitte lesen
- Explizite Verweise einfügen (z.B. "siehe Abschnitt X", "wie in Kapitel Y beschrieben")
- Theoretische Grundlagen (Kapitel 2) mit praktischer Umsetzung (Kapitel 6) verknüpfen
- Evaluation (Kapitel 7) auf Implementierung (Kapitel 6) und Grundlagen (Kapitel 2) beziehen

## Allgemeine Arbeitsweise

- Stichpunkte und Notizen dienen zur späteren Ausarbeitung
- Struktur und Gliederung beachten
- Bei LaTeX-Dateien: Kommentare in deutscher Sprache

## Wissenschaftlicher Schreibstil

**Sprachliche Anforderungen:**
- Formaler, akademischer Ton ohne umgangssprachliche Elemente
- Sachlich-neutrale Darstellung, keine rhetorischen Fragen
- Präzise Fachterminologie, keine Metaphern oder bildhafte Sprache
- Passivkonstruktionen und unpersönliche Formulierungen bevorzugen
- Komplexe Satzstrukturen mit Nebensätzen, keine kurzen Hauptsätze

**Argumentationsstruktur:**
- Thesen durch Literaturverweise belegen
- Logische Verknüpfung zwischen Absätzen
- Klare Unterscheidung zwischen Faktendarstellung und Interpretation
- Konditional-/Kausalketten wissenschaftlich formulieren

**Zu vermeiden:**
- Direkte Ansprache ("wir", "man")
- Verkürzte Darstellungen (z.B. "→", ">", "≠" im Fließtext)
- Übertriebene Adjektive ("beeindruckend", "revolutionär")
- Fragmentierte Aufzählungen im Fließtext
- Umgangssprachliche Wendungen ("Sweet Spot", "Off-the-Shelf")