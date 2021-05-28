<!-- Headers -->
# Headers

```
# Header 1
## Header 2
### Header 3
#### Header 4
##### Header 5
###### Header 6
```

# Header 1
## Header 2
### Header 3
#### Header 4
##### Header 5
###### Header 6

```
Alternatively, for H1 and H2, an underline-ish style:

Header 1
=

Header 2
-
```

Alternatively, for H1 and H2, an underline-ish style:

Header 1
=
Header 2
-

<!-- Emphasis -->
# Emphasis

```
Emphasis, aka italics, with *asterisks* or _underscores_.

Strong emphasis, aka bold, with **asterisks** or __underscores__.

Combined emphasis with **asterisks and _underscores_**.

Strikethrough uses two tildes. ~Scratch~ and ~~Scratch this.~~
```

Emphasis, aka italics, with *`asterisks`* or _`underscores`_.

Strong emphasis, aka bold, with **`asterisks`** or __`underscores`__.

Combined emphasis with **`asterisks and`_`underscores`_**.

Strikethrough uses two tildes. ~`Scratch`~ and ~~`Scratch this`~~

<!-- Blockquote -->
# Blockquote
```
> blockquote
```
> blockquote

<!-- Inline Code -->
# Inline Code
```
The `createServer()` method of `http` creates a new HTTP server and returns it.
```
The `createServer()` method of `http` creates a new HTTP server and returns it.


<!-- Horizontal Rule -->
# Horizontal Rule
```
---
___
```
---
___

<!-- Lists -->
# Lists

```
Unordered list use asterisks (*), minuses (-) and pluses (+)

* Unordered list can use asterisks
- Or minuses
+ Or pluses

    You can have properly indented paragraphs within list items. Notice the blank line above,
    and the leading spaces (at least one, but we'll use three here to also align the raw Markdown).

1. First ordered list item
2. Another item
    * Unordered sub-list. 
    * Unordered sub-list. 
3. Actual numbers don't matter, just that it's a number
    1. Ordered sub-list
    2. Ordered sub-list
4. And another item.

To have a line break without a paragraph, you will need to use two trailing spaces.
Note that this line is separate, but within the same paragraph.

    (This is contrary to the typical GFM line break behaviour, where trailing spaces are not required.)
```


Unordered list use asterisks (*), minuses (-) and pluses (+)

* Unordered list can use asterisks
- Or minuses
+ Or pluses

    You can have properly indented paragraphs within list items. Notice the blank line above,
    and the leading spaces (at least one, but we'll use three here to also align the raw Markdown).

1. First ordered list item
2. Another item
    * Unordered sub-list. 
    * Unordered sub-list. 
3. Actual numbers don't matter, just that it's a number
    1. Ordered sub-list
    2. Ordered sub-list
4. And another item.

To have a line break without a paragraph, you will need to use two trailing spaces.
Note that this line is separate, but within the same paragraph.

    (This is contrary to the typical GFM line break behaviour, where trailing spaces are not required.)


<!-- Link -->
# Link
```
Inline-style:

Format: `[link text](url "title")`

https://github.com - automatic!

[GitHub](http://github.com "GitHub")


Reference-style: 

Format: `[name] url "title"`

[url]: https://github.com/jabed-dev "Jabed Hossain"

[Jabed Hossain][url]

[jabed-dev][url]
```

Inline-style:

Format: `[link text](url "title")`

https://github.com - automatic!

[GitHub](http://github.com "GitHub")


Reference-style: 

Format: `[name] url "title"`

[url]: https://github.com/jabed-dev "Jabed Hossain"

[Jabed Hossain][url]

[jabed-dev][url]

<!-- Image -->
# Image 

```
Inline-style:

Format: ![Alt massage](url "title")

![GitHub](https://github.githubassets.com/images/modules/open_graph/github-mark.png "GitHub")

Image resize: <img src="url" alt="GitHub" width="200" height="150">

<img src="https://github.githubassets.com/images/modules/open_graph/github-mark.png" alt="GitHub" width="200" height="150">

Reference-style: 
Format: [name] url "title"

[image-name]: https://github.com/adam-p/markdown-here/raw/master/src/common/images/icon48.png "Markdown"

![Markdown Image][image-name]

![markdown Image][image-name]

link with image

[![Alt massage](image url)](link url)

[![Octocat](https://github.githubassets.com/images/icons/emoji/octocat.png "https://github.com")](https://github.com)
```

Inline-style:

Format: `![Alt massage](url "title")`

![GitHub](https://github.githubassets.com/images/modules/open_graph/github-mark.png "GitHub")

Image resize: `<img src="url" alt="GitHub" width="350" height="200">`

<img src="https://github.githubassets.com/images/modules/open_graph/github-mark.png" alt="GitHub" width="350" height="200">

Reference-style: 
Format: `[name] url "title"`

[image-name]: https://github.com/adam-p/markdown-here/raw/master/src/common/images/icon48.png "Markdown"

![Markdown Image][image-name]
![markdown Image][image-name]
![markdown Image][image-name]

link with image

`[![Alt massage](image url)](link url)`

[![Octocat](https://github.githubassets.com/images/icons/emoji/octocat.png "https://github.com")](https://github.com)


<!-- Videos -->
# Videos

```
Formate-1: [![Alternate Text]({image-url})]({video-url} "Link Title")

Formate-2: <a href="{video-url}" title="Link Title"><img src="{image-url}" alt="Alternate Text" /></a>
```

<!-- Emoji -->
# Emoji 

```
GitHub supports 
Emoji URL: https://gist.github.com/rxaviers/7360908 

Format:  :emoji name:

emoji!:+1: :sparkles: :camel: :tada:
:rocket: :metal: :octocat: 
```

GitHub supports 
Emoji URL: https://gist.github.com/rxaviers/7360908 

Format: `:emoji name:`

Emoji!

:+1: :sparkles: :camel: :tada: :rocket: :metal: :octocat: :star:


<!-- CODE BLOCKS -->
# CODE BLOCKS

~~~

Formate 1: ```
          code here..
          ```
            
Formate 2: ~~~
            code here..
           ~~~

Syntax-1 not language highlight: 

```
  code here..
```

Syntax-2 language highlight: 

```language name here
  code here..
```
~~~

Syntax 1:
```
let number = 20;
function test() {
    console.log("look ma’, no spaces"); 
}
```

Syntax 2:
```javascript
let number = 20;
function test() {
    console.log("look ma’, no spaces"); 
}
```

<!-- Tables -->
# Tables

```
Header-1 | Header-1 | Header-3
-------- | -------- | --------
Item-1   | Item-2   | Item-3
Item-4   | Item-5   | Item-6
Item-7   | Item-8   | Item-9
```
Header-1 | Header-1 | Header-3
-------- | -------- | --------
Item-1   | Item-2   | Item-3
Item-4   | Item-5   | Item-6
Item-7   | Item-8   | Item-9

<!-- Task List -->
# Task List
```
- [x] Write the press release
- [ ] Update the website
- [x] Contact the media 
```
- [x] Write the press release
- [x] Update the website
- [ ] Contact the media 


<!-- GitHub User name -->
# GitHub User name

```
[@jabed-dev](https://github.com/jabed-dev "Jabed Hossain")
```

[@jabed-dev](https://github.com/jabed-dev "Jabed Hossain")


<!-- Backslash Escapes -->
# Backslash Escapes

```
Markdown allows you to use backslash escapes to generate literal characters which would
otherwise have special meaning in Markdown’s formating syntax.

\*literal asterisks\*

\_literal asterisks\_
```
Markdown allows you to use backslash escapes to generate literal characters which would
otherwise have special meaning in Markdown’s formating syntax.

\*literal asterisks\*

\_literal asterisks\_

<!-- Comments -->
# Comments

```
<!-- comments here.. -->
```

