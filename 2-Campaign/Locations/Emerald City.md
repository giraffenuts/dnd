---
alias:
  - 
Tags:
  - Category/Location/Settlement
type: "-"
size: "-"
alignment: 
government: Monarchy
leader:
  - "[[2-Campaign/Characters/NPCs/Shell Heart.md|Shell Heart]]"
groups: 
region: ""
population: 2 million
races:
  - Humans
religion:
  - Unionism
  - Lurlinism
  - Pleasure Faith
  - Tik-Tokism
exampleProperty: Medium
view-count: 3
notable-NPCs:
  - "[[2-Campaign/Characters/NPCs/Shell Heart.md|Shell Heart]]"
  - "[[2-Campaign/Characters/NPCs/Nor Tigelaar.md|Nor Tigelaar]]"
profileImageSmall: z_Assets/img/Maps/EmeraldCityMap.jpg
---



> [!infobox|wfit]+
> # `=this.file.name`
> `INPUT[imageSuggester(optionQuery("z_Assets/img/Maps"),optionQuery("z_Assets/img/Locations")):profileImageSmall]`
> ###### Geography
>  |   |
> ---|---|
> Type | `INPUT[inlineSelect(option(-),option(Village), option(Town), option(City), option(State), option(Country), option(Other)):type]` |
> Size | `INPUT[inlineSelect(option(-),option(Tiny), option(Small), option(Medium), option(Large)):size]` |
> Region | `INPUT[text:region]` |
> ###### Politics
>  |   |
> ---|---|
> Govt Type | `INPUT[text:government]` |
> Ruler | `INPUT[inlineListSuggester(optionQuery(#Category/Character)):leader]` |
> ###### Society
>  |   |
> ---|---|
> Population | `INPUT[text:population]`|
> Affluence | `INPUT[inlineSelect(option(-), option(Low), option(Medium), option(High)):exampleProperty]` |
> Races | `INPUT[inlineList:races]` |
> Religions | `INPUT[inlineList:religion]`  |
> Organizations | `INPUT[inlineList:groups]` |

# `=this.file.name`
## Overview

### Placeholder Map
![[PlaceholderMap.png|Placeholder Map]]

### Placeholder Picture
![[PlaceholderPicture.png|Placeholder Picture]]

## Notable Characters
`INPUT[inlineListSuggester(optionQuery(#Category/Character)):notable-NPCs]`

## Description

## Story

## Points of Interest
`INPUT[inlineListSuggester(optionQuery(#Category/Location/POI)):POIs]`

## Valuables
`INPUT[inlineListSuggester(optionQuery(#Category/Item)):notable-items]`

## Internal Relationships

## Outward Relationships

## Background

## Additional Details

