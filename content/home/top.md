+++
# Hero widget.
widget = "hero"  # See https://sourcethemes.com/academic/docs/page-builder/
headless = false  # This file represents a page section.
active = true  # Activate this widget? true/false
weight = 1  # Order that this section will appear.

title = "ServiceNow Killed"

# Hero image (optional). Enter filename of an image in the `static/img/` folder.
hero_media = "cemetery-51550_640.jpg"

[design.background]
  # Apply a background color, gradient, or image.
  #   Uncomment (by removing `#`) an option to apply it.
  #   Choose a light or dark text color by setting `text_color_light`.
  #   Any HTML color name or Hex value is valid.

  # Background color.
  # color = "navy"
  
  # Background gradient.
  gradient_start = "#4bb4e3"
  gradient_end = "#2b94c3"
  
  # Background image.
  # image = ""  # Name of image in `static/img/`.
  # image_darken = 0.6  # Darken the image? Range 0-1 where 0 is transparent and 1 is opaque.

  # Text color (true=light or false=dark).
  text_color_light = true

# Call to action links (optional).
#   Display link(s) by specifying a URL and label below. Icon is optional for `[cta]`.
#   Remove a link/note by deleting a cta/note block.
[cta]
  url = "https://github.com/jacebenson/snkilled/issues/new?assignees=&labels=&template=add-new-item-to-sn-killed.md&title="
  label = "Suggest an addition"
  icon_pack = "fas"
  icon = "person"
  
#[cta_alt]
#  url = "#learn-more"
#  label = "Learn more"

# Note. An optional note to show underneath the links.
[cta_note]
 label = '<a class="nav-link " href="/#contribute" data-target="#contribute"><span>Contribute</span></a>'
+++

**Showing features in their state of decay**

<span style="text-shadow: none;"><a class="github-button" href="https://github.com/jacebenson/snkilled" data-icon="octicon-star" data-size="large" data-show-count="true" aria-label="Star this on GitHub">Star</a><script async defer src="https://buttons.github.io/buttons.js"></script></span>

## What are these states?

State    | Descriptipn
-------- | -----------
Current  | It's the current offering and should still be used
Replaced | It's still available, but you **should** use the newer option
Dead     | It's been listed as Depreciated