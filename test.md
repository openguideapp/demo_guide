

@[RELOAD](test.md)  @[HOME](home.md) 


---
# Headings

heading change color:

# h1 Heading{color=green}
## h2 Heading{color=green}
### h3 Heading{color=green}
#### h4 Heading{color=green}
##### h5 Heading{color=green}
###### h6 Heading{color=green}

heading change fontSize to 10:

# h1 Heading{fontSize=10}
## h2 Heading{fontSize=10}
### h3 Heading{fontSize=10}
#### h4 Heading{fontSize=10}
##### h5 Heading{fontSize=10}
###### h6 Heading{fontSize=10}


---
# Emphasis

-> Change every second example to fontSize 10

**This is bold text**
**This is bold text in fontSize 10**{fontSize=10 color=green}

__This is bold text__
__This is bold text in fontSize 10__{fontSize=10 color=green}

*This is italic text*
*This is italic text in fontSize 10*{fontSize=10 color=green}

_This is italic text_
_This is italic text in fontSize 10_{fontSize=10 color=green}

~~Strikethrough~~
~~Strikethroughin fontSize 10~~{fontSize=10 color=green}
  
  
---
# Blockquotes

> Blockquotes can also be nested...
>> ...by using additional greater-than signs right next to each other...
> > > ...or with spaces between arrows.


Change the hole blockquote to fontSize 10, 
the first line to fontsize 20, 
third line color=green:

> Blockquotes can also be nested...{fontSize=20}
>> ...by using additional greater-than signs right next to each other...
> > > ...or with spaces between arrows.{color=green}
{fontSize=10}

---
# Lists

Unordered

+ Create a list by starting a line with `+`, `-`, or `*`
+ Sub-lists are made by indenting 2 spaces:
- Marker character change forces new list start:
    * Ac tristique libero volutpat at
    + Facilisis in pretium nisl aliquet. This is a very long list item that will surely wrap onto the next line.
    - Nulla volutpat aliquam velit
+ Very easy!

Ordered

1. Lorem ipsum dolor sit amet
2. Consectetur adipiscing elit. This is a very long list item that will surely wrap onto the next line.
3. Integer molestie lorem at massa


Start numbering with offset:

57. foo
58. bar

Change the color of the List to green
1. And only the fontSize of this entry to 20{fontSize=20}
2. Consectetur adipiscing elit. This is a very long list item that will surely wrap onto the next line.
3. Integer molestie lorem at massa
{color=green}
  
  
---
# Code

Inline \`code\`

Indented code

    // Some comments
    line 1 of code
    line 2 of code
    line 3 of code


Block code "fences"

\`\`\`
Sample text here...
\`\`\`

Syntax highlighting

\`\`\` js
var foo = function (bar) {
return bar++;
};

console.log(foo(5));
\`\`\`

---
# Tables

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

center alligned
| Option | Description |
|:------:|:-----------:|
| data   | path to data files to supply the data that will be passed into templates. |
| engine | engine to be used for processing templates. Handlebars is the default. |
| ext    | extension to be used for dest files. |
  
  
  
---
# Links

[link text](https://www.google.com)

[link with title](https://www.google.com "title text!")

Autoconverted link https://www.google.com (enable linkify to see)


---
# Images

![Minion](https://octodex.github.com/images/minion.png)
![Stormtroopocat](https://octodex.github.com/images/stormtroopocat.jpg "The Stormtroopocat")

Like links, Images also have a footnote style syntax

![Alt text][id]

With a reference later in the document defining the URL location:

[id]: https://octodex.github.com/images/dojocat.jpg  "The Dojocat"


Typographic Replacements

Enable typographer option to see result.

(c) (C) (r) (R) (tm) (TM) (p) (P) +-

test.. test... test..... test?..... test!....

!!!!!! ???? ,,  -- ---

"Smartypants, double quotes" and 'single quotes'


Horizontal Rules

Some text above 
___ 

Some text in the middle

---

Some text below


# heurika!{color=#61dafb fontSize=90}  


![image](https://images.unsplash.com/photo-1696461353431-32c529d4585d?ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHx0b3BpYy1mZWVkfDR8RnpvM3p1T0hONnd8fGVufDB8fHx8fA%3D%3D&auto=format&fit=crop&w=400&q=60)


![image](https://images.unsplash.com/photo-1696461353431-32c529d4585d?ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHx0b3BpYy1mZWVkfDR8RnpvM3p1T0hONnd8fGVufDB8fHx8fA%3D%3D&auto=format&fit=crop&w=400&q=60)

test


without ./  
@[Click me!](media/nested/guide2.md)

with ./  
@[Click me!](./media/nested/guide2.md)

http  
@[Click me!](https://github.com/openguideapp/demo_guide)

normal markdown link  
[to guide2](media/nested/guide2.md)
