---
Tags:
  - Category/Character/NPC
AssociatedGroup: 
Gender: Female
Race: 
Age: 
Class: 
Alignment: 
Character-Role: 
Character-Residence: 
Character-Origin: 
Vitality: 
statblock: Commoner
source-link: "[[1-The Land of Oz/Characters/Nor Tigelaar (Wicked Wiki).md|Nor Tigelaar (Wicked Wiki)]]"
view-count: 2
vitality: Healthy
---



# `=this.file.name`

## Source
`INPUT[suggester(optionQuery("1-The Land of Oz/Characters")):source-link]`

> [!infobox|right wfit]
> # `=this.file.name`
> ![[ImagePlaceholder.png|cover hsmall]]
> [[ImagePlaceholder.png|Show To Players]]
> ###### Basic Information
> Type |  Stat |
> ---|---|
> Origin | `INPUT[suggester(optionQuery(#Category/Location/Settlement)):Character-Origin]` |
> Residence | `INPUT[suggester(optionQuery(#Category/Location/Settlement)):Character-Residence]` |
> Group  | `INPUT[inlineListSuggester(optionQuery(#Category/Group)):AssociatedGroup]`|
> Faith  | `INPUT[inlineListSuggester(optionQuery(#Category/Religion)):Religion]`|
> Gender | `INPUT[inlineSelect(option(Male), option(Female), option(Nonbinary)):Gender]` |
> Race | `INPUT[text:race]` |
> Age | `INPUT[number:age]` |
> Condition | `INPUT[inlineListSuggester(option(Blinded), option(Charmed), option(Deafened), option(Exhaustion), option(Frightened), option(Grappled), option(Incapacitated), option(Invisible), option(Paralyzed), option(Petrified), option(Poisoned), option(Prone), option(Restrained), option(Stunned), option(Unconscious)):condition]`  |
> Vitality | `INPUT[inlineSelect(option(Healthy), option(Injured), option(Sick), option(Deceased)):vitality]` |
> ###### Rules Info
> Type |  Stat |
> ---|---|
> Alignment | `=this.alignment` |
> Class | `=this.class` |
> Character Role | `=this.character-role` |

## Profile

**\<Add description here\>**

## Background Story

\<Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.

Sed ut perspiciatis unde omnis iste natus error sit voluptatem accusantium doloremque laudantium, totam rem aperiam, eaque ipsa quae ab illo inventore veritatis et quasi architecto beatae vitae dicta sunt explicabo. Nemo enim ipsam voluptatem quia voluptas sit aspernatur aut odit aut fugit, sed quia consequuntur magni dolores eos qui ratione voluptatem sequi nesciunt. Neque porro quisquam est, qui dolorem ipsum quia dolor sit amet, consectetur, adipisci velit, sed quia non numquam eius modi tempora incidunt ut labore et dolore magnam aliquam quaerat voluptatem. Ut enim ad minima veniam, quis nostrum exercitationem ullam corporis suscipit laboriosam, nisi ut aliquid ex ea commodi consequatur? Quis autem vel eum iure reprehenderit qui in ea voluptate velit esse quam nihil molestiae consequatur, vel illum qui dolorem eum fugiat quo voluptas nulla pariatur?\>
<br><br><br>
## Statblocks

> [!infobox|center wfit]
> ```statblock
> forceColumns: true
> columns: 2
> columnWidth: 425px
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
> monster: Scout
> forceColumns: true
> columns: 2
> columnWidth: 425px
> 
> ```

<br>

> [!infobox|center wfull]
>```encounter-table
>name: Nor Tigelaar
>creatures:
> - 1: Nor Tigelaar, ally
>```

