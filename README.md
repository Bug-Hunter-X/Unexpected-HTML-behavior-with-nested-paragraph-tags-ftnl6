# Unexpected HTML Behavior with Nested Paragraph Tags

This repository demonstrates a common, yet subtle, HTML error involving nested `<p>` (paragraph) tags.  The issue arises from the implicit closing of tags by the HTML parser, leading to unexpected rendering and potentially impacting accessibility and semantics.

The `bug.html` file shows the erroneous code, while `bugSolution.html` provides the corrected version.

## Problem

When nested `<p>` tags are improperly structured, the HTML parser may implicitly close tags prematurely. This can cause text to be rendered incorrectly and introduce unintended formatting.

## Solution

The solution is to ensure correct nesting of tags and to avoid implicit tag closure by properly structuring your HTML elements.  Using appropriate container elements (like `<div>`) with semantic meaning will resolve this.