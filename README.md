# SpendWise Dashboard Shell

SpendWise is a static financial dashboard built using HTML and CSS. The goal of this project is to create a clean, responsive dashboard interface using realistic made-up financial data.

## What I Built

The dashboard includes:

* A sidebar navigation menu
* A dashboard header
* A monthly financial summary
* Six spending category cards:

  * Food
  * Transport
  * Rent
  * Entertainment
  * Savings
  * Utilities
* Responsive design for desktop and mobile screens
* Hover and keyboard focus effects on dashboard cards
* A dark theme based on the user's system settings

## CSS Grid

CSS Grid is used for the overall dashboard layout. On larger screens, the dashboard is divided into two columns: a sidebar and the main content area.

Grid is also used to arrange the financial summary cards and spending category cards.

## Flexbox

Flexbox is used inside dashboard components. It helps arrange items in the header, sidebar navigation, summary sections, and category cards.

For example, Flexbox places the category icon and percentage on the same row inside each card.

## CSS Custom Properties

The application's colors are stored as CSS variables in the `:root` selector.

The variables include:

* Brand color
* Accent color
* Surface color
* Background color
* Primary text color
* Secondary text color

Using CSS variables makes the dashboard theme easier to maintain because colors can be changed from one location.

## Responsive Design

A media query is used for screens smaller than 768px.

Below 768px:

* The dashboard changes to a single-column layout
* The sidebar moves above the main content
* Summary cards display in one column
* Spending category cards display in one column
* Header content stacks vertically

The responsive layout can be tested using the browser DevTools Device Toolbar.

## Micro-interactions

The spending cards include hover and keyboard focus animations.

When a user hovers over or focuses on a card, the card moves slightly upward and displays a stronger shadow.

The transition lasts 200ms, which is below the required 250ms maximum.

## Dark Theme

The project also includes the stretch goal dark theme using:

`@media (prefers-color-scheme: dark)`

The dark theme works by overriding the CSS variables without changing the dashboard layout.

## Project Files

* `index.html` - Contains the dashboard structure and static financial information.
* `style.css` - Contains the dashboard layout, colors, responsive design, and animations.
* `README.md` - Explains what the project contains and how the major parts work.
## What's Coming Next

This version of SpendWise focuses on the visual dashboard structure and responsive design. The financial information currently displayed is static sample data.

JavaScript functionality starts next week. The next stage of the project will add interactive features such as entering expenses, calculating totals, updating spending categories, and making the dashboard respond to user input.
## Author

Robin
