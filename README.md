
# Hero Icons V2 fonts

I converted the hero icons to web friendly fonts. Will update this project should tailwindlabs add anymore icons.


I take no credit for anything in this repo. I was just tired of embedding SVGs. Huge thanks to everyone below.



## Usage

Super simple, drop the fonts in wwwroot/fonts and the css in wwwroot/css.
There are three versions, so there are three separate fonts depending which one you want. They're done so you can have multiple in one app.
I have chosen to not really support IE to utilze the class=* selector.

Each class has a pseudo selector for hero- and whatever suffice (-solid, -outline, -mini).

```
<span class="hero-calendar-solid"></span>
<span class="hero-calendar-days-outline"></span>
```

There is no need for a "hero" / "icon" before class to setup the font.


## Credits

TailwindLabs for making the icons

https://github.com/tailwindlabs/heroicons


SVG Fixer for converting strokes to outlines

https://github.com/oslllo/svg-fixer


Icomoon for building the font files

https://icomoon.io/




