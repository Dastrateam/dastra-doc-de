---
description: Diese Seite erläutert die Funktionsweise der benutzerdefinierten Berichte von Dastra
---

# Benutzerdefinierte Berichte

Diese leistungsstarke Funktion ermöglicht es Ihnen, maßgeschneiderte Berichte zu erstellen, die auf Ihre spezifischen Bedürfnisse zugeschnitten sind. Ob Sie ein Anfänger oder ein fortgeschrittener Nutzer sind – diese benutzerfreundliche Funktion bietet Ihnen maximale Flexibilität, um wichtige Informationen aus den Dastra-Daten zu extrahieren.

### Schnellstart

1. Klicken Sie im linken Menü auf "Benutzerdefinierte Berichte"\
   &#x20;![](<../../.gitbook/assets/image (292).png>)
2. Die Berichte sind in einem Kategoriensystem organisiert. Bevor Sie Ihren ersten Bericht erstellen, müssen Sie **eine erste Kategorie anlegen**
3. **Klicken Sie auf Bericht erstellen** und wählen Sie eine der beiden Optionen: Neuen Bericht erstellen oder aus einer Vorlage erstellen

## Glossar

* **Metrik**: Eine Metrik ist ein messbarer Wert, der es ermöglicht, Elemente zu gruppieren (aggregieren). _Beispiel: Die Anzahl der Verarbeitungen, die durchschnittliche Bearbeitungsdauer einer Aufgabe..._
* **Dimension**: Im Gegensatz zur Metrik ermöglicht die Dimension keine Aggregation der Daten. Es handelt sich um eine einfache Eigenschaft (= eine Spalte) eines Elements. \
  &#xNAN;_&#x42;eispiel: der Name der Verarbeitung, der Status der Verarbeitung, die Referenz, ..._

## Aufbau des Berichts

### Grundprinzipien

1. **Datenauswahl:** Wählen Sie die Daten aus, die Sie in Ihren Bericht aufnehmen möchten. Unsere benutzerfreundliche Oberfläche ermöglicht es Ihnen, Ihre Datensätze einfach zu durchsuchen und die relevanten Variablen (Metriken und Dimensionen) aus den verschiedenen Dastra-Tabellen auszuwählen.
2. **Erweiterte Filter:** Verfeinern Sie Ihre Ergebnisse mithilfe erweiterter Filter. Erstellen Sie spezifische Kriterien, um nur die für Ihre Analyse relevanten Daten zu extrahieren.
3. **Grafische Anpassung:** Erwecken Sie Ihre Berichte zum Leben, indem Sie Diagramme und Tabellen anpassen. Ändern Sie die Diagrammstile, die Ihren Bedürfnissen am besten entsprechen.
4. **Mehrfach-Export:** Exportieren Sie Ihre Berichte in verschiedenen Formaten wie PDF, Excel oder CSV. Teilen Sie Ihre Ergebnisse einfach mit Ihren Kollegen, Kunden oder Partnern. Integrieren Sie Ihre Daten einfach in Tools wie PowerBI.

### Datenauswahl

#### Auswahl der Datentabellen

Wählen Sie die verschiedenen Datentabellen aus, die Sie abfragen möchten: Verarbeitungen, Verarbeitungsschritte, Zweck, Tags... Sie können **bis zu 6 verschiedene Tabellen in jedem Bericht** abfragen.

<figure><img src="../../.gitbook/assets/image (293).png" alt=""><figcaption></figcaption></figure>

Klicken Sie auf "Weiter", wenn Sie die Tabellen ausgewählt haben

{% hint style="info" %}
Achtung: Sobald die Tabellen ausgewählt sind, können Sie nicht mehr zurückgehen, um die betreffenden Tabellen zu ändern.
{% endhint %}

#### Aufbau des Berichts anhand von Metriken und Dimensionen

Erstellen Sie Ihren Bericht, indem Sie die Metriken und Dimensionen auswählen, die Sie anzeigen möchten.

<figure><img src="../../.gitbook/assets/image (291).png" alt=""><figcaption></figcaption></figure>

Klicken Sie auf die Schaltfläche "Speichern" unten rechts auf der Seite

{% hint style="info" %}
Die Daten werden automatisch nach Dimensionen aggregiert, um die ausgewählten Metriken zu berechnen.&#x20;
{% endhint %}

Beispiel: Sie wählen die Variable "Anzahl Datenverarbeitungen" und "Status" aus und erhalten einen Bericht in folgender Form &#x20;

| Status  | Anzahl Datenverarbeitungen |
| ------- | -------------------------- |
| Entwurf | 12                         |
| Aktiv   | 560                        |

## Anzeige und grafische Darstellung des benutzerdefinierten Berichts

Sobald der Bericht erstellt wurde, werden Sie auf die folgende Seite weitergeleitet:&#x20;

<figure><img src="../../.gitbook/assets/image (290).png" alt=""><figcaption><p>Bildschirmaufnahme der Ergebnisse der benutzerdefinierten Berichte</p></figcaption></figure>

Um ein Diagramm hinzuzufügen, klicken Sie auf "**Diagramm hinzufügen**".

Sie können dann verschiedene Diagrammkategorien definieren.\
![](<../../.gitbook/assets/image (289).png>)

