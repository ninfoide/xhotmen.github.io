+++
title = "Handwriting Shortcode"
date = "2017-06-26T23:52:34-07:00"
hide_authorbox = true
disable_comments = true
categories = ["Documentation"]
[menu.main]
  weight = 1
  parent = "docs-shortcodes"
+++

Sometimes (sans-)serif fonts just don't cut it for what you're writing. You're posting a letter on your website and want it to look handwritten, or at least have the signature look handwritten. The `handwriting` shortcode provides you with a number of available handwriting fonts to achieve this effect.

<!--more-->

# Usage

```
{{%/* handwriting "font-name" */%}}
This text will look handwritten.
{{%/* /handwriting */%}}
```

Be sure to use `%%` and not `<>` as the one with `%` sends the content through the markdown parser, allowing you to still have bold, italics, etc. with your handwriting font. More [here](https://gohugo.io/extras/shortcodes/#shortcodes-with-markdown).

Available fonts are:

- `"allura"`
- `"calligraffiti"`
- `"dancing-script"`
- `"daniel"`
- `"euphoria-script"`
- `"journal"`
- `"kingthings-wrote"`
- `"note-this"`
- `"vag-handwritten"`

All fonts come from [FontSquirrel](https://www.fontsquirrel.com/), a website devoted to providing 100% free fonts, including for commercial use.
