# Enhanced Icon Alignment Stylesheet for Xymon

This stylesheet enhances the alignment of colored icons on Xymon pages for a cleaner and more organized appearance.

## Features

- Improves alignment of colored status icons.
- Ensures consistent spacing and layout.
- Minimal modifications to existing Xymon styles to ensure fallback to the current design without issues.

## Installation

1. Copy the `xymonbody.css` file to the appropriate directory on your Xymon server:
   ```bash
   cp xymonbody.css /path/to/xymon/server/www/gifs/
   ```
2. Apply the changes to ensure the new stylesheet is loaded:
   - Restart your HTTP server to serve the updated stylesheet:
     ```bash
     systemctl restart httpd
     ```
*(If you're using a different web server, replace `httpd` with the appropriate service name, such as `apache2` or `nginx`.)*

## Testing

1. Clear your browser cache to ensure the updated styles are displayed correctly.
2. Open the Xymon interface and verify the improved alignment of colored icons.
