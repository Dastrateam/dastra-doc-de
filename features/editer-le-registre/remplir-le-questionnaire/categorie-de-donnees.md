---
description: >-
  Erfahren Sie, wie Sie die Datenkategorien sowie die zugehörigen
  verarbeitungsspezifischen Aufbewahrungsregeln angeben.
---

# Daten und Aufbewahrung

[**Artikel 30 der DSGVO**](https://www.cnil.fr/fr/reglement-europeen-protection-donnees/chapitre4) verlangt auch die Eintragung der verarbeiteten Datenkategorien.

Hier geht es darum, die Kategorien der verarbeiteten Daten zu definieren. Diese können als gewöhnlich oder sensibel eingestuft werden. Es wird nämlich zwischen Daten unterschieden, die ein höheres Risiko für natürliche Personen darstellen, wie z. B. Gesundheitsdaten, Daten zu politischen Meinungen oder gewerkschaftlichen Aktivitäten. Daten zu Straftaten oder anderen Vollstreckungsmaßnahmen stellen ebenfalls besonders geschützte Daten dar.&#x20;

Ebenso kann die Sozialversicherungsnummer (NIR) als sensible Daten eingestuft werden.&#x20;

Die Erhebung sensibler Daten ist grundsätzlich verboten. Nur die in [**Artikel 9 der DSGVO**](https://www.cnil.fr/fr/reglement-europeen-protection-donnees/chapitre2) vorgesehenen Ausnahmen erlauben deren Erhebung.

## Datensätze

Der Datensatz fasst die Daten eines bestimmten Elements zusammen, zum Beispiel eine Tabelle in einer Datenbank oder ein Papiererhebungsformular.

### Verschiedene Anwendungsfälle der Datensätze

Datensätze können auf verschiedene Weise verwendet werden:

* **Fall Nr. 1**: Indem **ein Datensatz einem einzelnen Asset zugeordnet** wird. In diesem Fall entspricht der Datensatz den Daten des Assets und ist nicht generisch.
* **Fall Nr. 2**: Indem **ein Datensatz der Datenverarbeitung zugeordnet** wird. Dieser Datensatz kann spezifisch für die Datenverarbeitung sein und wird nicht in einer anderen Verarbeitung wiederverwendet.
* **Fall Nr. 3**: Indem **generische Datensätze der Datenverarbeitung zugeordnet** werden. In diesem Fall kann der Datensatz in mehreren Verarbeitungen wiederverwendet werden.

Für die Verwendung generischer Datensätze empfehlen wir folgendes Vorgehen:

* Öffnen Sie die Seite der Verarbeitung bezüglich der Datensätze
* Öffnen Sie einen neuen Tab auf der Seite der Datensätze in der Datenkartierung
* Wählen Sie den Datensatz in der Datenverarbeitung aus
* Wenn der Datensatz geändert werden muss, erstellen Sie einen neuen: Gehen Sie zum anderen Tab und duplizieren Sie den generischen Datensatz, indem Sie die gewünschten Felder entfernen oder hinzufügen
* Für mehr Übersichtlichkeit wird empfohlen, einen Tag für diese Datensätze zu verwenden (damit Sie sie im Datensatz-Selektor leicht unterscheiden können). Zum Beispiel: ein Tag "generisch" und ein Tag bezüglich der hinzugefügten oder entfernten Daten

#### Datensätze ohne Felder verwenden

Darüber hinaus ist es möglich, noch generischer zu bleiben, indem die dem Datensatz zugeordneten Daten nicht angegeben werden, sondern der Datensatz als Datenkategorie benannt wird (was im Sinne der DSGVO ebenfalls gültig ist).

Je nach Verarbeitung können Sie unterschiedliche Ansätze verfolgen, abhängig von der Sensibilität, die sie hinsichtlich der Rechte und Freiheiten der betroffenen Personen darstellen.

### Die Datenquelle im Datensatz angeben

In jedem Datensatz können Sie den Ursprung der Daten eintragen. Dieser ist entweder direkt, indirekt oder beides.&#x20;

Ein Feld zur Beschreibung des Erhebungsursprungs ermöglicht es, die erforderliche Präzision zu liefern.

<figure><img src="../../../.gitbook/assets/image (10) (2) (1).png" alt=""><figcaption><p>Datenquelle</p></figcaption></figure>

### Ein Asset dem Datensatz zuordnen

Datensätze haben von Natur aus die Bestimmung, [Assets](applications.md) zugeordnet zu werden.&#x20;

Sie können bei der Erstellung eines Datensatzes ein Asset zuordnen.&#x20;

<figure><img src="../../../.gitbook/assets/image (2) (1) (3).png" alt=""><figcaption><p>Asset-Selektor</p></figcaption></figure>

Ein Datensatz kann nur einem einzigen Asset zugeordnet werden. Durch die Definition der Datensätze eines Assets sind diese nämlich einzigartig.&#x20;

Betrachtet man beispielsweise eine Buchhaltungssoftware als Asset, könnten diesem Asset mehrere Datensätze zugeordnet werden, wie "Rechnungsdaten" mit den Daten zum Rechnungsverfolgungsmodul oder "Kundendaten" mit den Daten zu den Kundenkonten.

### Eine Kategorie betroffener Personen zuordnen

Für jeden Datensatz können Sie eine oder mehrere Kategorien betroffener Personen zuordnen.&#x20;

Dies ermöglicht es Ihnen, besser zu verstehen, welche Daten den betroffenen Personen zugeordnet sind. Darüber hinaus vereinfacht dies die Kartierungsarbeit.&#x20;

<figure><img src="../../../.gitbook/assets/image (3) (1) (3) (2).png" alt=""><figcaption><p>Selektor für Kategorien betroffener Personen</p></figcaption></figure>

{% hint style="info" %}
Die Angabe der betroffenen Personen ist nützlich für die Verwaltung von [Betroffenenanfragen](../../gerer-les-exercices-des-droits/). Sie können die Daten, die Gegenstand der Anfrage sind, leicht finden, indem Sie die betreffenden Datensätze schnell identifizieren.
{% endhint %}

### Datenfelder zuordnen

Jeder Datensatz soll durch Datenfelder ergänzt werden. Diese Felder sind die eigentlichen Daten.&#x20;

Die im Selektor angezeigten Felder sind die im Datenglossar verfügbaren Felder.&#x20;

<figure><img src="../../../.gitbook/assets/image (8) (1) (3).png" alt=""><figcaption><p>Datenfeld-Selektor</p></figcaption></figure>

Wenn eine Daten nicht vorhanden ist, können Sie sie direkt über diesen Selektor erstellen, um sie zum Datensatz hinzuzufügen.&#x20;

Die Felder können nach vordefinierten Kategorien kategorisiert werden. Es handelt sich insbesondere um die von der CNIL empfohlenen Kategorien.

<figure><img src="../../../.gitbook/assets/image (9) (2) (3).png" alt=""><figcaption><p>Selektor für Kategorien personenbezogener Daten</p></figcaption></figure>

Auf Feldebene können Sie auch das Vorhandensein sensibler Daten angeben. Zum Beispiel Gesundheitsdaten oder eine andere Art sensibler Daten.&#x20;

In diesem Fall werden Sie aufgefordert, die Erhebung dieser Daten und insbesondere die sie erlaubende Rechtsgrundlage zu begründen.

&#x20;

<figure><img src="../../../.gitbook/assets/image (4) (3) (2).png" alt=""><figcaption><p>Sensible Daten</p></figcaption></figure>

{% hint style="info" %}
Diese Information wird von der Anwendung analysiert, um ein intelligentes [DSFA](analyse-dimpact.md)-Kriterium auszulösen.&#x20;
{% endhint %}

### Eine Aufbewahrungsregel für Daten zuordnen

In jedem Datensatz können Sie eine Aufbewahrungsregel für Daten zuordnen.&#x20;

<figure><img src="../../../.gitbook/assets/image (6) (2).png" alt=""><figcaption><p>Speicherdauer</p></figcaption></figure>

Die Speicherdauern gelten standardmäßig, da sie auf Verarbeitungsebene angepasst werden können (siehe unten).

Sie können eine Dauer für die aktive Datenbank, für das Zwischenarchiv oder eine Löschregel hinzufügen.

Die aktive Datenbank ist die laufende Datenbank der Verarbeitung. Das Zwischenarchiv ist eine eingeschränktere Form der Aufbewahrung. Das Feld "Löschung" ermöglicht es Ihnen, die Bedingungen für die Löschung der Daten oder ihre Übermittlung zur endgültigen Archivierung zu beschreiben.

## Aufbewahrung der Daten

Die begrenzte Aufbewahrung der Daten gehört zu den allgemeinen Grundsätzen des Datenschutzrechts und wird in [**Artikel 5 Abs. 1 Buchst. e) der DSGVO**](https://www.cnil.fr/fr/reglement-europeen-protection-donnees/chapitre2) bekräftigt. Dieser sieht vor, dass Daten "_in einer Form gespeichert werden, die die Identifizierung der betroffenen Personen nur so lange ermöglicht, wie es für die Zwecke, für die sie verarbeitet werden, erforderlich ist_".

Konkret bedeutet dies, dass bei der Durchführung einer Datenverarbeitung an deren Zukunft gedacht werden muss, wenn der Verarbeitungszweck erfüllt ist. Die Daten müssen entweder endgültig vernichtet, anonymisiert oder für einen neuen kompatiblen Verarbeitungszweck verarbeitet werden.&#x20;

Die Speicherdauer hängt vom Verarbeitungszweck und der Art der Daten ab. Die Speicherdauern können nach Datentypen definiert werden. Zum Beispiel werden bei der Gehaltsabrechnung die Daten zur Gehaltsabrechnung 1 Monat in der aktiven Datenbank und 5 Jahre im Zwischenarchiv aufbewahrt, während die Daten zum Zahlungsauftrag nur so lange in der aktiven Datenbank aufbewahrt werden, wie es für die Erstellung der Gehaltsabrechnung erforderlich ist, und 10 Jahre ab Abschluss im Zwischenarchiv.&#x20;

Die Dauer kann als Wert angegeben werden oder, falls dies nicht möglich ist, als Kriterien zur Bestimmung der Aufbewahrungsfrist (z. B. bis zur Abmeldung). Es wird empfohlen, insbesondere von der CNIL in ihrer [**Empfehlung vom 11. Oktober 2005 zur elektronischen Archivierung im privaten Sektor**](https://www.legifrance.gouv.fr/affichCnil.do?id=CNILTEXT000017651957), Verfahren einzurichten, die die Verwaltung der Speicherdauern auf Ebene der Datenkategorie ermöglichen und insbesondere die Löschung oder Vernichtung von Daten verwalten.

#### Aufbewahrungsregeln eines Datensatzes anpassen

Die Datenfelder eines generischen Datensatzes können nicht von einer Verarbeitung zur anderen variieren. Die Speicherdauer kann jedoch unterschiedlich sein. Es ist nämlich möglich, die Speicherdauer eines Datensatzes je nach Verarbeitung anzupassen. Somit wird die Speicherdauer des Datensatzes nicht mehr berücksichtigt.&#x20;

Dazu muss der Datensatz der Verarbeitung hinzugefügt werden. In der Liste der Datensätze klicken Sie auf die Schaltflächen "Aktive Datenbank/...".

<figure><img src="../../../.gitbook/assets/image (4) (1) (5).png" alt=""><figcaption><p>Schaltfläche "Aktive Datenbank"</p></figcaption></figure>

Sie sehen dann das Anpassungsfenster.&#x20;

<figure><img src="../../../.gitbook/assets/image (11) (4).png" alt=""><figcaption><p>Fenster zur Anpassung der Speicherdauern</p></figcaption></figure>

Wenn die Speicherdauer auf Verarbeitungsebene angepasst wurde, erscheint ein kleines Stiftsymbol auf der betreffenden Schaltfläche:&#x20;

Das langfristige Ziel kann sein, die Verwendung generischer Datensätze zu reduzieren und sich einer präziseren Kartierung zuzuwenden, entweder über die Datenverarbeitungen (Fall Nr. 2) oder über die Assets (Fall Nr. 1).

<figure><img src="../../../.gitbook/assets/image (1) (1) (1) (2) (4).png" alt=""><figcaption><p>Auf Verarbeitungsebene angepasste Speicherdauer</p></figcaption></figure>

####

##

<br>
