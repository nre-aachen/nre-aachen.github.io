---
title: Showing Python snippets in code
layout: post_text
author: Florian	
categories: test
description: I assume we will all need to include code in some of our webpages sooner or later, here a collection of
 examples.
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

Now testing some Python code:

{% highlight python %}
class Stratigraphy(Event):
    """Sedimentary pile with defined stratigraphy

    """

    def __init__(self, **kwds):
        """Sedimentary pile with defined stratigraphy

        """
        # initialise variables
        self.properties = {}
        self.property_lines = {} # required to reassign properties later!
        self.layer_names = []
        self.num_layers = 0
        self.event_lines = []

        # iterate through lines and determine attributes
        if kwds.has_key("lines"):
            self.parse_event_lines(kwds['lines'])
            self.event_type = self.event_lines[0].split("=")[1].strip()

{% endhighlight %}