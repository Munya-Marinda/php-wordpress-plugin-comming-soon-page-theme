# Coming Soon Page Template

This WordPress theme template is designed to create a simple, full-width "Coming Soon" page with a centered image that automatically spans the entire width of the screen. It uses the `twentytwentytwo` theme as the parent theme and overrides it with a custom layout for this specific page.

### Files Explained

- **index.php**: Contains the HTML structure for the Coming Soon page, displaying a full-width image in the center of the viewport.
- **functions.php**: Enqueues the `twentytwentytwo` parent theme's style.css file to maintain consistency with the base theme.
- **style.css**: Contains theme metadata and any custom styles. Defines this theme as a child of `twentytwentytwo`.

---

## Installation

1. **Upload the Theme**:
   - Place the theme folder (e.g., `coming-soon-page`) in your WordPress installation under `wp-content/themes/`.

2. **Activate the Parent Theme**:
   - Ensure the `twentytwentytwo` theme is installed in your WordPress installation.

3. **Activate the Coming Soon Theme**:
   - Go to **Appearance > Themes** in the WordPress dashboard.
   - Activate the `Coming Soon Page` theme.

---

## Customization

1. **Changing the Image**:
   - To use a different image, edit the `src` attribute in the `<img>` tag in `index.php`.
   - Replace the current URL with the URL of your desired image.

2. **Style Adjustments**:
   - Additional custom styles can be added directly in `style.css` or by adding new CSS rules in the `<style>` block within `index.php`.

---

## Usage

- This theme is ideal for websites under construction or undergoing maintenance.
- It provides a minimalistic "Coming Soon" look with a centered image.

---

## Credits

This theme was created using:
- **Parent Theme**: [twentytwentytwo](https://wordpress.org/themes/twentytwentytwo/)
- **Image Source**: Photo by <a href="https://unsplash.com/@mitchel3uo?utm_content=creditCopyText&utm_medium=referral&utm_source=unsplash">Mitchell Luo</a> on <a href="https://unsplash.com/photos/black-and-white-striped-textile-FWoq_ldWlNQ?utm_content=creditCopyText&utm_medium=referral&utm_source=unsplash">Unsplash</a>
      

---

## License

This project is licensed under the MIT License.