# CSS Specificity Issue with !important and Inheritance

This repository demonstrates a subtle bug related to CSS specificity and the `!important` declaration.  The `!important` flag, while useful in some scenarios, can create unexpected behavior when combined with inheritance.

The bug showcases a situation where a parent element's `!important` style overrides the style of a more specific grandchild selector. This issue arises because inheritance happens before specificity calculations when `!important` is involved. The problem is described in detail in the `bug.css` file and a solution is provided in `bugSolution.css`.