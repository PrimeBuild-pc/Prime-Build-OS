<p align="center">
  <img src="https://github.com/user-attachments/assets/e255e56f-1f11-491b-ae94-7d805c2ee11e" />
" alt="PrimeBuild OS Banner" width="100%">
</p>

<h1 align="center">PrimeBuild OS</h1>
<p align="center">
  <b>Versione:</b> V1.0  
</p>

---

<p align="center">
  <a href="https://discord.gg/jBNk2vXKKd">
    <img src="https://img.shields.io/badge/Join%20our%20Discord-5865F2?style=for-the-badge&logo=discord&logoColor=white" alt="Join our Discord">
  </a>
  <a href="https://www.mediafire.com/file/mlo4xrfhv1k378u/Prime-Build-OS.zip/file">
    <img src="https://img.shields.io/badge/⬇️%20Download%20ISO-MediaFire-00BFFF?style=for-the-badge&logo=firefox&logoColor=white" alt="Download ISO">
  </a>
</p>

---

## 🧭 Panoramica

**PrimeBuild OS** è una versione di **Windows 11 personalizzata e ottimizzata** per offrire prestazioni superiori, reattività immediata e un ambiente di lavoro pulito.  
Progettata per utenti esperti, gamer e installatori che vogliono un sistema operativo pronto, veloce e senza componenti superflue.

### Include:
- Installazione **automatica** tramite `autounattend.xml`  
- **Rimozione del bloatware** e ottimizzazioni già applicate  
- **Utility TweakHub** integrata per tuning e gestione post-installazione  
- Compatibilità completa con UEFI/GPT  

---

## 💿 Installazione

### **PARTE 1 – Preparazione**
1. Scarica la ISO dal link in alto.  
2. Inserisci la tua chiavetta USB nel PC.  
3. Scarica e apri **[AnyBurn](https://anyburn.com/)**.  
4. Seleziona **Create bootable USB drive**.  
5. Imposta come *Image File* il file **ISO di PrimeBuild OS**.  
6. Imposta il *Boot Mode* su `UEFI (GPT FAT32)` e clicca **Next**.  
7. Formatta la chiavetta, attendi la scrittura dei file e verifica che siano comparsi nella directory.  
8. Riavvia il PC.

---

### **PARTE 2 – Installazione**
1. All’accensione, premi ripetutamente **F10** o **F11** per aprire il **Boot Menu**.  
2. Seleziona la chiavetta USB come dispositivo di avvio.  
3. Elimina tutte le partizioni del disco di destinazione → deve risultare come *Spazio non allocato*.  
4. Clicca **Next**: l’installazione inizierà automaticamente.  
5. Dopo circa 5 minuti, Windows sarà installato e ottimizzato.  
6. Riavvia il PC e ripristina eventuali backup personali.

---

## ⚙️ Cosa fare dopo l’installazione

1. **Driver di rete**  
   Se non hai connessione, scarica i driver LAN/Wi-Fi da un altro PC e installali.  

2. **Driver chipset e scheda madre**  
   - [AMD Chipset](https://www.amd.com/en/support)  
   - [Intel Chipset](https://www.intel.com/content/www/us/en/download-center/home.html)  

3. **Driver video**  
   - [NVIDIA Drivers](https://www.nvidia.com/download)  
   - [AMD Radeon Drivers](https://www.amd.com/en/support)  

   💡 Consiglio: per GPU NVIDIA usa [**TechPowerUp NV Clean Install**](https://www.techpowerup.com/download/techpowerup-nvcleanstall/)  
   (è già incluso in TweakHub all’interno della ISO).

4. **Riavvia** il sistema dopo ogni installazione driver.  

5. **Aggiornamenti di sistema**  
   - Apri *Impostazioni → Windows Update* → installa tutti gli aggiornamenti.  
   - Riavvia, quindi ripeti fino a completamento.  

6. **Aggiorna le app Microsoft Store e i pacchetti Winget**
   ```bash
   winget upgrade --all
   ```

7. **Apri TweakHub**
   Dal desktop, estrai e avvia **TweakHub**, l’utility PrimeBuild per installare app, ottimizzare i servizi e gestire tweak aggiuntivi.
   🔗 Repo: [PrimeBuild-pc/TweakHub](https://github.com/PrimeBuild-pc/TweakHub)

---

## 🌐 Community e Supporto

<p align="center">
  <a href="https://discord.gg/jBNk2vXKKd">
    <img src="https://invidget.switchblade.xyz/jBNk2vXKKd" alt="Discord Server Banner">
  </a>
</p>

Unisciti al server **PrimeBuild** per ricevere assistenza, suggerimenti, guide e aggiornamenti sulle future versioni del sistema.

---

## 📦 Risorse utili

* 🔧 [Altre App PrimeBuild](https://github.com/PrimeBuild-pc?tab=repositories)
* 🧩 [NV Clean Install (TechPowerUp)](https://www.techpowerup.com/download/techpowerup-nvcleanstall/)
* 💻 [TweakHub](https://github.com/PrimeBuild-pc/TweakHub)

---

## ⚠️ Disclaimer

Questa ISO è una versione **non ufficiale** di Windows 11 modificata e ottimizzata da PrimeBuild.
L’utilizzo è a tuo rischio e pericolo: assicurati di avere licenze e backup validi.
PrimeBuild non è affiliata con Microsoft Corporation.

---

<p align="center">
  <b>Grazie per aver scelto PrimeBuild OS.</b><br>
  <i>Buona installazione e buon tweaking.</i> 🖥️
</p>
