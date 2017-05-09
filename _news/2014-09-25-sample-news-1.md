---
layout: news

# TITLE TAG
# Limit length to 50-70 characters. Include primary keyword near the beginning of the the tag. 
# If it sounds natural include the secondary KW, otherwise it's OK not to have it.
# Use the pipe character "|" to separate terms if needed. This is a headline and should be compelling
# Example: Restaurant Scheduling Software | Try it Free. | Zip Schedules
# This is a headline so it should sound compelling.  

# DESCRIPTION TAG
# 160 - 250 characters max.  
# Use the keywords 1 - 2x but make it sound attractive to entice people to click on the link.
# This is the short description that the search engines will show under the page link that is displayed.

# Image 
# Image that will be shown in the article listing and at the top of the article.

# Category
# Only used for News Articles. The Category of the News Article. Categories are set in _config.yml.

permalink: top-10-employee-scheduling-benefits.html

title: "Welcome to Jekyll!"
subtitle: 
author: zip schedules
description: Scheduling software made for restaurants. Control your labor costs, communicate with staff and keep everyone in-the-loop with a free mobile apps.
image: blog.jpg
category: scheduling

---

You’ll find this post in your `_drafts` directory. When the post is in the draft directory is included, by default, when you build your site. If you would like to see the post you can run `jekyll serve --drafts`, which will generate your site with the draft article visibel. Use this for testing, before you publish your live site.
The "more" tag below marks the separation point of the first paragraph to display on the blog listing page.
<!--more-->
When you are ready to publish the post, move it to your `_posts` directory. Go ahead and edit it and re-build the site to see your changes. You can rebuild the site in many different ways, but the most common way is to run `jekyll serve`, which launches a web server and auto-regenerates your site when a file is updated.

To add new posts, simply add a file in the `_posts` directory that follows the convention `YYYY-MM-DD-name-of-post.ext` and includes the necessary front matter. Take a look at the source for this post to get an idea about how it works.

<h2>Sub-headings and highlighting </h2>
You can see above that if you want to add a sub-heading, you an use the h2 tag. To highlight some text, you can use the left single quote character.

You can add a block quote as follows:
<blockquote>The dreams of yesterday are the hopes of today and the reality of tomorrow. Science has not yet mastered prophecy. We predict too much for the next year and yet far too little for the next ten.</blockquote>


You can also highlight a block of text as follows:

{% highlight ruby %}
def print_hi(name)
  puts "Hi, #{name}"
end
print_hi('Tom')
#=> prints 'Hi, Tom' to STDOUT.
{% endhighlight %}

To add a link to a file use this text - [get the PDF]({{ site.url }}/assets/pdf/labeling.pdf) directly.

To insert an image in your post type the html, as follows: 

<img src="{{ site.baseurl }}/assets/images/post-sample-image.png" alt="Post Sample Image">


Check out the [Jekyll docs][jekyll-docs] for more info on how to get the most out of Jekyll. File all bugs/feature requests at [Jekyll’s GitHub repo][jekyll-gh]. If you have questions, you can ask them on [Jekyll Talk][jekyll-talk].

[jekyll-docs]: http://jekyllrb.com/docs/home
[jekyll-gh]:   https://github.com/jekyll/jekyll
[jekyll-talk]: https://talk.jekyllrb.com/
