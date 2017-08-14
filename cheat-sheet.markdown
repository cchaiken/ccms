---
title: Caylia's Cheat Sheet
date: 2017-08-14 04:18:00 Z
intro:
  main: Caylia's Cheat Sheet
  style: plain
---

## Access

* Your Siteleaf Login Location = [https://manage.siteleaf.com/](https://manage.siteleaf.com/)
* Your Main Site Admin Area =
 [https://manage.siteleaf.com/sites/59752581457ba03d2c73f34f/pages](https://manage.siteleaf.com/sites/59752581457ba03d2c73f34f/pages)

## Eventbrite
* [
How to access the eventbrite button](https://www.eventbrite.com.au/support/articles/en_US/How_To/how-to-sell-eventbrite-tickets-registrations-on-your-website-using-embeddable-widgets)
* The HTML color you need to set as the button background is `#9A0007`

## External Links (to open in new tab)

Use the following syntax:

`<a href="THE URL GOES HERE BETWEEN THE QUOTATION MARKS" target="_blank">THE LINKABLE TEXT THAT PEOPLE SEE LIVES HERE</a>`

And paste it directly into the main content field. Here's a real work example:

`<a href="http://throckmortontheatre.org/" target="_blank">The Throckmorton Theatre</a>`

## Embedding Videos

{% highlight liquid %}
{% raw %}
{% include video.html video=1 %}
{% endraw %}
{% endhighlight %}

## Testimonial Front Matter & Line Breaks

``` html
<em>This</em> is a code block with syntax highlighting.
```

```
{% include video.html video=1 %}
```