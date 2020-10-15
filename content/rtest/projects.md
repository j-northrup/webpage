+++
# A Demo section created with the Blank widget.
# Any elements can be added in the body: https://sourcethemes.com/academic/docs/writing-markdown-latex/
# Add more sections by duplicating this file and customizing to your requirements.

widget = "blank"  # See https://sourcethemes.com/academic/docs/page-builder/
headless = true  # This file represents a page section.
active = true  # Activate this widget? true/false
weight = 15  # Order that this section will appear.

title = ""
subtitle = "We work on a broad range of species and topics, ranging across numerous sub-disciplines in ecology and biology. Much of this work is focused on understanding the causes and consequences of animal movement and space-use, but we have projects focused on population ecology, genomics and numerous questions relevant to species conservation and management. Click on the project links to learn more, or filter by topic. "



[design]
  # Choose how many columns the section has. Valid values: 1 or 2.
  columns = "2"

[design.background]
  # Apply a background color, gradient, or image.
  #   Uncomment (by removing `#`) an option to apply it.
  #   Choose a light or dark text color by setting `text_color_light`.
  #   Any HTML color name or Hex value is valid.

  # Background color.
  # color = "navy"
  
  # Background gradient.
  # gradient_start = "DeepSkyBlue"
  # gradient_end = "SkyBlue"
  
  # Background image.
 # image = "headers/bubbles-wide.jpg"  # Name of image in `static/img/`.
 # image_darken = 0.6  # Darken the image? Range 0-1 where 0 is transparent and 1 is opaque.

  # Text color (true=light or false=dark).
  text_color_light = false

[design.spacing]
  # Customize the section spacing. Order is top, right, bottom, left.
  padding = ["20px", "0", "20px", "0"]

[advanced]
 # Custom CSS. 
 css_style = ""
 
 # CSS class.
 css_class = ""

[[gallery_item]]
album = "gallery"
image= "pbear.JPG"
caption="Southern Hudson Bay polar bears"

[[gallery_item]]
album = "gallery"
image= "bbear.JPG"
caption="Black bear population ecology in Ontario"

[[gallery_item]]
album = "gallery"
image= "drillrig.jpg"
caption="Interaction among drivers of global change"

[[gallery_item]]
album = "gallery"
image= "muledeer.JPG"
caption="Mule deer and natural gas development in the Piceance Basin, Colorado"


+++

{{< gallery >}}