# Shopify Developer Challenge

This project serves as a challenge to demonstrate my Shopify skills by building a simple Product Detail Page (PDP) using Shopify's Liquid syntax and the AJAX Cart API. All work is contained within the original repository from Unit 203.

## Setup

Simply follow these instructions to get the project running:

1. Clone this repository onto your development environment.
2. From the new folder, install the required modules using `npm install` (Or your favorite package manager).
3. Start the development server using `npm run dev`.

The page will be available at `localhost:3000` that will display the result PDP of this challenge.

# About the Challenge

To tackle this challenge, I prioritized simplicity, leveraging each language’s strengths:

- Shopify Liquid Syntax and HTML: for structuring the page
- CSS: to handle appearance, responsiveness, and styling
- JavaScript: for dynamic elements and Ajax integration

While I have extensive experience with Ajax, primarily for database integration, it was refreshing to use it in this context to access endpoints without involving a database.

If this were part of a real Shopify application, price formatting would already be handled using the `money_with_currency` directive. However, for this challenge, I utilized JavaScript's `Intl.NumberFormat` to ensure correct price formatting in Canadian dollars.

I thoroughly enjoyed this challenge, especially because of its practical nature. Delivering a product detail page (PDP) that can seamlessly integrate with the rest of the site, while being developed in parallel to meet QA requirements, greatly enhances both the safety and efficiency of website development and maintenance.
