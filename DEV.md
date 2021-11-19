# Development notes

## Palettes

The base of everything is a palette.

Multiple palette types should be supported

### Base and accents

The first palette type to be supported consists of a base gradient and a
selection of accent colours. The palette type has several subtypes,
parameterized by:

- Primary colours (RGB or RYB)
- Number of steps in the base gradient
- Maximum accent colour rank
- Number of accent colour shades

The default type is base-rgb-9-3-1, which has 9 steps in the base gradient and
12 accent colours spaced around the RGB colour wheel: red, orange, yellow,
chartreuse, green, spring green, cyan, azure, blue, violet, magenta, and rose.
For a base-ryb-9-3-1 palette, the accent colours would be red, vermillion,
amber, orange, chartreuse, green, teal, blue, violet purple and magenta.

## Schemes

From the palette, one or more schemes is created by choosing a subset of base
and accent colours.

## Themes

Finally, themes are generated from a palette and a scheme.


