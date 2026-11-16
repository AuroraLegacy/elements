# Aurora Legacy: 2024 rules only (dnd-2024 branch)

This branch keeps only content for the **2024 rules (D&D 5.5e)**, so nothing written for the 2014 rules can end up on a 5.5e character:

* the shared `core/internal.xml` and `core/ALE.xml`;
* Player's Handbook (2024), Dungeon Master's Guide (2024), Monster Manual (2025);
* the monsters of the System Reference Document 5.2.1 (`core/system-reference-document-5.2.1`), the ones the Monster Manual (2025) file doesn't have. They include material from the SRD 5.2.1 by Wizards of the Coast LLC, available at https://www.dndbeyond.com/srd, licensed under the [Creative Commons Attribution 4.0 International License](https://creativecommons.org/licenses/by/4.0/legalcode);
* the 2024 books from Aurora Legacy pull requests not merged upstream yet: Astarion's Book of Hungers and Netheril's Fall (#334), Forgotten Realms: Heroes of Faerûn and Adventures in Faerûn (#335), Lorwyn: First Light (#340), Eberron: Forge of the Artificer (#341), Arcana Unleashed and Arcana Unleashed: Deadfall (#354), Ravenloft: The Horrors Within (#355), with fixes for broken references.

Master index (Aurora Builder's *Additional Content* tab, or DaybreakBuilder's Content page): https://raw.githubusercontent.com/SpikeTheDragon40k/elements/dnd-2024/AuroraLegacy.index

## 2024-rules content coverage

✅ in this branch · ❌ missing · ➖ no player options (monsters/items/adventure only)

| Book | Released | Type | Status | Upstream PR |
|---|---|---|---|---|
| Player's Handbook (2024) | Sep 2024 | Core | ✅ | merged |
| Dungeon Master's Guide (2024) | Nov 2024 | Core | ✅ | merged |
| Monster Manual (2025) | Feb 2025 | Core | ✅ | merged |
| System Reference Document 5.2.1 | 2025 | Core (monsters) | ✅ | — |
| Quests from the Infinite Staircase | Jul 2024 | Adventure anthology | ❌ ➖ | — |
| Dragon Delves | Jul 2025 | Adventure anthology | ❌ ➖ | — |
| Starter Set: Heroes of the Borderlands | Sep 2025 | Starter set | ❌ | — |
| Astarion's Book of Hungers | 2025 | Supplement (digital) | ✅ | #334 |
| Netheril's Fall | 2025 | Supplement (digital) | ✅ | #334 |
| Forgotten Realms: Heroes of Faerûn | Nov 2025 | Player sourcebook | ✅ | #335 |
| Forgotten Realms: Adventures in Faerûn | Nov 2025 | DM sourcebook | ✅ | #335 |
| Eberron: Forge of the Artificer | Dec 2025 | Class sourcebook | ✅ | #341 |
| Lorwyn: First Light | 2026 | Setting sourcebook | ✅ | #340 |
| Ravenloft: The Horrors Within | 2026 | Setting sourcebook | ✅ | #355 |
| Arcana Unleashed | Sep 2026 | Sourcebook | ✅ | #354 |
| Arcana Unleashed: Deadfall | Sep 2026 | Adventure | ✅ | #354 |
| Unearthed Arcana (2024+ playtests) | ongoing | Playtest | ❌ | — |
| Winter 2026 book (unannounced) | TBA | — | ❌ | — |

Release dates are approximate; check D&D Beyond for exact ones.

`master` stays an unmodified copy of [AuroraLegacy/elements](https://github.com/AuroraLegacy/elements). The original README follows.

---

# Aurora Builder
Visit the [website](http://www.aurorabuilder.com "Aurora Website") for more information about the Aurora character builder app.

# Aurora Legacy Project
The goal of Aurora Legacy is to continually support Aurora Builder app with updates to content files.  <br>
[Project's Discord Server](https://discord.gg/3n5uakXT2a "Project Discord Server"), where you can find the announcements, discuss relevant news and receive help with your homebrew files.  <br>
Please take a moment to review the [contributing guidelines](https://github.com/AuroraLegacy/elements/blob/master/.github/CONTRIBUTING.md) when creating an issue, making a content request, or submitting a pull request.

## Extending Content
Go to the _Additional Content_ tab in Aurora, enter the URL of the index file, and have Aurora download the content to the custom folder for you. When these files get updated, Aurora will be able to keep content files up to date automatically.

<u>**Warning:**</u> Users who previously used content from now archived Aurora repository, must first delete following folders and files in "_custom_" folder (you can open it through the Additional Content tab's "Content Folder" button), before using links below: "core" folder, "_supplements_" folder, "_unearthed-arcana_" folder, "_core.index_" file, "_supplements.index_" file, "_unearthed-arcana.index_" file. <br/>
This also applies to users who want to change from Individual Indexes Download to All in One Download. <br/>
_**Additionally**_, old characters may require re-selecting some options, due to changes in new files (that includes errata, and general fixes).

### Download Options:
<details>
  <summary><b>Option 1: All In One Download</b></summary>
  • Master Index: https://raw.githubusercontent.com/AuroraLegacy/elements/master/AuroraLegacy.index
</details>
<hr style="width:750px; height:2px; margin-top:-10px; margin-bottom:5px; background-color:rgb(150,150,150)">
<details>
  <summary><b>Option 2: Individual Indexes Download</b> </summary>
 • Core Index: https://raw.githubusercontent.com/AuroraLegacy/elements/master/core.index <b>(Required by following Indexes)</b> <br>
  • Supplements Index: https://raw.githubusercontent.com/AuroraLegacy/elements/master/supplements.index <b>(Requires Core Index)</b> <br>
  • Unearthed Arcana Index: https://raw.githubusercontent.com/AuroraLegacy/elements/master/unearthed-arcana.index <b>(Requires Core Index)</b> <br>
  • Collaborations Index: https://raw.githubusercontent.com/AuroraLegacy/elements/master/collaborations.index <b>(Requires Core Index)</b>
</details>

## Disclaimer
Aurora Legacy repository is intended as a place for easily-accessible Aurora Builder content (xml) files of products you already own. Please ensure you only access content in accordance with your local laws.

All images are property of the respected owners and are stored for static links.

Project's contact email: aurorabuilderlegacy@gmail.com. Aurora Legacy is a fan project, and isn't affiliated with the Aurora Builder or Wizards of the Coast.

## Other Community Driven Repositories
A collection of community driven content can be found [here](https://github.com/community-elements "Community Elements") which includes some homebrew content posted on Reddit and D&D Wiki.
