# ICA12 · Quote / API

Wire up the quote button page so a click loads a random Christmas trivia question and the page shows one when it loads.

## Where the starter came from

HTML and CSS are copied from the public course materials:

- [week10-materials](https://github.com/anthonypinter/atls2200-fa25/tree/main/week10-materials) (`ica10.html`, `ica10.css`)
- The same markup also appears at the repo root as [`icai10.html`](https://github.com/anthonypinter/atls2200-fa25/blob/main/icai10.html), which links `ica10.css`.

That folder is the quote-button page: a "Generate a new bit of trivia!" button (`#js-new-quote`) and an empty quote element (`#js-quote-text`). The other cited path, [atls2200/ica12](https://github.com/anthonypinter/atls2200/tree/main/ica12), returned 404, so nothing was copied from it.

The course JavaScript was not copied. `main.js` is comments only.

Names in this folder: `ica12.html`, `style.css`, and `main.js`. The week 10 HTML did not link a stylesheet and pointed at `ica11.js`. This copy links `style.css` and `main.js` (with `defer`) so those files actually load. Confirm both links as you work.

Live link to submit after this folder is on `main`:

`https://dnagubadi.github.io/Senior_Projects/ica/ica12/ica12.html`

Canvas asks for an `ica11` link. That looks like a typo for this page. Submit the `ica12.html` link unless the assignment text says otherwise.

## Checklist

- [ ] Confirm `ica12.html` links `style.css` and `main.js` correctly.
- [ ] Use `querySelector` to store the new-quote button in a variable.
- [ ] Add a click listener that calls `getQuote`.
- [ ] Log on click and confirm the log in the console.
- [ ] Store the endpoint `https://trivia.cyberwisp.com/getrandomchristmasquestion` in a variable.
- [ ] Fetch that endpoint inside `getQuote`.
- [ ] Log a successful response.
- [ ] On error, write to the console and call `alert`.
- [ ] Write `displayQuote` so it puts the text into `#js-quote-text`.
- [ ] Call `displayQuote` from `getQuote`.
- [ ] Show a quote when the page loads.
- [ ] Push it live and submit the link. The Canvas text says `ica11`; that is likely a typo for this `ica12.html` page.
