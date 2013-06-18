---
layout: post
title: Second Post
---

Highlighting code snippets
==============

Jekyll also has built-in support for syntax highlighting of code snippets using Pygments, 
and including a code snippet in any post is easy. 
Just use the dedicated Liquid tag as follows:


```ruby
def show
  @widget = Widget(params[:id])
  respond_to do |format|
    format.html # show.html.erb
    format.json { render json: @widget }
  end
end
```

And the output will look like this:
------------------------------------

```ruby
def show
  @widget = Widget(params[:id])
  respond_to do |format|
    format.html # show.html.erb
    format.json { render json: @widget }
  end
end
```