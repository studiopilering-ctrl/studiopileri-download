# studiopileri — Download per Windows

Applicazione GIS con strumenti CAD e Marine Engineering Studio. Questa repository distribuisce istruzioni e pacchetti compilati; non contiene il repository sorgente, progetti o archivi dello studio.

## Download

Aprire la [pagina delle release](https://github.com/studiopilering-ctrl/studiopileri-download/releases/latest) e scaricare **studiopileri-0.8.6-Setup-Windows.exe** per la prima installazione. Il download è pubblico e non richiede un account GitHub.

## Installazione consigliata

1. Chiudere le altre finestre di studiopileri.
2. Eseguire l’installer EXE della release.
3. Aprire studiopileri dal Desktop o dal menu Start.

L’installer controlla WebView2 e .NET Framework 4.8 e, se mancanti, avvia i programmi ufficiali Microsoft inclusi. Per scaricare questi componenti serve Internet; per .NET possono servire il consenso amministratore e il riavvio. Python, le librerie GIS/PROJ e le DLL Visual C++ richieste sono incluse.

Windows 10/11 a 64 bit. Internet serve per cartografie e dati online. Per una copia portatile si può usare lo ZIP, estraendo tutta la cartella `studiopileri` e mantenendo `_internal` accanto all’EXE; lo ZIP non installa i prerequisiti.

I dati sono separati dal programma, in `%LOCALAPPDATA%\\studiopileri`. Il pulsante Aggiornamenti continua a installare le nuove versioni tramite il canale firmato GitHub.

I progetti rimangono nell’archivio locale del singolo PC. Questa versione non comprende condivisione multiutente o sincronizzazione fra computer.

## Versione 0.8.6

Novità: misura visibile durante il disegno; coordinate dei vertici in TXT/CSV/JSON; rotazione del pontile e delle singole barche trascinando la maniglia sulla mappa; immagini personali come livelli georeferenziati (GeoTIFF oppure JPG/PNG con world file e CRS), con visibilità e opacità salvate.

Mappa con livelli ufficiali e opacità; esportazione georeferenziata per AutoCAD; rilievi XYZ; Marine sulla stessa mappa, batimetrie EMODnet e rilievi dello studio, layout preliminari, profili del fondale e salvataggio delle soluzioni.

Analisi e strumenti marittimi preliminari: consultare fonti, metadati e verifiche mancanti. Le batimetrie pubbliche non sostituiscono rilievi adeguati e non sono per navigazione. Compatibilità nella specifica versione AutoCAD da collaudare.

Licenze e attribuzioni dei componenti di terze parti sono incluse nel pacchetto.
