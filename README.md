# INFO 1300(SP25) - Activity - Class-20-Cookie-Banner

## Cookie Banner Implementation Notes

Follow these steps to implement the cookie banner

1. Review the HTML and CSS for the cookie banner.
   
   HTML: note the `elements` and `classes` used<br>
   CSS:  note the `.banner` classes created<br>

2. Code the HTML & CSS for Interactivity

    Add the `id="cookie-banner"` to the `dialog` element <br>
    Add the `id="cookie-accept-button` to the `button` element <br>
    Add the `.hidden` class to the CSS

        .hidden {
            display: none !important;
        }

    Be sure to include the `!important` part!

3.  Setup `index.html` to use jQuery
   
    Add `jquery-3.7.1.js` file at the bottom of all the HTML pages - this is already in your `scripts` sub-directory:
   
     `<script src="scripts/jquery-3.7.1.js"></script>`

4.  Create a `cookie-banner.js` file in the `scripts` sub-directory

5.  Add `cookie-banner.js` file at the bottom of all the HTML pages - **after** the `jquery-3.7.1.js`:
   
     `<script src="scripts/cookie-banner.js"></script>`

6. Test that your `cookie-banner.js` script is loading

    Add `console.log("cookie-banner.js loaded!")"` to `cookie-banner.js`

    `Inspect` the page and open the `console` top view the messages.

    The console should display the message `cookie-banner.js loaded!` if everything is setup properly.

7. Code the interactivity for the cookie banner using these snippets:

    Listen/Respond to Events on an Element -

        $("TODO_CSS_SELECTOR").on("click", function() {
            // TODO: snippet(s) to respond to the click event.
        });

    Use a console message to confirm your listening event works.

        console.log("cookie accept button clicked!");

    Add/Remove CSS Class - 

        $("TODO: Selector").addClass("TODO: class name");

        $("TODO: Selector").removeClass("TODO: class name");

8.  Make the cookie banner fixed at the bottom of the page:

    `position: fixed;`<br>
    `bottom: 0;`<br>
    `z-index: 10;`


## VS Code and Development Server

- **To Code**: Open this repository as a Codespace on GitHub.
- **To View Site**: Start the web server by clicking "Go Live" in the bottom right-hand corner.
  - Once the web server has started, view the website in a web browser by clicking "Open in Browser".
