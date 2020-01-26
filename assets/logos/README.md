# Logo

Please use only this repository as official resource for C2DL-Logo assets. All assets are published as svg to ensure that the assets can be used in any resolution or size.

| `Logo Type` | Description         |
|:----------- |:------------------- |
| c2dl        | Normal C2DL Logo    |
| c2dl-tail   | C2DL Logo with tail |

## Asset Name

`<logo type><property list>`.svg

Optional property of the asset. Any asset can have none, one or multiple properties sortet by the following list (01 - `n`).

### Property 01: `.square`

The logo has a square base area. This variant should be used for assets that requires to be squared like website favicon or application logos. The logo should have a native size of `64x64`. If it is not possible to fit the logo in `64x64` sizes like `128x128`, `256x256`, `512x512`, ... can be used. It can be used for any `1:1` size like `8x8` or `512x512`.

### Property 02: `.min`

Minified version of the svg. The formatting is removed and the data are stored condenced.

## Dimensions and sizes

- Asset dimensions (`viewBox`) should be as small as possible for the specific form
- The used elements should be as smal as possible
- All dimensions, element sizes, positions and transformations should use integer if possible

## Accessability

Logos fulfill the [Web Content Accessibility Guidelines (WCAG) 2.0](https://www.w3.org/TR/WCAG20/). The requirements are:

- Logo title

	```
	<title>{{Title text}}</title>
	```

- Elements like `<symbol>` and `<path>` have a information text that describes the element in english

	```
	<desc>{{Element description}}</desc>
	```
