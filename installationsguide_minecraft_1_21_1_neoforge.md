# Komplet Guide: Minecraft 1.21.1 med NeoForge & Mods

Denne guide gennemgår trin for trin, hvordan du opsætter en ren installation af **Minecraft 1.21.1 (Java Edition)** med **NeoForge** samt installerer mods som Create, Create: Gunsmithing, GeckoLib, NTGL og Cozy Home.

---

## Indhold
1. [Forudsætninger](#forudsætninger)
2. [Trin 1: Kør Minecraft 1.21.1 (Vanilla) én gang](#trin-1-kør-minecraft-1211-vanilla-én-gang)
3. [Trin 2: Download og installer NeoForge](#trin-2-download-og-installer-neoforge)
4. [Trin 3: Download de 5 mods fra CurseForge](#trin-3-download-de-5-mods-fra-curseforge)
5. [Trin 4: Flyt mod-filerne til spillets mods-mappe](#trin-4-flyt-mod-filerne-til-spillets-mods-mappe)
6. [Trin 5: Start spillet og kontrollér](#trin-5-start-spillet-og-kontrollér)
7. [Fejlfinding & ofte stillede spørgsmål](#fejlfinding--ofte-stillede-spørgsmål)

---

## Forudsætninger

* Den officielle **Minecraft Launcher** til PC/Mac.
* **Java 21 (JDK / JRE):** Hvis du ikke kan åbne NeoForge `.jar`-filen ved at dobbeltklikke, skal du installere Java 21 (f.eks. fra [Adoptium Temurin 21](https://adoptium.net/temurin/releases/?version=21)).
* En aktiv internetforbindelse til at downloade filer.

---

## Trin 1: Kør Minecraft 1.21.1 (Vanilla) én gang

> **Hvorfor dette trin er nødvendigt:** NeoForge kan ikke installere sig selv ovenpå en Minecraft-version, hvis versionens grundfiler ikke allerede er hentet ned på computeren.

1. Åbn **Minecraft Launcher**.
2. Vælg **Minecraft: Java Edition** i menuen i venstre side.
3. Klik på fanen **Installationer** (*Installations*) i toppen af vinduet.
4. Klik på **Ny installation** (*New installation*):
   * **Navn:** `1.21.1 Vanilla` (eller hvad du ønsker)
   * **Version:** Rul ned og vælg **release 1.21.1** *(Pas på: Vælg **ikke** 1.21.11)*
   * Klik på **Opret** (*Create*).
5. Gå tilbage til fanen **Spil** (*Play*), vælg din nye `1.21.1`-profil i rullemenuen til venstre for den grønne knap, og tryk på **Spil**.
6. Vent til spillet starter og når til hovedmenuen.
7. Tryk på **Afslut spil** (*Quit Game*).
8. **Vigtigt:** Luk **Minecraft Launcher** helt ned.

---

## Trin 2: Download og installer NeoForge

1. Gå ind på den officielle NeoForge-hjemmeside: [neoforged.net](https://neoforged.net/).
2. Vælg Minecraft-version **1.21.1**.
   * *Bemærk:* Versionsnumrene for 1.21.1 hedder **21.1.x** (undgå versioner der starter med 21.11.x).
3. Hent **Installer (.jar)**.
4. Gå til din mappe med **Overførsler** (*Downloads*) og dobbeltklik på den downloadede fil (`neoforge-21.1.x-installer.jar`).
5. Et installationsvindue åbner:
   * Sørg for, at feltet **Install client** er markeret.
   * Stien til din `.minecraft`-mappe vælges automatisk som standard.
   * Klik på **OK**.
6. Vent på at installationen fuldføres, indtil dialogboksen viser:  
   *`Successfully installed client profile neoforge`*
7. Klik på **OK** for at lukke installationsprogrammet.

---

## Trin 3: Download de 5 mods fra CurseForge

Ved manuel søgning på [CurseForge](https://www.curseforge.com/) skal du altid sikre dig følgende filtre:
* **Game Version:** `1.21.1` (ikke 1.21.11)
* **Mod Loader:** `NeoForge`

Download følgende 5 filer til din computer:

| Mod Navn | Filnavn | Direkte download-link |
| :--- | :--- | :--- |
| **GeckoLib** | `geckolib-neoforge-1.21.1-4.9.3.jar` | [Download GeckoLib](https://www.curseforge.com/minecraft/mc-mods/geckolib/download/8893490) |
| **Create** | `create-1.21.1-6.0.10.jar` | [Download Create](https://www.curseforge.com/minecraft/mc-mods/create/download/7963363) |
| **Create: Gunsmithing** | `create-gunsmithing-1.21.1-1.4.9.jar` | [Download Gunsmithing](https://www.curseforge.com/minecraft/mc-mods/cgs/download/8501347) |
| **NTGL (NukaTeam's Gun Lib)** | `ntgl-1.21.1-3.2.0.jar` | [Download NTGL](https://www.curseforge.com/minecraft/mc-mods/nukateams-gun-lib/download/8585353) |
| **Cozy Home** | `CozyHome-NeoForge-1.21.1-v1.1.1.jar` | [Download Cozy Home](https://www.curseforge.com/minecraft/mc-mods/cozy-home-forge-neoforge-port/download/8858411) |
| **Moretransport** | `moretransport_bike-0.3.0.jar` | https://www.curseforge.com/minecraft/mc-mods/moretransport-motorbike/download/9191740 |
| **OAmP** | `OAmP-1.21.1-V3.jar` | https://www.curseforge.com/minecraft/mc-mods/mts-iv-official-automobile-pack/download/7933542 |
| **Immersive Vehicles** | `Immersive Vehicles-1.21.1-24.0.0.jar` | https://www.curseforge.com/minecraft/mc-mods/minecraft-transport-simulator/download/7926606 |
| **MTS Official** | `MTS Official Pack-1.21.1-V29.jar` | https://www.curseforge.com/minecraft/mc-mods/transport-simulator-official-vehicle-set/download/7933734 |
| **architectury** | `architectury-13.0.11-neoforge.jar` | https://www.curseforge.com/minecraft/mc-mods/architectury-api/download/8492726 |
| **framework** | `framework-neoforge-26.3-0.13.27.jar` | https://www.curseforge.com/minecraft/mc-mods/framework/download/9054859 |
| **Minecolonies** | `minecoloniesphfe-1.0.0.jar`|| https://www.curseforge.com/minecraft/mc-mods/minecolonies-pams-harvestcraft-2-food-extended/download/8147481|
| **MCTier Library** | `mctier_engine-1.0.0.jar`| https://www.curseforge.com/minecraft/mc-mods/mctier-library/download/8123069 |
| **minecolonies** | `minecolonies-1.1.1411-1.21.1-snapshot.jar` | https://www.curseforge.com/minecraft/mc-mods/minecolonies/download/9401752 |
| **blockui** | `blockui-1.0.212-1.21.1-snapshot.jar` | https://www.curseforge.com/minecraft/mc-mods/blockui/download/9137005 |

***Udgået mods:***
| **pokebike** | `pokebike-neoforge-4.0.jar` | https://www.curseforge.com/minecraft/mc-mods/pokebike/download/9272596 |



> **Bemærk:** Hvis browseren advarer om, at `.jar`-filer kan skade din computer, vælger du blot **Behold** (*Keep*). Du skal **ikke** køre eller pakke disse filer ud.

---

## Trin 4: Flyt mod-filerne til spillets mods-mappe

1. Åbn **Minecraft Launcher**.
2. Klik på fanen **Installationer** (*Installations*) øverst.
3. Find profilen ved navn **neoforge** (eller **neoforge-21.1.x**).
4. Før musen hen over profilen, og klik på **Mappe-ikonet** helt til højre.
5. Din Minecraft-rodmappe (`.minecraft`) åbner nu i Windows Stifinder / macOS Finder.
6. Dobbeltklik på mappen **`mods`**.
   * *Hvis mappen `mods` mangler:* Højreklik i et tomt område, vælg **Ny** > **Mappe**, og skriv præcis `mods` (med små bogstaver).
7. Flyt eller kopiér alle **5 `.jar`-filer** fra din Overførsler-mappe ind i denne **`mods`**-mappe.

---

## Trin 5: Start spillet og kontrollér

1. Gå tilbage til **Minecraft Launcher** og klik på fanen **Spil** (*Play*).
2. Tjek i menuen ved siden af den store grønne knap, at **neoforge-21.1.x** er valgt.
3. Klik på **Spil** (*Play*).
   * Markér boksen med, at du forstår konsekvenserne ved at køre et modificeret spil, hvis launcheren spørger.
4. Når spillet er indlæst:
   * I bunden af startskærmen vil der stå information om NeoForge.
   * Klik på menupunktet **Mods** for at se listen. Kontrollér, at Create, Create: Gunsmithing, NTGL, GeckoLib og Cozy Home alle fremgår som aktive.

---

## Fejlfinding & ofte stillede spørgsmål

### 1. NeoForge installer-filen vil ikke åbne ved dobbeltklik
* **Årsag:** Windows ved ikke, hvilket program der skal køre `.jar`-filer, eller du mangler en installeret Java-version.
* **Løsning:** Download og installer **Java 21** fra [Adoptium](https://adoptium.net/). Hvis filen åbner i WinRAR eller 7-Zip, skal du højreklikke på installationsfilen, vælge **Åbn med** > **Java(TM) Platform SE binary**.

### 2. Spillet crasher under opstart
* **Forkert version:** Sørg for, at ingen af dine mods er til version *1.21.11* eller ældre udgaver som *1.20.1*.
* **Loader-uoverensstemmelse:** Kontrollér, at du ikke ved en fejl har downloadet Fabric-udgaver af mods (alle 5 filer skal være mærket med NeoForge).

### 3. Tildeling af mere RAM (anbefales til Create)
1. Åbn **Minecraft Launcher** > **Installationer**.
2. Klik på de tre prikker ud for din NeoForge-profil og vælg **Rediger** (*Edit*).
3. Klik på **Flere indstillinger** (*More options*).
4. I feltet **JVM-argumenter** ændres startparameteren fra `-Xmx2G` til f.eks. `-Xmx4G` eller `-Xmx6G` (afhængigt af hvor mange GB RAM din computer har).
5. Klik på **Gem** (*Save*).
