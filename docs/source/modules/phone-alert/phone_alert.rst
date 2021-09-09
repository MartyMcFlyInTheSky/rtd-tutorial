SMS- und Telefonalarm
#####################

Wie richte ich einen SMS- / Telefonalarm ein?
*********************************************
 
.. image:: /res/modules/phone_alert/1.png

#. Wählen Sie im RITUNE Menü den Eintrag «Objekte» und lassen Sie sich die Module anzei-gen
#. Scrollen sie in der Modulliste ggf. nach unten um den Eintrag «SMS- und Telefonalarme» zu finden. Klicken sie darauf.
#. Klicken sie auf das «Plus»-Icon in der oberen linken Ecke des Modulfensters. Es erscheint eine Maske zur Konfiguration des Alarms.

.. image:: /res/modules/phone_alert/2.png

4. Titel: Geben sie hier einen passenden Namen für den SMS-/Telefonalarm ein. Damit er-scheint er später in der Liste.
#. Verbundene Alarme: Wählen sie durch einen Klick auf die quadratische Checkbox alle Alarme aus, für die Sie Benachrichtigungen erhalten möchten.
#. Alarmpläne: Hier können Sie einstellen, welche Person nacheinander und in welcher Form benachrichtigt wird.

Alarme auswählen (5)
*************************
Wie kann ich nach einem spezifischen Alarm suchen?
==================================================
RITUNE bietet im Moment noch keine Suchfunktion für die Alarmliste an. Sie können jedoch die in ihrem Browser integrierte Suchfunktion (Ctrl-F) nutzen, um in der Liste der Alarme nach Wörtern oder Wortteilen zu suchen.

Was wenn ich über ALLE Alarme informiert werden möchte?
=======================================================
Dazu markieren Sie unter «Verbundene Alarme» die Checkbox neben «Name». Damit werden alle Alarme ausgewählt.
 
Wie kann ich Einstellen, welche Alarme in der Liste zur Auswahl stehen?
=========================================================================
Das ist nicht möglich aber auch nicht nötig, da immer ALLE verfügbaren Alarme angezeigt werden. Wie ein Alarm instanziert wird lesen sie hier nach.


Auswahl der benachrichtigten Personen (6)
********************************************
Wie erfasse ich eine neue Person die benachrichtigt werden soll?
=================================================================
Klicken Sie auf den «Plus»-Button in der linken oberen Ecke des Kastens «Alarmpläne». Es er-scheint eine neue Zeile in der Liste der Personen, in der Sie Namen und Telefonnummer ein-tragen können sowie die Art der Benachrichtigung und die Benachrichtigungsstufe.

Wie definiere, wer nach wem benachrichtigt wird?
================================================
Im rechten Bereich im Kasten «Alarmpläne» finden sie Spalten mit der Abstufung 1 – 10. Für jede erfasste Person können Sie nun auswählen, welcher Stufe sie zugehörig ist. Der Alarm wird beginnend mit Stufe 1 immer für eine ganze Stufe herausgeschickt, zu der mehrere Per-sonen gehören können. Stufe 2 wird hierbei nach Stufe 1 losgeschickt, Stufe 3 nach Stufe 2 etc…
Bsp: Wenn Alice der Stufe 1 und Bob der Stufe 2 zugeordnet ist, erhält zuerst Alice die Be-nachrichtigung. Quittiert sie nach x Versuchen nicht erhält Bob y Minuten später den Alarm. X und y können sie im Kasten «Regeln» selbst definieren.

Wie stelle ich ein, nach welcher Zeit andere Personen benachrichtigt werden? 
============================================================================
Ein Alarm wird nur dann weitergeschickt, wenn er nach x Versuchen nicht quittiert wird (???). Diese Anzahl und die zeitlichen Abstände der Versuche können Sie im Feld «Anzahl Versuche pro Stufe» und «Verzögerung zwischen Versuchen (Minuten) einstellen. Danach wartet das Sys-tem das unter «Verzögerung zwischen Stufen (Minuten)» eingestellte Zeitintervall ab bevor es die nächsthöhere Stufe benachrichtigt.
Kann ich individuell einstellen, dass für Stufe 3 länger mit der Benachrichtigung gewar-tet wird als für Stufe 2?
Nein, es wird zwischen allen Stufen dasselbe Zeitintervall abgewartet das sie im Kasten «Re-geln» einstellen können.

FAQ
*************
Von welcher Nummer werden die Alarme versandt?
=================================================================
asdfasdf

Kann ich auch per E-Mail benachrichtigt werden?
=================================================================
Über das PhoneAlert Modul zurzeit noch nicht, durch die Funktionen-Konfigurationsmaske kann diese 

Welche Form haben die Telefonalarme?
=================================================================
Die Telefonalarme werden von einer automatisierten Stimme in einem einheitlichen Format vorgetragen.

Wie sieht ein typischer SMS-Alarm aus?
=================================================================
[Bild]
(Erweitert)

Wie kann ich die Nummer einstellen, von der SMS und Telefonanrufe getätigt werden?
==================================================================================
PLIWO
