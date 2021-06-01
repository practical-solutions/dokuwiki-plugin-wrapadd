# DokuWiki-Plugin: Wrap Plus

Requires: [WRAP-Plugin](https://www.dokuwiki.org/plugin:wrap)

This plugin contains additional containers for the common WRAP-Plugin for DokuWiki.


## list-deep

Origin: https://www.dokuwiki.org/plugin:wrap:extensions
Function: Change format of an ordered list

Printable (dw2pdf): no

```
<WRAP list-deep>
  - Item 1
    - Item 1.1.
  - Item 2
</WRAP>
```


## border

Adds a simple border to any wrap container.

Printable (dw2pdf): yes

```
<WRAP border>
Content
</WRAP>
```

## nicebox

Origin: https://www.dokuwiki.org/plugin:wrap:extensions
Function: Adds simple message boxes

Printable (dw2pdf): yes

```
<WRAP nicebox red|orange|green|purple|yellow|blue|marine>
Any content
</WRAP>
```

## formalbox

Function: Another box variant for formal purposes, especially when used with tables.

Printable(dw2pdf): yes

```
<WRAP formalbox>
A formal decision
| By the director | in the meeting | 13th June 2025 |
</WRAP>
```
