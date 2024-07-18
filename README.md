# Barbeque sign up webpage

A simple sign up webpage for a barbeque webinar.

This project is part of the [Learn Responsive Web Design](https://scrimba.com/learn/responsive) course on [Scrimba](https://scrimba.com).

## Implementation

* Responsive.
* Accessible + screen reader friendly.
* Mobile first approach.

While my implementation follows the course content loosely, it isn't an exact match of the design or the implementation shown in the course. I created the project from scratch and made some intentional changes with the aim of improving upon the provided design. Here's a non-exhaustive list:

* Font sizes have been adjusted to make them more legible and consistent across the page.
* Spacing issues have been fixed. The elements will no longer appear too close to each other.
* The low contrast of the register button text has been fixed.
* The 'Join us for this live webinar' text no longer appears at the bottom of the page, which is primarily an issue when the page height is too long.
* `aria-*` attributes have been added throughout the page. Screen readers are now able to announce the names of the form inputs.
* The height of the form elements has been increased.

## Dependencies

None. The project uses only HTML, CSS.

## Run locally

Download the 'src' folder and open 'index.html' in the browser.

## Screenshots

See [screenshots](screenshots/).

For comparison purposes, I've added extra screenshots that show the original Scrimba implementation. Note that the final built page on Scrimba is missing a `<meta name="viewport">` tag and was displaying incorrectly on mobile. This has been fixed for the purposes of taking screenshots.
