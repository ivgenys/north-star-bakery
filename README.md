# North Star Bakery - Introduction to Web Development.

For my Introduction to Web Development class at Sophia Learning, I built this
four-page site for North Star Bakery on Oak Street in Minneapolis, with the live
GitHub Pages preview hosted at https://ivgenys.github.io/north-star-bakery/.

In Touchstone 2, I wrote the HTML5 markup across `index.html`, `products.html`,
`about.html`, and `contact.html` with audio and video players, a responsive
picture tag, and a pre-order pickup form. In Touchstone 3, I linked an external
`styles.css` file to all four pages using four warm bakehouse colors (`#FAF5EE`
oat cream, `#4A2C18` espresso brown, `#9E3E18` cinnamon rust, and `#231A14` dark
charcoal) paired with Georgia and Verdana fonts.

Many morning commuters check North Star Bakery's hours on a phone, so the base
rules in `styles.css` use Flexbox with `flex-direction: column` on the header,
navigation list, feature sections, and card grids to stack everything in a
single vertical column. At the `768px` media query breakpoint, the navigation
list switches to `flex-direction: row` to form a centered horizontal menu bar,
and the card grid switches to a three-column Flexbox row so the specialty,
product, and staff cards sit side by side.
