# Markdown Cheat Sheet

## Table of Contents
- [Typography](#typography)
- [Headers](#headers) 
- [Lists](#lists)
- [Links](#links)
- [Alignment](#alignment)
- [Drop Down Menus](#drop-down-menus)
- [Images and Video](#images-and-video)
- [Tips and Tricks](#other-tips-and-tricks)

## Typography
Words can be **bold with two asteriks or two underlines**, *italic with one asterisks or one underline*, ~strike through~, or `coded`. 

> You can use > for "Block Quotes"

## Headers
# H1 - Titles
## H2 - Headers
### H3 - Smaller Headings
#### H4 - Normal, bold text
##### H5 - Smaller than normal
Headers 1 and 2 automatically create line breaks, but you can use dashes or equal signs to add them in as well. 

## Lists
Help break up information into readable bullet points:
- Point
  - Subpoint
    - subpoint

Break things down chronologically or step by step: 
1. Step One
    1. First
        1. subpoint
2. Step Two
    1. First
        1. subpoint
3. Step Three
    1. First
        1. subpoint
- [x] Don't forget task lists! 
- [ ] They can come in handy to get things done. 

## Links
Links can be:
- [Inline Style](https://github.com/newshipt/TechHub) 
- [Inline Style with Title](https://github.com/newshipt/TechHub "TechHub")
- [Relative Reference to a Repository](../tree/master/culture) 
- [Reference Style Link][this is a reference]
- [Numbers Reference Style Link][1]
- [Link to the Text Itself]

[this is a reference]: https://github.com/newshipt/TechHub
[1]: https://github.com/newshipt/TechHub
[Link to the text itself]: https://github.com/newshipt/TechHub

## Alignment

<div align="right">Align to the right.</div>
<div align="center">You can align to center also.</div>
<div align="left">Or align left.</div>

## Drop Down Menus
<details> <summary>Drop Down Menu</summary>

You can hide text this way or create a menu to other links and links within the document itself.
</details>
</br>
<details open> <summary>Open Drop Down Menu</summary>

If you want the text to be visible but containable, open drop downs can be useful. 
</details>
</br>



 
## Other Tips and Tricks

- Spacing is important, especially in Markdown on Github. It's the difference between:

####This 

and
#### This
- You can do emojis :neutral_face:! If you're interested in that sort of thing :laughing:
  - You can find more available emojis [here](https://gist.github.com/rxaviers/7360908 "Complete List of GitHub Emojis"). 
- **Highlighting inside of inline text:** 
```diff
+ Can only highlight green in here

- Can only highlight red in here
``` 
- **Hanging Indents**
<dl>
  <dt>How about a hanging indent?</dt>
  <dd>Good for Q&A.</dd>
</dl>

For additional reading, check out [GitHub Flavored Markdown](https://help.github.com/categories/writing-on-github/). 
