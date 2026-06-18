# Sinergia Clinic Website

<p align="center">
  <img src="icon.png" alt="Sinergia Clinic icon" width="96">
</p>

A static website for Sinergia Clinic, a local health and fitness clinic in Valencia. The site presents the clinic's main services, contact options, location, and appointment call-to-actions in a simple one-page format.

The interface is currently in Spanish.

## Features

- Responsive one-page layout built with Bootstrap.
- Service sections for physiotherapy, personal training, nutrition, and podiatry.
- Service-specific call-to-action buttons for booking appointments.
- Phone links for direct mobile contact.
- WhatsApp contact flow with a pre-filled message based on the selected service.
- Email contact flow using a generated `mailto:` link.
- Embedded Google Maps location.
- Social links for Instagram and Facebook.
- Patient testimonial section.

## Tech Stack

- HTML
- CSS
- JavaScript
- [Bootstrap 4](https://getbootstrap.com/docs/4.6/getting-started/introduction/)
- [Font Awesome](https://fontawesome.com/) for social and contact icons

## Running Locally

Clone the repository and open `index.html` in a browser:

```bash
git clone https://github.com/MarcosGibert/Sinergia.git
cd Sinergia
open index.html
```

You can also serve the folder locally:

```bash
python3 -m http.server 8000
```

Then visit `http://localhost:8000`.

Because the site loads Bootstrap, Font Awesome, jQuery, and the Google Maps embed from external CDNs/services, an internet connection is required for the full experience.

## Project Context

This project was built as a lightweight website for a real local clinic. The goal was to create a clear digital presence where visitors can understand the available services, find the clinic, and start a booking conversation through familiar contact channels.

## Structure

- `index.html` contains the page markup, styling, and JavaScript interactions.
- `icon.png` is used as the site icon.
- `fisioterapia.png`, `entrenamiento.png`, `nutricion.png`, and `podologia.png` support the service sections.


