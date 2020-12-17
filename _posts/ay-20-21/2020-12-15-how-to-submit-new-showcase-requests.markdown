---
layout: post
title:  "How to submit new project showcase requests ?"
date:   2020-12-08 20:10:07 +0800
img: "/assets/img/ay20-21/ta/manual-3684460_640.jpg"

code: "https://github.com/CS3237/cs3237.github.io"

categories: ay2020-21

tags: health social utility

team: 
  - name: Ashwin
    github: ashwinsk
  - name: Sylvian
    github: ashwinsk
  - name: Zhaoying
    github: ashwinsk

excerpt: How to guide for the project showcase for AY 2020-21

---

### CS3237 Instructions

Please refer to the sample code [here](https://github.com/CS3237/cs3237.github.io/tree/gh-pages). 
For any other queries please feel free to either raise an issue in github or email us.

#### Project Page
You need to create a markdown page for your project as shown [here](https://github.com/CS3237/cs3237.github.io/blob/gh-pages/_posts/ay-20-21/2020-12-15-how-to-submit-new-showcase-requests.markdown).
It is recommended to create a copy of this file and start editing in this.
<br>
This file will contain all the information you wish to convey about your project. 
It is recommended to add your motivation, usage and benefits etc in this document.
<br>
While writing the different sections for the page in markdown please make sure you use `##` or lower, as `#` will be used for the post title. 
** Please follow the file naming conventions described in the Jekyll section below. **
<br>
This file needs to be only uploaded to this [directory](https://github.com/CS3237/cs3237.github.io/tree/gh-pages/_posts/ay-20-21).
<br>

#### Images
A thumbnail image for your project needs to be uploaded which will be displayed on the homepage along with all the other projects. 
The link to this image needs to be added as shown in `line 5` of your markdown file as shown in this [example](https://github.com/CS3237/cs3237.github.io/blob/gh-pages/_posts/ay-20-21/2020-12-15-how-to-submit-new-showcase-requests.markdown).
<br>
You can add the image(s) by creating a folder under the `assests/img/ay20-21` folder with your group number [here](https://github.com/CS3237/cs3237.github.io/tree/gh-pages/assets/img/ay20-21).
<br>
Please try to keep the images in 100 - 500 KB.

#### Team
You need to add a simple name, this name will be publically displayed, of your team member, and his/her github username in the team section as shown in 
`lines 16-21` of your markdown file as shown [here](https://github.com/CS3237/cs3237.github.io/blob/gh-pages/_posts/ay-20-21/2020-12-15-how-to-submit-new-showcase-requests.markdown)

#### Project Code
If you wish to add a link to your code on github or any other hosting you may do so as described in `line 7` of this file. 
This is recommended but not mandatory.

#### Tags
Please add appropriate tags to your project from the following list: 
1. commerce
1. health
1. education
1. food
1. social

Please raise a PR/comment if you have any other relevant tags in mind. We plan to use this to organise the projects in the future.

#### Submission
Once you are done editing the pages, you may raise a PR to the `gh-pages` branch on github of the project. 
Please make sure you are only adding the markdown file for your project and the required images.
    

### Jekyll Basics

Jekyll requires blog post files to be named according to the following format:

`YEAR-MONTH-DAY-group-<group-number>-<title>.MARKUP`

Where `YEAR` is a four-digit number, `MONTH` and `DAY` are both two-digit numbers, and `MARKUP` / `markdown` is the file extension representing the format used in the file. 
After that, include the necessary front matter. 

Jekyll also offers powerful support for code snippets:
{% highlight ruby %}
def print_hi(name)
  puts "Hi, #{name}"
end
print_hi('Tom')
#=> prints 'Hi, Tom' to STDOUT.
{% endhighlight %}

You can also add HTML directly, although it is discouraged. You may only use it for embedding images/videos in the page.
<iframe width="420" height="315"
src="https://www.youtube.com/embed/tgbNymZ7vqY">
</iframe>

You can also add images the default way in markdown.

Check out the [Jekyll docs][jekyll-docs] for more info on how to get the most out of Jekyll. File all bugs/feature requests at [Jekyll’s GitHub repo][jekyll-gh]. If you have questions, you can ask them on [Jekyll Talk][jekyll-talk].

[jekyll-docs]: https://jekyllrb.com/docs/home
[jekyll-gh]:   https://github.com/jekyll/jekyll
[jekyll-talk]: https://talk.jekyllrb.com/

 
