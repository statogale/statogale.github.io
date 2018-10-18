---
title: Welcome to Jekyll!
date: '2018-09-23 12:44:00 +0100'
categories:
- php
author: jill
tags:
- javascript
- php
# featured_image: /assets/img/sample.jpg
---

You’ll find this post in your `posts` directory. Go ahead and edit it and re-build the site to see your changes. 

You can rebuild the site in many different ways, but the most common way is to run `jekyll serve`, which launches a web server and auto-regenerates your site when a file is updated.

To add new posts, simply add a file in the `_posts` directory that follows the convention `YYYY-MM-DD-name-of-post.ext` and includes the necessary front matter. Take a look at the source for this post to get an idea about how it works.

Jekyll also offers powerful support for code snippets:

{% highlight ruby linenos %}
def show
  @widget = Widget(params[:id])
  respond_to do |format|
    format.html # show.html.erb
    format.json { render json: @widget }
  end
end
{% endhighlight %}

{% highlight Javascript linenos %}
function show(name) {
   console.log(name)
}
  
{% endhighlight %}