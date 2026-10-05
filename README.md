# SpendWise Dashboard Shell

## Project Overview

SpendWise is a responsive financial dashboard designed to help users visualize and organize their monthly expenses and savings. This project uses HTML and CSS to create a modern dashboard layout.

## Features

* Sidebar navigation menu
* Header with a welcome message
* Six financial category cards
* Responsive layout for mobile and desktop
* CSS Grid for the main dashboard and category cards
* Flexbox for the header, sidebar navigation, and individual cards
* CSS custom properties for consistent colors
* Hover and keyboard focus animations
* Dark theme support based on system preferences

## Financial Categories

The dashboard displays the following static financial information:

* Food: KSh 8,500
* Transport: KSh 4,200
* Rent: KSh 10,000
* Entertainment: KSh 3,500
* Savings: KSh 6,000
* Utilities: KSh 2,800

## Technologies Used

* HTML5
* CSS3
* CSS Grid
* Flexbox
* CSS Variables
* Media Queries

## Project Structure

* `index.html` — Contains the dashboard structure, sidebar, header, and category cards.
* `style.css` — Contains the styling, Grid and Flexbox layouts, responsive design, animations, and dark theme.
* `README.md` — Explains the project and its features.

## Responsive Design

The dashboard uses a media query at 768px to adapt to smaller screens. On mobile devices, the sidebar and main content are arranged in a single column, and the financial cards are displayed vertically.

## Micro-interactions

The financial cards include hover and keyboard focus effects using CSS transforms and box shadows. The transitions last 200ms.

## Dark Theme

The project includes a dark theme using the `prefers-color-scheme: dark` media query. It changes the CSS custom properties to support dark backgrounds and lighter text.

## How to Run

1. Download or clone the repository.
2. Open `index.html` in a web browser.
3. View the dashboard on desktop or use browser DevTools to test the mobile layout.

## Project Goal

The goal of this project is to build a clean, responsive dashboard shell using modern CSS layout techniques as a foundation for a future financial tracking application.
