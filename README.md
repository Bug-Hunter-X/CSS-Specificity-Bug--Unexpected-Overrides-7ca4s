# CSS Specificity Bug: Unexpected Overrides

This repository demonstrates a subtle bug related to CSS selector specificity. The bug arises from the overlapping specificity of selectors, leading to unexpected styling overrides. The solution illustrates how to resolve this issue by carefully considering the order and specificity of selectors.

## Bug Description

The provided CSS code contains multiple selectors targeting paragraph elements within a div. However, the unexpected behavior happens due to a combination of class, id, and element selectors which may conflict with each other. 