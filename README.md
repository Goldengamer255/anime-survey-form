# Anime Movie Survey

A short, fun survey form about popular anime movies, built with plain HTML and CSS. It was made as a freeCodeCamp Responsive Web Design project (Build a Survey Form).

## What's in the survey

- **Personal details:** name and email (both required, email format validated by the browser) and an optional phone number.
- **Which have you watched?** Checkboxes for *I Want To Eat Your Pancreas*, *Your Name*, *A Silent Voice*, *Weathering With You* and *The Tunnel To Summer*.
- **Choose one to review:** a dropdown of the same five films.
- **How did you find it?** Radio buttons from "Best Movie Ever!!!!" down to "Why was this movie even created".
- **Comments:** a free-text box for extra thoughts, then a Submit button.

## Project structure

```
index.html   Form markup
styles.css   Styling (full-page background image, translucent form panel)
```

## Running it

No build step. Open `index.html` in any browser. (The background image is loaded from the web, so you need an internet connection to see it.)

## Skills learned

**HTML forms**
- Building a complete form with `<form>`, `<fieldset>`, `<label>` and a submit input.
- Choosing the right input type for each question: `text`, `email`, `number`, `checkbox`, `radio`, `<select>` and `<textarea>`.
- Grouping radio buttons with a shared `name` so only one can be selected.
- Built-in browser validation with `required`, `type="email"` and `min` / `max`, plus helpful `placeholder` text.

**Accessibility**
- Linking every control to a `<label>` using `for` / `id`, so clicking a label focuses its input and screen readers announce it properly.
- Using semantic headings (`h1`, `h2`) and `lang` on the root element.

**CSS**
- Centring and sizing a layout with `width`, `max-width`, `min-width`, `vw` and `margin: auto`.
- Full-page background images and a semi-transparent overlay with `rgba()` to keep text readable.
- Styling form controls consistently (block labels, full-width inputs, attribute selectors like `input[type="submit"]`).
- Reusable utility classes (`.inline`) to override default styles for checkboxes and radios.

**Workflow**
- Following a spec of required element IDs and structure.
- Version control and publishing a project to GitHub.
