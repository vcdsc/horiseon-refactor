# Module 1 Challenge: Horiseon Code Refactor

## Description

This challenge's theme was accessibility. Main goals were to ensure Client's codebase follows accessibility standards, which entails:

- Use of semantic HTML elements.
- Images and icon elements contain accessible alt attributes.

# Main Takeaways

- The use of semantic HTML elements not only makes for a more easily maintainable codebase (since elements follow a logical structure), it can also have impacts on the quality of information screen readers can capture. For instance, if we leave an `img` `alt` attribute empty a screen reader will skip over it, so if the image has a purpose other than decoration and it adds to the meaning of the text next to it, the `alt` attribute will provide a better user experience to a screen reader user.

- Not only is the use of the `alt` attribute important, the quality of the information contain within it is so as well. The `alt` attribute should be as descriptive as possible, and we should not rely on just keywords or generalizations.

- In terms of the effects of the use of semantic HTML elements on the CSS, any styling that was dependent on more general selectors, such as `div`, for instance, need to be adjusted so the style of the page can remain unaffected.

- Where possible, grouping CSS selectors results in a cleaner CSS style sheet, and us abiding by [the DRY principle](https://en.wikipedia.org/wiki/Don%27t_repeat_yourself).

## GitHub Pages

Deployed version of the website can be seen [here]().

## License

Please refer to the LICENSE in the repo.
