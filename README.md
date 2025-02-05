# CSS Specificity and Inheritance Conflict

This repository demonstrates a subtle bug related to CSS specificity and inheritance, causing unexpected behavior when applying hover styles.

The `bug.css` file contains the problematic code, where a hover style inherits a parent's style instead of applying the more specific style rule defined. The `bugSolution.css` file shows how to correctly resolve this conflict and apply the intended style by adjusting specificity or using the `!important` flag.