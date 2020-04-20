+++
# Hero widget.
widget = "hero"  # See https://sourcethemes.com/academic/docs/page-builder/
headless = true  # This file represents a page section.
active = true  # Activate this widget? true/false
weight = 10  # Order that this section will appear.

title = "TACOCAT:"

# Hero image (optional). Enter filename of an image in the `static/img/` folder.
hero_media = "taco_cat_art_with_fill_white_connectors.png"

[design.background]
  # Apply a background color, gradient, or image.
  #   Uncomment (by removing `#`) an option to apply it.
  #   Choose a light or dark text color by setting `text_color_light`.
  #   Any HTML color name or Hex value is valid.

  # Background color.
  color = "black"
  
  # Background gradient.
  # gradient_start = "#4bb4e3"
  # gradient_end = "#2b94c3"
  
  # Background image.
  image = "tacocat_motherboard.jpeg"  # Name of image in `static/img/`.
  image_darken = 0.6  # Darken the image? Range 0-1 where 0 is transparent and 1 is opaque.
  image_size = "contain"  #  Options are `cover` (default), `contain`, or `actual` size.
  image_position = "right"  # Options include `left`, `center` (default), or `right`.
  image_parallax = true  # Use a fun parallax-like fixed background effect? true/false
  
  # Text color (true=light or false=dark).
  text_color_light = true

# Call to action links (optional).
#   Display link(s) by specifying a URL and label below. Icon is optional for `[cta]`.
#   Remove a link/note by deleting a cta/note block.
[cta]
  url = "publication/conference-paper"
  label = "Whitepaper"
  
[cta_alt]
  url = "video/project-demo/"
  label = "Video Demonstration"
  icon_pack = "fas"
  icon = "View Documentation"

# Note. An optional note to show underneath the links.
[cta_note]
  label = "TACOCAT is a hardware-based machine learning accelerator built from ordinary components. Its neural network can be trained to recognize any set of three handwritten characters. When tested with five different three-letter subsets of the alphabet, prediction accuracy test results ranged from 86 to 97%"
+++

**Trainable Acceleration of Classification Operations via Commonly Available Technology**

<!-- <span style="text-shadow: none;"><a class="github-button" href="https://github.com/gcushen/hugo-academic" data-icon="octicon-star" data-size="large" data-show-count="true" aria-label="Star this on GitHub">Star</a><script async defer src="https://buttons.github.io/buttons.js"></script></span> -->
