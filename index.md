---
layout: default
---

Text can be **bold**, _italic_, or ~~strikethrough~~.

[Link to another page](./another-page.html).

There should be whitespace between paragraphs.

There should be whitespace between paragraphs. We recommend including a README, or a file with information about your project.

# Header 1

This is a normal paragraph following a header. GitHub is a code hosting platform for version control and collaboration. It lets you and others work together on projects from anywhere.

## Header 2

> This is a blockquote following a header.
>
> When something is important enough, you do it even if the odds are not in your favor.

### Header 3

```js
// Javascript code with syntax highlighting.
var fun = function lang(l) {
  dateformat.i18n = require('./lang/' + l)
  return true;
}
```

```ruby
# Ruby code with syntax highlighting
GitHubPages::Dependencies.gems.each do |gem, version|
  s.add_dependency(gem, "= #{version}")
end
```

#### Header 4

*   This is an unordered list following a header.
*   This is an unordered list following a header.
*   This is an unordered list following a header.

##### Header 5

1.  This is an ordered list following a header.
2.  This is an ordered list following a header.
3.  This is an ordered list following a header.

###### Header 6

| head1        | head two          | three |
|:-------------|:------------------|:------|
| ok           | good swedish fish | nice  |
| out of stock | good and plenty   | nice  |
| ok           | good `oreos`      | hmm   |
| ok           | good `zoute` drop | yumm  |

### There's a horizontal rule below this.

* * *

### Here is an unordered list:

*   Item foo
*   Item bar
*   Item baz
*   Item zip

### And an ordered list:

1.  Item one
1.  Item two
1.  Item three
1.  Item four

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
  - level 2 item
  - level 2 item
- level 1 item

### Small image

![Octocat](https://github.githubassets.com/images/icons/emoji/octocat.png)

### Large image

![Branching](https://guides.github.com/activities/hello-world/branching.png)


### Definition lists can be used with HTML syntax.

<dl>
<dt>Name</dt>
<dd>Godzilla</dd>
<dt>Born</dt>
<dd>1952</dd>
<dt>Birthplace</dt>
<dd>Japan</dd>
<dt>Color</dt>
<dd>Green</dd>
</dl>

```
Long, single-line code blocks should not wrap. They should horizontally scroll if they are too long. This line should be long enough to demonstrate this.
```

```
The final element.
```
```glass.css
/* Glassmorphism base for cards, panels, buttons */
body {
    background: linear-gradient(135deg, #1a1a2e, #0f0f1a);
    font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
    color: #fff;
}

h1, h2, h3 {
    color: #e0e0ff;
}

.session-card {
    background: rgba(255, 255, 255, 0.05); /* semi-transparent */
    backdrop-filter: blur(15px) saturate(180%);
    -webkit-backdrop-filter: blur(15px) saturate(180%);
    border-radius: 16px;
    border: 1px solid rgba(255,255,255,0.2);
    padding: 20px;
    margin-bottom: 20px;
    box-shadow: 0 8px 32px 0 rgba(0, 0, 0, 0.37);
    transition: transform 0.3s ease, box-shadow 0.3s ease;
}

.session-card:hover {
    transform: translateY(-5px);
    box-shadow: 0 12px 40px 0 rgba(0, 0, 0, 0.5);
}

.resume-btn {
    background: linear-gradient(135deg, #7dcfff, #ff77ff);
    border: none;
    border-radius: 12px;
    padding: 10px 18px;
    cursor: pointer;
    font-weight: bold;
    color: #000;
    transition: all 0.3s ease;
}

.resume-btn:hover {
    background: linear-gradient(135deg, #ff77ff, #7dcfff);
    transform: scale(1.05);
}

#search {
    background: rgba(255,255,255,0.05);
    padding: 15px;
    border-radius: 16px;
    backdrop-filter: blur(15px);
    border: 1px solid rgba(255,255,255,0.2);
    max-width: 900px;
    margin: 0 auto 50px;
}
