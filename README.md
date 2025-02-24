[![build](https://github.com/aelassas/bookcars/actions/workflows/build.yml/badge.svg)](https://github.com/aelassas/bookcars/actions/workflows/build.yml) [![test](https://github.com/aelassas/bookcars/actions/workflows/test.yml/badge.svg)](https://github.com/aelassas/bookcars/actions/workflows/test.yml) [![coveralls](https://coveralls.io/repos/github/aelassas/bookcars/badge.svg)](https://coveralls.io/github/aelassas/bookcars) [![loc](https://raw.githubusercontent.com/aelassas/bookcars/refs/heads/loc/badge.svg)](https://github.com/aelassas/bookcars/actions/workflows/loc.yml) [![docs](https://img.shields.io/badge/docs-wiki-brightgreen)](https://github.com/aelassas/bookcars/wiki) [![live demo](https://img.shields.io/badge/live-demo-brightgreen)](https://bookcars.dynv6.net:3002/)

<!--
[![docs](https://img.shields.io/badge/docs-wiki-brightgreen)](https://github.com/aelassas/bookcars/wiki)
[![live demo](https://img.shields.io/badge/live-demo-brightgreen)](https://bookcars.dynv6.net:3002/)
[![loc](https://raw.githubusercontent.com/aelassas/bookcars/refs/heads/loc/badge.svg)](https://github.com/aelassas/bookcars/actions/workflows/loc.yml) 
[![tested with jest](https://img.shields.io/badge/tested_with-jest-brightgreen?logo=jest)](https://github.com/jestjs/jest)
[![PRs welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg)](https://github.com/aelassas/bookcars/pulls)
[![codecov](https://codecov.io/gh/aelassas/bookcars/graph/badge.svg?token=FSB0H9RDEQ)](https://codecov.io/gh/aelassas/bookcars)
[![codecov](https://img.shields.io/codecov/c/github/aelassas/bookcars?logo=codecov)](https://codecov.io/gh/aelassas/bookcars)
[![coveralls](https://coveralls.io/repos/github/aelassas/bookcars/badge.svg)](https://coveralls.io/github/aelassas/bookcars)
-->

## BookCars

BookCars is a highly customizable, scalable, and cost-efficient solution for car rental businesses. Its robust feature set and open-source nature make it a sustainable choice for long-term growth in the rental industry.

With BookCars, you can deploy your own customizable car rental marketplace at minimal cost using the [Docker-based setup](https://github.com/aelassas/bookcars/wiki/Installing-(Docker)). The platform integrates Stripe for secure payments and can be efficiently hosted on a 1GB RAM droplet, making it an ideal choice for single/multi-supplier operations looking for a scalable and cost-effective solution. You can deploy this solution for under $5/month using cloud providers like [Hetzner](https://www.hetzner.com/cloud/) or [DigitalOcean](https://www.digitalocean.com/pricing/droplets).

BookCars is designed to work with multiple suppliers. Suppliers can manage their car fleets and bookings from the admin dashboard. BookCars can also work with a single supplier and can be used as a car rental aggregator.

From the admin dashboard, admins can create and manage suppliers, cars, countries, locations, parking spots, customers and bookings.

When new suppliers are created, they receive an email prompting them to create an account in order to access the admin dashboard and manage their car fleets and bookings.

Customers can sign up from the frontend or the mobile app, search for available cars based on pickup and drop-off points and time, choose a car and complete the checkout process.

## Features

* Supplier management
* [Supplier contracts](https://github.com/aelassas/bookcars/wiki/Supplier-Contracts)
* Ready for one or multiple suppliers
* Car fleet management
* [Dynamic price calculation](https://github.com/aelassas/bookcars/wiki/Price-Calculation)
* Location, country, parking spots and map features
* Booking management
* Payment management
* Customer management
* Multiple login options (Google, Facebook, Apple, Email)
* Multiple payment methods (Credit Card, PayPal, Google Pay, Apple Pay, Link, Pay Later)
* Multiple language support (English, French, Spanish)
* [Multiple currencies support](https://github.com/aelassas/bookcars/wiki/Add-New-Currency)
* Multiple pagination options (Classic pagination with next and previous buttons, infinite scroll)
* Operational Stripe Payment Gateway
* Responsive admin dashboard and frontend
* Native Mobile app for Android and iOS with single codebase
* Push notifications
* Secure against XSS, XST, CSRF and MITM
* Supported Platforms: iOS, Android, Web, Docker

## Live Demo

Some features are locked down on the demo links provided. To unlock all the features contact me by email and I will give a full access. You can find my email on my [GitHub](https://github.com/aelassas) profile page.

### Frontend

* URL: https://bookcars.dynv6.net:3002/
* Login: jdoe@bookcars.ma
* Password: B00kC4r5

### Admin Dashboard

* URL: https://bookcars.dynv6.net:3001/
* Login: admin@bookcars.ma
* Password: B00kC4r5

### Mobile App

<!--
You can install the Android app on any Android device.

#### Scan this code with a device

Open the Camera app and point it at this code. Then tap the notification that appears.

![QR](https://bookcars.github.io/content/qr-code-4.5.png)

#### How to install the Mobile App on Android

* On devices running Android 8.0 (API level 26) and higher, you must navigate to the Install unknown apps system settings screen to enable app installations from a particular location (i.e. the web browser you are downloading the app from).

* On devices running Android 7.1.1 (API level 25) and lower, you should enable the Unknown sources system setting, found in Settings > Security on your device.

#### Alternative Way
-->

You can install the Android App by downloading the APK and installing it on any Android device.

* [Download APK](https://github.com/aelassas/bookcars/releases/download/v4.8/bookcars-4.8.apk)
* Login: jdoe@bookcars.ma
* Password: B00kC4r5

## Documentation

1. [Overview](https://github.com/aelassas/bookcars/wiki/Overview)
2. [Why Use BookCars](https://github.com/aelassas/bookcars/wiki/Why-Use-BookCars)
2. [Architecture](https://github.com/aelassas/bookcars/wiki/Architecture)
3. [Installing (Self-hosted)](https://github.com/aelassas/bookcars/wiki/Installing-(Self%E2%80%90hosted))
4. [Installing (VPS)](https://github.com/aelassas/bookcars/wiki/Installing-(VPS))
5. [Installing (Docker)](https://github.com/aelassas/bookcars/wiki/Installing-(Docker))
   1. [Docker Image](https://github.com/aelassas/bookcars/wiki/Installing-(Docker)#docker-image)
   2. [SSL](https://github.com/aelassas/bookcars/wiki/Installing-(Docker)#ssl)
6. [Setup Stripe](https://github.com/aelassas/bookcars/wiki/Setup-Stripe)
7. [Build Mobile App](https://github.com/aelassas/bookcars/wiki/Build-Mobile-App)
8. [Demo Database](https://github.com/aelassas/bookcars/wiki/Demo-Database)
   1. [Windows, Linux and macOS](https://github.com/aelassas/bookcars/wiki/Demo-Database#windows-linux-and-macos)
   2. [Docker](https://github.com/aelassas/bookcars/wiki/Demo-Database#docker)
9. [Run from Source](https://github.com/aelassas/bookcars/wiki/Run-from-Source)
10. [Run Mobile App](https://github.com/aelassas/bookcars/wiki/Run-Mobile-App)
    1. [Prerequisites](https://github.com/aelassas/bookcars/wiki/Run-Mobile-App#prerequisites)
    2. [Instructions](https://github.com/aelassas/bookcars/wiki/Run-Mobile-App#instructions)
    3. [Push Notifications](https://github.com/aelassas/bookcars/wiki/Run-Mobile-App#push-notifications)
    4. [Run iOS App](https://github.com/aelassas/bookcars/wiki/Run-Mobile-App#run-ios-app)
11. [Add New Language](https://github.com/aelassas/bookcars/wiki/Add-New-Language)
12. [Add New Currency](https://github.com/aelassas/bookcars/wiki/Add-New-Currency)
13. [Unit Tests and Coverage](https://github.com/aelassas/bookcars/wiki/Unit-Tests-and-Coverage)
14. [Price Calculation](https://github.com/aelassas/bookcars/wiki/Price-Calculation)
15. [Supplier Contracts](https://github.com/aelassas/bookcars/wiki/Supplier-Contracts)
16. [Logs](https://github.com/aelassas/bookcars/wiki/Logs)

## License

BookCars is [MIT licensed](https://github.com/aelassas/bookcars/blob/main/LICENSE).
