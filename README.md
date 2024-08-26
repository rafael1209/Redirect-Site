# Redirect to Telegram Channel

This project is a simple HTML file that instantly redirects users to a specified Telegram channel. It also includes meta tags for embedding a preview of the link when shared on social media and messaging platforms.

## Table of Contents

- [Description](#description)
- [Installation](#installation)
- [Usage](#usage)
- [Customization](#customization)
- [License](#license)

## Description

This HTML file redirects the user to a Telegram channel immediately upon page load. The included Open Graph and Twitter Card meta tags ensure a rich link preview when the page is shared.

## Installation

1. Download or clone the repository:

    ```bash
    git clone https://github.com/yourusername/redirect-to-telegram.git
    ```

2. Navigate to the project directory:

    ```bash
    cd redirect-to-telegram
    ```

3. Edit the `index.html` file if necessary.

## Usage

Simply open the `index.html` file in your browser, and you will be instantly redirected to the specified Telegram channel.

## Customization

- **Redirect URL**: Change the `url` value in the meta tag `<meta http-equiv="refresh" content="0;url=https://google.com">` to the URL of your channel.
- **Link Preview**: Update the Open Graph and Twitter Card meta tags in the `<head>` section:
  - `og:title` — The title of the link preview.
  - `og:description` — The description of the link preview.
  - `og:image` — The URL of the image used for the preview.

Example of updated meta tags:

```html
<meta property="og:title" content="Your Title">
<meta property="og:description" content="Your description">
<meta property="og:image" content="https://example.com/your-image.jpg">
<meta property="og:url" content="https://your-site.com">
