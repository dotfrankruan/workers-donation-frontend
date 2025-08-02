# Workers Donation Frontend

This project is a static HTML frontend for a donation page. It integrates with a backend service to create Stripe Checkout sessions.

## Features

*   **Donation Form**: A simple form to collect the donation amount, currency, and an optional note.
*   **Stripe Integration**: Redirects to Stripe Checkout for secure payment processing.
*   **Theme Toggle**: Supports light and dark modes.
*   **Responsive Design**: Built with Tailwind CSS for a responsive layout.

## Pages

*   `index.html`: The main donation page.
*   `donation-success.html`: The page displayed after a successful donation.
*   `donation-canceled.html`: The page displayed after a canceled donation.

## Configuration

To use this frontend, you need to configure the following variables in the `<script>` section of `index.html`:

*   `stripePublishableKey`: Your Stripe publishable key.
*   `createCheckoutSessionUrl`: The URL of your backend endpoint that creates a Stripe Checkout session.
*   `successUrl`: The URL to redirect to after a successful donation.
*   `cancelUrl`: The URL to redirect to after a canceled donation.
