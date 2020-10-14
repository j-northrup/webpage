+++
# A Projects section created with the Portfolio widget.
widget = "portfolio"  # See https://sourcethemes.com/academic/docs/page-builder/
headless = true  # This file represents a page section.
active = true  # Activate this widget? true/false
weight = 65  # Order that this section will appear.

title = "Research"
subtitle = "We work on a broad range of species and topics, ranging across numerous sub-disciplines in ecology and biology. Much of this work is focused on understanding the causes and consequences of animal movement and space-use, but we have projects focused on population ecology, genomics and numerous questions relevant to species conservation and management. Click on the project links to learn more, or filter by topic. "

[content]
  # Page type to display. E.g. project.
  page_type = "project"
  
  # Filter toolbar (optional).
  # Add or remove as many filters (`[[content.filter_button]]` instances) as you like.
  # To show all items, set `tag` to "*".
  # To filter by a specific tag, set `tag` to an existing tag name.
  # To remove toolbar, delete/comment all instances of `[[content.filter_button]]` below.
  
  # Default filter index (e.g. 0 corresponds to the first `[[filter_button]]` instance below).
  filter_default = 0

  [[content.filter_button]]
    name = "All"
    tag = "*"
  
  [[content.filter_button]]
    name = "Movement ecology"
    tag = "Movement ecology"
	
  [[content.filter_button]]
    name = "Population ecology"
    tag = "Population ecology"
	
  [[content.filter_button]]
    name = "Land-use change"
    tag = "Land-use change"
	
  [[content.filter_button]]
    name = "Hierarchical models"
    tag = "Hierarchical models"
	
  [[content.filter_button]]
    name = "Climate change"
    tag = "Climate change"
	
  [[content.filter_button]]
    name = "Large mammals"
    tag = "Large mammals"
	
  [[content.filter_button]]
    name = "Conservation biology"
    tag = "Conservation biology"
	
  [[content.filter_button]]
    name = "Combining genomics and ecology"
    tag = "Combining genomics and ecology"
	
[design]
  # Choose how many columns the section has. Valid values: 1 or 2.
  columns = "2"

  # Toggle between the various page layout types.
  #   1 = List
  #   3 = Card
  #   5 = Showcase
  view = 3

  # For Showcase view, flip alternate rows?
  flip_alt_rows = false

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
  # image = "background.jpg"  # Name of image in `static/img/`.
  # image_darken = 0.6  # Darken the image? Range 0-1 where 0 is transparent and 1 is opaque.

  # Text color (true=light or false=dark).
  # text_color_light = true  
  
[advanced]
 # Custom CSS. 
 css_style = ""
 
 # CSS class.
 css_class = ""
+++

