<center><img src="https://raw.githubusercontent.com/ApexStudios-Dev/.github/refs/heads/master/assets/minecraft/new/fantasydice.png" alt="mod-logo" width="666" height="82"></center>

<br>

**Fantasy's Dice** adds various **Dungeons & Dragons** inspired **Dice** to Minecraft.

Dice may be crafted in a **StoneCutter** by inserting the matching base material.
**Wooden Dice** need **Planks**, **Iron Dice** need **Iron Ingots**, **Diamond Dice** need **Diamonds** etc.

Dice are fully data configurable, meaning that the sidedness and material for a given dice can be changed using **Data Components**.

- "**fantasydice:sides**"
  - Sets the sidedness for a given dice, may be set to any positive integer (>=1).
  - Dice will roll a random value between 1 and "**fantasydice:sides**"
  - Built-in sides are: **4**, **6**, **8**, **10**, **12**, **20**.
  - A new client item property selector is available "**fantasydice:sides**", which allows selecting item models based on the dice sides component.
- "**fantasydice:material**"
  - Sets the material for a given dice, may be set to any lower-snake-cased alphanumeric String value (regex: **[a-z0-9_-]**).
  - Built-in materials are: **wooden**, **stone**, **bone**, **iron**, **golden**, **diamond**, **emerald**, **netherite**, **copper**, **ender**, **frozen**, **slime**, **redstone**, **paper**, **amethyst** and **chocolate**.
  - This component is mostly used for item cooldowns and display names, models and recipes will need to be updated/defined manually using data packs.
  - A new client item property selector is available "**fantasydice:material**", which allows selecting item models based on the dice material component.

---

[Join us on **Discord**](https://discord.apexstudios.dev/)

[<img src="https://raw.githubusercontent.com/ApexStudios-Dev/.github/refs/heads/master/assets/third_party/discord_banner.svg" alt="discord-banner" width="174" height="59">](https://discord.apexstudios.dev/)

[![bisecthosting-banner](https://www.bisecthosting.com/partners/custom-banners/f4d8198a-6c2a-4d86-8d74-1977589e8ef7.webp)](https://www.bisecthosting.com/apexstudios)

