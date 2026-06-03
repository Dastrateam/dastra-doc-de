---
description: >-
  Erfahren Sie, wie Sie ein Cookie-Einwilligungs-Widget auf Ihrer Website
  einrichten.
---

# Konfigurieren Sie ein Cookie-Einwilligungs-Widget

DASTRA ermöglicht es Ihnen, ein Cookie-Einwilligungs-Widget direkt auf Ihrer Website einzurichten, das den Empfehlungen der CNIL zu Cookies und anderen Trackern entspricht.

## Was beinhaltet das Dastra Cookie-Einwilligungs-Widget&#x20;

Dieses Widget besteht aus mehreren Elementen:

![Ein „Cookie"-Symbol, das unten links auf dem Bildschirm erscheint](<../../../.gitbook/assets/Capture web\_6-5-2022\_93427\_www.dastra.eu.jpeg>)

![Ein ausklappbares Einführungsfenster](<../../../.gitbook/assets/image (42).png>)

![Die Liste der Cookies nach Verarbeitungszweck, die von der Website verwendet werden](<../../../.gitbook/assets/image (40) (1).png>)

## Voraussetzungen&#x20;

Um Ihr Cookie-Einwilligungs-Widget zu implementieren, müssen Sie zuvor **die auf Ihrer Website gesetzten Cookies identifiziert** und **nach Verarbeitungszweck-Kategorien klassifiziert** haben. Das Cookie-Einwilligungsmodul von DASTRA ermöglicht dies in wenigen Klicks.

{% hint style="info" %}
Um die Implementierung des Cookie-Einwilligungs-Widgets zu erleichtern, hat Dastra alle notwendigen Schritte in einem Modul zusammengefasst – von den Voraussetzungen bis zu den Codezeilen.
{% endhint %}

Um die auf Ihrer Website gesetzten Cookies zu scannen, besuchen Sie die folgende Seite:

{% content-ref url="scannez-les-cookies-deposes-sur-votre-site-web.md" %}
[scannez-les-cookies-deposes-sur-votre-site-web.md](scannez-les-cookies-deposes-sur-votre-site-web.md)
{% endcontent-ref %}

Um die Cookies nach Einwilligungskategorien zu klassifizieren, besuchen Sie die folgende Seite:

{% content-ref url="classifiez-les-cookies-par-categories-de-consentement.md" %}
[classifiez-les-cookies-par-categories-de-consentement.md](classifiez-les-cookies-par-categories-de-consentement.md)
{% endcontent-ref %}

## Definieren Sie das Erscheinungsbild Ihres Ziel-Cookie-Einwilligungs-Widgets

Um ein Cookie-Einwilligungs-Widget auf Ihrer Website einzurichten, müssen Sie zur Oberfläche „Erscheinungsbild" des Cookie-Einwilligungsmoduls von DASTRA navigieren. Nachdem Sie Ihr erstes Einwilligungs-Widget erstellt haben, klicken Sie darauf, um eine Seite aufzurufen, auf der Sie verschiedene Funktionen für das Widget finden. Klicken Sie auf „Erscheinungsbild des Widgets".&#x20;

![Oberfläche „Erscheinungsbild" des DASTRA Cookie-Einwilligungsmoduls](<../../../.gitbook/assets/Capture web\_6-5-2022\_93842\_app.dastra.eu.jpeg>)

Von dieser Oberfläche aus können Sie **Ihr Widget vollständig anpassen**, damit es auf Ihrer Website so angezeigt wird, wie Sie es wünschen.&#x20;

{% hint style="info" %}
Sie können auch weitere allgemeine Änderungen am Widget in den Bereichen „Konfiguration", „Texte und Übersetzungen" und „Auslöser" vornehmen.
{% endhint %}

Wenn die Konfiguration abgeschlossen ist, klicken Sie auf „Veröffentlichen". Sie können auch eine Vorschau des Endergebnisses auf Ihrer Website anzeigen, indem Sie auf „Vorschau" klicken.&#x20;

![](<../../../.gitbook/assets/Capture web\_6-5-2022\_94118\_app.dastra.eu.jpeg>)

## Fügen Sie den Widget-Code auf Ihrer Website ein

Sobald Ihr Ziel-Cookie-Einwilligungs-Widget definiert ist, können Sie es dank der **automatisch von DASTRA generierten Codezeilen** direkt auf Ihrer Website integrieren.\
\
Navigieren Sie dazu zum Tab „Installation", nachdem Sie Ihr Widget im Menü des Cookie-Moduls ausgewählt haben, und fügen Sie den automatisch generierten Code vor dem Ende des HTML-Tags \<body> Ihrer Website ein.

![HTML-Code-Generierung des Widgets](<../../../.gitbook/assets/image (58).png>)

{% hint style="info" %}
Sie können den Google Tag Manager verwenden, um diesen Code dynamisch auf jeder Seite einzufügen.
{% endhint %}

Zögern Sie nicht, Ihren Webmaster für diesen Schritt hinzuzuziehen. Sobald dieser durchgeführt ist, erscheint ein Widget auf Ihrem Bildschirm.

{% hint style="info" %}
Aus Sicherheitsgründen können nur Websites mit einem SSL-Zertifikat vom Typ „https" ein Widget einrichten. &#x20;
{% endhint %}
