# micdrop — installers

micdrop is a real-time karaoke queue for bars: guests scan a QR code, pick a song on their
phone and join the queue; the DJ runs the evening from a console; a public screen shows who
sings now and who is next.

This repository only hosts the Windows installers and the files the app uses to update
itself. Download the latest `micdrop-Setup-<version>.exe` from the **Releases** page.

Installing: run the setup (one click). Windows SmartScreen may warn because the installer is
not code-signed: choose "Informations complémentaires" then "Exécuter quand même". The app
then opens its settings window: paste the activation code you received, choose a DJ PIN,
"Enregistrer et démarrer".

Updates are automatic: installed apps check this repository at every start.
