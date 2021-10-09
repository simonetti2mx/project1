What did you like about this website?
    the website is very clean and simple to navigate without seeming underdeveloped.

Describe one significant difference between your own P1 site and this person's. E.g.
    Which has a better user experience (and why)?
        I think Michael Simonetti has a better user experience, especially on phone screens or screens of that size because this website has a better layout on smaller screens.
    Which codebase do you think would be more maintainable (and why)?
Is the code well-structured within files, and well-organized between files and directories?
    if not, suggest some specific improvements
        The html files don't have a main or body section, instead using your own div.  I would suggest using both main and body to make it easier to read and for screnreaders.
        Along with that, the headers of every page (the links at the top) and be placed in a `<header>` so its easier to understand what they are.
Did you find any other issues? If so, briefly enumerate them.
    In bench.html, you have a `<h1>` inside of a `<p>`, which also doesn't even have a closing `</p>`. (causes for a failed lift)
    And the other `<h1>`'s are also in `<p>` when they could be in a div instead to keep the flow and also make it easier to read.
    You should also use `<article>` and other elements instead of `<p>` to differentiate each section.
    One more thing, I would suggest adding more id's and classes to elements so people know what each element is for, even if you don't use it to change style

  were semantically appropriate elements selected
   no (see above)
  is the CSS refactored to limit duplication?
   Mostly, instead of having two seperate css files with duplicate info, you should instead use @display to change how it looks when its on a small screen.

Do you have any other constructive comments for the author?
    the design is much better than my website, but the code is messy and hard to read, and if someone were to use a screen reader, they would have even more trouble navigating your website.