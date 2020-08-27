+++
# Contact widget.
widget = "contact"  # See https://sourcethemes.com/academic/docs/page-builder/
headless = false  # This file represents a page section.
active = true  # Activate this widget? true/false
weight = 130  # Order that this section will appear.

title = "Contact"
subtitle = ""

# Automatically link email and phone?
autolink = true

# Email form provider
#   0: Disable email form
#   1: Netlify (requires that the site is hosted by Netlify)
#   2: formspree.io
email_form = 0

# Netlify form settings.
[netlify]
  captcha = false  # Enable CAPTCHA challenge to reduce spam?
+++

<div id="map" style="width:400px;height:400px;background:yellow"></div>
<script>
function myMap() {
    var uluru = {lat: 50.863656, lng: 4.675785};
    var map = new google.maps.Map(document.getElementById('map'), {
      zoom: 9,
      center: uluru
    });
    var marker = new google.maps.Marker({
      position: uluru,
      map: map
    });
}
</script>
<script src="https://maps.googleapis.com/maps/api/js?key=AIzaSyBhyvKEGsGmCI3fi7D12wLwbkglMpLSNaU&callback=myMap"></script>
