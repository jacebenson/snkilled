+++
# A Demo section created with the Blank widget.
# Any elements can be added in the body: https://sourcethemes.com/academic/docs/writing-markdown-latex/
# Add more sections by duplicating this file and customizing to your requirements.

widget = "blank"  # See https://sourcethemes.com/academic/docs/page-builder/
headless = true  # This file represents a page section.
active = false  # Activate this widget? true/false
weight = 30  # Order that this section will appear.

title = "Install"
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

You only need to take two steps to install this.

1.  In Studio, [import application from Github](https://docs.servicenow.com/bundle/newyork-application-development/page/build/applications/task/t_ImportAppFromSourceControl.html).\
  `https://github.com/jacebenson/atf.git`
1.  Due the nature of self contained test, this application requires the ability to Create, Modify, and Delete groups.\
  However Scoped applications do not have this access normally, to enable this update the Group Table by going here: `/sys_db_object.do?sysparm_query=name=sys_user_group`
  - Under Application Access
      - Check "Can Create"
      - Check "Can Update"
      - Check "Can Delete"
      - Save