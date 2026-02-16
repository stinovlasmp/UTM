


    Je možné vynalézt jediný stroj, který lze použít k výpočtu jakékoli vyčíslitelné sekvence.

-- Alan Turing, 1936

UTM je plně funkční emulátor systému a hostitel virtuálních strojů pro iOS a macOS. Je založen na QEMU. Stručně řečeno, umožňuje vám spouštět Windows, Linux a další na vašem Macu, iPhonu a iPadu. Více informací na https://getutm.app/ a https://mac.getutm.app/


<img width="450" height="430" alt="obrazek" src="https://github.com/stinovlasmp/UTM/blob/main/screen.png" />

<img width="450" height="430" alt="obrazek" src="https://github.com/stinovlasmp/UTM/blob/main/screenmac.png" />

## Funkce

* Plná emulace systému (MMU, zařízení atd.) pomocí QEMU
* Podpora více než 30 procesorů včetně x86_64, ARM64 a RISC-V
* Grafický režim VGA pomocí SPICE a QXL
* Režim textového terminálu
* USB zařízení
* Akcelerace založená na JIT pomocí QEMU TCG
* Frontend navržený od nuly pro macOS 11 a iOS 11+ s využitím nejnovějších a nejlepších API
* Vytvářejte, spravujte a spouštějte virtuální počítače přímo z vašeho zařízení

## Další funkce macOS

* Hardwarově akcelerovaná virtualizace pomocí Hypervisor.framework a QEMU
* Spouštění hostovaných systémů macOS s Virtualization.framework na macOS 12+

## UTM SE

UTM/QEMU vyžaduje pro maximální výkon dynamické generování kódu (JIT). JIT na zařízeních iOS vyžaduje buď jailbreaknuté zařízení, nebo jedno z různých řešení dostupných pro konkrétní verze iOS (další podrobnosti viz „Instalace“).
