+++
# A Demo section created with the Blank widget.
# Any elements can be added in the body: https://sourcethemes.com/academic/docs/writing-markdown-latex/
# Add more sections by duplicating this file and customizing to your requirements.

widget = "blank"  # See https://sourcethemes.com/academic/docs/page-builder/
headless = true  # This file represents a page section.
active = true  # Activate this widget? true/false
weight = 1 # Order that this section will appear.

title = "What is this?"
subtitle = ""

[design]
  # Choose how many columns the section has. Valid values: 1 or 2.
  columns = "1"

[design.background]
  # Apply a background color, gradient, or image.
  #   Uncomment (by removing `#`) an option to apply it.
  #   Choose a light or dark text color by setting `text_color_light`.
  #   Any HTML color name or Hex value is valid.

  # Background color.
  # color = "navy"
  
  # Background gradient.
  gradient_start = "DarkGreen"
  gradient_end = "ForestGreen"
  
  # Background image.
  # image = "image.jpg"  # Name of image in `static/img/`.
  # image_darken = 0.6  # Darken the image? Range 0-1 where 0 is transparent and 1 is opaque.

  # Text color (true=light or false=dark).
  text_color_light = true

[design.spacing]
  # Customize the section spacing. Order is top, right, bottom, left.
  padding = ["20px", "0", "20px", "0"]

[advanced]
 # Custom CSS. 
 css_style = ""
 
 # CSS class.
 css_class = ""
+++

This is a list to simply see on a feature by feature basis what is and is not "current" in ServiceNow.

# Why?

- I can't remember this stuff
- It's easier to search a list than it is to ask me or find it in the docs

# Can you elaborate on that?

Sure.  ServiceNow has a lot of offerings.  Over time the offerings change and sometimes merge/split/replace eachother.  They have to keep the old things because making a customer move off of some old tech is not a good thing to tell someone.  However, that leaves it up to the admins and developers to somehow know what is current.  The purpose of this is just to track the things and their last update or if they have been replaced by some other feature.  Some simple examples.  Execution Plans(sometimes called deliever plans) were used for a long time.  However Workflow was added in 2009.  You can still use workflow today.  Flow designer was introduced in 2017, it does things workflow did.  Should you still use workflow?  Well you can.  But new development is happening in Flow designer.