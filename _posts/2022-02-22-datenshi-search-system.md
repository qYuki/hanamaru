---
date: 2022-02-22 20:20:00
layout: post
title: Datenshi Search System
description: Welcome to Datenshi isolated search system!
image: https://cdn.discordapp.com/attachments/700283326740824086/945567112754249739/unknown.png
category: osu
tags:
  - osu!direct
  - search-system
  - datenshi
author: Momoka
paginate: false
---
Good Afternoon, Little Demons!

Today, we are announcing an upcoming feature teaser!

The **Datenshi Isolated osu!direct**! This is an attempt to mimic in-game search system with several features.

As of now Datenshi supports **two search modes**. The deprecated default one and the upcoming new one, which is backed by new search internal system.

To access either modes by choice, you need to supply certain prefixes that is accepted by the system.

## Feature Usage

|Mode|Prefixes|
|:-:|:-:|
|Default|`b!`/`bancho!`|
|Datenshi|`d!`/`dt!`/`datenshi!`|

Otherwise, by not supplying prefixes users will phase out the search system from time to time.

## Keyword Traits

About the search parameters, we allow several things here:
- phrases, quoted by either single or double quotes. **not backtick**.
- keywords, an expression composed with operand as separator.
- words, anything that is not fitting above.
- negated statements, only works on phrases and words.

### Allowed Keywords

In general they conform with `=` sign, however some keywords like integer/float comparison may allow *any human comparison sign*. With that in mind, any fields that are supposed to be integer, will not be read if the given value is not a valid integer, and considered as word/phrase.

List of allowed keywords for now:
- `artist`, `title`, `creator`, `source`
- `hp`, `od`, `cs`, `ar`, `keys`
- `star`, `rating`, `length`, `bpm`

This list is tentative and may grow (and maybe not updated instantly as per the change) as well.

## Feature Rolling Schedule

|Phase|Time|
|:-:|:-:|
|Public Test|2022 March 1st, 7:00 UTC+7|
|Public Use|2022 May 1st, 7:00 UTC+7|

After 1st May, default search system will be **Datenshi Search.**

![](https://cdn.discordapp.com/attachments/874910377937354763/945605506834264114/unknown.png)
