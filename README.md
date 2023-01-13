![](/abyssal-thumbnail.png)

# Abyssal
Abyssal is a simple theme from a type enthusiast (me) who was looking for modifications that would improve the reading and writing experience without dramatically changing [Obsidian](https://obsidian.md/)’s interface. 

Inspired by the depths of the ocean, it’s a theme that focuses on white space and mute colors (respecting accessibility standards). Your accent color will influence the theme but not in an expressive way (it’s too dark where the abyssal fish live 🐟). 

Abyssal does not require any plugins or extra snippets: it should work out–of–the–box using the default system font ([more on that later](#-why-system-fonts)) both on Windows and Mac, light and dark themes, translucent or not. But! It supports **colorful headings** and a **bigger line height** via the [Style Settings community plugin](https://github.com/mgmeyers/obsidian-style-settings)—more details on the [customization](#-customization) section. 

There were many small details handled in Abyssal, but the most notable are:

- Asymmetrical spacing for more breathing room of the vertical rhythm (based on an 8px grid)
- Bespoke line-height treatment for each heading type
- Higher contrast through type size, weight, and spacing
- Contextual spacing based on the display or omission of some items (e.g., Inline title)

Special attention was given to the styling of:

- Highlights
- List spacing
- Tables
- Front-matter display + inline title

![](/abyssal-screenshots.png)

Abyssal is my first theme as a new-ish user of [Obsidian](https://obsidian.md/), so some bugs may be found (I couldn’t test on mobile or on Linux yet, for example). Please report them, and I’ll do my best to fix them! 

I made those modifications initially as a snippet based on my personal needs (long-form writing and reading) and preferences (roomy vertical rhythm), but then it grew to the point that it made sense to expose it as a theme and share it with you 😄 

## ⤵️ Instalation
Abyssal can be found by opening Obsidian and going to:

Settings › Appearance › Themes, click on “Manage” and search for Abyssal.

## 🤖 Why system fonts
As a type design enthusiast, I’m always excited to use my favorite typefaces from foundries and designers that I like ([OHNO](https://ohnotype.co/fonts/degular), [ABC Dinamo](https://abcdinamo.com/typefaces/arizona), [Flavia Zimbardi](https://flaviazim.com/typefaces/lygia-sans), [Phil Pluckthun](https://philpl.gumroad.com/l/dank-mono?layout=profile)), and that was my first inclination when installing Obsidian. But soon, I saw myself writing CSS to properly typeset them—after all, each font needs specific grooming: a baseline grid/leading setting that works for one won’t necessarily work for the other; sizing scales that look great in a grotesque might not work that well in a humanist counterpart, etc. There’s no one–size–fits–all solution, so I decided to work with what I, and everyone else, would have in common: system fonts. 

If I could make all the extra and contextual spacing work with the default system font, it wouldn’t take much to figure out how to groom whatever font I would choose for myself, so I started playing with it. The fun thing is that I liked the results on macOS (that uses SF Pro) and Windows 11 (Segoe UI), which led me to want to share the results as a theme with you.

On my personal vault, I created tiny snippets with typeset mods for specific typefaces that I have licensed on my computer (and some from places like Google Fonts), but overall I was pleased to use the system fonts with the Abyssal settings as well.

## ⌇ Leading/Line height
I often prefer larger values for the line height; it’s often the first thing I change, even on coding editors like VS Code or Nova. I don’t know if it’s visual preference or impairment, but I prefer more spacing there. But, since Abyssal takes care of other vertical spacing aspects, the default line height with the default system font seems to work well for English text. For other scripts, I preferred a larger value—but that’s your call; you can toggle a larger version in [options](#options). 

## 📐 Baseline
To make things coherent despite the asymmetrical spacing of headings and other block items (which is a personal preference, not a rule), I initially created a baseline grid of 16px. Still, I wanted more control over some details, so I divided it in 8px instead, used it as a background in Obsidian, and it guided me via multiples/subdivisions while spacing and sizing.

![](/abyssal-grid-example.png)

This is not a big deal, but it helped me get into a more InDesign/Publisher kinda process, which was fun (the difference being the way that baseline is rendered on the web versus on print–focused apps, but what mattered for me was the visualization of consistency/coherence while exploring options). 

## 🎨 Colors
All the colors of Abyssal were hand-generated (if that’s a thing) in Figma using good–old–trial–and–error for legibility and contrast; as soon as a hue clicked fitted the theme, the rest of the colors would follow with movements on the S, and L values to keep things coherent (I don’t know why but I’m obsessed with abyssal fish, deep ocean and, therefore, the blue color, so that ended up influencing the theme). 

I confess I don’t use the light theme of any app where I need to write or read for long periods, so my bias of not using pure #FFF or #000 might be a bit off, but my personal impression is that these softer tones created a gentler experience for the eyes.

## ✨ Customization
This is my first theme and attempt at modifying Obsidian, so I didn’t dive deep into customization options, which I want to explore and improve later (either within Abyssal or another theme). However, as a baby step, there are two options:

- Colorful headers (from H1 to H6)
- Larger line height

You can access those options via the plugin [Style Settings community plugin](https://github.com/mgmeyers/obsidian-style-settings). 

The plugin [Contextual typography](https://github.com/mgmeyers/obsidian-contextual-typography) is not required, but if installed, it will bring tiny–but–mighty improvements to Abyssal.

## ⚖️ Licensing
You’re welcome to customize, change and remix the theme! Just keep in mind that any modification or distribution must retain the original MIT License and credit me as the author and the authors of any other code or snippet used in your variation. 

If you have any questions, comments or suggestions, please feel free to reach out ❤️ Happy writing!