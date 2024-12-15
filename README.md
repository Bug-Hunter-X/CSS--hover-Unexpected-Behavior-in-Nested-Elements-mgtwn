# CSS :hover Unexpected Behavior in Nested Elements

This repository demonstrates an uncommon CSS bug related to the unexpected behavior of the `:hover` pseudo-class when applied to nested elements.  The problem arises from a misunderstanding of CSS specificity and how the cascade works. 

The `bug.css` file contains the erroneous code, exhibiting the unexpected styling.  The `bugSolution.css` file provides the corrected CSS, resolving the unintended style changes.  Refer to the files for code examples and a detailed description of the issue and its resolution.

## Issue Description

The issue is observed when attempting to style nested elements using `:hover`. Specifically, hovering over an inner element unintentionally alters the style of its parent element. This happens due to the way CSS specificity handles selectors and cascade.

## Solution

The solution involves understanding CSS specificity rules. By strategically selecting and adjusting selectors, we ensure that each element receives its intended styling on hover, without affecting other elements unintentionally. Refer to `bugSolution.css` for the implementation of the solution.