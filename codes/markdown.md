[Home](/) [Codes](/codes/)

# Markdown Guide

## 1. Headlines


Enter a **#** before adding your headline.

To use sub headlines, add more **#**.

You can add up to 6 different headlines.

*Example:*
```
# This is a h1 Headline

## This is a h2 Headline

### This is a h3 Headline
```

*Output:*

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

*Example:*

```
**this is bold text**

*This is italic text*

~~Strikethrough~~
```

*Output:*

**this is bold text**

*This is italic text*

~~Strikethrough~~

## 3. Horizontal rule

To add a horizontal line just add three dashes.

*Example:*

```
---
```

*Output:*

---

## 4. Lists

Unordered

- Create a list by starting a line with - + or *
- but use the dash obviously
  - indented list item by indenting the list
  - Another item

Ordered

1. This is an ordered list
2. You can create an ordered list by starting with 1.
3. The numbers are actually irrelevant
4. As you can see here.

## 5. Block quotes

*Example:*

```
> Blockquotes can also be nested
> > by using an additional greather than sign
> > > here is the third level of nesting
> > > > still workds
> > > > > still
> > > > > > crazyyyy
```

*Output:*

> Blockquotes can also be nested
> > by using an additional greather than sign
> > > here is the third level of nesting
> > > > still workds
> > > > > still
> > > > > > crazyyyy

## 6. Code snippets

To use inline code snippets, surround your code by using the ` character.

*Example:*

```
Inline `code snippet` 
```

*Output:*

Inline `code snippet`

To insert full blocks of code surround the code by three *`* characters each

*Example:*
~~~
```
This is some cool source code...
```
~~~

*Output:*

```
This is some cool source code...
```

To use Syntax highlighting specify the language of your code after the opening ``` characters

*Example:*

````
```js
const foo = function (bar) {
  return bar++;
};
cinsole.log(foo(5));
```
````

*Output:*

```js
const foo = function (bar) {
  return bar++;
};
cinsole.log(foo(5));
```

## 7. Links

To use links you have to combine square brackets and paranthesis.

Enter your displayed Link text into the square brackets and the link itself into the paranthesis

*Example:*

```
[Enter the link text here](main.html)
```

*Output:*

[Enter the link text here](main.html)

If you don't want to specify the displayed text and use the link itself you can just set the link into <>

*Example:*

```
Auto converted link <https://github.com>
```

*Output:*

Auto converted link <https://github.com>

## 8. Images

Images work in a similar fashion. Just add an Exclamation point **!** in front. The text in the square brackets is used as an alt text.

*Example:*
```
![Minion](https://octodex.github.com/images/minion.png)
```

*Output:*

![Minion](https://octodex.github.com/images/minion.png)

## 9. Tables

Tables are weird. Basically you just have to draw one yourself.
Start out by putting the top row into these vertical lines |.

Then specify by using the next line to draw the table containing dashes.

To align your text to the right or left hand side, use a colon.

*Example:*

```
| First name | Last name |
| ---------- | --------: |
| Dorian     |   Wilhelm |
| Other      |    People |
```

*Output:*

| First name | Last name |
| ---------- | --------: |
| Dorian     |   Wilhelm |
| Other      |    People |

## 10. Inline HTML

Inline html works just like html. Just write your code in html and it will be automatically converted to html. 

*Example:*

```html
<h3>This is an h3</h3>

<details>Some hidden content</details>
```

*Output:*

<h3>This is an h3</h3>

<details>Some hidden content</details>



## Escaping

\# This is not a heading

## Keyboard keys

<kbd></kbd>
