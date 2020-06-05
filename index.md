---
layout: default
---
{% assign data = site.data.data %}

Text can be **bold**, _italic_, or ~~strikethrough~~.

[Markdown cheat sheet](https://lmgtfy.com/?q=markdown+cheat+sheet)

Some paragraph text.

Some more paragraph text. {{ data.other }}

# Header 1

Most annoying header

## Header 2

> Blockquote time!
>
> More of the same quote.

### Header 3

```css
div.group1 {
    font-family: "Times New Roman", serif;
    font-size: 12px;
    color: blue;
}
```

#### Header 4

*   unordered list
*   unordered list
*   unordered list

##### Header 5

1.  ordered list item 1
3.  ordered list item 2
2.  ordered list item 3

###### Header 6

| head1        | head two          | 3     |
|:-------------|:-----------------:|:------|
| yes          | food              | okay  |
| no           | games             | random|
| maybe        | uh oh             | huh?  |
| hmm          | code `what?`      | yep   |

### Horizontal rules

* * *
---

### And a nested list:

- level 1 item
  - level 2 item
  - level 2 item
    - level 3 item
    - level 3 item
- level 1 item
  - level 2 item
  - level 2 item
  - level 2 item
- level 1 item
- level 1 item

### Small image

![Small image](./assets/images/small-img.png)

### Large image

![Large image](./assets/images/large-img.png)


### You can use html too!

<p>This is written using html <code>p</code></p>
