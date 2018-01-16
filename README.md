# chrome-crash-test-case

Loading `Kibana.html` in Chrome with hardware acceleration turned on and a dedicated graphics card will cause the tab to freeze up.

One fix for this seems to be optimzing the SVG code in `Kibana_files/kibana.svg`. To test this, change to the `optimizesvg` branch of this repo.

Is seems the particular SVG files in this repo uncover some illusive flaw in Chrome.
