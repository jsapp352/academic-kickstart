+++
# A Demo section created with the Blank widget.
# Any elements can be added in the body: https://sourcethemes.com/academic/docs/writing-markdown-latex/
# Add more sections by duplicating this file and customizing to your requirements.

widget = "blank"  # See https://sourcethemes.com/academic/docs/page-builder/
headless = true  # This file represents a page section.
active = true  # Activate this widget? true/false
weight = 22  # Order that this section will appear.

title = "Project Background"
subtitle = ""

[design]
  # Choose how many columns the section has. Valid values: 1 or 2.
  columns = "2"

[design.background]
  # Apply a background color, gradient, or image.
  #   Uncomment (by removing `#`) an option to apply it.
  #   Choose a light or dark text color by setting `text_color_light`.
  #   Any HTML color name or Hex value is valid.

  # Background color.
  # color = "white"
  
  # Background gradient.
  # gradient_start = "DarkGreen"
  # gradient_end = "ForestGreen"
  
  # Background image.
  # image = "tacocat_touchscreen_demo.jpeg"  # Name of image in `static/img/`.
  # image_darken = 1.0  # Darken the image? Range 0-1 where 0 is transparent and 1 is opaque.
  # image_size = "cover"  #  Options are `cover` (default), `contain`, or `actual` size.
  # image_position = "center"  # Options include `left`, `center` (default), or `right`.
  # image_parallax = true  # Use a fun parallax-like fixed background effect? true/false
  
  # Text color (true=light or false=dark).
  # text_color_light = false

[design.spacing]
  # Customize the section spacing. Order is top, right, bottom, left.
  padding = ["20px", "0", "20px", "0"]

[advanced]
 # Custom CSS. 
 css_style = ""
 
 # CSS class.
 css_class = ""
+++

## Problem

- Many useful software-based neural network models are too large and slow to be implemented on mobile devices. Hardware-based neural network accelerators may soon allow these models to run on phones and tablets without sending data to the cloud.

- We were interested in building an experimental hardware-based neural network, but all of the research designs that we found used hardware that is not yet commercially available, such as memristor crossbar arrays.

## Solution

- We wondered if it would be possible to build a demonstration-sized network that would be able to classify datasets containing a small number of different characters.

 - After investigating the project's feasibility, we set out to design a demonstration-sized network that can recognize a set of three handwritten characters using commonly-available discrete components. 
