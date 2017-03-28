# poynter-style-guide-2017

Style Guide from the Poynter Digital Design Challenge 2017. Typecast template by John Martins. Typography by Jeffrey Zeldman. Code cleanup by Noël Jackson. A studio.zeldman.com contribution to the cause. Support #realnews.


### Feb - Mar 2017 Update

The above paragraph is the text from the original readme file.

I forked Zeldman's GitHub page at <https://github.com/studiozeldman/poynter-style-guide-2017>

A working sample article that uses Zeldman's design ideas can be found at <https://studiozeldman.github.io/poynter-reader-2017> with the GitHub repo for that page found [here](https://github.com/studiozeldman/poynter-reader-2017).


I'm adding supporting links to this interesting Poynter project.

* <https://www.poynterdesign.org>
* [Poynter Design Challenge](https://library.fora.tv/conference/poynter_digital_design_challenge)
* Jan 9, 2017 - [Digital Design Challenge: What next?](https://www.poynterdesign.org/blogs/2017/1/9/digital-design-challenge-what-next)
* Jan 18, 2017 - [Design: An antidote for fake news](https://www.poynterdesign.org/blogs/2017/1/18/design-an-antidote-for-fake-news)
* Jan 20, 2017 - [Five design answers that add up](https://www.poynterdesign.org/blogs/2017/1/20/five-design-answers-that-add-up)
* Jan 30, 2017 - [What was said](https://www.poynterdesign.org/blogs/2017/1/30/what-was-said)
* Jan 31, 2017 - [The big points](https://www.poynterdesign.org/blogs/2017/1/31/the-big-points)
* [The Speakers](https://www.poynterdesign.org/speakers)
* [The Presentations](https://www.poynterdesign.org/presentations)
* Jan 31, 2017 - The Mario Blog - [Digital Design Challenge: Those article pages move up front](http://garciamedia.com/blog/digital_design_challenge_those_article_pages_move_up_front)
* Dec 19 2016 - Zeldman - [To Save Real News](http://www.zeldman.com/2016/12/19/save-real-news)
* Jan 28, 2017 - Zeldman - [Digital Newspaper Design Challenge: A Report from Poynter, Part 1](http://www.zeldman.com/2017/01/28/digital-newspaper-design-challenge-report-poynter-part-1/)
* Feb 6, 2017 - Zeldman - [Authoritative, Readable, Branded: Report from Poynter Design Challenge, Part 2](http://www.zeldman.com/2017/02/06/readable-branded-design)
* Feb 14, 2017 - moxiesozo.com - [Challenging Designers to Create Better Reading Experiences Online](https://moxiesozo.com/2017/02/14/roger-black-challenging-designers-create-better-reading-experiences-online)


### March 2017 formatting changes

I added more test text to the article body in index.html.

I made small changes to style.css that satisfy my interests.

My test page:

<http://testcode.soupmode.com/zeldman/poynter-style-guide-2017/index.html>

On a desktop/laptopl computer, the original page fount at:

<https://studiozeldman.github.io/poynter-style-guide-2017>

causes a horizontal scrollbar to appear, especially when resizing the browser to a smaller size. A media query accounts for this when viewing the page on a smaller device, but I don't want to see the horizontal scrollbar on any screen.

For `div.content1` in style.css, I changed `width: 600px;` to `max-width: 600px;` and I added `width: 100%;`.`

