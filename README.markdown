
## Slide Show (S9) Template Pack - deck.js

The [deck.js](https://github.com/imakewebthings/deck.js) package by Caleb Troughton (aka imakewebthings) bundled up into 
a Slide Show (S9) template pack.

Note, the package is configured to use the following headers in `slides.html.erb`:

    author: Your Name Here
    title: Your Slide Show Title Here
 
## Try It Yourself - How To Use the Template Pack

If you want to try it yourself, install (fetch) the new template pack. Issue the command:

    $ slideshow -f https://github.com/geraldb/slideshow-deck.js/raw/master/deck.js.txt

To check if the new template got installed, use the `-l/--list` switch/command:

    $ slideshow -l

Listing something like:

    Installed templates include:
       deck.js.txt (/home/gerald/.slideshow/templates/deck.js/deck.js.txt)

Now you're ready to use it using the `-t/--template` switch. Example:

    $ slideshow -t deck.js.txt tutorial

That's it. 

## Samples

See a sample in Markdown in the repo titled ['Getting Started with deck.js'](https://raw.github.com/geraldb/slideshow-deck.js/master/sample.markdown).


## Questions? Comments?

Questions? Comments?
Send them along to the [Free Web Slide Show Alternatives (S5, S6, S9, Slidy And Friends) Forum/Mailing List](http://groups.google.com/group/webslideshow).
Thanks!

## What's Slide Show (S9)?

A Ruby gem that lets you create slide shows and author slides in plain text
using a wiki-style markup language that's easy-to-write and easy-to-read.
More [Slide Show (S9) Project Site &raquo;](http://slideshow.rubyforge.org)