# IMD Weather Radar & Satellite Viewer

A sleek, responsive, and user-friendly web application to view the latest Doppler Weather Radar and Satellite imagery directly from the India Meteorological Department (IMD). This tool allows users to quickly select a station and browse through various meteorological image products in a clean, modern interface with an interactive image viewer.

## Features

  * **Station Selector:** Easily switch between 35+ IMD radar stations across India with a convenient dropdown menu.
  * **Comprehensive Imagery:** Access a wide range of products, including:
      * **Radar:** Combined Azimuth Range (CAZ), Plan Position Indicator (PPI), Surface Rainfall Intensity (SRI), and animated GIFs.
      * **Satellite:** Infrared, Visible, Water Vapour, and CTBT imagery for both Asia and Global sectors, including animated versions.
  * **Interactive Modal Viewer:**
      * Click on any thumbnail to open a high-resolution image in a full-screen modal.
      * Navigate between different images seamlessly using arrow keys or on-screen buttons.
      * **Zoom & Pan:** Click to zoom in on specific details and pan across the image for in-depth analysis (desktop only).
  * **Keyboard Shortcuts:** Press `?` to view all available keyboard shortcuts and tips.
  * **Live Timestamp:** Displays the current date and time in IST, so you always know how fresh the data is.
  * **Responsive Design:** Fully optimized for a seamless experience on desktops, tablets, and mobile devices.
  * **Loading & Error States:** Smooth loading animations with automatic retry mechanism and clear "Not Available" messages.
  * **Direct Data Source:** All imagery is fetched directly from the official IMD website, ensuring data accuracy.
  * **Accessibility:** Full keyboard navigation support, ARIA labels, and screen reader friendly.
  * **PWA Support:** Can be installed as a Progressive Web App on mobile devices.

## Keyboard Shortcuts

- **Arrow Keys (← →):** Navigate between images in the viewer
- **ESC:** Close modal/help dialog
- **?:** Open keyboard shortcuts help
- **Enter/Space:** Activate focused image card
- **Tab:** Navigate through interactive elements

## Technical Features

- **SEO Optimized:** Comprehensive meta tags, Open Graph, and Twitter Card support
- **Structured Data:** JSON-LD schema for better search engine understanding
- **Image Retry Logic:** Automatic retry with exponential backoff for failed image loads
- **Smooth Animations:** Hardware-accelerated CSS animations for better performance
- **Touch Gestures:** Swipe support for mobile navigation

## Browser Support

Works on all modern browsers including:
- Chrome/Edge (recommended)
- Firefox
- Safari
- Mobile browsers (iOS Safari, Chrome Mobile)

## Contributing

Contributions, issues, and feature requests are welcome\! Feel free to check the `issues` page on the repository if you want to contribute.

-----

*Disclaimer: This is an unofficial viewer and is not affiliated with the India Meteorological Department (IMD). All data is sourced directly from the publicly available sections of the [IMD website](https://mausam.imd.gov.in/).*
