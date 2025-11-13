# IMC Moodle Customization

This project contains custom code and styling for the IMC Moodle platform.

## Overview
The customization includes:
1. **Unit Banner** – HTML and CSS code for displaying unit-specific banners.
2. **UI Enhancements** – Additional CSS modifications for the new learning interface style.

## Important Notes
- Due to Moodle’s **security and content filtering policies**, some CSS properties and HTML tags (e.g. `display: flex`) are **not allowed**.
- Using restricted styles may cause layout inconsistencies between the **Admin view** and the **Student view**.
- Always test changes in both environments to ensure consistent appearance.

## Tips for Development
- Keep the structure simple and compatible with Moodle’s text editor.
- Use table-based layouts instead of Flexbox for multi-button banners.
- Avoid inline scripts and restricted attributes to prevent Moodle from sanitizing your code.