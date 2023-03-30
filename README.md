# Computer-Painting
Computer Painting using opencv to generate random colorful rangoli patterns.

## Overview
A 16 by 16 matrix is taken where each cell is filled with a random number from 1 to 4. 
This random matrix is used to create paintings where each cell is mapped to one of four images according to the number it contains. 
The four images (with random features) are created using opencv such that when arranged as per random matrix they give beautiful rangoli patterns.

## Customization
The following parameters can be modified in the code to customize the generated image:
<ul>
  <li>image_size: The size of the image in pixels (default is 256).</li>
  <li>background_color: The RGB color of the image background (default is a vibrant pink).</li>
  <li>center_radius: The radius of the filled circle in the center of the image (default is a random value between image_size/4 and image_size/2).</li>
  <li>num_concentric_circles: The number of concentric circles around the center circle (default is 4).</li>
  <li>num_petals: The number of petals around the center circle (default is 8).</li>
  <li>num_quarter_circles: The number of quarter circles at each corner of the image (default is 4).</li>
  <li>max_radius_ratio: The maximum ratio between the radius of each shape and the radius of the center circle (default is 2).</li>
  <li>max_thickness: The maximum thickness of each shape in pixels (default is 5).</li>
<ul> Feel free to experiment with these parameters to create your own unique rangoli images!
