# Contributing

Please take a moment to review this document in order to make the contribution
process easier and effective. Following these guidelines helps to communicate that you respect the time of the developer managing these files.

<br>

## Using the issue tracker

The issue tracker is the preferred channel for content [issues](#issues) and [requests](#requests). Please **do not** use the issue tracker for personal support regarding the character builder (use info@aurorabuilder.com or [Aurora Discord Server](https://discord.gg/MmWvNFV)).

<br>

<a name="issues"></a>
## Content Issues

Create an [issue](https://github.com/AuroraLegacy/elements/issues/new/choose) using the _Content Issue_ template.<br>
A content issue might be one of the following:

* missing content from an existing source <sup>1</sup>
* typo in a (sheet) description or and outdated description (due to errata for example)
* incorrect values, traits, or features being added

<sup>1</sup> The source might be marked as incomplete or has an additional information indicator with more information about why it's incomplete. This might be a contribution that was included in an incomplete state in the past. This will not be done in the future to avoid having multiple incomplete sources that are never finished.

<br>

<a name="pull-requests"></a>
## Pull Requests

Good pull requests are a great help. They should remain focused in scope and avoid containing unrelated commits. Make sure to **not** create one from your master branch, instead create a new branch for it. All pull requests will go through the [review process](#review-process). Small, focused pull requests are typically quicker to review and merge, but it is better to combine pull requests when making multiple changes within the same file(s) or focus.

Please ask on the [project discord server](https://discord.gg/3n5uakXT2a "Project Discord Server") or in a github issue before embarking on any significant pull request (Example: adding significant content, refactoring files), otherwise you risk spending a lot of time working on something that the project's developer might not want to merge into the repository.

Next, make sure the content contribution falls in the [project scope](#scope) and adheres to the following guidelines to make checking and testing contributes easier and less time consuming.

* Name your pull request with the format `[Source Abbreviation] %Specific Title%`. Use `[MISC]` when modifying files from multiple sources (Example: `[PHB] Fireball description fixes`)
* Give your commits a meaningful name instead of just _updated file1.xml_
* When making changes to an existing file, increase the version number by 1 (Example: from 0.1.2 to 0.1.3), no matter number of the commits.
* Indent the files properly (using tabs, size 4) to make them readable
* Make sure the IDs of new elements only contain alphanumeric characters in upper case, underscores (`[A-Z]`, `[0-9]`, `_`) and no spaces or other special characters.
* Make sure to check and test your files - See [review process](#review-process)
* Ensure the contribution is complete and ready to be checked and merged before opening a pull request. If you're working on something large, you can create an issue with a todo list and/or open a draft pull request to communicate your progress.

<br>

<a name="review-process"></a>
## Review Process

Anyone is welcome to assist in the review process and it is a huge help.
All pull requests require 2 or more reviews depending on the complexity and the number of files/lines being changed. It is uncommon that a file will be perfect when starting the review process. Approving a pull request with problems or requesting changes without appropriate context may cause a review to be ignored as part of the review process.

A good review will be different depending on the element(s) being changed or added. Below is a basic list of things to check for:

#### Overall:
* Check that the file does not contain errors on launch and appears in the app
* Check the element(s) and see that the description is as close to the source material as possible
* Make sure that sources and spells in the main description of the element are written in italics (Example: `<i>Player's Handbook</i>` or `<i>magic missile</i>`)
* Check every description for common copy paste issues (Examples: `l` instead of `1`, random spaces in the middle of words, random spaces around punctuation, or missing spaces)
* Make sure that `==UNKNOWN_VALUE==` doesn't appear anywhere on the sheet when testing changes in the app
* Check that unnecessary elements are hidden from the compendium (Example: helper elements for selecting spellcasting ability, duplicate items within the same source)
* Check that new files have correct links

#### Races / Subraces / Classes / Archetypes:
* Load the element(s) at each level before and after a feature is added or text is changed (it is best to just step through every level and check the sheet preview)

#### Armor / Weapons / Items / Magic Items:
* Check that magic equipment only appears for the appropriate type of armor/weapon
* Check that features/bonuses are added/removed when toggling equip/attune

#### Spells
* Check that the correct supports are present


<br>

<a name="scope"></a>
## Project Scope

### In the Project Scope

* Official Core Rulebooks and Supplements <sup>1</sup>
* Unearthed Arcana <sup>1</sup> (Playtest Material)
* Digital only content provided on official sites like D&D Beyond. <sup>1</sup> <sup>2</sup>
* Collaborations between Wizards of the Coast and a third party. <sup>1</sup> <sup>2</sup> <sup>3</sup>

<sup>1</sup> some material might require features not supported by the Aurora Builder, these materials will be reviewed on case-by-case basis<br>
<sup>2</sup> this material is being approved on a case-by-case basis<br>
<sup>3</sup> mostly will be categorized under Third Party due to the lesser known and generally unallowed nature of the material<br>

<a name="scope-out"></a>
### Out of the Project Scope

* personal homebrew content
* content from reddit <sup>1</sup>, D&D Wiki <sup>2</sup>, D&D Beyond Homebrew, DMs Guild, and other sites that allow users to post uncurated homebrew content.
* content from other franchises converted to 5e (Example: lord of the rings, pokemon, final fantasy, etc).

<sup>1</sup> There is a community repository for content from reddit [here](https://github.com/community-elements/elements-reddit).<br>
<sup>2</sup> There is a community repository for content from D&D Wiki [here](https://github.com/community-elements/elements-dndwiki).

