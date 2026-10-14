# Symptly Privacy

**Hosts the privacy policy, terms of service, support FAQ, and data-rights page for Symptly, an iOS symptom and wellness tracker.**

Live: **https://symptly-privacy.vercel.app**

## Pages

Everything lives in one file, `index.html`, with five tabs switched by a small inline script:

- **Privacy Policy**, last updated March 18, 2026
- **Terms of Service**, including the "not a medical device" disclaimer and subscription terms
- **Support**, an FAQ on logging, scores, correlations, export, and subscriptions
- **Contact Us**, a form that opens a pre-filled `mailto:` link in the user's mail app and posts nothing to a server
- **Your Data**, covering access, deletion, export, and GDPR and CCPA notes

## What the policy says

Symptly keeps symptom logs, daily check-ins, journals, medications, Apple Health readings (sleep, heart rate, steps, active minutes), and weather data on the device, and syncs them only through the user's own iCloud account via CloudKit. All analysis runs on the device with Core ML. The policy states that Symptly has no servers that receive health information, uses no analytics, tracking pixels, or third-party SDKs, serves no ads, does not use data for model training, and never sells or shares data; HealthKit data is never used for marketing. The only outside services listed are Apple HealthKit, CloudKit, StoreKit, and WeatherKit or Open-Meteo for weather. Users can export a CSV, delete single entries, clear all data, or reset the app.

## Update and deploy

Vercel deploys the `main` branch to production. Edit `index.html` and push to `main`.

Contact: keshav-krishnan@outlook.com
