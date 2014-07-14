---
layout: api
title: toString
---
[stdlib](../index.md) / [kotlin.template](index.md) / [toString](toString.md)

# toString
Converts the string template into a string using the given formatter
```
public fun StringTemplate.toString(formatter: Formatter): String
```
## Description
```
public fun StringTemplate.toString(formatter: Formatter): String
```
to encode values as Strings performing any special encoding (such as for HTML)
or internationalisation.
See [[HtmlFormatter] and [[LocaleFormatter] respectively.
