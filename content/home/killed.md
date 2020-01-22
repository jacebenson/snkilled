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
Alive        | 
Life Support | Has no updates & has replacement
Comatose     | Has no updates & no replacement
Dead         | Not installable & has replacement
Dead & Gone  | Broken & not going to get fixed
-->
Thing                                | Born | Died | State        | Notes 
------------------------------------ | ---- | ---- | ------------ | ------
Help the Help Desk                   | 2004 | 2020 | Dead & Gone  | In Orlando this is no longer available to be installed for new instances.
Enterprise Release Management        | 2017 | 2020 | Dead         | In Orlando this is no longer available to be installed for new instances.
Facilities Service Management        | 2008 | 2020 | Dead         | In Orlando this is no longer available to be installed for new instances.
Workflow                             | 2008 | 2017 | Life Support |
Content Management System (CMS)      | 2009 | 2016 | Dead         | In Orlando this is no longer available to be installed for new instances.
Homepages                            | 2004 | 2013 | Life Support |
IT SAM                               | 2007 | 2018 | Life Support |
Listv3                               | 2016 | 2018 | Dead         |
JSON Processor                       | 2004 | 2013 | Dead         |
JSONv2 Processor                     | 2013 | 2015 | Comatose     |
Orchestration - Node Based Licensing | 2010 | 2018 | Dead         |
[Processors]                         | 2004 | 2018 | Life Support | While legacy, custom processors will continue to be supported, creating new custom processors has been deprecated. Instead, please use the Scripted REST APIs.
[Application Creator]                | 2015 | 2019 | Dead         | There is no migration path from the legacy application creator to Guided Application Creator. You can add a property to force legacy application creator to open instead of Guided Application Creator. For more information, see [Activate the legacy application creator]. 
[Execution Plans]                    | 2002 | 2008 | Life Support | This is really a legacy feature that is still around and I'm sure some people use it, but I can't imagine it has any support.  Was replaced with Workflow, and then again with Flow Designer.
[GS SQL]                             | 2002 | 2015 | Dead         | When truncating table, gs.sql orphans records and causes data corruption. That is the main reason it was dangerous.

[GS SQL]: https://www.servicenowelite.com/blog/2014/2/1/glidesystem-sql
[Execution Plans]: https://docs.servicenow.com/bundle/madrid-it-service-management/page/product/service-catalog-management/concept/c_ExecutionPlans.html
[Processors]: https://docs.servicenow.com/bundle/newyork-application-development/page/script/processors/concept/c_Processors.html
[Application Creator]: https://docs.servicenow.com/bundle/newyork-application-development/page/build/applications/concept/c_ApplicationCreationOptions.html
[Activate the legacy application creator]: https://docs.servicenow.com/bundle/newyork-application-development/page/build/applications/task/activate-legacy-app-creator.html