---
aliases: 
tags:
  - Category/Location/POI
  - Category/Location/Settlement/City
type: Prison-City
size: Large
alignment: 
government: Mayorship
leader:
  - "[[2-Campaign/Characters/NPCs/Chyde.md|Chyde]]"
groups: 
region: "[[Emerald City]]"
population: 
races:
  - Humans
  - Animals
  - Dwarves
  - Elves
religion:
  - "[[1-The Land of Oz/Religion/Unionism.md|Unionism]]"
  - "[[1-The Land of Oz/Religion/Pleasure Faith.md|Pleasure Faith]]"
  - "[[1-The Land of Oz/Religion/Lurlinism.md|Lurlinism]]"
notable-NPCs:
  - "[[2-Campaign/Characters/NPCs/Nor Tigelaar.md|Nor Tigelaar]]"
affluence: Low
---

> [!infobox|wfit]+
> # `=this.file.name`
> `INPUT[imageSuggester(optionQuery("")):profileImageSmall]`
> ###### Geography
>  |   |
> ---|---|
> Type | `INPUT[suggester(option(Village), option(Town), option(City), option(State), option(Country), allowOther):type]` |
> Size | `INPUT[inlineSelect(option(Tiny), option(Small), option(Medium), option(Large)):size]` |
> Region | `INPUT[suggester(option(Munchkinland), option(Gillikin), option(The Vinkus), option(Quadling Country), option([[Emerald City]]), option(The Glikkus), option(Ugabu), allowOther):region]` |
> ###### Politics
>  |   |
> ---|---|
> Govt Type | `INPUT[text(class(meta-bind-med-width),placeholder(Government)):government]` |
> Ruler | `INPUT[inlineListSuggester(optionQuery(#Category/Character)):leader]` |
> ###### Society
>  |   |
> ---|---|
> Population | `INPUT[text(class(meta-bind-med-width),placeholder(Population)):population]`|
> Affluence | `INPUT[inlineSelect(option(Low), option(Medium), option(High), option(Extreme)):affluence]` |
> Races | `INPUT[inlineList:races]` |
> Religions | `INPUT[inlineListSuggester(optionQuery(#Category/Religion)):religion]`  |
> Organizations | `INPUT[inlineListSuggester(optionQuery(#Category/Group)):groups]` |


# `=this.file.name`
## Overview

### Placeholder Map
`INPUT[imageSuggester(optionQuery("2-Campaign/Maps")):mapImage]`

### Placeholder Picture
`INPUT[imageSuggester(optionQuery("")):profileImageLarge]`

## Notable Characters
`INPUT[inlineListSuggester(optionQuery(#Category/Character)):notable-NPCs]`

## Description

## Story

## Points of Interest
`INPUT[inlineListSuggester(optionQuery(#Category/Location/POI)):POIs]`

## Districts & Wards

### Free District

#### Market Ward
- Black market
#### Hive Ward
- The slums
#### Under-Mayor's Ward
- 
### Prison District

#### Watchman's Ward
- 
#### The Cages
- 
#### Outer Ward
- 
#### Inner Ward
- 
#### Central Ward
- 

## Valuables
`INPUT[inlineListSuggester(optionQuery(#Category/Item)):notable-items]`

## Internal Relationships

## Outward Relationships

## Background

## Additional Details

