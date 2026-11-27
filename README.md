# Kimberly Hayman: personal website

A single-page site: one file, `index.html`, with no build step. Open it in any browser to preview.

## Editing text
Open `index.html` in any text editor. Each part of the page is marked with a comment:

- `INTRO`: your name, tagline, and location
- `ABOUT`: your bio paragraphs and the three "values" cards
- `CONTACT`: email, LinkedIn, and location

Change the words between the tags (for example, between `<p>` and `</p>`) and save the file. Leave the tags themselves alone.

## Adding your photo
1. Save your photo as `photo.jpg` in this folder (a square image works best).
2. In `index.html`, find `<span>KH</span>` and replace it with `<img src="photo.jpg" alt="Kimberly Hayman">`.

## Changing colors
The colors are listed together at the top of the `<style>` section under `:root`. Change `--accent` to swap the teal for another color.
