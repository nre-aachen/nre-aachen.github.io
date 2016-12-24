---
title: Showing Python snippets in code
layout: post_text
author: Florian	
categories: test
---

I assume we will all need to include code in some of our webpages sooner or later, here a collection of
 examples.


Testing some highlighted Ruby code (straight from the Jekyll intro):

{% highlight ruby %}
def show
  @widget = Widget(params[:id])
  respond_to do |format|
    format.html # show.html.erb
    format.json { render json: @widget }
  end
end
{% endhighlight %}