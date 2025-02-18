---
alias:
  - 
Tags:
  - Category/Location/POI
type: ""
size: ""
alignment: 
government: 
leader: 
groups: 
region: ""
population: ""
races: []
religion: []
view-count: 2
notable-NPCs:
  - "[[1-The Land of Oz/Characters/Elphaba Thropp (Wicked Wiki).md|Elphaba Thropp (Wicked Wiki)]]"
  - "[[1-The Land of Oz/Characters/Liir Thropp (Wicked Wiki).md|Liir Thropp (Wicked Wiki)]]"
  - "[[1-The Land of Oz/Characters/Nor Tigelaar (Wicked Wiki).md|Nor Tigelaar (Wicked Wiki)]]"
---



> [!infobox|wfit]+
> # `=this.file.name`
> `INPUT[imageSuggester(optionQuery("")):profileImageSmall]`
> ###### Geography
>  |   |
> ---|---|
> Type | `INPUT[inlineSelect(option(Village), option(Town), option(City), option(State), option(Country), option(Other)):type]` `INPUT[suggester(option(Village), option(Town), option(State), option(Country), option(Lake), option(Outpost)):exampleProperty]` |
> Size | `INPUT[inlineSelect(option(Tiny), option(Small), option(Medium), option(Large)):size]` |
> Region | `INPUT[text:region]` |
> ###### Politics
>  |   |
> ---|---|
> Govt Type | `INPUT[text(placeholder(Government)):government]` |
> Ruler | `INPUT[inlineListSuggester(optionQuery(#Category/Character)):leader]` |
> ###### Society
>  |   |
> ---|---|
> Population | `INPUT[text(placeholder(Population)):population]`|
> Affluence | `INPUT[inlineSelect(option(-), option(Low), option(Medium), option(High)):exampleProperty]` |
> Races | `INPUT[inlineList:races]` |
> Religions | `INPUT[inlineListSuggester(optionQuery(#Category/Religion)):religion]`  |
> Organizations | `INPUT[inlineList:groups]` |

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

## Valuables
`INPUT[inlineListSuggester(optionQuery(#Category/Item)):notable-items]`

## Internal Relationships

## Outward Relationships

## Background

## Additional Details

