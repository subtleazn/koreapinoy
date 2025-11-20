# Korea Pinoy International Film Festival Blogger Theme

This is a custom Blogger theme designed for the Korea Pinoy International Film Festival website, deployed on `korea.pinoyseoul.com`. This theme has been updated to improve Search Engine Optimization (SEO), structured data (Schema.org), and social media sharing capabilities.

## Features

-   **Dynamic SEO:** Optimized `<title>` and `<meta name="description">` tags that dynamically adapt to the page content (homepage, individual posts).
-   **Structured Data (JSON-LD):** Implements `WebSite` schema for the overall blog and `BlogPosting` schema for individual articles, improving how content is presented in search results.
-   **Enhanced Social Sharing:** Includes Open Graph (for Facebook, LinkedIn) and Twitter Card meta tags to ensure articles are displayed beautifully when shared on social media platforms, featuring dynamic titles, descriptions, and images.

## Installation

To install this theme on your Blogger blog:

1.  Navigate to your Blogger dashboard.
2.  Go to `Theme` -> `Edit HTML`.
3.  Replace the entire existing HTML content with the content of the `theme.xml` file provided in this repository.
4.  Save the theme.

## Customization

### Default Images for Social Sharing

The theme includes placeholders for a default share image and a publisher logo. You **MUST** update these URLs:

-   **Default Share Image:** Look for `https://korea.pinoyseoul.com/img/default-share-image.jpg` in `theme.xml` and replace it with the URL of your desired default image. This image will be used when a specific post image is not available for social sharing.
-   **Publisher Logo:** Look for `https://korea.pinoyseoul.com/img/logo.png` in `theme.xml` within the `BlogPosting` schema and replace it with the URL of your organization's logo.

### Other Customizations

Feel free to modify the CSS and HTML within `theme.xml` to match your branding and design preferences.

## Author

**Nash Ang**
*Under the umbrella of PinoySeoul Media Enterprise*

## License

(If applicable, add your license information here, e.g., MIT License)
