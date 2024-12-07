
# HEW-Score: Hirnfunktionsausfall-Eignung-Wille (HEW) - Tool zur DSO Meldeempfehlung

## Beschreibung

Der **HEW-Score** ist ein interaktives Tool, das zur Berechnung der **DSO-Meldeempfehlung** verwendet wird. Basierend auf den Eingabewerten für **IHA (Indikator der Hirnfunktionsausfälle)**, **medizinische Eignung** und **Organspendewille**, gibt dieses Tool eine Empfehlung ab, ob eine Meldung an die **Deutsche Stiftung Organtransplantation (DSO)** erforderlich ist oder nicht.

Die Berechnung basiert auf folgenden Kriterien:
- **IHA** (Indikator für Hirnfunktionsausfall)
- **Medizinische Eignung**
- **Organspendewille**

Das Tool stellt sicher, dass medizinische Fachkräfte schnell eine informierte Entscheidung treffen können, ob ein Patient für die Meldung an die DSO geeignet ist.

## Funktionen

- Auswahl der **IHA** (festgestellt, erwartet/vermutet, nicht feststellbar)
- Eingabe der **medizinischen Eignung** (keine KI, unklar, bekannte KI)
- Auswahl der **Organspendewille** (Zustimmung, ungeklärt, Ablehnung)
- Berechnung des HEW-Scores und Anzeige der entsprechenden DSO-Meldeempfehlung.

Das Ergebnis wird mit einer Empfehlung zur Meldung an die DSO oder ohne Meldung angezeigt.

## Anwendung

1. **Auswahl der Optionen**: 
   - Wähle die Optionen aus, die auf den Patienten zutreffen:
     - IHA
     - Medizinische Eignung
     - Organspendewille

2. **Berechnung**: 
   - Klicke auf den **"Auswertung"**-Button, um den HEW-Score zu berechnen.
   
3. **Ergebnis**: 
   - Das Tool zeigt das Ergebnis und eine Empfehlung an, ob eine Meldung an die DSO erforderlich ist.

4. **DSO Spenderhotline**: 
   - Du kannst die **DSO Spenderhotline** durch Klicken auf den Button erreichen.

## Wie man das Tool nutzt

1. **Klonen oder herunterladen**:
   - Du kannst das Repository klonen oder die Dateien direkt herunterladen, um sie lokal auszuführen:
     ```bash
     git clone https://github.com/dein-benutzername/HEW-Score.git
     ```
   
2. **Öffnen der Datei**:
   - Öffne die `index.html` in deinem Browser, um das Tool zu verwenden.

3. **Interaktive Nutzung**:
   - Wähle die entsprechenden Optionen aus und klicke auf den "Auswertung"-Button, um das Ergebnis zu sehen.

## Technologie

- **HTML**: Struktur und Inhalt des Tools
- **CSS**: Stil und Layout der Benutzeroberfläche
- **JavaScript**: Berechnungslogik und Interaktivität
- **Flexbox**: Für responsives Design

## Mitwirkende

Dieses Projekt wurde entwickelt von:

- **F. Lehmann**
- **S.F. Ehrentraut**
- **J. Weller**

Weitere Informationen zum medizinischen Hintergrund des HEW-Tools finden Sie in der [Medizinischen Klinik - Intensivmedizin und Notfallmedizin 2024](https://link.springer.com/article/10.1007/s00063-024-xxxxx-x).

## Lizenz und Namensnennung

Dieses Projekt ist unter der [MIT License](LICENSE) lizenziert. Bitte beachten Sie, dass bei Verwendung des Codes oder Weiterentwicklung des Codes die ursprünglichen Autoren genannt werden müssen. 


### Namensnennung (Attribution)

Bei der Nutzung oder Weiterentwicklung dieses Codes ist es erforderlich, die ursprünglichen Autoren zu nennen. Bitte verwenden Sie dafür folgenden Hinweis:

> Dieses Projekt basiert auf dem Originalcode von F. Lehmann, S.F. Ehrentraut und J. Weller/Universitätsklinikum Bonn, verfügbar unter [https://stefanehrentraut.github.io/HEW-Score/].

---

### Hinweise zur Verwendung:

- Stelle sicher, dass dein Browser JavaScript unterstützt und aktiviert ist.
- Die **DSO Spenderhotline**-Funktion ist mit einem Link zu einer externen Webseite verbunden.

---

**Hinweis:** Falls du vorhast, das Tool weiter zu entwickeln oder zu verbessern, kannst du Forks des Repositories erstellen und Pull Requests einreichen. So kannst du auch zum Projekt beitragen.

---
