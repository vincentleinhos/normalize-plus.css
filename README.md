# standardize.css

<a href="http://vincentleinhos.com/standardize/"><img
  src="http://vincentleinhos.com/standardize/img/github.png" alt="standardize.css logo" align="right" style=""></a>

> standardize.css combines the best of CSS **resets** and **normalize**.css in line with modern standards.

[standardize.css](http://vincentleinhos.com/standardize/) is based on
[normalize.css](https://github.com/necolas/normalize.css) v4.1.1.

## What does it do?

| normalize.css | CSS reset | standardize.css |
|     :---:     |   :---:   |      :---:      |
| Preserves useful defaults | **Let you start from scratch** | Mostly like a CSS reset: No predefined rules that are likely to be overwritten anyway. For example, normalize.css: `font-family: sans-serif` *Comment: Why? Once you change the font,.. such lines are unnecessary* |
| **Corrects bugs and common browser inconsistencies** | - | Same as normalize.css |
| **Explains what code does** using detailed comments | - | Same as normalize.css |
| - | - | **Improves text readability and flexibility of elements**. For example, using better font-rendering, `border-box` and making images responsive |
| - | - | Includes the [**clearfix hack**](http://nicolasgallagher.com/micro-clearfix-hack/) by Nicolas Gallagher |
| - | - | Use the **compressed** CSS, which is four times smaller, for faster page loads |

## Install

[Download the compressed, production standardize.min.css](http://vincentleinhos.com/standardize.min.css).

[Download the uncompressed, development standardize.css](http://vincentleinhos.com/standardize.css).

Link to standardize inside the head section; no other style should come before this.
Fell free to adapt it to your needs.

## Browser support

* Chrome
* Firefox (+ ESR)
* Edge
* Internet Explorer 8+
* Safari 6+
* Opera

## Acknowledgements

Thankful for normalize.css – a project by [Nicolas Gallagher](https://github.com/necolas),
co-created with [Jonathan Neal](https://github.com/jonathantneal).
