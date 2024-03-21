---
layout: post
# If your post title is longer or more complicated
# than can be represented in the filename, uncomment the following line
# and specify a custom title
# title:  "Sample Blog Post"

# Uncomment only one of the below categories
categories: 
#- Bug Fix
#- Contribution


# Enter your name below
author: Adrian Edwards
---

For my contribution, I decided to create this website and post this sample blog post. I decided to do this because I wanted to help provide a blogging platform for SJ to allow the students of HFOSS to have a place to submit their blog posts for the last half of the semester.

This blog post can be used in several ways:
- Reading it should provide a tutorial explaining some of the basics of how to use this blog for HFOSS students who will be adding posts to it 
- Looking at its source code can provide a template that can be reused to help kickstart the writing of new blog posts, or to demonstrate some examples of how to use markdown
<!-- - Demonstrate (to some extent) what a well-written, detailed blog post looks like. (That said this post will probably be longer than is expected for the actual HFOSS assignments because it may contain a lot of tutorial content)  -->
- As documentation for any future readers who are interested in the rationale behind the existence of this site (such as Future HFOSS students, TA's, or FOSSRIT org admins)

## What is this site?
This is a site that is built using Jekyll, a tool that allows you to build websites. It is natively supported by [GitHub pages](https://docs.github.com/en/pages) - a free website hosting service provided by GitHub. It is quite commonly used by developers to create their own personal or portfolio websites.

## Why not something else, like WordPress?
HFOSS is a class designed to help teach some of the basics behind open source. By using git and GitHub to submit the blog posts, there are more opportunities to practice using the tools that are used by real-world projects. Additionally, the WordPress sites from previous classes are no longer around and are hard to point to as examples that are particularly positive or negative.

## How do I use it?
This repository may look like a mess of many, many files, but realistically the only files you will likely care about as an HFOSS student are in the `_posts` folder. This is where you will upload your blog posts. The basic process goes something like this:

1. Log into your GitHub account
2. Create a fork of this repository and clone it to your computer if that's how you prefer to work (feel free to try a few different ways)
3. Create a new branch on your fork starting from the `main` branch
4. Find the `_posts` folder and create a copy of this sample post, giving it a new, dated filename (Jekyll requires blog post files to be named according to the following format `YEAR-MONTH-DAY-title`) and changing the contents accordingly (ideally making commits and pushing to your new branch as you go)
5. [Optional] You can also configure github pages (through the settings tab of your forked repository) to host a website site based on your new branch, so you can preview your changes and make sure your post looks the way you want. There are also ways to assemble the website on your computer if you prefer a more hands-on process (Ask in class or come to office hours if you want to learn more about this!) 
6. When you are ready to submit, create a "pull request" back to the original repository. This will take the contents of your new branch and submit it as a proposed change to the main class website. Once approved, your blog post will be added to the main class web page.
7. [Recommended] Whenever the main class webpage updates, it may be helpful to also update the main branch of your fork (github provides a handy "sync" button) so that you can stay up to date



## More Markdown features
In addition to the formatting used so far in this document, Markdown offers several other things that may be useful to blog posts. 

### Images

![a meme depicting a cartoon person screaming "OPEN SOURCE"](https://ankitrokdeonsns.github.io/assets/img/open_source.jpeg)


[Here](https://www.markdownguide.org/basic-syntax/#images-1) is a link to more documentation on markdown images.

### Tables

| Item         | Price    | # In stock |
| ------------ | -------- | ---------- |
| Juicy Apples | 1.99     | *7*        |
| Bananas      | **1.89** | 5234       |

[Here](https://www.markdownguide.org/extended-syntax/#tables) is a link to more documentation on markdown tables.

## More Jekyll Features
Jekyll can also provide some formatting and other useful features. Check out the [Jekyll docs][jekyll-docs] for more info on how to get the most out of Jekyll. Here are some notable examples:


### Code snippets

{% highlight ruby %}
def print_hi(name)
  puts "Hi, #{name}"
end
print_hi('Tom')
#=> prints 'Hi, Tom' to STDOUT.
{% endhighlight %}


[jekyll-docs]: https://jekyllrb.com/docs/home
