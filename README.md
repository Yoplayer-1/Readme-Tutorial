# Basics (Thats all I know !!) 

To get started visit https://www.makeareadme.com/ and https://guides.github.com/features/mastering-markdown/#intro

# What is Markdown?

Markdown is a way to style text on the web. You control the display of the document; formatting words as bold or italic, adding images, and creating lists are just a few of the things we can do with Markdown. Mostly, Markdown is just regular text with a few non-alphabetic characters thrown in, like # or *.

You can use Markdown most places around GitHub:

* Gists
* Comments in Issues and Pull Requests
* Files with the .md or .markdown extension


# Text
It's very easy to make some words **bold** and other words *italic* with Markdown. You can even [link to Google!](http://google.com)


# Lists

Sometimes you want numbered lists:

1. One
2. Two
3. Three

Sometimes you want bullet points:

* Start a line with a star
* Profit!

Alternatively,

- Dashes work just as well
- And if you have sub points, put two spaces before the dash or star:
  - Like this
  - And this
  
  ### If your project is open source so you might want a license
  If you read [this section](https://www.makeareadme.com/#license-1) there is written we want a license. Use this [website](https://choosealicense.com/) to get one.
  
  
  
  # Images
  
  you can either choose images from the web like this
  ![Image of Yaktocat](https://octodex.github.com/images/yaktocat.png)
  
  or choose a local image like this
  ![](hacker.jpg)
  
  or link it to a webpage
  
  
  [![GOOGLE](https://www.google.com/images/branding/googlelogo/1x/googlelogo_color_272x92dp.png)](https://www.google.com/)


  
 
# Code
There are many different ways to style code with GitHub's markdown. If you have inline code blocks, wrap them in backticks: `var example = true`.  If you've got a longer block of code, you can indent with four spaces:

    if (isAwesome){
      return true
    }

GitHub also supports something called code fencing, which allows for multiple lines without indentation:

```
if (isAwesome){
  return true
}
```

And if you'd like to use syntax highlighting, include the language:

```javascript
if (isAwesome){
  return true
}
```

and I don't know *JS* so lets use **Python**

```
print("This is sooooo cool")
```

lets add syntax highlighting

```python
print("This is also cool")
```

# EXTRAS

GitHub supports many extras in Markdown that help you reference and link to people. If you ever want to direct a comment at someone, you can prefix their name with an @ symbol: Hey @Yoplayer-1 — Like this tutorial
But I have to admit, tasks lists are my favorite:

- [x] This is a complete item
- [ ] This is an incomplete item

When you include a task list in the first comment of an Issue, you will see a helpful progress bar in your list of issues. It works in Pull Requests, too!

And, of course emoji! 😀

# Syntax guide

Here’s an overview of Markdown syntax that you can use anywhere on GitHub.com or in your own text files.
Headers

# This is an <h1> tag
## This is an <h2> tag
###### This is an <h6> tag

Emphasis

*This text will be italic*
_This will also be italic_

**This text will be bold**
__This will also be bold__

_You **can** combine them_

Lists
Unordered

* Item 1
* Item 2
  * Item 2a
  * Item 2b

Ordered

1. Item 1
1. Item 2
1. Item 3
   1. Item 3a
   1. Item 3b

Images

![GitHub Logo](https://github.githubassets.com/images/modules/logos_page/GitHub-Mark.png)
Format: [Alt Text](https://github.com/logos)

Links

http://github.com - automatic!
[GitHub](http://github.com)

Blockquotes

As Kanye West said:

> We're living the future so
> the present is our past.

Inline code

I think you should use an
`<addr>` element here instead.

