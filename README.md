# filemaker-html-utils-package


The [filemaker-html-utils-package]((https://github.com/mrwatson-de/espanso-filemaker-html-utils-package))
is a clone of the [html-utils-package](https://github.com/woodenbell/html-utils-package) for FileMaker developers,
but with the trigger prefix `:;`instead of `::` (which would be problematic in the FileMaker world!)

`:;` is the best internationally-acceptable trigger sequence that I could find:

- It starts with the standard espanso trigger letter `:`
- It is not so dissimilar to the `::` trigger of the original module
- On German keyboards it's just the two neighbouring keys `.` and `,` with the `SHIFT` key (which nicely rolls off the fingers)
- On most English / U.S. keyboards it's the same key twice: `:' and then again with `SHIFT` (which is nearly as good)

Happy FileMaking !

MrWatson

---

Make HTML5 easier and less time-consuming with this [Espanso](https://espanso.org/) package!


# Installation

Make sure you have already installed [Espanso](https://espanso.org/install/) first.

```
espanso install html-utils-package
espanso restart
```

That's all. You can start using the package. Open your favorite editor and type `:doctype` to test!

# Triggers

| Trigger  | Result |
| ------------- | ------------- |
| `:;docskel` | Generates an empty document with `utf-8` and `viewport` headers (unindented) |
| `:;doctype` | `<!DOCTYPE html>` |
| `:;charset` | `<meta charset="">` |
| `:;utf-8` | `<meta charset="UTF-8">` |
| `:;viewport` | `<meta name="viewport" content="width=device-width, initial-scale=1">` |
| `:;meta-author` | `<meta name="author" content="">` |
| `:;meta-desc` | `<meta name="description" content="">` |
| `:;meta-keywords` | `<meta name="keywords" content="">` |
| `:;title` | `<title></title>` |
| `:;div` | `<div></div>` |
| `:;html` | `<html></html>` |
| `:;head` | `<head></head>` |
| `:;body` | `<body></body>` |
| `:;a` | `<a href=""></a>` |
| `:;br` | `<br>` |
| `:;button` | `<button type="button"></button> ` |
| `:;style` | `<style></style>` |
| `:;css` | `<link rel="stylesheet" type="text/css" href="">` |
| `:;script` | `<script></script>` |
| `:;js` | `<script type="text/javascript" src=""></script>` |
| `:;form` | `<form action="" method=""></form>` |
| `:;label` | `<label for=""></label>` |
| `:;submit` | `<input type="submit" value="">` |
| `:;input-text` | `<input type="text" name="" id="">` |
| `:;input-password` | `<input type="password" name="" id="">` |
| `:;input-radio` | `<input type="radio" name="" id="" value="">` |
| `:;input-checkbox` | `<input type="checkbox" name="" id="" value="">` |
| `:;input-file` | `<input type="file" name="" id="">` |

# Contributions to the original html-utils-package
If you feel like there's any important tag/snippet missing, feel free to create a Pull Request or open an [Issue on the original package](https://github.com/woodenbell/html-utils-package/issues/new).

# Contributions to the filemaker-html-utils-package
If there's a problem with the FileMakerization of trhe module, feel free to create a Pull Request or open an [Issue on this package](https://github.com/mrwatson-de/espanso-filemaker-html-utils-package/issues/new).


