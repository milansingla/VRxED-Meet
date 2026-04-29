# VRxED-Meet

**Meeting Panel | VRxED - Medical Education Technology**

![VRxED-Meet](https://lovable.dev/opengraph-image-p98pqg.png)

## Overview

VRxED-Meet is a browser-based meeting solution tailored specifically for medical education and healthcare training. It offers enterprise-grade video conferencing combined with real-time translation capabilities, breaking down language barriers in the medical field.

## Features

- **Live Translation**: Real-time translation in 50+ languages to facilitate global medical collaboration and education.
- **Enterprise-Grade Video Conferencing**: High-quality, reliable, and secure video meetings designed for professional healthcare environments.
- **Browser-Based**: No installations required. Accessible directly from modern web browsers for seamless join experiences.
- **Deep-Link Support**: Built-in routing recovery for static hosting environments to ensure reliable navigation and link sharing.

## Deployment

This repository contains the optimized production build of the VRxED-Meet frontend. It is ready to be served by any static file hosting service (e.g., Vercel, Netlify, GitHub Pages, or a standard Nginx/Apache server).

### Hosting Instructions

1. Serve the root directory of this repository.
2. Ensure your static hosting is configured to redirect all 404 requests to `index.html` to support the client-side routing.
3. A `404.html` is included, which utilizes a meta-refresh strategy to preserve paths across full page reloads on standard static hosts like GitHub Pages.

## Project Structure

- `index.html`: The main entry point.
- `assets/`: Contains the bundled JavaScript and CSS files, as well as static assets like the VRxED logo.
- `404.html`: Fallback page for single-page application (SPA) routing on static hosts.
- `robots.txt`: Search engine crawling directives.

## About VRxED

VRxED is dedicated to advancing medical education through innovative technology solutions.