# M365-02 · Senden als Funktionspostfach

**Auswirkung** · Eine Person kann ein Funktionspostfach öffnen. Nachrichten mit dem Absender des Postfachs werden abgewiesen.

**Erhebung** · Zeitpunkt, genaue Meldung, gewünschte Absenderadresse und genehmigten Ticketbezug aufnehmen. Test direkt über Outlook im Web wiederholen, um die lokal gespeicherte Absenderauswahl als Ursache einzugrenzen.

**Eingrenzung** · Exchange-Administration prüft die Delegierung des richtigen Postfachs. Full Access erlaubt das Öffnen des Postfachs. Send As erlaubt das Senden unter der Adresse des Postfachs. Im simulierten Verlauf besteht Full Access, während die genehmigte Send-As-Delegierung fehlt.

**Übergabe** · Exchange-Administration mit Genehmigungsreferenz, Postfachkennung, betroffenem Konto und beiden Testergebnissen beauftragen. Nach genehmigter Zuweisung die Verarbeitung abwarten und mit einer neuen Nachricht testen.

**Gegenprobe** · Die Testperson wählt das Funktionspostfach als Absender. Ein interner Testempfänger bestätigt, dass die Nachricht mit der Adresse des Funktionspostfachs im Von-Feld ankommt. Für den Abschluss Zeitpunkt und Genehmigung dokumentieren.

**Ticketnotiz** · „Postfachzugriff bestand bereits. Die Exchange-Administration ergänzte die genehmigte Send-As-Delegierung. Absenderadresse beim Empfänger bestätigt.“
