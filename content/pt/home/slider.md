+++
# Slider widget.
widget = "slider"  # See  https://sourcethemes.com/academic/docs/page-builder/
headless = true  # This file represents a page section.
active = true  # Activate this widget? true/false
weight = 20  # Order that this section will appear.

# Slide interval.
# Use `false` to disable animation or enter a time in ms, e.g. `5000` (5s).
interval = false

# Slide height (optional).
# E.g. `500px` for 500 pixels or `calc(100vh - 70px)` for full screen.
height = "325px"

# Slides.
# Duplicate an `[[item]]` block to add more slides.
[[item]]
  title = ""
  content = "Eu colaborei com manuscritos publicados em revistas científicas internacionais de alta qualidade."
  align = "center"  # Choose `center`, `left`, or `right`.

  # Overlay a color or image (optional).
  #   Deactivate an option by commenting out the line, prefixing it with `#`.
  overlay_color = "#404040"  # An HTML color value.
  overlay_img = "picking.jpg"  # Image path relative to your `static/img/` folder.
  overlay_filter = 0.4  # Darken the image. Value in range 0-1.

  # Call to action button (optional).
  #   Activate the button by specifying a URL and button label below.
  #   Deactivate by commenting out parameters, prefixing lines with `#`.
  cta_label = "Veja as minhas publicaçōes"
  cta_url = "publication"
  cta_icon_pack = "fas"
  cta_icon = "newspaper"

[[item]]
  title = ""
  content = "Tenho trabalhado no Brasil e nos Estados Unidos para reduzir o impacto das plantas daninhas nos ecossistemas."
  align = "left"

  overlay_color = "#404040"  # An HTML color value.
  overlay_img = "farming.png"  # Image path relative to your `static/img/` folder.
  overlay_filter = 0.4  # Darken the image. Value in range 0-1.
  
  cta_label = "Veja o meu CV"
  cta_url = "/resume/CV.pdf"
  cta_icon_pack = "fas"
  cta_icon = "file"

[[item]]
  title = ""
  content = "Eu sou um entusiasmado cientista de dados"
  align = "right"

  overlay_color = "#404040"  # An HTML color value.
  overlay_img = "landscape.jpg"  # Image path relative to your `static/img/` folder.
  overlay_filter = 0.4  # Darken the image. Value in range 0-1.

  cta_label = "Veja os meus projetos"
  cta_url = "projects"
  cta_icon_pack = "fas"
  cta_icon = "project-diagram"
  

+++
