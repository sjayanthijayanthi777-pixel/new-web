# Car Images Download Website

A simple static website for downloading car images.

## Usage

1. Open `index.html` in your web browser.
2. View the gallery of car images.
3. Click the "Download" button below each image to download it to your device.

## Adding More Images

To add more car images:

1. Place your image files in the same directory as `index.html` (or in a subfolder).
2. Add a new `<div class="image-item">` block in the gallery section of `index.html`.
3. Update the `src` attribute of the `<img>` tag to point to your image.
4. Update the `href` attribute of the `<a>` tag to the same image path, and ensure the `download` attribute is present.

Example:
```html
<div class="image-item">
    <img src="your-car-image.jpg" alt="Your Car">
    <a href="your-car-image.jpg" download class="download-btn">Download</a>
</div>
```

## Troubleshooting

- If downloads don't work, ensure the image files are accessible and the paths are correct.
- For online images, some browsers may block downloads due to CORS policies. Use local images for best compatibility.
- If the page doesn't load properly, check that `styles.css` is in the same directory.

## Technologies Used

- HTML5
- CSS3