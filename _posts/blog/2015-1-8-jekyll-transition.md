---
layout: post
title: "The Jekyll Transition"
modified:
categories: blog
excerpt:
tags: []
image:
  feature:
date: 2015-01-08T23:39:55-04:00
---

## Jekyll is Awesome

So Jekyll is a "thing". I don't know what took me so long to transition over from my old blog.
However, it's a lifesaver in terms of increasing efficiency around creating a blog post, writing a blog post, posting, and updating posts. Everything is streamlined... Once I was over the initial confusion of how to set everything up, it's been smooth sailing. Basically, GitHub makes posting static contant seamless with GitHub pages. Jekyll, an open source project static site generator, takes this to a new level by giving you all the tools needed to blogs, personal, projects, or organizational sites. 

## Rundown of some cool things that are easy with Jekyll.

* Launching a server to test your blog
* Adding a new post is as simple as one, two, three
* Jekyll also offers support for code snippets
* Jekyll is really well documented

### Build & Launch! 

A lot of times it can be confusing to test your site. Not with Jekyll. The below is all you need to run in terminal to get up and running. 

<div class="highlight"> 
  <pre>
    <code class="language-text" data-lang="text"> 
    bundle exec jekyll build <br>
    bundle exec jekyll serve
    </code> 
  </pre>
</div>

### New Posts Lightening Fast

Find any post in your `_posts` directory - edit your post and re-build (or run with the `-w` switch) to see your changes!
To add new posts, simply add a file in the `_posts` directory that follows the convention: YYYY-MM-DD-name-of-post.ext. Done! 

### Code Snippets Anyone?

{% highlight ruby %}
def print_hi(name)
  puts "Hi, #{name}"
end
print_hi('Steph')
#=> prints 'Hi, Steph' to STDOUT.
{% endhighlight %}

### Questions? They Have Answers

Take a look at the [Jekyll docs][jekyll] for more info on how to get the most out of Jekyll. You can file all bugs/feature requests at [Jekyll's GitHub repo][jekyll-gh].

[jekyll-gh]: https://github.com/jekyll/jekyll
[jekyll]:    http://jekyllrb.com

Have fun! 
