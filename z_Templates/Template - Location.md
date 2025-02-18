---
alias:
  - 
Tags:
  - Category/Location
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
---

<% await tp.file.move("/2-Campaign/Locations/" + tp.file.title) %>

<%*
const hasTitle = !tp.file.title.startsWith("NewLocation");
let title;
if (!hasTitle) {
    title = await tp.system.prompt("Location Name");
    await tp.file.rename(title);
} else {
    title = tp.file.title;
}
_%>


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

## Valuables
`INPUT[inlineListSuggester(optionQuery(#Category/Item)):notable-items]`

## Internal Relationships

## Outward Relationships

## Background

## Additional Details

