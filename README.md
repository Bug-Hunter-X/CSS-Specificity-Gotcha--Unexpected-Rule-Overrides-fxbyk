# CSS Specificity Gotcha: Unexpected Rule Overrides

This repository demonstrates a subtle yet common issue in CSS related to specificity and inheritance.  The `bug.css` file shows a situation where a seemingly less relevant CSS rule overrides another based on its specificity. The solution, in `solution.css`, provides a way to address this issue effectively.

## Problem

CSS specificity rules sometimes lead to unexpected results. A more general rule might unintentionally override a more specific rule due to the pseudo-class involved.

## Solution

The solution might involve carefully considering the specificity of your CSS rules and using the appropriate selector to get the intended result.  This may involve restructuring your CSS to ensure correct inheritance and specificity levels are achieved.