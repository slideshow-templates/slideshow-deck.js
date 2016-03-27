title: Getting Started with deck.js
author: Caleb Troughton

%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%
%% Note: Use the `--h2` option to break up slides on heading level 2   %%
%% (the default is `--h1`, that is, heading level 1).                  %%
%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%


## How to Make a Deck

1. ### Write Slides
   Slide content is simple HTML.
2. ### Choose Themes
   One for slide styles and one for deck transitions.
3. ### Include Extensions
   Add extra functionality to your deck, or leave it stripped down.


## The Markup

Slides are just HTML elements with a class of `slide`.

    <section class='slide'>
      <h2>How to Make a Deck</h2>
      <ol>
        <li>
          <h3>Write Slides</h3>
          <p>Slide content is simple HTML.</p>
        </li>
        <li>
          <h3>Choose Themes</h3>
          <p>One for slide styles and one for deck transitions.</p>
        </li>
        <li>
          <h3>Include Extensions</h3>
          <p>Add extra functionality to your deck, or leave it stripped down.</p>
        </li>
      </ol>
    </section>


## Themes

### Style Themes

Customizes the colors, typography, and layout of slide content.

    <link rel='stylesheet' href='/path/to/css/style-theme.css'>

### Transition Themes

Defines transitions between slides using CSS3 transitions.
Less capable browsers fall back to cutaways. But __you__ aren't using _those_ browsers
to give your presentations, are you?

    <link rel='stylesheet' href='/path/to/css/transition-theme.css'>


## Extensions

Core gives you basic slide functionality with left and right arrow navigation,
but you may want more. Here are the ones included in this deck:

- **deck.goto**: Adds a shortcut key to jump to any slide number.  Hit g, type in the slide number, and hit enter.
- **deck.hash**: Enables internal linking within slides, deep linking to individual slides, and updates the address bar and a permalink anchor with each slide change.
- **deck.menu**: Adds a menu view, letting you see all slides in a grid. Hit m to toggle to menu view, continue navigating your deck, and hit m to return to normal view. Touch devices can double-tap the deck to switch between views.
- **deck.navigation**: Adds clickable left and right buttons for the less keyboard inclined.
- **deck.status**: Adds a page number indicator. (current/total)

Each extension folder in the download package contains the necessary JavaScript, CSS, and HTML files. For a complete list of extension modules included in deck.js, check out the  [documentation](http://imakewebthings.github.com/deck.js/docs).


## Continued...

To be done


## Digging Deeper

If you want to learn about making your own themes,
extending deck.js, and more, check out the [documentation](http://imakewebthings.github.com/deck.js/docs).