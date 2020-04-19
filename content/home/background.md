+++
# A Demo section created with the Blank widget.
# Any elements can be added in the body: https://sourcethemes.com/academic/docs/writing-markdown-latex/
# Add more sections by duplicating this file and customizing to your requirements.

widget = "blank"  # See https://sourcethemes.com/academic/docs/page-builder/
headless = true  # This file represents a page section.
active = true  # Activate this widget? true/false
weight = 32  # Order that this section will appear.

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

Modern neural networks are capable of helping us in many ways, especially through sound and image recognition. However, many software-based neural network models are too large and slow to be implemented on mobile devices. Hardware-based neural networks may allow mobile devices to perform complex recognition tasks without sending data out to the cloud.

Upon reviewing the current research in hardware-based neural network design, we found that most designs use custom-fabricated devices based on emerging nonvolatile memory devices, such as memristors, in order to build networks that are complex enough to recognize 10+ image types in a given dataset. We were interested in building an experimental hardware-based neural network, but we found that memristor crossbar arrays were not commercially available.

## Solution

Building a hardware-based neural network capable of recognizing 10 or more handwritten characters would be impractical without the use of custom-fabricated microdevices, but we wondered if it would be possible to build a demonstration-sized network that would be able to recognize a smaller number of character types in each dataset.

 After investigating the project's feasibility through additional literature reviews, system-level simulations, and individual physical component tests, we set out to design a demonstration-sized network that can recognize a set of 3 handwritten characters using commonly-available discrete components. 
