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

And, of course emoji! :grinning:

# Syntax guide

Here’s an overview of Markdown syntax that you can use anywhere on GitHub.com or in your own text files.
Headers

# This is an <h1> tag
## This is an <h2> tag
###### This is an <h6> tag

##Emphasis

*This text will be italic*
_This will also be italic_

**This text will be bold**
__This will also be bold__

_You **can** combine them_

##Lists
###Unordered

* Item 1
* Item 2
  * Item 2a
  * Item 2b

###Ordered

1. Item 1
1. Item 2
1. Item 3
   1. Item 3a
   1. Item 3b

##Images

![GitHub Logo](https://github.githubassets.com/images/modules/logos_page/GitHub-Mark.png)
Download logos of GitHub: ![Alt Text](https://github.com/logos)

##Links

http://github.com - automatic!
[GitHub](http://github.com)

##Blockquotes

As Kanye West said:

> We're living the future so
> the present is our past.

Inline code

I think you should use an
`<addr>` element here instead.


# GitHub Flavored Markdown

GitHub.com uses its own version of the Markdown syntax that provides an additional set of useful features, many of which make it easier to work with content on GitHub.com.

Note that some features of GitHub Flavored Markdown are only available in the descriptions and comments of Issues and Pull Requests. These include @mentions as well as references to SHA-1 hashes, Issues, and Pull Requests. Task Lists are also available in Gist comments and in Gist Markdown files.
Syntax highlighting

Here’s an example of how you can use syntax highlighting with GitHub Flavored Markdown:

```javascript
function fancyAlert(arg) {
  if(arg) {
    $.facebox({div:'#foo'})
  }
}
```

You can also simply indent your code by four spaces:

    function fancyAlert(arg) {
      if(arg) {
        $.facebox({div:'#foo'})
      }
    }

Here’s an example of Python code without syntax highlighting:

def foo():
    if not bar:
        return True

Task Lists

- [x] @mentions, #refs, [links](example.com), **formatting**, and <del>tags</del> supported
- [x] list syntax required (any unordered or ordered list supported)
- [x] this is a complete item
- [ ] this is an incomplete item

If you include a task list in the first comment of an Issue, you will get a handy progress indicator in your issue list. It also works in Pull Requests!
Tables

You can create tables by assembling a list of words and dividing them with hyphens - (for the first row), and then separating each column with a pipe |:

First Header | Second Header
------------ | -------------
Content from cell 1 | Content from cell 2
Content in the first column | Content in the second column

Would become:
First Header 	Second Header
Content from cell 1 	Content from cell 2
Content in the first column 	Content in the second column
SHA references

Any reference to a commit’s SHA-1 hash will be automatically converted into a link to that commit on GitHub.

16c999e8c71134401a78d4d46435517b2271d6ac
mojombo@16c999e8c71134401a78d4d46435517b2271d6ac
mojombo/github-flavored-markdown@16c999e8c71134401a78d4d46435517b2271d6ac

Issue references within a repository

Any number that refers to an Issue or Pull Request will be automatically converted into a link.

#1
mojombo#1
mojombo/github-flavored-markdown#1

Username @mentions

Typing an @ symbol, followed by a username, will notify that person to come and view the comment. This is called an “@mention”, because you’re mentioning the individual. You can also @mention teams within an organization.
Automatic linking for URLs

Any URL (like http://www.github.com/) will be automatically converted into a clickable link.
Strikethrough

Any word wrapped with two tildes (like ~~this~~) will appear crossed out.
Emoji

GitHub supports [emoji](https://docs.github.com/en/free-pro-team@latest/github/writing-on-github/basic-writing-and-formatting-syntax#using-emoji)!

To see a list of every image we support, check out the [Emoji Cheat Sheet](https://github.com/ikatyang/emoji-cheat-sheet/blob/master/README.md).

you can directly add it like 😀 and with shortcode :grinning:

Some of the [custom](https://github.com/ikatyang/emoji-cheat-sheet/blob/master/README.md#github-custom-emoji) GitHub emoji are below:

Atom IDE :atom:

Basecampy :basecampy:

Electron :electron:

Finnadie :finnadie:

GODMODE :godmode:

Neckbeard :neckbeard:

RAGE 1 :rage1:

RAGE 2 :rage2:

Rage 3 :rage3:

RAGE 4 :rage4:

Shipit :shipit:

Troll Face :trollface: 	

Basecamp :basecamp:

Bowtie :bowtie:

Feels Good :feelsgood:

Gober Serk :goberserk:

Hurt real BAD :hurtrealbad:

Octocat :octocat:

Suspect :suspect:
