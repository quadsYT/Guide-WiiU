# Mocha - Indexiine

## Preparazione Della SD {docsify-ignore}

Ora inseriremo i file CFW richiesti e alcuni altri file homebrew sulla scheda SD.

?> **Nota Bene** La tua SD dovrà essere formattata in FAT32. Se la tua SD non è formattata in FAT32 usa [GUIFormat](http://ridgecrop.co.uk/index.htm?guiformat.htm) con 32k (32768) di Unità di allocazione per formattarla. **Non** chiamare la SD come `wiiu` o causerà problemi con homebrew.

### Cosa ti servirà {docsify-ignore}

- Il Mocha <a href="docs/files/config.ini" download>config</a>.
- La versione più recente dell' [Homebrew Launcher Installer](https://github.com/wiiu-env/homebrew_launcher_installer/releases/latest).
  - Dovrai scaricare il file `payload.zip`.
- La versione 1.4 dell' [Homebrew Launcher](https://github.com/dimok789/homebrew_launcher/releases/tag/1.4).
  - Dovrai installare la versione 1.4 di `homebrew_launcher.v1.4.zip`.
- La versione più recente di [WUP Installer GX2](https://wiiubru.com/appstore/zips/wup_installer_gx2.zip).
- La versione più recente di [Wii U NAND Dumper](https://github.com/koolkdev/wiiu-nanddumper/releases/latest).
- La versione più recente dell' [Homebrew App Store](https://github.com/vgmoose/hbas/releases/latest).
  - Dovrai installare il file `wiiu-extracttosd.zip`.
- La versione più recente di [Mocha](https://www.wiiubru.com/appstore/zips/mocha.zip).
- La versione più recente di <a href="docs/files/SaveMii_Mod.zip" download>SaveMii Mod</a>.
- La versione più recente di [Indexiine Installer](https://github.com/GaryOderNichts/indexiine-installer/releases/latest).

### Istruzioni {docsify-ignore}

?> **Nota Bene** I file info.json e manifest.install non servono per la modifica e quindi possono essere eliminati.

1. Inserisci la SD della tua Wii U nel PC.
1. Copia i contenuti di `wup_installer_gx2.zip` nella root della tua scheda SD.
1. Copia i contenuti del file `nanddumper.zip` nella root della tua SD.
1. Copia i contenuti del file `wiiu-extracttosd.zip` nella root della tua SD.
1. Copia i contenuti del file `homebrew_launcher.v.1.4.zip` nella root della tua SD.
1. Copia i contenuti di `mocha.zip` nella root della tua SD.
1. Copia i contenuti di `indexiine-installer.zip` nella root della tua SD.
1. Copia i contenuti del file `savemii_mod.zip` nella root della tua SD.
1. Copia il file `config.ini` nella cartella `/wiiu/apps/mocha` nella tua SD.
1. Copia il `payload.elf` dal `payload.zip` nella cartella `wiiu` nella tua SD.
