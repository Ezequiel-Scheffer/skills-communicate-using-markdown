# Skills comunnicate using markdown


## Add an image

Include descriptive text in the square brackets. This text is read aloud for people using screen readers. It's also shown at times when your image doesn't display, such as when there's a poor connection.

> Example:  `![Image of Yaktocat](https://octodex.github.com/images/yaktocat.png)`

#### The output:

![Image of Yaktocat](https://octodex.github.com/images/yaktocat.png)


## Add a code example

In addition to code blocks, some code blocks should be rendered differently depending on the language.

### Command line

```
$ git init
Initialized empty Git repository in /Users/skills/Projects/recipe-repository/.git/
```

### HTML

``` HTML
<div class="row">
  <div class="col-md-6 col-md-offset-3">
    <h1>Hello World</h1>
  </div>
</div>
```

### JavaScript

``` js
var add2 = function(number) {
	return number + 2;
}
```

### Python

```python
a, b = 0, 1
while b < 10:
    print(b)
    a, b = a, a + b
```
