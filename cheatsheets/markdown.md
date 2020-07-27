# Markdown Guide

## 1. Headlines

Enter a **#** before adding your headline.

To use sub headlines, add more **#**.

You can add up to 6 different headlines.

_Example:_

```
# This is a h1 Headline

## This is a h2 Headline

### This is a h3 Headline
```

_Output:_

---

# This is a h1 Headline

## This is a h2 Headline

### This is a h3 Headline

---

## 2. Paragraphs

Lines of text will be interpreted as a single paragraph.
In order to start a new paragraph you'll have to insert an extra new line between them.

Like this.

To cause a line break, add two spaces at the end of a line

Like  
this

## 3. Emphasis

_Example:_

```
**this is bold text**

*This is italic text*

~~Strikethrough~~
```

_Output:_

**this is bold text**

_This is italic text_

~~Strikethrough~~

## 3. Horizontal rule

To add a horizontal line just add three dashes.

_Example:_

```
---
```

_Output:_

---

## 4. Lists

Unordered

- Create a list by starting a line with - + or \*
- but use the dash obviously
  - indented list item by indenting the list
  - Another item

Ordered

1. This is an ordered list
2. You can create an ordered list by starting with 1.
3. The numbers are actually irrelevant
4. As you can see here.

## 5. Block quotes

_Example:_

```
> Blockquotes can also be nested
> > by using an additional greather than sign
> > > here is the third level of nesting
> > > > still workds
> > > > > still
> > > > > > crazyyyy
```

_Output:_

> Blockquotes can also be nested
>
> > by using an additional greather than sign
> >
> > > here is the third level of nesting
> > >
> > > > still workds
> > > >
> > > > > still
> > > > >
> > > > > > crazyyyy

## 6. Code snippets

To use inline code snippets, surround your code by using the ` character.

_Example:_

```
Inline `code snippet`
```

_Output:_

Inline `code snippet`

To insert full blocks of code surround the code by three _`_ characters each

_Example:_

````
```
This is some cool source code...
```
````

_Output:_

```
This is some cool source code...
```

To use Syntax highlighting specify the language of your code after the opening ``` characters

_Example:_

````
```js
const foo = function (bar) {
  return bar++;
};
cinsole.log(foo(5));
```
````

_Output:_

```js
const foo = function (bar) {
  return bar++;
};
cinsole.log(foo(5));
```

## 7. Links

To use links you have to combine square brackets and paranthesis.

Enter your displayed Link text into the square brackets and the link itself into the paranthesis

_Example:_

```
[Enter the link text here](main.html)
```

_Output:_

[Enter the link text here](main.html)

If you don't want to specify the displayed text and use the link itself you can just set the link into <>

_Example:_

```
Auto converted link <https://github.com>
```

_Output:_

Auto converted link <https://github.com>

## 8. Images

Images work in a similar fashion. Just add an Exclamation point **!** in front. The text in the square brackets is used as an alt text.

_Example:_

```
![Minion](https://octodex.github.com/images/minion.png)
```

_Output:_

![Minion](https://octodex.github.com/images/minion.png)

## 9. Tables

Tables are weird. Basically you just have to draw one yourself.
Start out by putting the top row into these vertical lines |.

Then specify by using the next line to draw the table containing dashes.

To align your text to the right or left hand side, use a colon.

_Example:_

```
| First name | Last name |
| ---------- | --------: |
| Dorian     |   Wilhelm |
| Other      |    People |
```

_Output:_

| First name | Last name |
| ---------- | --------: |
| Dorian     |   Wilhelm |
| Other      |    People |

## 10. Inline HTML

Inline html works just like html. Just write your code in html and it will be automatically converted to html.

_Example:_

```html
<h3>This is an h3</h3>

<details>Some hidden content</details>
```

_Output:_

<h3>This is an h3</h3>

<details>Some hidden content</details>

## Escaping

\# This is not a heading

## Keyboard keys

<kbd></kbd>
