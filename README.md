# DokuWiki-Plugin: Wrap Plus

Requires: [WRAP-Plugin](https://www.dokuwiki.org/plugin:wrap)

This plugin contains additional containers for the common WRAP-Plugin for DokuWiki.


## picbutton

For creating navigation buttons. The wrap-container should contain an image in the first place and a link in the second place

Printable (dw2pdf): yes (but not optimized for printing)

```
<WRAP picbutton>
{{example-image.png?nolink}}
[[link]]
</WRAP>

```

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

