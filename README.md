# Daily Milk Sales — Mobile Web App

A mobile-friendly installable Progressive Web App based on the supplied Daily Milk Sales HTML app.

## Features
- Track packet counts for Heritage, Vijaya, and Amul
- Calculate daily sales totals and milk volume
- Edit prices, hide products, and add products
- Create a daily invoice suitable for printing/saving as PDF
- Open a UPI payment intent and manually mark a payment as verified
- Save records in the current browser/device
- Install on supported phones and cache the app shell for offline opening

## Install on a phone
Open the deployed HTTPS URL in your phone's browser and choose **Add to Home Screen** / **Install app** if offered.

## Deploy
The included GitHub Actions workflow deploys the root of this repository to GitHub Pages on pushes to `main`. In repository **Settings → Pages**, choose **GitHub Actions** as the source if prompted.

## Important data and payment notes
- Sales records and settings are stored in browser local storage on the device; they are not synchronized between devices and can be lost if browser data is cleared.
- UPI is opened with the total pre-filled when supported. The app does not independently verify bank settlement; check the payment app before marking a payment as confirmed.
- This is an installable web app, not a signed native Android APK.