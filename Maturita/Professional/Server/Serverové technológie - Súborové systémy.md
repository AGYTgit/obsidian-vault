
---

**Otázka č. 1:**

- **Opíšte jednotlivé súborové systémy používané v operačných systémoch Microsoft**
    
    - **FAT (File Allocation Table):**
        
        - **FAT16:** Starší systém; max. 2 GB partície.
            
        - **FAT32:** Rozšírenie FAT; max. 2 TB partície; 4GB limit na súbor.
            
        - **exFAT:** Pre flash; väčšie súbory a partície.
            
    - **NTFS (NT File System):**
        
        - Štandardný systém; žurnálovanie, ACL, rozsiahle úložisko, kompresia, šifrovanie.
            
- **Porovnajte systémy súborov FAT a NTFS**
    
    **Funkcia**|**FAT (FAT16, FAT32)**|**NTFS**
    ---|---|---
    Maximálna veľkosť súboru|4 GB (FAT32)|Veľmi veľká
    Maximálna veľkosť partície|2 TB (FAT32)|Veľmi veľká
    Spoľahlivosť|Nízka|Vysoká
    Bezpečnosť|Obmedzená|Robustná
    Výkon|Pomalší|Rýchlejší
    Funkcie|Základné|Pokročilé
    Prípady použitia|Jednoduché úložiská, staršie OS|Moderné Windows, pokročilé úložisko
    
- **Vysvetlite relatívnu a absolútnu cestu k súborom a adresárom**
    
    - **Absolútna cesta:** Úplná cesta od koreňového adresára. (e.g., C:......\file.txt, /home/user/file.txt)
        
    - **Relatívna cesta:** Cesta vzhľadom na aktuálny adresár. (e.g., ./file.txt, ../../file.txt)
        

---

**Otázka č. 2:**

- **Opíšte oprávnenia súborov a priečinkov v Microsoft Windows Server**
    
    Windows používa ACL: ACE určujú povolenia (Čítanie, Zápis, Spustenie, Úplné riadenie, Úprava) pre používateľov/skupiny. Povolenia sa dedia. Nastavenie cez GUI, `icacls`, PowerShell.
    
- **Opíšte správu úložného priestoru a typy diskov v Microsoft Windows Server**
    
    - **Správa diskov:** Nástroj na správu diskov/zväzkov.
        
    - **Úložné priestory:** Virtualizácia; zoskupovanie diskov, odolnosť, vrstvenie.
        
    - **Typy diskov:**
        
        - Základné: MBR/GPT partície.
            
        - Dynamické: Rozložené/pruhované/zrkadlené zväzky.
            
- **Vysvetlite možnosti virtualizácie Hyper-V v Microsoft Windows Server**
    
    Hyper-V: Hypervízor; spustenie viacerých VM. Funkcie: hardvérová virtualizácia, virtuálne disky (VHDX), siete, snímky, živá migrácia, replikácia.
    

---

**Otázka č. 3:**

- **Opíšte funkciu skriptov v unixových operačných systémoch, princípy práce s nimi**
    
    Skripty: Textové súbory s príkazmi pre shell (napr. Bash). Automatizácia úloh, správa systému. Spúšťanie: `chmod +x script.sh ; ./script.sh`.
    
- **Opíšte systémy súborov operačného systému Oracle Solaris - UFS a ZFS**
    
    - **UFS:** Tradičný systém súborov Unixu.
        
    - **ZFS:** Moderný systém; transakčný, copy-on-write, snímky, RAID-Z, dynamické prideľovanie, veľká kapacita.
        
- **Opíšte prácu so záplatami v operačnom systéme Oracle Solaris, princípy, delenie**
    
    Záplaty: Balíky pre opravy/aktualizácie. Príkazy: `patchadd`, `patchrm`. Typy: bezpečnostné, odporúčané, povinné, individuálne, kumulatívne.