+++
# A Demo section created with the Blank widget.
# Any elements can be added in the body: https://sourcethemes.com/academic/docs/writing-markdown-latex/
# Add more sections by duplicating this file and customizing to your requirements.

widget = "blank"  # See https://sourcethemes.com/academic/docs/page-builder/
headless = true  # This file represents a page section.
active = true  # Activate this widget? true/false
weight = 12 # Order that this section will appear.

title = "List of the killed or nearly killed products"
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

<!--
State        | Descriptipn
------------ | -----------
Life Support | Has no updates & has replacement
Coma         | Has no updates & no replacement
Nearly Dead  | Not installable & has replacement
Dead         | Broken & not going to get fixed
-->
Thing                                | Life                   | State        | Notes 
------------------------------------ | ---------------------- | ------------ | ------
Help the Help Desk                   | 2004 - 2020 (16 years) | Dead         |
Enterprise Release Management        | 2017 - 2020 (4 years)  | Dead         |
Facilities Service Management        | 2008 - 2020 (12 years) | Dead         |
Workflow                             | 2008 - 2017 (9 years)  | Life Support |
Cms                                  | 2009 - 2016 (7 years)  | Dead         |
Homepages                            | 2004 - 2013 (9 years)  | Life Support |
IT SAM                               | 2007 - 2018 (9 years)  | Dead         |
Listv3                               | 2016 - 2018 (2 years)  | Dead         |
JSON                                 | 2004 - 2013 (9 years)  | Dead         |
JSONv2                               | 2013 - 2015 (2 years)  | Coma         |
Orchestration - Node Based Licensing | 2010 - 2018 (8 years)  | Dead         |
[Processors]                         | 2004 - 2018 (14 year)  | Life Support | While legacy, custom processors will continue to be supported, creating new custom processors has been deprecated. Instead, please use the Scripted REST APIs.

[Processors]: https://docs.servicenow.com/bundle/newyork-application-development/page/script/processors/concept/c_Processors.html