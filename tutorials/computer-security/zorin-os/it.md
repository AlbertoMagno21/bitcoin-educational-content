---
name: Zorin OS
description: Guida completa per installare e utilizzare Zorin OS come alternativa moderna a Windows
---

![cover](assets/cover.webp)

## Introduzione

Un sistema operativo (OS) è il software fondamentale che permette a un computer di operare: gestisce hardware, software, sicurezza e interfaccia utente.
Zorin OS è una distribuzione Linux progettata specificamente per facilitare la transizione da Windows, offrendo tutti i vantaggi del software libero: sicurezza, stabilità, privacy e prestazioni.

Basato su Ubuntu LTS, Zorin OS combina alta compatibilità software con un'interfaccia familiare e personalizzabile, rendendolo un'alternativa credibile e accessibile a Windows.

## Perchè Zorin OS ?

- **Interfaccia familiare**: aspetto simile a Windows (menu di avvio, barra delle applicazioni);
- **Transizione facilitata**: pensato per gli utenti provenienti da Windows;
- **Sicurezza rinforzata**: architettura Linux, meno esposizione ai virus;
- **Rispetto della privacy**: nessuna raccolta dati invadente;
- **Performance ottimizate**: funziona correttamente su macchine modeste;
- **Basato su Ubuntu LTS**: stabile, aggiornamenti regolari e ampia compatibilità;
- **Personalizzazione avanzata**: tramite lo strumento Zorin Appearance.

## Installazione e configurazione

### 1. Prerequisiti

**Configurazione necessarie**:

- Una chiave USB da almeno **8 GB** (12 GB raccommandati);
- Un computer con almeno **25 GB di spazio diponibile nel disco fisso**;
- Una connessione a Internet (reccommandato).

### 2. Scaricare Zorin OS

- Visita il sito ufficiale: [https://zorin.com/os](https://zorin.com/os)

![Page de téléchargement Balena Etcher](assets/fr/03.webp)

- Scegli **Zorin OS Core** (versione gratuita raccomandata)

![Page de téléchargement Balena Etcher](assets/fr/04.webp)

- Scarica l’immagine ISO

Zorin OS propone anche:
- **Zorin OS Lite** (computer vecchi)
- **Zorin OS Pro** (a pagamento, con accordi avanzati e supporto)

## Creazione di una chiave USB avviabile

È possibile utilizzare diversi strumenti, per esempio Balena Etcher:
- Scarica [Balena Etcher](https://etcher.balena.io/) e installala.
- Apri Balena Etcher, poi seleziona l'immagine ISO di Zorin.
- Seleziona la chiave USB come supporto di destinazione.
- Clicca su Flash e attendi la fine del processo.

![Utilisation de Balena Etcher](assets/fr/05.webp)

## Avviare la chiave e accesso al BIOS

Spegnere il computer su cui si desidera installare Zorin OS e quindi collegare l'unità USB.
All'avvio del tuo computer accedi al BIOS (`ESC`, `F9` o `F11` secondo la marca) e seleziona allora la chiave USB come periferica di avvio quindi premi il tasto `Avvio` per lanciare l'inizializzazione.

- All'avvio, selezionare **prova o Installa Zorin OS**.

![capture](assets/fr/08.webp)

- Se hai una scheda grafica NVIDIA, seleziona **Prova o Installa Zorin OS (NVIDIA drivers aggiornati)**.
- Attendi durante il controllo dei file.

![capture](assets/fr/09.webp)

- Nel programma di installazione di Zorin OS, seleziona il linguaggio **Italiano** poi clicca su Installa **Zorin OS**.

![capture](assets/fr/10.webp)

- Seleziona il layout della tastiera.

![capture](assets/fr/11.webp)

- Verifica le caselle **Seleziona aggiornamenti durante l'installazione Zorin OS** e **Installa un software di terze parti per grafica e hardware Wi-Fi e formati multimediali aggiuntivi**.

![capture](assets/fr/12.webp)

- Per installare Zorin OS sull'intero disco: seleziona **Cancella disco e installa Zorin OS**.

![capture](assets/fr/14.webp)

Per installare Zorin OS a fianco di Windows (dual-boot):

- Seleziona **Installa Zorin OS a fianco di Windows Boot Manager**.

![capture](assets/fr/15.webp)

- Si non hai partizioni sul tuo disco, scegli lo spazio del disco da allocare a Zorin OS poi clicca su **Installa ora**.

![capture](assets/fr/16.webp)

- Conferma due volte le modifiche sul disco.

![capture](assets/fr/16.webp)

![capture](assets/fr/17.webp)

- Seleziona la zona geografica **Roma**.

![capture](assets/fr/18.webp)

- Crea il tuo account utente e nomina il tuo computer.

![capture](assets/fr/19.webp)

- Pazienta durante l'installazione a Zorin OS.

![capture](assets/fr/20.webp)

- Una volta che l'installazione è terminata, clicca su **Riavvia ora**.

![capture](assets/fr/21.webp)

- Scollega la chiave USB d'installazione e clicca su Avvio.

![capture](assets/fr/22.webp)

## Scoprire e utilizzare Zorin OS

### Primo avvio

All'avvio del computer, si aprirà GRUB – il gestionale di avvio di Linux. Per défaut, **Zorin OS** è selezionato; dopo circa 30 secondi, si avvierà automaticamente.

![capture](assets/fr/23.webp)

Se hai installato Zorin OS in dual-boot con Windows, puoi avviare Windows selezionando **Windows Boot Manager**.

Connettiti con il tuo account utente:

![capture](assets/fr/24.webp)

Al primo avvio, l’applicazione **Benvenuto su Zorin OS**, se lanciata, ti aiuta a scoprire il tuo nuovo sistema operativo.

![capture](assets/fr/25.webp) 

![capture](assets/fr/26.webp)

![capture](assets/fr/27.webp)

![capture](assets/fr/28.webp)

![capture](assets/fr/29.webp)

![capture](assets/fr/30.webp)

![capture](assets/fr/31.webp)

![capture](assets/fr/32.webp)

### Aggiornare il sistema

In breve, il gestore dell'aggiornamento si aprirà per avvisarti che gli aggiornamenti sono disponibili. Installali cliccando sul pulsante **Installa ora**.

![capture](assets/fr/33.webp)

Puoi verificare manualmente se ci sono aggiornamenti disponibili nell’applicazione **Software** > Aggiorna:

![capture](assets/fr/34.webp)

### Personalizazzione

La prima scelta da fare su Zorin OS è quella di scegliere la **disposizione del desktop** più confortevole. Troverai disposizioni simili a quelle presenti su Windows (e ancora di più con la versione Pro).

Per questo, aperto **Zorin Appareance** > **Tipo**:

![capture](assets/fr/35.webp)  

Quindi apri **Impostazioni** per personalizzare il sistema:
**Suono – Parametri – Zorin OS**

![capture](assets/fr/36.webp)

**Account online – Impostazioni – Zorin OS**

![capture](assets/fr/37.webp)

### Applicazioni

Per installare le applicazioni, hai molteplici possibilità:

- **Software**, nello Zorin OS App Store. Le applicazioni provengono da diverse fonti: Apt, Flatpak e Snap.  

![capture](assets/fr/38.webp)

![capture](assets/fr/39.webp)

- **apt** installazioni (linea di comando):
  
```bash
sudo apt install gparted
```

![capture](assets/fr/40.webp)

Per altre informazioni sull'applicazione di installazione su Zorin OS, consulta questa pagina: [Installa Apps (Zorin.com)](https://zorin.com/help/install-apps/).

### Applicazioni Windows

Per installare le applicazioni Windows, avviare installando il pacchetto **zorin-windows-app-support** via Terminal :

```bash
sudo apt install zorin-windows-app-support
```

Per informazioni sulle applicazioni di Windows compatibili e sul loro livello di compatibilità, vedi [Wine Application Database](https://appdb.winehq.org/). Troverai i seguenti distintivi, che corrispondono al livello di compatibilità (dal migliore al peggiore): Platinum, Gold, Silver, Bronze e Garbage.

Per installare un applicazione di Windows con estensione .exe o .msi, hai due opzioni:

- Apri **PlayOnLinux** e clicca sul tasto **Installa** per navigarefra le app e i giochi compatibili.  

![capture](assets/fr/41.webp)

- Doppio clic sui **file .exe ou .msi** dell’applicatione e lasciati guidare dal programma d'installazione.  
  
![capture](assets/fr/42.webp)

![capture](assets/fr/43.webp)

## Conclusione e risorse supplementari

Zorin OS costituisce un'alternativa solida e accessibile a Windows, combinando semplicità, sicurezza e privacy.

Consente una transizione fluida a Linux, senza sacrificare comfort o produttività.

Al fine di andare oltre nella protezione della vita digitale, ti consiglio di utilizzare servizi privacy-friendly, in particolare per la comunicazione crittografata:

https://planb.academy/tutorials/computer-security/communication/proton-mail-c3b010ce-254d-4546-b382-19ab9261c6a2
