# This is a github learning repository

---
**This is bold.** <br>
*This is italic,* <br>
__This is bold.__ <br>
_This is italic_ <br>
~~Strikethrough~~ <br>
___
## Blockquotes:
I am in a blockquote. See! whatever you write here will be within this block. CHeck that out. 
Lorem ipsum dolor sit amet, consectetur adipiscing elit. Etiam ultricies lectus vel laoreet auctor. Pellentesque facilisis hendrerit neque, eu convallis purus pulvinar vitae. Nam venenatis mattis odio. Ut imperdiet fringilla sagittis. Sed ipsum nunc, pharetra sit amet justo in, ultrices faucibus metus. Nunc quis enim a elit facilisis mollis. Donec eleifend, lectus non laoreet vulputate, mauris risus suscipit odio, non ornare magna erat semper elit. Nunc ac enim non nibh ullamcorper rutrum. Aliquam dictum ligula nec ipsum sodales, 

eget fermentum arcu tempus. Duis et arcu quis lectus porttitor congue. Suspendisse tempor sit amet purus a varius. Duis commodo aliquam mi eget finibus. Interdum et malesuada fames ac ante ipsum primis in faucibus. Orci varius natoque penatibus et magnis dis parturient montes, nascetur ridiculus mus. Pellentesque leo est, congue nec nibh at, sollicitudin porttitor dolor.


___
## Lists:
### Unordered:

+ first
+ second
+ third
  + sublist (indent 2 spaces)
  + sublist 2
+ fourth

### Ordered lists:
1. first
2. second
3. third

---
### Code blocks:
Inline `code` <br>

Indented `code`

**Block of code**
```python
    #  python comments
    def remainder(a, b):
      return a%b
```
---
## Tables:
| Option | Description |
| ------ | ----------- |
| data   | path to data files to supply the data that will be passed into templates. |
| engine | engine to be used for processing templates. Handlebars is the default. |
| ext    | extension to be used for dest files. |

Right aligned columns
| Option | Description |
| ------:| -----------:|
| data   | path to data files to supply the data that will be passed into templates. |
| engine | engine to be used for processing templates. Handlebars is the default. |
| ext    | extension to be used for dest files. |

---
## Links:
[link test](http://dev.nodeca.com)

[link with title](http://nodeca.github.io/pica/demo/ "title text!")

Autoconverted link https://github.com/nodeca/pica (enable linkify to see)
---
## Images:

![Minion](https://octodex.github.com/images/minion.png)
![Stormtroopocat](https://octodex.github.com/images/stormtroopocat.jpg "The Stormtroopocat")

Like links, Images also have a footnote style syntax

![Alt text][id]

With a reference later in the document defining the URL location:

[id]: https://octodex.github.com/images/dojocat.jpg  "The Dojocat"

---

## Plugins

The killer feature of `markdown-it` is very effective support of
[syntax plugins](https://www.npmjs.org/browse/keyword/markdown-it-plugin).


### [Emojies](https://github.com/markdown-it/markdown-it-emoji)

> Classic markup: :wink: :crush: :cry: :tear: :laughing: :yum:
>
> Shortcuts (emoticons): :-) :-( 8-) ;)

see [how to change output](https://github.com/markdown-it/markdown-it-emoji#change-output) with twemoji.


### [Subscript](https://github.com/markdown-it/markdown-it-sub) / [Superscript](https://github.com/markdown-it/markdown-it-sup)

- 19^th^
- H~2~O


### [\<ins>](https://github.com/markdown-it/markdown-it-ins)

++Inserted text++


### [\<mark>](https://github.com/markdown-it/markdown-it-mark)

==Marked text==


### [Footnotes](https://github.com/markdown-it/markdown-it-footnote)

Footnote 1 link[^first].

Footnote 2 link[^second].

Inline footnote^[Text of inline footnote] definition.

Duplicated footnote reference[^second].

[^first]: Footnote **can have markup**

    and multiple paragraphs.

[^second]: Footnote text.


### [Definition lists](https://github.com/markdown-it/markdown-it-deflist)

Term 1

:   Definition 1
with lazy continuation.

Term 2 with *inline markup*

:   Definition 2

        { some code, part of Definition 2 }

    Third paragraph of definition 2.

_Compact style:_

Term 1
  ~ Definition 1

Term 2
  ~ Definition 2a
  ~ Definition 2b


### [Abbreviations](https://github.com/markdown-it/markdown-it-abbr)

This is HTML abbreviation example.

It converts "HTML", but keep intact partial entries like "xxxHTMLyyy" and so on.

*[HTML]: Hyper Text Markup Language

### [Custom containers](https://github.com/markdown-it/markdown-it-container)

::: warning
*here be dragons*
:::


