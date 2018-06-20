---
layout: post
title: Testing more stuff
tags: [test]
---

The formats being tested in this post use [markdown](http://markdowntutorial.com/).  So far I learned how to convert text into links, bold, and italic. I also test how to add headings, tables, code excerpts, boxes, and images. 

**Here is some bold text**

## Here is a secondary heading

Here's a useless table:

| table h1 | table h2 | table h3 |
| :------ |:--- | :--- |
| e1 | e2 | e3 |
| e4 | e5 | e6 |
| e7 | e8 | e9 |
| e10 | e11 | e12 |


Here's a random image

![BlackHole](/img/blackhole.jpg)

Here's a code chunk:

~~~
def function(x) {
  return(x + 5);
}
function(3)
~~~

And here is the same code with syntax highlighting:

```python
def function(x) {
  return(x + 5);
}
function(3)
```

And here is the same code yet again but with line numbers:

{% highlight python linenos %}
def function(x) {
  return(x + 5);
}
function(3)
{% endhighlight %}

## Boxes
You can add notification, warning and error boxes like this:

### Notification

{: .box-note}
**Note:** This is a notification box.

### Warning

{: .box-warning}
**Warning:** This is a warning box.

### Error

{: .box-error}
**Error:** This is an error box.
