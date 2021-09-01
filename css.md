## What is CSS
  CSS helps you to create great-looking web pages by defining rules that your webpage will use.

  ## CSS example
    " h1 { color: red; font-size 5em;}"
    In this example your h1 text would be red with a text size of 5em.

    In the previous example h1 would be considered the selector. Whats inside the curly braces would be the declarations, wich can be multiple things wich form property and value pairs.

      Css is broken down into modules, [MDN](https://developer.mozilla.org/en-US/docs/Web/CSS/Reference) is a good place to go to reference these.

  ## Three ways to insert CSS
    * External CSS
    * Internal CSS
    * Inline CSS

  ### External CSS
    Handy !  Do your CSS work seperately then "reference" your html document to your ext. css file.

  ### Internal CSS
    The internal style is defined inside the <style> element, inside the head section.

  ### Inline CSS
    To use inline styles, add the style attribute to the relevant element. The style attribute can contain any CSS property.

  ## Cascading Order
    What style will be used when there is more than one style specified for an HTML element?

All the styles in a page will "cascade" into a new "virtual" style sheet by the following rules, where number one has the highest priority:

Inline style (inside an HTML element)
External and internal style sheets (in the head section)
Browser default
So, an inline style has the highest priority, and will override external and internal styles and browser defaults.






