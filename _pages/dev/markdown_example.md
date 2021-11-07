---
title: "markdown_example"
layout: single
toc: false
permalink: /dev/markdown_example
published: true
hidden: false
---

<br>

<font size="5">
  <b> text : style </b>
</font>

| style | language | syntax | output |
| :-    | :-       | :-     | :-     |
| italic | Markdown | `*italic*`{:.language-yaml .highlight} | *italic* |
|        | HTML     | `<i> italic </i>`{:.language-yaml .highlight} | <i> italic </i> |
|        | CSS      | `<font style="font-style:italic"> italic </font>`{:.language-yaml .highlight} | <font style="font-style:italic"> italic </font> |
| bold | Markdown | `**bold**`{:.language-yaml .highlight} | **bold** |
|      | HTML     | `<b> bold </b>`{:.language-yaml .highlight} | <b> bold </b> |
|      | CSS      | `<font style="font-weight:bold"> bold </font>`{:.language-yaml .highlight} | <font style="font-weight:bold"> bold </font> |
  
***
***

<font size="5">
  <b> text : line </b>
</font>

| line | language | syntax | output |
| :-   | :-       | :-     | :-     |
| underline | HTML | `<u> underline </u>`{:.language-yaml .highlight} | <u> underline </u> |
|           | CSS  | `<font style="text-decoration:underline"> underline </font>`{:.language-yaml .highlight} | <font style="text-decoration:underline"> underline </font> |
| strike | HTML | `<s> strike </s>`{:.language-yaml .highlight} | <s> strike </s> |
|        | CSS  | `<font style="text-decoration:line-through"> strike </font>`{:.language-yaml .highlight} | <font style="text-decoration:line-through"> strike </font> |
| overline | CSS | `<font style="text-decoration:overline"> overline </font>`{:.language-yaml .highlight} | <font style="text-decoration:overline"> overline </font> |
| dotted | CSS | `<font style="text-decoration:underline dotted"> dotted </font>`{:.language-yaml .highlight} | <font style="text-decoration:underline dotted"> dotted </font> |

***
***

<font size="5">
  <b> text : color </b>
</font>

| color | language | syntax | output |
| :-    | :-       | :-     | :-     |
| text | HTML | `<font color="yellow"> yellow </font>`{:.language-yaml .highlight} | <font color="yellow"> yellow </font> |
|      | CSS  | `<font style="color:yellow"> yellow </font>`{:.language-yaml .highlight} | <font style="color:yellow"> yellow </font> |
| background | CSS | `<font style="background-color:darkgray"> darkgray </font>`{:.language-yaml .highlight} | <font style="background-color:darkgray"> darkgray </font> |

***
***

<font size="5">
  <b> structure : heading </b>
</font>

```text
# level 1
## level 2
### level 3
```
# level 1
## level 2
### level 3

***
***

<font size="5">
  <b> structure : blockquote </b>
</font>

```text
> level 1
>> level 2
>>> level 3
```
> level 1
>> level 2
>>> level 3

inline > quote test

***
***

<font size="5">
  <b> structure : list </b>
</font>

```text

```
- AAA
  - aaa
    - aaaaaa
- BBB
  1. first
  3. second
  5. third
- CCC
  - [ ] to do
  - [x] done

***
***

<font size="5">
  <b> structure : table </b>
</font>

```text
| left | center | right |
| :-   | :-:    | -:    |
| text | text   | text  |
| left<br>left_left_left | center<br>center_center_center | right<br>right_right_right |
```

| left | center | right |
| :-   | :-:    | -:    |
| text | text   | text  |
| left<br>left_left_left | center<br>center_center_center | right<br>right_right_right |

***

<font size="5">
  <b> code : inline </b>
</font>

```text
inline code `SELECT * FROM t` shown
```
inline code `SELECT * FROM t`{:.language-yaml .highlight} shown

***
***

<font size="5">
  <b> code : block </b>
</font>

```text
\```python
\print('one')
\print('two')
\```
```
```python
print('one')
print('two')
```

***
***

<font size="5">
  <b> emoji : square </b>
</font>

| syntax | symbol |
| :- | :-: |
| `:red_square:`{:.language-yaml .highlight} | 🟥 |
| `:orange_square:`{:.language-yaml .highlight} | 🟧 |
| `:yellow_square:`{:.language-yaml .highlight} | 🟨 |
| `:green_square:`{:.language-yaml .highlight} | 🟩 |
| `:blue_square:`{:.language-yaml .highlight} | 🟦 |
| `:purple_square:`{:.language-yaml .highlight} | 🟪 |
| `:brown_square:`{:.language-yaml .highlight} | 🟫 |
| `:white_large_square:`{:.language-yaml .highlight} | ⬜ |
| `:black_large_square:`{:.language-yaml .highlight} | ⬛ |

***
***

<font size="5">
  <b> emoji : circle </b>
</font>

| syntax | symbol |
| :- | :-: |
| `:red_circle:`{:.language-yaml .highlight} | 🔴 |
| `:orange_circle:`{:.language-yaml .highlight} | 🟠 |
| `:yellow_circle:`{:.language-yaml .highlight} | 🟡 |
| `:green_circle:`{:.language-yaml .highlight} | 🟢 |
| `:large_blue_circle:`{:.language-yaml .highlight} | 🔵 |
| `:purple_circle:`{:.language-yaml .highlight} | 🟣 |
| `:brown_circle:`{:.language-yaml .highlight} | 🟤 |
| `:white_circle:`{:.language-yaml .highlight} | ⚪ |
| `:black_circle:`{:.language-yaml .highlight} | ⚫ |

***
***

<font size="5">
  <b> image </b>
</font>

```text
[GitHub][github_logo]
![GitHub][github_logo]{width=200}
[github_logo]: https://upload.wikimedia.org/wikipedia/commons/thumb/2/29/GitHub_logo_2013.svg/1200px-GitHub_logo_2013.svg.png
```
[GitHub][github_logo]
![GitHub][github_logo]{width=200}
[github_logo]: https://upload.wikimedia.org/wikipedia/commons/thumb/2/29/GitHub_logo_2013.svg/1200px-GitHub_logo_2013.svg.png
