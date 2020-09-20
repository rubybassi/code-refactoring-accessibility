![GitHub Repo stars](https://img.shields.io/github/stars/rubybassi/code-refactoring-accessibility?style=social)

# HTML CSS Git: Code Refactor

## Background

This project is my attempt of refactoring Horiseon's existing website code to make it more accesible, through HTML5 and CSS best practice, and meeting the acceptance criteria as shown below. 

[View my final project on GitHub pages](https://rubybassi.github.io/code-refactoring-accessibility/)

Comments were added throughout both HTML and CSS files, highlighting the improved semantic structure and changes.  

### Challenges

I came across a two challenges: 

1. Selecting the right semantic elements for the main section, mainly choosing when to use the `<section>` and `<article>` element. Although there is a plethora of documentation and guidelines online, i struggled to find the best solution for my particular challenge; in the end i decided that the `<article>` element worked better as the items could be independenet, stand-alone content.  
2. Deteriming if there was a feasable solution to adding an alt description to the CSS background-image declaration. I decided as the image was borderline decorative and the challenge of loosing the convenient `<background-size: cover>` styling, that i would leave this as is. I did not wrap it in a `<section>` element as according to W3C's HTML documentation: "A section is a thematic grouping of content, typically with a heading." – i did not find this the case and thought a `<div>` element would suffice.

If you have feedback / advice on the above, please feel free to comment.


### User Story

> AS A marketing agency
> I WANT a codebase that follows accessibility standards
> SO THAT our own site is optimized for search engines

### Acceptance Criteria

> GIVEN a webpage meets accessibility standards
> WHEN I view the source code
> THEN I find semantic HTML elements
> WHEN I view the structure of the HTML elements
> THEN I find that the elements follow a logical structure independent of styling and positioning
> WHEN I view the image elements
> THEN I find accessible alt attributes
> WHEN I view the heading attributes
> THEN they fall in sequential order
> WHEN I view the title element
> THEN I find a concise, descriptive title

### Mock Up

The following image shows the web application's appearance:

![End Game Mock Up](images/01-html-css-git-homework-demo.png)

### My Development Enviromment:
* [Visual Studio Code](https://code.visualstudio.com/)
* Terminal
* [Git](https://git-scm.com/book/en/v2/Getting-Started-Installing-Git)
* [headingsMap Chrome extension – first image below](https://chrome.google.com/webstore/detail/headingsmap/flbjommegcjonpdmenkdiocclhjacmbi?hl=en)
* [Google Page Speed Insights report - second image below](https://developers.google.com/speed/pagespeed/insights/)

![headingsApp extension for testing document outline](/images/headingsmap_test.png)

![Google Page Speed Insight report](/images/google-speed-score.png)
