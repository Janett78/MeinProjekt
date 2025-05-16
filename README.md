Dokumentation: MeinProjekt
1. GitHub Repository einrichten
    Ich habe mich bei Git Hub angemeldet und ein neues Repository erstellt, mit dem Namen MeinProjekt.
        ![Anmeldung bei GitHub](bilder/1.AnmeldungGitHub.jpg)
        ![Erstellung Repository](bilder/2.ErstellenRepository.jpg)
        ![Erstellung Repository](bilder/3.RepositoryErstellt.jpg)

2. Prüfung SSH-Schlüssel und Erstellung
    Ich habe geprüft ob bereits ein SSH-Schlüssel vorhanden ist oder erstellt werden muss. Da keiner vorhanden war habe ich diesen erstellt.
        ![Prüfung SSH-Schlüssel](bilder/4.PrüfungSSH-Schlüssel.jpg)
        ![Erstellung SSH-Schlüssel](bilder/5.ErstellungSSH-Schlüssel.jpg)

3. Klonen des Repositorys, konfigurieren von Git, erstellen von initialem Commit
    Ich habe das Repository geklont, git mit meinem Namen und meiner Mailadresse konfiguriert und einen initialen commit erstellt.
        ![erster Klonen-Versuch](bilder/6.ersterVersuchZuKlonen.jpg)
        ![Verbindung mit GitHub (SSH)](bilder/7.VerbindungSSHmitGitHub.jpg)
        ![projekt geklont](bilder/8.ProjektKlonen.jpg)
        ![Konfig git](bilder/9.konfigurationGit.jpg)
        ![initialer Commit](bilder/10.InitialerCommit.jpg)

4. Branch feature erstellen, neue Datei und commit
    Ich habe einen neuen Branch mit dem Namen feature erstellt, in diesem einen neuen Unterordner utils mit der Datei database.py darin und davon wurde dann ein commit erstellt. Dann wurde die eine Änderung in der Hauptdatei main.py vorgenommen und diese commited.
        ![Erstellung Branch feature](bilder/11.BranchFeatureErstellen.jpg)
        ![Unterordner mit Datei und Commit](bilder/12.punkt14-neueDatei+commit.jpg)
        ![Änderung in main.py](bilder/13.Punkt15-ÄnderungHauptdatei+commit.jpg)

5. Schritte zum Merge des feature- Branches in den main- Branch
    Zuerst wechselte ich wieder in den main-branch, dort wurde dann die Hauptdatei main.py noch einmal bearbeitet und danach ein commit durchgeführt. Nun wurde ein merge des feature-Branch in den main- Branch versucht der zum Konflikt führte.
        ![Wechsel in main-Branch](bilder/14.Punkt16-wechselZumMain.jpg)
        ![Bearbeitung main und commit](bilder/15.Punkt17-mainBearbeitet+commit.jpg)
        ![Merge-Versuch von feature in main](bilder/16.Punkt18-mergeVersuch.jpg)
        ![Konflikt](bilder/17.KonfliktInMain.py.jpg)