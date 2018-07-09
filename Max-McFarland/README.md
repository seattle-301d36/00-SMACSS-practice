##### How did you determine which rules should be placed in each new CSS file?

By looking at what was being selected, I used the SMACSSs rules to try and differentiate what selectors went is what css page. I thought about it as if each page of css loaded individually (similarly to how html loads before the CSS). The elements that were "BASE" were the ones that would have the biggest overall scope, yet would change it very little (almost like a slight modification to the base HTML). The elements in "LAYOUT" effected only the layout/positioning of the elements. The page should look complete from a layout perspective if only this and the Base page load. Finally, the "MODULES" page includes all tweaks needed to spruce up the style of the page. This includes the font, coloring, and small individual positioning.
---

##### Did you do any refactoring of the existing CSS? If so, briefly explain what you did and why.

I did not, I simply copied and pasted the existing CSS into the various files. 
