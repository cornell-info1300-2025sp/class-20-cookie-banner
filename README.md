# INFO 1300(SP25) - Activity - Class-20-Cookie-Banner

## Cookie Banner Implementation Notes

Follow these steps to implement the cookie banner

1. Review the HTML and CSS for the cookie banner.
   
   HTML: note the `elements` and `classes` used<br>
   CSS:  note the `.banner` classes created<br>

2. Code the HTML & CSS for Interactivity

    - Add the `id="cookie-banner"` to the `dialog` element <br>
    - Add the `id="cookie-accept-button` to the `button` element <br>
    - Add the `.hidden` class to the CSS

        `.hidden {
            display: none !important;
        }`

        Be sure to include the `!important` part!

3.  Setup `index.html` to use jQuery
   
    - Add `jquery-3.7.1.js` file at the bottom of all the HTML pages - this is already in your `scripts` sub-directory:
   
        `<script src="scripts/jquery-3.7.1.js"></script>`

4.  Setup `cookie-banner.js` to code the JS interactivity

    - Create a `cookie-banner.js` file in the `scripts` sub-directory

    - Add `cookie-banner.js` file at the bottom of all the HTML pages - **after** the `jquery-3.7.1.js`:
   
        `<script src="scripts/cookie-banner.js"></script>`

5. Test that your `cookie-banner.js` script is loading

    - Add `console.log("cookie-banner.js loaded!");` to `cookie-banner.js`

    - `Inspect` the page and open the `console` top view the messages.

        The console should display the message `cookie-banner.js loaded!` if everything is setup properly.

6. Code the interactivity for the cookie banner using the [Project 3 Snippets](https://github.coecis.cornell.edu/info1300-spring25/info1300-2025sp-resources/blob/main/assignments/project3/p3-interactivity-snippets.md):

    - Copy in your commented out Pseudocode:

        // when #cookie-accept-button is clicked<br>
        // &nbsp;&nbsp;&nbsp; add .hidden class to #cookie-banner
  
    - Review the [Project 3 Snippets](https://github.coecis.cornell.edu/info1300-spring25/info1300-2025sp-resources/blob/main/assignments/project3/p3-interactivity-snippets.md) and add the snippets you need to complete your pseudocode:
     
        - [Event On-Click-Element Snippet](https://github.coecis.cornell.edu/info1300-spring25/info1300-2025sp-resources/blob/main/assignments/project3/p3-interactivity-snippets.md#event-snippet-on-click-element)

        - Use a [Console Log Snippet](https://github.coecis.cornell.edu/info1300-spring25/info1300-2025sp-resources/blob/main/assignments/project3/p3-interactivity-snippets.md#snippet-console-log) to confirm your listening event works

        - [Add CSS Class to Element Snippet](https://github.coecis.cornell.edu/info1300-spring25/info1300-2025sp-resources/blob/main/assignments/project3/p3-interactivity-snippets.md#event-snippet-on-click-element)

7.  Make the cookie banner fixed at the bottom of the page using:

    `position: fixed;`<br>
    `bottom: 0;`<br>
    `z-index: 10;`

8.  Notice the `:hover` effect on the banner's `button` element

9.  Clean up the code

    - remove `console.log` messages from JS
    - remove the TODO: comments from HTML/CSS

10. Validate the JS code
    
    - validate the JS by rerunning the interactivity 
    - no errors == validated (codespace messages OK)


## VS Code and Development Server

- **To Code**: Open this repository as a Codespace on GitHub.
- **To View Site**: Start the web server by clicking "Go Live" in the bottom right-hand corner.
  - Once the web server has started, view the website in a web browser by clicking "Open in Browser".
