---
Tags:
  - Category/Character/NPC
AssociatedGroup:
  - Arjiki Clan
  - Blacklung Brigade
Gender: Female
Race: 
Age: 
Class: 
Alignment: 
Religion: 
Character-Role: 
Character-Residence: "[[2-Campaign/Locations/Southstairs.md|Southstairs]]"
Character-Origin: Kiamo Ko
Vitality: 
statblock: Commoner
age: 32
race: Human
vitality: Injured
alignment: Chaotic Neutral
character-role: Guide, Informant, Sidekick
class: Rogue
---



# `=this.file.name`

Source: `INPUT[suggester(optionQuery("1-The Land of Oz/Characters")):source-link]`

> [!infobox|wfit static embed clear-hr]+
> # `=this.file.name`
> `INPUT[imageSuggester(optionQuery("z_Assets/img/NPCs")):profileImage]`
> [[ImagePlaceholder.png|Show To Players]]
> ###### Basic Information
> Attribute |  Description |
> ---|---|
> Origin | `INPUT[suggester(optionQuery(#Category/Location/Settlement), allowOther):Character-Origin]` |
> Residence | `INPUT[suggester(optionQuery(#Category/Location/Settlement), allowOther):Character-Residence]` |
> Group  | `INPUT[inlineListSuggester(optionQuery(#Category/Group), allowOther):AssociatedGroup]`|
> Faith  | `INPUT[inlineListSuggester(optionQuery(#Category/Religion),option(Agnostic),option(Atheist),option(Other)):Religion]`|
> Gender | `INPUT[inlineSelect(option(Male), option(Female), option(Nonbinary)):Gender]` |
> Race | `INPUT[text(class(meta-bind-med-width),placeholder(Race)):race]` |
> Age | `INPUT[number(class(meta-bind-tiny-width),placeholder(Age)):age]` |
> Vitality | `INPUT[inlineSelect(option(Healthy), option(Injured), option(Sick), option(Deceased)):vitality]` |
> ###### Rules Info
> Attribute |  Description |
> ---|---|
> Alignment | `INPUT[suggester(option(Lawful Good), option(Neutral Good), option(Chaotic Good), option(Lawful Neutral), option(True Neutral), option(Chaotic Neutral), option(Lawful Evil), option(Neutral Evil), option(Chaotic Evil)):alignment]` |
> Class | `INPUT[suggester(option(Artificer), option(Barbarian), option(Bard), option(Cleric), option(Druid), option(Fighter), option(Monk), option(Paladin), option(Ranger), option(Rogue), option(Sorcerer), option(Warlock), option(Wizard), allowOther):class]` |
> Character Role | `INPUT[text:character-role]` |
> ## Statblocks
> ```statblock
> forceColumns: true
> columns: 2
> columnWidth: 250px
> name: Nor Tigelaar
> source: 5e SRD
> size: Medium
> type: humanoid
> subtype: human
> alignment: chaotic neutral
> ac: 13
> hp: 16
> hit_dice: 3d8 + 2
> speed: 30 ft.
> stats:
>   - 11
>   - 14
>   - 12
>   - 11
>   - 13
>   - 11
> skillsaves:
>   - investigation: 4
>   - perception: 5
>   - stealth: 6
>   - survival: 5
> damage_vulnerabilities: ""
> damage_resistances: ""
> damage_immunities: ""
> condition_immunities: ""
> senses: passive Perception 15
> languages: any one language (usually Common)
> cr: 1/2
> bestiary: true
> traits:
>   - name: Keen Hearing and Sight
>     desc: Nor has advantage on Wisdom (Perception) checks that rely on hearing or sight.
>     attack_bonus: 0
> actions:
>   - name: Multiattack
>     desc: Nor makes two melee attacks or two ranged attacks.
>     attack_bonus: 0
>   - name: Shortsword
>     desc: "Melee Weapon Attack: +4 to hit, reach 5 ft., one target. Hit: 5 (1d6 + 2) piercing damage."
>     attack_bonus: 4
>     damage_dice: 1d6
>     damage_bonus: 2
>   - name: Longbow
>     desc: "Ranged Weapon Attack: +4 to hit, ranged 150/600 ft., one target. Hit: 6 (1d8 + 2) piercing damage."
>     attack_bonus: 4
>     damage_dice: 1d8
>     damage_bonus: 2
> ```
> 
>```encounter-table
>name: Individual
>creatures:
> - 1: Nor Tigelaar, ally
>```
## Profile

**Ilianora** (formerly known as **Princess** **Nor Tigelaar**) is the youngest child of Fiyero and Sarima and the half-sister of Liir. Throughout the novels, she has been a tribal princess of the Arjiki Clan in The Vinkus, a political prisoner of the Wizard, and a member of the company of the Clock of the Time Dragon, under the apprenticeship of Mister Boss.

She had a sharp face. Her white hair was lustrous and thick, no sign of yellowing. Indeed, noted Brrr, Ilianora had good skin tone, only a few wrinkles around the eyes. Her chin hadn’t sunk and her color was high. Ruby plum.
## Relationships
`INPUT[suggester(optionQuery("1-The Land of Oz/Characters"),optionQuery("2-Campaign/Characters"),allowOther):relationships]`
## History
### Childhood
>[!quote] Wicked: the Life and Times of the Wicked Witch of the West
>Nor, long-legged and thumb-sucking at nine years old, still needed a lap to crawl into before going to sleep... Nor had a delicate lisp and she said wunning in the wain for running in the rain. She befriended stones and candles and blades of grass that grew against all logic in the cracks of the coping stones around the windows.