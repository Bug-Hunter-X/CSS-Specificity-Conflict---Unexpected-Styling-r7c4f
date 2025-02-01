# CSS Specificity Conflict

This repository demonstrates a common issue in CSS: specificity conflicts.  When multiple CSS rules apply to the same element, the most specific rule wins. This can lead to unexpected styling if not carefully considered.

The `bug.css` file shows the problematic code. The `bugSolution.css` file demonstrates how to resolve the conflict using more precise selectors or the `!important` flag (although `!important` should be used sparingly).

## How to reproduce

1. Open `bug.html` in your browser.
2. Observe the paragraph's color. It should be red because the more specific `p` selector has higher specificity than the `.container` selector.

## How to fix

Open `bugSolution.css` to see how to fix it.