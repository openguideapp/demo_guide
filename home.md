Headings

  # h1 Heading 8-){color=green fontSize=1}
  ## h2 Heading{color=green fontSize=1}
  ### h3 Heading{color=green fontSize=1}
  #### h4 Heading{color=green fontSize=1}
  ##### h5 Heading{color=green fontSize=1}
  ###### h6 Heading{color=green fontSize=1}


Horizontal Rules{color=green fontSize=1}

  Some text above {color=green fontSize=1}
  ___ {color=green fontsize=1}

  Some text in the middle{color=green fontSize=1}

  ---{color=green fontsize=1}

  Some text below{color=green fontSize=1}


Emphasis{color=green fontsize=1}

  **This is bold text**{color=green fontSize=1}

  __This is bold text__{color=green fontSize=1}

  *This is italic text*{color=green fontSize=1}

  _This is italic text_{color=green fontSize=1}

  ~~Strikethrough~~{color=green fontSize=1}


Blockquotes

  > Blockquotes can also be nested...{color=green fontsize=1}
  >> ...by using additional greater-than signs right next to each other...{color=green fontSize=1}
  > > > ...or with spaces between arrows.{color=green fontsize=1}


Lists

  Unordered

  + Create a list by starting a line with `+`, `-`, or `*`
  + Sub-lists are made by indenting 2 spaces:{color=green fontSize=1}
    - Marker character change forces new list start:
      * Ac tristique libero volutpat at
      + Facilisis in pretium nisl aliquet. This is a very long list item that will surely wrap onto the next line.
      - Nulla volutpat aliquam velit
  + Very easy!

  Ordered

  1. Lorem ipsum dolor sit amet
  2. Consectetur adipiscing elit. This is a very long list item that will surely wrap onto the next line.
  3. Integer molestie lorem at massa
{color=green fontSize=1}

  Start numbering with offset:

  57. foo
  58. bar{color=green fontsize=1}


Code

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


Tables

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
  | :------:| :-----------:|
  | data   | path to data files to supply the data that will be passed into templates. |
  | engine | engine to be used for processing templates. Handlebars is the default. |
  | ext    | extension to be used for dest files. |
  
Links

  [link text](https://www.google.com)

  [link with title](https://www.google.com "title text!")

  Autoconverted link https://www.google.com (enable linkify to see)


Images

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




# heurika!{.red color=#61dafb fontSize=90}  

# heurika!{.red color=green fontSize=40}

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
