[![Version](https://vsmarketplacebadge.apphb.com/version-short/nicola-granata.zenburn-cold-gray.svg)](https://marketplace.visualstudio.com/items?itemName=nicola-granata.zenburn-cold-gray)&nbsp;[![Downloads](https://vsmarketplacebadge.apphb.com/downloads-short/nicola-granata.zenburn-cold-gray.svg)](https://marketplace.visualstudio.com/items?itemName=nicola-granata.zenburn-cold-gray)&nbsp;[![Installs](https://vsmarketplacebadge.apphb.com/installs-short/nicola-granata.zenburn-cold-gray.svg)](https://marketplace.visualstudio.com/items?itemName=nicola-granata.zenburn-cold-gray)&nbsp;[![Rating](https://vsmarketplacebadge.apphb.com/rating-short/nicola-granata.zenburn-cold-gray.svg)](https://marketplace.visualstudio.com/items?itemName=nicola-granata.zenburn-cold-gray)&nbsp;

# Zenburn Cold Gray (deprecated in favor of [Zenburn In Grays](https://marketplace.visualstudio.com/items?itemName=nicola-granata.zenburn-in-grays))

## **Zenburn** token colors based themes

All the themes shown below are part of a suite designed to try to reduce visual fatigue while using VSCode.

The ultimate goal of the suite is to offer a good chance to find a theme that reduces disturbing elements and eye strain as much as possible.

However, attempts were made to leave error signals and selections clearly visible with moderate color contrasts.

> Tip 1: If you like versioning your code, try [**Version Boss**](https://marketplace.visualstudio.com/items?itemName=nicola-granata.version-boss)! `Version Boss` is a free extension that `simplifies versioning of script files`. Download it at [Marketplace](https://marketplace.visualstudio.com/items?itemName=nicola-granata.version-boss).

> Tip 2: I suggest replacing the `Zenburn Cold Gray` theme with [**Zenburn In Grays**](https://marketplace.visualstudio.com/items?itemName=nicola-granata.zenburn-in-grays) theme that contains the same skins with a Cold Gray background and in other sub-themes variants `Cold` / `Flat` / `Warm` / `Anthracite` / `Midnight` / `Nirvana` / `Low Blue`.

> Tip 3: Themes variants are pretty similar but you can find right colour intensity based on your monitor `sRGB` representation.


## Whats's new in Zenburn Cold Gray V. 1.1.94

> Note: [`Development`] sections in *Changelog* are addressed to the developer to remind him of any important changes that occurred during the writing of the code and do not always concern improvements made to the extension or to the theme.

- [`Themes`] `Dark Matter` suite only: added `Anthracite` sub-theme, with extra cold gray background;
- [`Themes`] Deprecated `Zenburn Cold Gray` in favor of `Zenburn in Grays`;
- [`Development`] Added function for deprecate old themes that insert deprecation in favor of theme indicated;
- [`Development`] Short badge on `README.md`;
- [`Development`] Improved {app_name} UI PHP and JS functions to auto-unselect harmful build options after build theme/extension.


See `Changelog` for previous versions.

## Zenburn Cold Gray Demo

`Note`: This demo not contains all subset of variants, because the representation of color in GIF format is not completely faithful.

![Zenburn Cold Gray Demo](./_gfx/zenburn-cold-gray-demo.gif)

### **Zenburn Cold Gray** variants descriptions:

- `Cold` - Cold Gray Background and Cold Token Colors;
- `Midnight` - Midnight Blue Background, inspired by *Telegram X Midnight Theme* and Cold, Desatured Token Colors;
- `Nirvana` - Low Blue Light only on Token Colors;
- `Low Blue` - Low Blue Light on Ui and Token Colors.


### **Zenburn Cold Gray** skins:

- `Zenburn Cold Gray - Cold - Asphalt`;
- `Zenburn Cold Gray - Cold - Eggplant`;
- `Zenburn Cold Gray - Cold - Lazy`;
- `Zenburn Cold Gray - Cold - Sugar Paper`;
- `Zenburn Cold Gray - Low Blue - Asphalt`;
- `Zenburn Cold Gray - Low Blue - Lazy`;
- `Zenburn Cold Gray - Midnight - Sugar Paper`;
- `Zenburn Cold Gray - Nirvana - Asphalt`;
- `Zenburn Cold Gray - Nirvana - Eggplant`;
- `Zenburn Cold Gray - Nirvana - Lazy`;
- `Zenburn Cold Gray - Nirvana - Sugar Paper`.


## All my Themes

[All my Themes on Marketplace](https://marketplace.visualstudio.com/search?term=publisher%3A%22Nicola%20Granata%22&target=VSCode&category=Themes&sortBy=Relevance).

- `Zenburn Cold Gray`
- [Zenburn Dark Matter](https://marketplace.visualstudio.com/items?itemName=nicola-granata.zenburn-dark-matter)
- [Zenburn In Grays](https://marketplace.visualstudio.com/items?itemName=nicola-granata.zenburn-in-grays)


### Note

- `Zenburn Cold Gray` is now a subset of `Zenburn in Grays`. I suggest moving on to the fuller `Zenburn in Grays`.
- `Zenburn tokenColors` are based on `Zenburn` VSCode porting by **Ryan Olson** ([Zenburn Theme by Ryan Olson](https://marketplace.visualstudio.com/items?itemName=ryanolsonx.zenburn)).

## About Themes

### Themes **Zenburn** based

**Zenburn** variants derives from the combination of Eclipse `Zenburn Theme` and Eclipse `DevStyle` Extension.
These variants has a dark gray cold/flat/warm backgrounds (based on the theme you installed), desaturated token colors (for code) and experimental **Nirvana** (Low Blue Light only on token colors) and **Low Blue Light** (applied to all main set of skins and token colors) with some exceptions:

- some icons cannot seems to be filtered;
- images in extensions README.md and in image viewer cannot be filtered.

# About my PHP Script `VSCode Themes Master`

The `Zenburn Cold Gray` prototype was initially a manual editing of the VSCode settings and some tokens, based on the `Zenburn` theme porting from Eclipse IDE (see below the thanks, to the paragraph `Gratitude`) in conjunction with the background of the DevStyle extension for Eclipse IDE.

Realizing that, to optimize some aspects of the theme, I would have had to evaluate an infinite series of colors, I decided that I would have done first to build mathematical functions for optimizing and correcting saturation / brightness / color / transparency / contrast of configurations already consolidated.

Specifically, I created _VSCode Themes Master_ in PHP (localhost script, not distributed) that allows you to set the basic colors of the skin, on which they are calculated, with a parametric and configurable reference system for each variant, all the others interface colors, applying, at the same time, tonal variations both on the interface and on the colors of the tokens.

My personal need to optimize the colors of the VScode interface to make it uniform to the _Eclipse IDE_ interface (_Zenburn_ + _DevStyle_), has led me to notice that, despite almost all my monitors are from the same manufacturer and despite having selected the temperature color on the `sRGB` standard (which therefore has brightness, contrast and range set to specific values), the visual impact, on the same theme variant, is different: more saturated and warm on some and more cold and desaturated on others .

_VSCode Themes Master_ allows me to build all the files necessary for the publication of the theme and, for this reason, it was easy (but not so easy) for me to test and distribute single themes with many color variations of the UI and tonal variations of the tokens for the code, to try to standardize the display between monitors with "different" `sRGB` representations (for example: using a cold theme on monitors with a tendency to warm colors and vice versa, or a flat theme that, in some cases, seems to be the correct compromise between extremes).

# Gratitude

## Zenburn based Themes

Many thanks to **Ryan Olson**, for his VSCode Zenburn porting, of which this variant is 99.999% composed, and to Zenburn for his fantastic theme.

## License

MIT
