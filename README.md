# 🎭 SetSkin Skript

Et simpelt og effektivt Skript til at ændre spillerens skin ved hjælp af **SkinsRestorer API** – understøtter både Minecraft-navne og URL'er!

---

## 🧩 Krav

For at dette Skript virker korrekt, skal følgende plugins være installeret:

- ✅ **[Skript](https://github.com/SkriptLang/Skript)** – grundlæggende syntaks og kommandohåndtering  
- ✅ **[Skript-Reflect](https://github.com/TPGamesNL/skript-reflect)** – bruges til at tilgå og arbejde med Java API'er (SkinsRestorer)  
- ✅ **[SkBee](https://github.com/ShaneBeee/SkBee)** – kræves for avanceret tab-completion  
- ✅ **[SkinsRestorer](https://www.spigotmc.org/resources/skinsrestorer.2124/)** – giver adgang til skin system og API

---

## 🖥️ Kommando

- 🔁 **Cooldown:** 2 sekunder  
- 💬 **Brug:** `/setskin <navn | url>`  
- 🔄 Understøtter både Minecraft-brugernavne og links til skins fra f.eks. **MinersNeedCoolShoes** eller **Mineskin.org**

---

## 🧠 Funktionalitet

- Indlæser skin data asynkront  
- Viser status i action bar mens data indlæses  
- Tilføjer skin til spiller ved hjælp af `SkinsRestorer API`  
- Informerer spilleren hvis skin ikke blev fundet  
- Tab-completion hjælper spilleren med input

---

## 🧪 Eksempel

```bash
/setskin Notch
/setskin https://mineskin.org/skin/1234567890



📦 Installation
Placer .sk-filen i din plugins/Skript/scripts mappe

Sørg for at alle nødvendige plugins er installeret

Kør /sk reload <filnavn> in-game eller via konsol

🧑‍💻 Bidrag
Du er velkommen til at ændre, forbedre og tilpasse scriptet til dit netværk eller community!

⚠️ Bemærk
SkinsRestorer API kan ændre sig mellem versioner – sørg for at bruge en kompatibel version med din server og Skript Reflect.

