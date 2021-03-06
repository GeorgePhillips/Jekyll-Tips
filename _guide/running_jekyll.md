---
title: Running Jekyll
order: 3
---

### Start with static
With Jekyll you do not need to learn all of it to get started. A Jekyll site usually starts as static HTML which gets gradually improved.

We'll be using one of the thousands of free html template for this guide. Of course, you can easily build your website from scratch using any css or javascript framework you desire. One of the big advantages of using Jekyll is you have complete control over all the source code.

Download and unzip the [Crafty Template](/crafty.zip).

### Running Jekyll
Now let's run Jekyll on the website.

{% highlight bash %}
cd ~/Downloads/crafty # or wherever you've unzipped the template
jekyll serve
{% endhighlight %}

Open your browser and go to [http://localhost:4000](http://localhost:4000). If all has gone well it'll show the website! This may not seem particularly exciting but let me explain what's actually going on here.

Jekyll is monitoring changes on your website. Anytime a file is updated it rebuilds the site, puts the resulting static website in the ``_site`` directory, then serves it live on port 4000. We can leave this running and get on with adding some cool Jekyll features.
