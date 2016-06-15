LyX Installation unter Windows
______________________________________________________________________________


1. MiKTex herunterladen + installieren
   http://miktex.org/download

2. Unter "Programme -> MiKTex -> Maintenance (Admin)" den "Paket Manager" 
   ausführen, dort unter "Name:" nach "koma-script" suchen und installieren
   (unter Linux die Pakete: "texlive-collection-publishers" zzgl. der
   "texlive-collection**recommended", "textlive-collection-langgerman")

3. LyX 2.1.0 Windows Installer runterladen + installieren
   http://www.lyx.org/WebDe.Download#toc3
   -> dabei wird nach einem Update von MiKTex gefragt - bitte ausführen

4. LyX start und unter "Werkzeuge" die Funktion "Neu konfigurieren" ausführen
   -> es werden die aktualisierten MiKTex Pakete neu eingelesen

5. LyX ist bereit zum Arbeiten
   -> in LyX unter "Hilfe -> LaTeX-Konfiguration" sollte bei "Koma-Script"
      nun "scrlttr2: ja" stehen, ist dort ein "nein" eingetragen,
      im MiKTex "Maintenance -> Settings" auf "Refresh FNDB" und
      "Update Formats" gehen, danach wieder mit Schritt 4. beginnen


WICHTIG:    Alle Bilder und sonstigen ins Dokument eingefügten Dateien
            müssen zwingend mit im Dokument-Verzeichnis abgelegt werden,
            da LyX stets nur Verweise auf die Dateien enthält.
            Daher: Für jedes LyX-Dokument ein eigenes Verzeichnis anlegen und
            dort alle zugehörigen Dateien ablegen.
              
TIPP:  Zentrierte + autom. skalierte Grafiken
        -> "Abbildungs-Gleitobjekt" einfügen (Bild im Rahmen Symbol)
        -> Grafik einfügen (Bild-Symbol) 
        -> im Grafik Dialog "Breite" auf "95" Einheit auf "Textbreite %" setzen
        -> Absatz-Einstellungen (P-Symbol) auf "Absatz-Einrücken" = nein und "zentriert"

       Absätze mit dicker Schrift, ohne Nummerierung
       -> Absatzformat "Unterunterabschn.*" wählen - "*" steht für nicht nummeriert
       
______________________________________________________________________________
    Christian Dähn, Schwerin 2014