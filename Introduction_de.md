---
id: SEB_de
title: SEB Allgemein
nav_order: 5
---

## Safe Exam Browser (SEB) 

Der Safe Exam Browser (SEB) ist eine abgesicherte Browser-Applikation, um Onlineprüfungen auf Learning Management Systemen (LMS) zuverlässig durchführen zu können. Durch den Start der SEB-Applikation wird ein herkömmlicher Windows- oder macOS Computer in einen sogenannten Kioskmodus versetzt und somit zu einer temporär abgesicherten Arbeitsstation. SEB regelt den Zugriff auf Hilfsmittel wie Systemfunktionen, andere Websites und Programme und unterbindet die Verwendung von unerlaubten Ressourcen während einer Prüfung.

Der SEB läuft auf einem lokalen Computer und ist über das Internet mit einem Lernmanagementsystem (LMS) oder einem E-Assessment-System, wie OLAT oder Ans verbunden. 

### SEB-Browser Komponenten

Die internen Komponenten des SEB bestehen aus der **Kiosk-Applikation** und dem **Browser**. Hinzu kommt dann die Verknüpfung zur SEB-Prüfungsumgebung in das zum Einsatz kommende **Lernmanagementsystem** (OLAT oder Ans). Die Funktion der verschiedenen Bestandteile wird hier genauer erläutert: 

Die **Kioskapplikation** sperrt den Computer und startet den SEB-Browser sowie optionale Drittanbieteranwendungen. 

Der **SEB-Browser** übernimmt die Kommunikation mit dem Prüfungssystem. Dabei wird die Prüfungsseite über eine voreingestellte URL geladen und angezeigt. Zudem blendet die Browser-Komponente die Nutzung von Navigationselementen wie Adressleiste, Suchmaschinenfeld usw. aus. 

Das **Lernmanagementsystem / E-Assessmenttool (OLAT, Ans)** enthält sogenannte Quizmodule, die für Online-Prüfungen genutzt werden. Somit wird die Benutzeroberfläche des LMS darauf reduziert, nur die Navigation für die Prüfung zu enthalten (keine Links zu anderen Seiten außerhalb des Quiz) und keine anderen unerwünschten Funktionen wie Messaging. 


### Starten des SEB
Wenn Sie SEB starten, werden alle derzeit laufenden Anwendungen ausgeblendet und alle angeschlossenen Bildschirme werden mit einem schwarzen Hintergrund versehen. Auf dem Hauptbildschirm öffnet SEB sein Webbrowser-Fenster, das den gesamten Bildschirm ausfüllt (das Fenster kann dennoch in der Größe verändert und verschoben werden). Dabei SEB öffnet die Webseite unter der voreingestellten Start-URL, was einige Sekunden dauern kann. 

### Beenden des SEB
Um SEB zu beenden, drücken Sie einfach die Beenden-Schaltfläche im SEB-Dock, Cmd-Q oder die rote Schließen-Schaltfläche im Browserfenster. Generell ist das Beenden von SEB in den Einstellungen mit einem Passwort geschützt, welches nur Systemadministratoren herausgeben können. Wenn SEB beendet wird, werden die Anwendungen, die vor dem Start von SEB sichtbar waren, wieder eingeblendet.
