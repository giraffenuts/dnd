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
> ![[PlaceholderPicture.png|cover hsmall]]
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

