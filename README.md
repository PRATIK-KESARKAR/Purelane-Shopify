# Purelane Homepage - Shopify Theme Integration

This repository contains the completed **Troopod AI Product Engineer Assignment**. The goal of this project was to migrate a high-fidelity, interactive HTML/CSS prototype (the Purelane Homepage) into a production-ready Shopify Dawn theme, ensuring pixel-perfect fidelity, responsive design, and dynamic Shopify Liquid integration.

## 🚀 Key Features & Implementation Details

*   **Cinematic Hero Section:** Fully integrated the interactive hero stage with automatic sliding SVG bottles, ambient floating animations, and scroll-driven parallax effects, matching the prototype perfectly.
*   **Premium Product Cards:** Upgraded the default Dawn product cards to match the beautiful, glassmorphism-inspired "Bestsellers" UI, maintaining perfect alignment and typography.
*   **Dynamic Liquid Sections:** Converted static HTML into customizable Shopify sections:
    *   **Hero** (Dynamic messaging, SVG bottle fallbacks)
    *   **Bestsellers** (Product grids and onboarding states)
    *   **Combos/Bundles** (Tiered pricing display)
    *   **Reviews** (Horizontal scrolling rail)
    *   **Ingredients, Pillars, & Proof** (Trust and informational sections)
*   **Performance & CSS Architecture:** Consolidated the prototype's custom styling into `purelane.css` and integrated it globally via `theme.liquid`. Used efficient intersection observers for scroll animations in `purelane.js`.

## 🛠 Tech Stack

*   **Platform:** Shopify (Dawn Theme Architecture)
*   **Templating:** Liquid
*   **Styling:** Vanilla CSS (CSS Variables, Flexbox/Grid, Animations)
*   **Interactivity:** Vanilla JavaScript (IntersectionObserver, scroll listeners)

## 💻 How to Run Locally

1.  Ensure you have the [Shopify CLI](https://shopify.dev/docs/themes/tools/cli) installed.
2.  Clone this repository and navigate to the `dawn` directory:
    ```bash
    cd dawn
    ```
3.  Authenticate and run the local development server:
    ```bash
    shopify theme dev --store YOUR_STORE_URL
    ```
4.  Open the provided localhost link to view and customize the theme in the Shopify Theme Editor.

## 📝 Assignment Notes

*   All layout adjustments have been rigorously tested to ensure the final Shopify store matches the provided HTML prototype flawlessly.
*   SVGs and onboarding states have been heavily utilized to ensure the UI looks incredible even if real product images are not yet uploaded by the merchant.
