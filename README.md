
# Local Business QR Feedback Page

A single-page web app designed for restaurant/customer feedback collection via QR code.

## Features

- Mobile-friendly, fast-loading single-page interface
- 1-to-5 star rating flow
- Redirect to Google review for 4-5 star ratings and copy comment text to clipboard
- Direct feedback submission via Formspree for low ratings
- Thank-you/discount messages and confetti effect on successful actions

## Technologies

- HTML5
- Tailwind CSS (CDN)
- Vanilla JavaScript
- Font Awesome
- Formspree (webhook/form endpoint)

## Setup and Run

1. Clone the project:
   - `git clone <repo-url>`
2. Go to the project folder:
   - `cd localbusiness-qr`
3. Open `index.html` in your browser.

Note: You can also use an extension like VS Code Live Server for local development.

## Configuration

Update these values in `index.html` for your own business:

- `googlePlaceId`
- `ownerWebhookUrl` (Formspree endpoint)
- Business name, address, phone number, and working hours

## App Preview

![App Preview](./assets/app-preview.png)

## License

This project is licensed under the [MIT](./LICENSE) License.