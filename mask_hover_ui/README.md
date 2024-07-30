# Mask Hovering

This SDK offers a comprehensive guide for implementing advanced mask object removal techniques, introducing key elements such as:
Extracting segmented object masks when invoking the ‘objects/mask_generator’ API.
Utilizing the canvas to display segmented object masks on the image via hover interaction.
Demonstrating how to select a specific mask by clicking on it and employing it to trigger the object removal API.

#### To test the SDK, follow these steps:
1. Clone the project.
2. Open the ```mask_hover_ui/template.html``` file in your browser, preferably Chrome.
3. Hover over the image, and click on any mask to observe the associated ```mask_id```, which can be used to invoke the object removal API.

#
![manual_brush.png](..%2Fdemo%2Fmask_hovering.png)
