# landing-page

How the text was put underneath the image:
Each image and its corresponding text are wrapped inside a container div with the class element-content. This container is responsible for grouping the image and text together.

The .element-content class is styled as a flex container with a column layout. This ensures that its child elements (image and text) are stacked vertically.

Image Styling:
The image itself is styled to ensure it takes up the full width, maintains its aspect ratio, and has some margin at the bottom for separation from the text.

Text Styling:
The text within each .element-content is styled to have a maximum width (60% of its container) and aligned to the left. This ensures that the text does not exceed a certain width and is left-aligned under the image.

By wrapping each image and text within a container and using flexbox properties, we create a layout where the images and texts are aligned in a column for each element. The .element-content class plays a crucial role in this, defining the flex container that organizes the image and text in a vertical arrangement.