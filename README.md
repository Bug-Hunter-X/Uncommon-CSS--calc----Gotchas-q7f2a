# Uncommon CSS `calc()` Gotchas

This repository demonstrates some uncommon issues that can arise when using the `calc()` function in CSS. These issues are often subtle and can lead to unexpected behavior if not properly understood.

## Issues Addressed:

*   **Percentages within `calc()`:**  The behavior of percentages within `calc()` calculations can be surprising if you are not considering the context of percentage calculation.
*   **Operator Precedence:**  `calc()` follows standard mathematical order of operations. Understanding this is important to make sure the calculations are done in the correct order.
*   **Browser Compatibility:** Although widely supported, ensure that you test `calc()` in different browsers for compatibility.

## How to Reproduce

1.  Clone this repository.
2.  Open `bug.css` and `bugSolution.css` to see the examples.
3.  Experiment with changing the parent container's width in the HTML to observe the different outcomes.