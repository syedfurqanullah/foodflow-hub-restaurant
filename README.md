# FoodFlow Restaurant Management & Ordering Website

FoodFlow is a practice frontend project built collaboratively by our team as part of the Bano Qabil program. It presents a restaurant ordering experience for customers and a separate admin interface for restaurant management. The project is designed for learning and frontend practice, not as a live ordering service.

## Live demo

[View FoodFlow](https://foodflow-kitchen.netlify.app/)

## Screenshot

![FoodFlow home page](./assets/screenshots/home%20page.png)

## What is included

- A customer website with the home page, menu, food categories, gallery, contact page, cart, checkout preview, order pages, and account page.
- An admin interface with dashboard, orders, customers, menu management, settings, and sign-in pages.
- Responsive layouts for mobile, tablet, and desktop screens.
- Shared theme variables for changing customer-site and admin-panel colors.

## Project structure

```text
Food Flow Restaurant/
├── index.html                 Customer home page
├── pages/
│   ├── admin/                 Admin interface pages
│   ├── menu/                  Food category pages
│   └── ...                    Customer pages
├── css/
│   ├── admin/                 Admin styles and theme variables
│   ├── ...                    Shared and page-specific styles
│   └── variables.css          Customer-site theme variables
├── assets/
│   ├── images/                Food and website images
│   ├── icons/                 Website icons and favicon
│   └── screenshots/           Project screenshots
└── js/                        Existing JavaScript files
```

The planned technologies are HTML, CSS, and JavaScript. The current website pages use HTML and CSS; JavaScript features will be implemented in a later stage. The existing files in `js/` are not currently linked from the HTML pages.

## Run the website locally

1. Open the project folder in Visual Studio Code.
2. Start a local preview using the Live Server extension.
3. Open `index.html` in the preview.

No package installation or build step is required.

## Demo limitations

FoodFlow is a front-end demonstration. Sign-in, sign-up, cart actions, orders, payments, contact forms, and admin updates are not connected to a server or database. Do not enter real personal or payment information.

## Project information

- **Program:** Bano Qabil
- **Project type:** Team Collaborative practice frontend project
- **Focus:** Restaurant management and online ordering
- **Planned technologies:** HTML, CSS, and JavaScript
- **Current implementation:** HTML and CSS; JavaScript features are planned for later
