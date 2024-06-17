# magnific-popup-gallery-builder

This repository contains an interactive web interface for creating magnific-popup.js-compatible image galleries. It provides an easy and intuitive way to upload images, enter image source and alt text, and generate the necessary HTML code and bash script for the gallery.

# Image Gallery Web Interface

## Features

- Drag and drop images or click the "+" button to upload images
- Display uploaded images as thumbnails in a grid layout
- Enter image source and alt text for each image
- Dynamically update the gallery code as input values change
- Generate a bash script to automate image directory creation, image copying, thumbnail generation, and HTML code output
- Utilize Magnific Popup library for a responsive and visually appealing gallery

## Getting Started

1. Clone the repository:

   ```
   git clone https://github.com/your-username/image-gallery-web-interface.git
   ```

2. Open the `index.html` file in a web browser.

3. Drag and drop images onto the designated area or click the "+" button to select images.

4. Enter the desired image source and alt text for each image.

5. Click the "Export Script" button to generate and download the bash script.

6. Run the downloaded bash script to create the necessary directory structure, copy images, generate thumbnails, and output the gallery HTML code.

7. Copy the generated HTML code and paste it into the HTML page where you want to display the gallery.

8. Ensure that you have imported the Magnific Popup library from Cloudflare or your own server. Add the following line in the `<head>` section of your HTML page:

   ```html
   <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/magnific-popup.js/1.1.0/magnific-popup.min.css">
   <script src="https://cdnjs.cloudflare.com/ajax/libs/magnific-popup.js/1.1.0/jquery.magnific-popup.min.js"></script>
   ```

9. Initialize the Magnific Popup gallery by adding the following JavaScript code:

   ```javascript
   $(document).ready(function() {
     $('.gallery-item').magnificPopup({
       type: 'image',
       gallery: {
         enabled: true
       }
     });
   });
   ```

10. Your image gallery should now be fully functional and responsive.

## Usage

1. Open the `index.html` file in a web browser.
2. Drag and drop images onto the designated area or click the "+" button to select images.
3. Enter the image source and alt text for each image using the provided input fields.
4. Click the "Export Script" button to generate and download the bash script.
5. Run the downloaded bash script to create the necessary directory structure, copy images, generate thumbnails, and output the gallery HTML code.
6. Copy the generated HTML code and paste it into your desired HTML page.
7. Ensure that you have imported the Magnific Popup library and initialized the gallery as described in the "Getting Started" section.

## Contributing

Contributions are welcome! If you have any suggestions, bug reports, or feature requests, please open an issue or submit a pull request.

## Updates

Version 1.1 (Planned)

Add support for custom thumbnail sizes
Implement drag-and-drop reordering of gallery items
Improve error handling and validation for user inputs

Version 1.2 (Planned)

Introduce a configuration panel for customizing gallery styles (e.g., grid layout, spacing, border)
Add option to include captions for each gallery item
Enhance accessibility by improving keyboard navigation and ARIA attributes

Version 1.3 (Planned)

Implement server-side processing for handling large galleries and optimizing performance
Add support for multiple galleries on a single page
Introduce a gallery preview feature for instant visual feedback during gallery creation

Version 2.0 (Future)

Develop a plugin architecture for extending the functionality of the gallery interface
Implement user authentication and authorization for personalized gallery management
Introduce collaborative features for team-based gallery creation and editing

## License

This project is licensed under the [MIT License](LICENSE).

Feel free to customize the README further based on your specific requirements and add more sections as needed.
