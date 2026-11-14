# Komplet Guide: Minecraft 1.21.1 med NeoForge & Mods

Denne guide gennemgår trin for trin, hvordan du opsætter en ren installation af **Minecraft 1.21.1 (Java Edition)** med **NeoForge** samt installerer din samlede mod-pakke (herunder Create, Create: Gunsmithing, MineColonies, Immersive Vehicles, Pam's HarvestCraft 2, Cozy Home m.fl.).

---

## Indhold
1. [Forudsætninger](#forudsætninger)
2. [Trin 1: Kør Minecraft 1.21.1 (Vanilla) én gang](#trin-1-kør-minecraft-1211-vanilla-én-gang)
3. [Trin 2: Download og installer NeoForge](#trin-2-download-og-installer-neoforge)
4. [Trin 3: Download alle 22 mods fra CurseForge](#trin-3-download-alle-22-mods-fra-curseforge)
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

## Trin 3: Download alle 22 mods fra CurseForge

Ved manuel søgning på [CurseForge](https://www.curseforge.com/) skal du altid sikre dig følgende filtre:
* **Game Version:** `1.21.1` (ikke `1.21.11` eller `26.3`)
* **Mod Loader:** `NeoForge`

Download følgende **22 aktive mod-filer** til din computer:

| Mod Navn | Filnavn | Download-link |
| :--- | :--- | :--- |
| **GeckoLib** | `geckolib-neoforge-1.21.1-4.9.3.jar` | [Download GeckoLib](https://www.curseforge.com/minecraft/mc-mods/geckolib/download/8893490) |
| **Create** | `create-1.21.1-6.0.10.jar` | [Download Create](https://www.curseforge.com/minecraft/mc-mods/create/download/7963363) |
| **Create: Gunsmithing** | `create-gunsmithing-1.21.1-1.4.9.jar` | [Download Gunsmithing](https://www.curseforge.com/minecraft/mc-mods/cgs/download/8501347) |
| **NTGL (NukaTeam's Gun Lib)** | `ntgl-1.21.1-3.2.0.jar` | [Download NTGL](https://www.curseforge.com/minecraft/mc-mods/nukateams-gun-lib/download/8585353) |
| **Cozy Home** | `CozyHome-NeoForge-1.21.1-v1.1.1.jar` | [Download Cozy Home](https://www.curseforge.com/minecraft/mc-mods/cozy-home-forge-neoforge-port/download/8858411) |
| **Moretransport** *(tjek 1.21.1 NeoForge)* | `moretransport_bike-0.3.0.jar` | [Download Moretransport](https://www.curseforge.com/minecraft/mc-mods/moretransport-motorbike/download/9191740) |
| **OAmP (Official Automobile Pack)** | `OAmP-1.21.1-V3.jar` | [Download OAmP](https://www.curseforge.com/minecraft/mc-mods/mts-iv-official-automobile-pack/download/7933542) |
| **Immersive Vehicles** | `Immersive Vehicles-1.21.1-24.0.0.jar` | [Download Immersive Vehicles](https://www.curseforge.com/minecraft/mc-mods/minecraft-transport-simulator/download/7926606) |
| **MTS Official Pack** | `MTS Official Pack-1.21.1-V29.jar` | [Download MTS Official Pack](https://www.curseforge.com/minecraft/mc-mods/transport-simulator-official-vehicle-set/download/7933734) |
| **Architectury API** | `architectury-13.0.11-neoforge.jar` | [Download Architectury API](https://www.curseforge.com/minecraft/mc-mods/architectury-api/download/8492726) |
| **Framework** *(erstat `26.3`-filen)* | `framework-neoforge-1.21.1-x.x.x.jar` | [Hent Framework (1.21.1 NeoForge)](https://www.curseforge.com/minecraft/mc-mods/framework/files/all?page=1&pageSize=20&version=1.21.1&gameVersionTypeId=6) |
| **MineColonies - PH2 Food Extended** *(tjek 1.21.1)* | `minecoloniesphfe-1.0.0.jar` | [Download MineColonies PHFE](https://www.curseforge.com/minecraft/mc-mods/minecolonies-pams-harvestcraft-2-food-extended/download/8147481) |
| **MCTier Library** *(tjek 1.21.1 NeoForge)* | `mctier_engine-1.0.0.jar` | [Download MCTier Library](https://www.curseforge.com/minecraft/mc-mods/mctier-library/download/8123069) |
| **MineColonies** | `minecolonies-1.1.1411-1.21.1-snapshot.jar` | [Download MineColonies](https://www.curseforge.com/minecraft/mc-mods/minecolonies/download/9401752) |
| **BlockUI** *(afhængighed til MineColonies)* | `blockui-1.0.212-1.21.1-snapshot.jar` | [Download BlockUI](https://www.curseforge.com/minecraft/mc-mods/blockui/download/9137005) |
| **Domum Ornamentum** *(afhængighed til MineColonies)* | `domum-ornamentum-1.0.237-snapshot-main.jar` | [Download Domum Ornamentum](https://www.curseforge.com/minecraft/mc-mods/domum-ornamentum/download/9394376) |
| **Structurize** *(afhængighed til MineColonies)* | `structurize-1.0.837-1.21.1-snapshot.jar` | [Download Structurize](https://www.curseforge.com/minecraft/mc-mods/structurize/download/9333948) |
| **Multi-Piston** *(påkrævet afhængighed til MineColonies)* | `multipiston-1.21.1-x.x.x.jar` | [Hent Multi-Piston (1.21.1 NeoForge)](https://www.curseforge.com/minecraft/mc-mods/multi-piston/files/all?page=1&pageSize=20&version=1.21.1&gameVersionTypeId=6) |
| **Pam's HarvestCraft 2 - Food Extended** | `pamhc2foodextended-NEOFORGE-1.21.1-1.0.0.jar` | [Download PH2 Food Extended](https://www.curseforge.com/minecraft/mc-mods/pams-harvestcraft-2-food-extended/download/6221521) |
| **Pam's HarvestCraft 2 - Food Core** | `pamhc2foodcore-NEOFORGE-1.21.1-1.0.4.jar` | [Download PH2 Food Core](https://www.curseforge.com/minecraft/mc-mods/pams-harvestcraft-2-food-core/download/6919485) |
| **Pam's HarvestCraft 2 - Crops** | `pamhc2crops-NEOFORGE-1.21.1-1.0.9.jar` | [Download PH2 Crops](https://www.curseforge.com/minecraft/mc-mods/pams-harvestcraft-2-crops/download/8064883) |
| **Pam's HarvestCraft 2 - Trees** | `pamhc2trees-NEOFORGE-1.21.1-1.0.9.jar` | [Download PH2 Trees](https://www.curseforge.com/minecraft/mc-mods/pams-harvestcraft-2-trees/download/7847533) |

### Udgåede mods (skal ikke lægges i `mods`-mappen)

| Mod Navn | Filnavn | Arkiv-link |
| :--- | :--- | :--- |
| **Pokebike** | `pokebike-neoforge-4.0.jar` | [Se Pokebike på CurseForge](https://www.curseforge.com/minecraft/mc-mods/pokebike/download/9272596) |

> **Vigtige bemærkninger før næste trin:**
> * Hvis browseren advarer om, at `.jar`-filer kan skade din computer, vælger du blot **Behold** (*Keep*). Du skal **ikke** køre eller pakke disse filer ud.
> * Undgå at lægge `framework-neoforge-26.3-0.13.27.jar` i mappen – brug udelukkende `1.21.1`-udgaven af **Framework**.
> * For filer uden versionsnummer i selve filnavnet (`moretransport_bike-0.3.0.jar`, `minecoloniesphfe-1.0.0.jar` og `mctier_engine-1.0.0.jar`) bør du dobbelttjekke under *Files* på CurseForge, at de er mærket med **1.21.1** og **NeoForge**.

---

## Trin 4: Flyt mod-filerne til spillets mods-mappe

1. Åbn **Minecraft Launcher**.
2. Klik på fanen **Installationer** (*Installations*) øverst.
3. Find profilen ved navn **neoforge** (eller **neoforge-21.1.x**).
4. Før musen hen over profilen, og klik på **Mappe-ikonet** helt til højre.
5. Din Minecraft-rodmappe (`.minecraft`) åbner nu i Windows Stifinder / macOS Finder.
6. Dobbeltklik på mappen **`mods`**.
   * *Hvis mappen `mods` mangler:* Højreklik i et tomt område, vælg **Ny** > **Mappe**, og skriv præcis `mods` (med små bogstaver).
7. Flyt eller kopiér alle **22 aktive `.jar`-filer** fra din Overførsler-mappe ind i denne **`mods`**-mappe.

---

## Trin 5: Start spillet og kontrollér

1. Gå tilbage til **Minecraft Launcher** og klik på fanen **Spil** (*Play*).
2. Tjek i menuen ved siden af den store grønne knap, at **neoforge-21.1.x** er valgt.
3. Klik på **Spil** (*Play*).
   * Markér boksen med, at du forstår konsekvenserne ved at køre et modificeret spil, hvis launcheren spørger.
4. Når spillet er indlæst:
   * I bunden af startskærmen vil der stå information om NeoForge.
   * Klik på menupunktet **Mods** for at se listen, og kontrollér at alle dine mods fremgår som aktive uden fejlmeddelelser.

---

## Fejlfinding & ofte stillede spørgsmål

### 1. NeoForge installer-filen vil ikke åbne ved dobbeltklik
* **Årsag:** Windows ved ikke, hvilket program der skal køre `.jar`-filer, eller du mangler en installeret Java-version.
* **Løsning:** Download og installer **Java 21** fra [Adoptium](https://adoptium.net/). Hvis filen åbner i WinRAR eller 7-Zip, skal du højreklikke på installationsfilen, vælge **Åbn med** > **Java(TM) Platform SE binary**.

### 2. Spillet crasher under opstart
* **Forkert Minecraft-version:** Sørg for, at ingen af dine mods er til version *1.21.11*, *26.3* (f.eks. den tidligere Framework-fil) eller ældre udgaver som *1.20.1*.
* **Manglende afhængighed:** Kontrollér at **Multi-Piston**, **BlockUI**, **Domum Ornamentum** og **Structurize** alle ligger i `mods`-mappen sammen med **MineColonies**.
* **Loader-uoverensstemmelse:** Kontrollér, at du ikke ved en fejl har downloadet Fabric-udgaver af mods – alle filer skal være til **NeoForge**.

### 3. Tildeling af mere RAM (anbefales kraftigt til 20+ mods)
Med tunge mods som **Create**, **MineColonies** og **Immersive Vehicles** bør spillet tildeles mindst **6 GB RAM**:
1. Åbn **Minecraft Launcher** > **Installationer**.
2. Klik på de tre prikker ud for din NeoForge-profil og vælg **Rediger** (*Edit*).
3. Klik på **Flere indstillinger** (*More options*).
4. I feltet **JVM-argumenter** ændres startparameteren fra `-Xmx2G` til `-Xmx6G` (eller `-Xmx8G`, hvis din PC har 16 GB RAM eller mere).
5. Klik på **Gem** (*Save*).