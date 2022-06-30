Cheatsheet on the syntax for styling README.md files for github

regular text

# the smallest heading

## the second largest heading

###### the smallest heading

**bold**
_italic_
**bold and nested_italic_text**
~~strikethrough~~
**_All bold and italic_**
<sub>subscript text</sub>
<sup>superscript text</sup>

Read the quote :

> This text is a quote

Some basic Git commands are. this is how to make a code block :

```
git status
git add
git commit
```

How to make a link :
This is a link to [google](https://www.google.com)

how to get a nested link -
[My portfolio page](nested/index.html)

How to get an image -
![This is an image](images/583231.png)

how to display for light and dark theme :
<picture>

  <source media="(prefers-color-scheme: dark)" srcset="https://user-images.githubusercontent.com/25423296/163456776-7f95b81a-f1ed-45f7-b7ab-8fa810d529fa.png">
  <source media="(prefers-color-scheme: light)" srcset="https://user-images.githubusercontent.com/25423296/163456779-a8556205-d0a5-45e2-ac17-42d089e3c3f8.png">
  <img alt="Shows an illustrated sun in light color mode and a moon with stars in dark color mode." src="https://user-images.githubusercontent.com/25423296/163456779-a8556205-d0a5-45e2-ac17-42d089e3c3f8.png">
</picture>

- List item 1
- List item 2
- List item 3

* List item 1
* List item 2
* List item 3

1. List item 1

- List item 1.1
- List item 1.2
- List item 1.1.1

2. List item 2
3. List item 3

To create a task list, preface list items with a hyphen and space followed by [ ]. To mark a task as complete, use [x]:

- [x] #739
- [ ] https://github.com/octo-org/octo-repo/issues/740
- [ ] Add delight to the experience when all tasks are complete :tada:

footnotes :
Here is a simple footnote[^1].
A footnote can also have multiple lines[^2].  
You can also use words, to fit your writing style more closely[^note].
[^1]: My reference.
[^2]: Every new line should be prefixed with 2 spaces.  
 This allows you to have a footnote with multiple lines.
[^note]:
Named footnotes will still render with numbers instead of the text but allow easier identification and linking.  
 This footnote also has been made with a different syntax using 4 spaces for new lines.

<!-- This is a comment -->
