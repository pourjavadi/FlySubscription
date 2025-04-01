# Fly Subscription Template Marzban

*A sleek, modern subscription dashboard template designed for Marzban, built with HTML, CSS, and JavaScript.*

---

## Overview

"Fly Subscription Template Marzban" is a beautifully designed, responsive subscription dashboard template tailored for the Marzban VPN panel. It features a glassmorphism UI, light/dark theme toggle, an accordion for configuration links, and QR code generation for easy sharing. This template is perfect for displaying user subscription details and providing download links for V2Ray clients across multiple platforms.

### Features
- **Responsive Design**: Optimized for all screen sizes (max-width: 480px for cards).
- **Glassmorphism UI**: Transparent, blurred backgrounds with vibrant gradients.
- **Theme Toggle**: Switch between light and dark modes with a smooth transition.
- **Accordion Links**: Collapsible section for configuration links with copy and QR code options.
- **Platform Icons**: Font Awesome icons for Android, Windows, Linux, and iOS.
- **Dynamic QR Codes**: Generate QR codes for each configuration link on demand.
- **Animations**: Subtle fade-in effects for a polished user experience.

---

## Demo
![Untitled-2](https://github.com/user-attachments/assets/3dd47258-c91e-46b1-9276-f7216f7ace35)


---

## Installation

To use this template in your project, follow these steps:

1. **Clone the Repository**:
   ```bash
   sudo wget -N -P /var/lib/marzban/templates/subscription/ https://raw.githubusercontent.com/pourjavadi/FlySubscription/refs/heads/main/index.html
2. **Run the following commands in your server terminal** :
   ```bash
   echo 'CUSTOM_TEMPLATES_DIRECTORY="/var/lib/marzban/templates/"' | sudo tee -a /opt/marzban/.env
   echo 'SUBSCRIPTION_PAGE_TEMPLATE="subscription/index.html"' | sudo tee -a /opt/marzban/.env
