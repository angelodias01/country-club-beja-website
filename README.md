# Country Club Beja Website

This repository contains the source code for the Country Club Beja landing page. It is a responsive, single-page website designed to showcase a nightlife venue, highlight upcoming events, and facilitate VIP table reservations.

## Project Overview

The project is designed to provide a premium digital experience for club-goers. It utilizes a dark, gold-accented color scheme to reflect the club's atmosphere ("O Coração da Noite"). The site functions as a central hub for customers to view the party calendar, explore the venue's vibe through social proof, and contact the establishment directly via WhatsApp for bookings.

## Key Features

### Immersive Hero Section
The landing page opens with a full-screen video background to immediately engage visitors, overlaid with the club's branding and a call-to-action for reservations.

### Event Calendar
A dynamic carousel section displays upcoming parties and themed nights. This feature is powered by Swiper.js and includes responsive breakpoints to ensure visibility on mobile, tablet, and desktop screens.

### VIP Reservation System
The VIP section highlights the premium services available. It features a direct integration with WhatsApp, allowing users to book tables or bottle service with a single click. A floating action button ensures this option is always accessible as the user scrolls.

### Visual Design and Animations
The interface uses a custom dark theme with gold accents defined in CSS variables. Elements on the page utilize scroll-triggered animations (fade-ups, zooms) powered by the AOS (Animate On Scroll) library to create a dynamic browsing experience.

### Responsive Navigation
The navigation bar adapts to the user's scroll position, changing transparency for better readability. On smaller screens, it collapses into a hamburger menu for ease of use.

## Technologies Used

* **HTML5:** Semantic markup structure.
* **CSS3:** Custom styling using CSS Grid, Flexbox, and CSS Variables for consistent theming.
* **JavaScript (ES6):** Logic for the mobile menu, scroll effects, and library initialization.
* **External Libraries:**
    * **Swiper.js:** Used for the touch-friendly events slider.
    * **AOS (Animate On Scroll):** Used for element entrance animations.
    * **FontAwesome:** Used for iconography throughout the interface.

## File Structure

* **index.html:** The main HTML document containing the structure of the Hero, Events, VIP, and Vibe sections.
* **style.css:** Contains all styling rules, including global variables for colors (Black, Dark, Gold) and typography settings (Montserrat and Open Sans).
* **script.js:** Handles the initialization of the AOS animation library, the Swiper carousel configuration, and the toggle logic for the mobile navigation menu.

## Usage

This project consists of static web files. To view the website, open the `index.html` file in any modern web browser. No server-side processing or compilation is required.
