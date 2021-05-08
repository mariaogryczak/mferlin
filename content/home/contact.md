---
# An instance of the Contact widget.
# Documentation: https://sourcethemes.com/academic/docs/page-builder/
widget: contact

# This file represents a page section.
headless: true

# Order that this section appears on the page.
weight: 130

title: Contact
subtitle:

content:
email = "maria.ferlin@pg.edu.pl"
phone = "+48 790 55 77 58"

# Address
# For country_code, use the 2-letter ISO code (see https://en.wikipedia.org/wiki/ISO_3166-1_alpha-2 )
address = {street = "Gabriela Narutowicza 11/12,  ", city = "Gdańsk", region = "", postcode = "80-233", country = "Poland", country_code = "PL"}

# Geographic coordinates
# To get your coordinates, right-click on Google Maps and choose "What's here?". The coords will show up at the bottom.
coordinates = {latitude = "", longitude = ""}

# Directions for visitors to locate you.
directions = "Enter Building of Faculty of Electrical and Control Engineering and take the stairs to Office 207 on Floor 2"

# Office hours
# A list of your office hours. To remove, set to an empty list `[]`.
office_hours = ["Monday to Friday 09:00 to 15:00"]

# Enter an optional link for booking appointments (e.g. calendly.com).
appointment_url = ""

# Contact links
#   Set to `[]` to disable, or comment out unwanted lines with a hash `#`.
contact_links = [
  {icon = "linkedin", icon_pack = "fab", name = "Find me on LinkedIn", link = "https://www.linkedin.com/in/maria-ferlin-b86770162/"},
  {icon = "twitter", icon_pack = "fab", name = "DM Me", link = "https://twitter.com/Maria13801905"},
  ]
  # Automatically link email and phone or display as text?
  autolink: true
  
  # Email form provider
  form:
    provider: netlify
    formspree:
      id:
    netlify:
      # Enable CAPTCHA challenge to reduce spam?
      captcha: false
  
design:
  columns: '2'
---
