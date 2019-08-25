# FreeCodeCampAppliedVisualDesign

 Furthering CSS revision via FreeCodeCamp's Applied Visual Design resources and copying passed code to Git repo as I go through each task. Documenting below anything new I learn, or anything I am reminded of that I may have forgotten.

    - Reminded of use of HTML's <em> tag to italicize text.
    - Gained clearer understanding of use of box shadows:
        - Takes four values always in same order:
            box-shadow: offset-x offset-y blur-radius* spread-radius* color;
            * = optional
    - Gained better knowledge of use of CSS opacity property.
        - If applied to parent elements will affect all children (found through experimentation).
    - Learned proper use of HSL color wheel.
    - Learned how to use repeating linear gradients.
        - Make identical pairs of color stops to create stripes:
            background: repeating-linear-gradient(45deg,
                    yellow 0px,
                    yellow 40px,
                    black 40px,
                    black 80px);
    -Learned use of ::before and ::after pseudo elements.