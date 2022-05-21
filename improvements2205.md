## Home Improvement in the Observatory

For months, I couldn't use my observatory as first the dome had trouble with its motor and after that worked again, the Mount computer suddenly died. So it had to be sent to the manufacturer for repair.
All these cirumstances resulted in the fact that even though I already bought my CDK in March 2021, even in May 2022 I still wasn't able to run even one single imaging night.
So I started to use the time to upgrade and improve my equipment, and change some old "interim" solutions, that would otherwise become final ones, eventually...

For quite some time I had two devices on my personal "wish list" and in May 2022 I finally decided to buy these items:
1. The Optec Alnitak Flip-Flat for use with the StarFire Refractor.
2. The PegausAstro Falcon Rotator for use with my Camera (and adapted using the Baader M68 System so I can mount it all on any Telescope).

### The Optec Alnitak Flip-Flat

To build a really remote-controllable Observatory, you need a solution to remotely open and close the cover of the telescopes. Some years ago, I tried to develop something myself - see my [Klodeckelautomat Repository](https://github.com/hdiessner/klodeckelautomat) and it worked pretty well, but only with a standalone PC application as I didn't want to do a deep-dive into ASCOM driver programming.

Enter Flip-Flat: Remote opening and closing of the telecope cover, but even combined with a flat fielding device integrated into the cover including ASCOM & INDI drivers. But could it also be used for creating dark frames while in closed position and the flat field light turned off?

At least, my version doesn't really light-seal the front when covering the Telescope - and if light can shine in, dust might enter aswell. So I needed to change that. As I bought the largest version with 190mm diameter, a 3d design of an additional sealing made from flex filament came to mind. It should just fit onto the print bed of my 3d printer. So I designed it and after some 8 hours of printing time I was able to test my new "Alnitak Skirt":
- fits perfectly around the cover part
- needed two small, additional cut-outs (sharp knife) to not interfere with the base of the motor box
- when closed, the cover is now light-tight and the inside of the scope is perfectly dark

I uploaded the STL file over on [Thingiverse]()

**Bold** and _Italic_ and `Code` text

[Link](url) and ![Image](src)
```

For more details see [GitHub Flavored Markdown](https://guides.github.com/features/mastering-markdown/).

### Jekyll Themes

Your Pages site will use the layout and styles from the Jekyll theme you have selected in your [repository settings](https://github.com/hdiessner/astrohd/settings/pages). The name of this theme is saved in the Jekyll `_config.yml` configuration file.

### Support or Contact

Having trouble with Pages? Check out our [documentation](https://docs.github.com/categories/github-pages-basics/) or [contact support](https://support.github.com/contact) and we’ll help you sort it out.
