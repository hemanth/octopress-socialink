octopress socialink plugin
================

## Installation

Place the socialink.rb in your `~/octopress/plugin/` dir.

## Useage

```ruby
{% sl social handle %}
```

* social can be any of : gh, fb, gp, tw, in, fl. [github, facebook, googleplus, twitter, linkdin, flickr respectivly]

## Examples:

Input: 

```ruby
{% sl gh hemanth %}
{% sl fb hemanth %}
{% sl tw gnumanth %}
```

Output: 

```html
<a href='https://github.com/hemanth'>hemanth</a>
<a href='https://facebook.com/hemanth'>hemanth</a>
<a href='https://twitter.com/gnumanth'>gnumanth</a>
```
