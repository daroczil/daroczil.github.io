+++
fragment = "embed"
#disabled = true
date = "2017-10-07"
weight = 120
#background = "secondary"

#title = "Időpontfoglalás"
#subtitle = "Válasszon az alábbi naptárból egy (kékkel jelölt) szabad napot, majd időpontot, és kattintson a 'Confirm' gombra. Ezt követően adja meg nevét és email címét, továbbá a látogatás céljának rövid leírását (pl. veszettségoltás, fogkőeltávolítás vagy a panaszok leírás), majd kattintson a kék 'Schedule Event' gombra."
#title_align = "left" # Default is center, can be left, right or center

# Embed a form via an iframe
# Mailerlite is one example of a working provider.
# There are others such as convertkit.
# Only necessity is for them to use iframes.
#media = '<!-- Calendly inline widget begin --><div class="calendly-inline-widget" data-url="https://calendly.com/daroczidr/rendeles?hide_event_type_details=1" style="min-width:320px;height:660px;"></div><script type="text/javascript" src="https://assets.calendly.com/assets/external/widget.js"></script><!-- Calendly inline widget end -->'
#media = '<script src="https://embed.ycb.me" async="true" data-domain="daroczil" data-content="all"></script>'
media = '''<div style="width: 100%;" id="inline-embed-container">
    <!-- NeetoCal widget will be added here -->
  </div>
  <script>window.neetoCal = window.neetoCal || { embed: function(){(neetoCal.q=neetoCal.q||[]).push(arguments)} };</script>
  <script async
    src="https://cdn.neetocal.com/javascript/embed.js">
  </script>
  <script>
    neetoCal.embed({
      type: "inline",
      id: "4a39cef2-f292-4f9e-854f-75c8a550f562",
      organization: "daroczidr",
      elementSelector: "#inline-embed-container",
      styles: "height: 100%; width: 100%;", 
      queryParams: { "dynamicHeight": true, "lang": "hu" },
      slug: "vizsgalat",
      isSidebarAndCoverImgHidden: "false",
      shouldForwardQueryParams: "false"
    });
  </script>'''
# primary_color=00693E
responsive = false # prevent responsive behaviour
size = "100" # 25, 50, 75, 100 (percentage) - default: 75
padding="0"
+++
