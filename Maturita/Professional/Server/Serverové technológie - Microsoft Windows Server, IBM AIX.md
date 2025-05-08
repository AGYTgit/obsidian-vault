
---

**Otázka č. 1: Microsoft Windows Server**

- **Vysvetlite metódy a typy inštalácie Microsoft Windows Servera**
    
    - **Inštalačné metódy:** Interaktívna (GUI), bezobslužná (automatizovaná), inovácia, čistá inštalácia, Server Core (bez GUI), inštalácia z VHD.
        
    - **Typy inštalácie:** Úplná (s GUI) a Server Core (bez GUI).
        
- **Definujte serverové roly, ich služby a funkcie**
    
    Serverové roly poskytujú špecifické služby a funkcie. Príklady:
    
    - **AD DS:** Adresárové služby, autentifikácia, autorizácia. Funkcie: správa kont, jednotné prihlásenie, bezpečnostné politiky, DNS.
        
    - **DHCP:** Automatické prideľovanie IP adries.
        
    - **DNS:** Preklad názvov na IP adresy.
        
    - **File Server:** Zdieľanie súborov.
        
    - **IIS:** Webhosting.
        
    - **Hyper-V:** Virtualizácia.
        
- **Opíšte inštaláciu roly servera a jej následnú modifikáciu**
    
    - **Inštalácia:** Cez Správcu servera (GUI) alebo PowerShell (Install-WindowsFeature).
        
    - **Modifikácia:** Pridávanie/odstraňovanie služieb rolí a funkcií, konfigurácia nastavení (cez Správcu servera alebo PowerShell).
        

---

**Otázka č. 2: IBM AIX a Oracle Solaris**

- **Opíšte základné vlastnosti operačného systému IBM AIX, jeho virtualizáciu**
    
    AIX: spoľahlivosť, škálovateľnosť, bezpečnosť, štandardy UNIX, JFS2. Virtualizácia: PowerVM (hardvérová a OS virtualizácia, virtuálny I/O), Micro-Partitioning.
    
- **Opíšte základné vlastnosti a časti operačného systému Oracle Solaris**
    
    Solaris: škálovateľnosť, pokročilé siete, ZFS, DTrace. Časti: jadro, shell, ZFS, sieťový zásobník, SMF.
    
- **Opíšte typy inštalácií operačného systému Oracle Solaris**
    
    Interaktívna, automatizovaná (JumpStart), z Live média, sieťová.
    

---

**Otázka č. 3: Práca s príkazovým riadkom v unixovom operačnom systéme**

Pre túto časť poskytnem príklady použitia Bash, štandardného shellu pre mnohé unixové systémy, vrátane Linuxu.

- **Preveďte prácu s príkazovým riadkom v unixovom operačnom systéme - prehliadanie adresárovej hierarchie, vypisovanie obsahu súborov**
    
    `pwd` (aktuálny adresár)
    `ls` (obsah adresára)
    `cd` (zmena adresára)
    `tree` (stromová štruktúra adresára)
    `cat` (zobrazenie obsahu súboru)
    `less` (stránkovanie)
    `head` (prvých N riadkov)
    `tail` (posledných N riadkov).
    
- **Preveďte prácu s príkazovým riadkom v unixovom operačnom systéme - vytváranie, kopírovanie, presúvanie, mazanie súborov a adresárov**
    
    `mkdir` (vytvorenie adresára)
    `touch` (vytvorenie prázdneho súboru)
    `cp` (kopírovanie)
    `mv` (presun/premenovanie)
    `rm` (vymazanie súboru)
    `rm -r` (vymazanie adresára)
    `rmdir` (vymazanie prázdneho adresára).
    
- **Preveďte prácu s príkazovým riadkom v unixovom operačnom systéme - základné prístupové práva súborov (rwx) a prístupové zoznamy (ACL)**  

    `r` (čítanie)
    `w` (zápis)
    `x` (spustenie)
    `chmod` (zmena povolení)
    ACL:
    `getfacl` (získanie ACL)
    `setfacl` (nastavenie ACL).