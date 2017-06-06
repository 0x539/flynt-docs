---
title: Styling
weight: 32
menu:
  main:
    parent: components
    identifier: component-styling
    weight: 32
---

Each component can have a style file. By default, Flynt supports vanilla CSS files, and the pre-processor [Stylus](http://stylus-lang.com/).

The style file should be named `style`, and be placed within the individual component folder. This file will be automatically compiled to the `dist` folder in the same location.

For example: `Components/ExampleComponent/style.styl` compiles to `dist/Components/ExampleComponent/style.css`

**This will not automatically enqueue the styles in the front-end.** To do this, you must enqueue the files within the component's `functions.php` file. [Learn how to do this here](functions.md#enqueueing-assets-and-dependencies).

It is also possible to add support for other pre-processors with gulp. [See an example of how to switch to SASS here](../core/customization/changing-style-language.md).