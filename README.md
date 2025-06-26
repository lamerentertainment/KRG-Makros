# "KRG (Kriminalgericht) Makros": Übersicht und Funktionsumfang

## Ausgangslage/Problemstellung

Mit der zunehmenden Digitalisierung liegen immer mehr Verfahrensdokumente digital vor oder können innert nützlicher Frist digitalisiert werden. Aktueller "state of the art" zur Wiedergabe elektronischer Verfahrensakten ist das PDF-Format. Wünschenswert wäre, wenn man mit dem Textinhalt eines PDF-Dokuments – etwa zur Erstellung eines Urteilsentwurfs – in einem Textverarbeitungsprogramm sofort weiterarbeiten könnte. Leider gestaltet sich die diesbezügliche Übertragung einer PDF-Textstelle in eine Word-Textstelle oft mühevoll, wie nachfolgendes Beispiel zeigt:

![image](https://github.com/user-attachments/assets/f904e5c3-6554-440e-9c93-182e598e78ce)

Wird die folgende Textstelle in einem PDF-Programm – etwa mit dem Tastenkürzel ctrl+C – kopiert und in einem Word Dokument (Tastenkombination: ctrl+V) eingefügt, könnte der eingefügte Text etwa so aussehen:

![image](https://github.com/user-attachments/assets/c4cf1e59-da09-4b84-8770-3db0e1667a1f)

Dieser Text muss – soll er in ein akzeptables Format gebracht werden – weiterverarbeitet werden, es müssen alle Zeilenschaltungen händisch entfernt werden. Zudem müssen die Worttrennungen (Kartof-fel, neh-men) entfernt werden. Zuletzt muss das kleingeschriebene L beim Wort "lch" mit einem grossgeschriebenen I ausgetauscht werden. Dies bedeutet im Ergebnis, dass zur Einfügung dieses Textabschnitts mind. neun weitere Bearbeitungsschritte erforderlich sind.

## Hilfestellung durch KRG Makros

Um erforderlichen Arbeitsschritte der Einfügung eines aus einem PDF-Dokument kopierten Textabschnitts zu verringern, stellen die KRG Makros zwei Hilfestellungen zur Verfügung. Diese Hilfestellungen können in Word beispielsweise wie folgt als Buttons eingebunden werden.

![image](https://github.com/user-attachments/assets/d42f692f-2ba3-47c4-a53d-fb4dc49e0e64)

## Makro "Text aus PDF einfügen" (PDFTextEinfuegen)

![image](https://github.com/user-attachments/assets/b115da65-1361-4045-889e-78d9357d5a5e)

Das Makro "Text aus PDF einfügen" setzt – bei einem Klick auf den Button – einen zuvor im PDF-Dokument kopierten, nun in der sog. Zwischenablage befindlichen, Textabschnitt an der Stelle ein, wo der Cursor gesetzt ist. Dabei werden die zuvor beschriebenen Arbeitsschritte – Zeilenumschaltungen löschen, Worttrennungen löschen, fehlerhafte Erkennung des I als L im Wort "Ich" – automatisch ausgeführt. Über diese Arbeitsschritte muss man sich keine Gedanken mehr machen, sondern den Text nur noch auf Fehler überprüfen, die ansonsten bei Textkonversionen aus PDF-Dokumenten regelmässig entstehen können (in vorliegendem Beispiel wurde bspw. das S in "es" als grossgeschrieben erkannt).

![image](https://github.com/user-attachments/assets/f10a5c81-90dc-4028-986d-b0315bb5f2c6)

## Makro "als Aussage von Mann/Frau einfügen" (AussageMannEinfuegen/AussageFrauEinfuegen)

![image](https://github.com/user-attachments/assets/f4fc19e3-c534-4ee1-8a4a-0bb42608b02e)

Die Makros/Buttons "als Aussage von Mann einfügen"/"als Aussage von Frau einfügen" können verwendet werden, wenn es darum geht, die Angabe/Aussage einer Drittperson wiederzugeben (etwa die Wiedergabe von Aussagen anlässlich von Einvernahmen oder die Geltendmachung eines Rechtsstandpunkts einer Verfahrenspartei). Diese Makros führen – zusätzlich zu den oben beschriebenen Funktionen (PDFTextEinfuegen) – weitere Anpassungen an dem in der Zwischenablage befindlichen Text durch, bevor er eingefügt wird. 

-	Einerseits erfolgt die Umstellung von der ersten in die dritte Person, 
-	anderseits werden die Verben in die Konjunktivform umgestellt 

So wird bspw. der Satz "Ich bin unschuldig" in "Er sei unschuldig" konvertiert.

Dabei – wie das nachfolgend angeführte Beispiel zeigt – ist zu beachten, dass diese Anpassungen nur mit einer "hart codierten" Liste von vielfach verwendeten Verben vorgenommen werden. Der eingefügte Text bedarf in jedem Fall noch der Kontrolle und (meistens auch) Überarbeitung.

![image](https://github.com/user-attachments/assets/beabaca7-fbdc-4b6e-ac69-c29d2be0a7f1)

## weitere Funktionalitäten

nebst den zuvor angesprochenen Funktionen, für welche die KRG Makros ursprünglich entwickelt worden sind, sind im Laufe der Zeit weitere hinzugekommen:

![image](https://github.com/user-attachments/assets/7ee3f226-8b57-4e29-a1b1-693208470c87)

Diese Makros dienen dem schnellen Nachschlagen von Gesetzesartikeln des Bundes und Bundesgerichtsentscheiden. Sie funktionieren so, dass man in einem Text eine entsprechende Gesetzesangabe (mitsamt der Abkürzung "Art. " und der Abkürzung des Erlasses) markiert 

![image](https://github.com/user-attachments/assets/30fca8f4-dbd3-4c0e-875b-a84045ed2868)

und dann den entsprechenden Button bzw. das Makro aktiviert. Dann sollte sich der Browser bei der fraglichen Gesetzesbestimmung öffnen:

![image](https://github.com/user-attachments/assets/cfd5493a-b955-4313-b46a-200bba5f5d7c)

Dieselbe Funktionalität besteht für das schnelle Aufrufen von Bundesgerichtsentscheiden auf der Website bger.li, indem man die Fall-Nummer des Entscheids markiert und den entsprechenden Button drückt:

![image](https://github.com/user-attachments/assets/809fc82a-af14-428b-aa8e-7eee736e1083)

![image](https://github.com/user-attachments/assets/49690f61-02a1-4dd3-8a0c-5b504965cfa3)

