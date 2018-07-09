##### How did you determine which rules should be placed in each new CSS file?

I followed the base/layout/modules guidance in the SMACSS guide. Due to time constraints I wasn't able to apply all of the SMACSS recommendations, such as refactoring the Module's use on ID selectors (which is a no-no) and the fact that some of the layout styles (like the header and the footer) were applying the styling rules to rather specific elements (<p> and <nav>) instead of the broader elements of <header> and <footer>. 

---

##### Did you do any refactoring of the existing CSS? If so, briefly explain what you did and why.

Not really -- and mainly due to time constraints. I did comment out a free-standing </div> on line 19 in the HTML that didn't appear to belong.
