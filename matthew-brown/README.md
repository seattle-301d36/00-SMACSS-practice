##### How did you determine which rules should be placed in each new CSS file?

by first taking out those large elements belonging to base. I then divided the layout and module . The criteria I used was to keep the semantic tags (header footer nav aside )in layout as the are a big bigger and general in scope. I then went through the remaining and asked if this was a smaller component - Ultimately I included the classes and IDs in the module along with any of the photo styling  

---

##### Did you do any refactoring of the existing CSS? If so, briefly explain what you did and why.

I did not. I think the only thing that might cause an issue is with the importing of the fonts. If a style folder needed the import it would cause issue but in this case, I dont believe any fonts were affected
