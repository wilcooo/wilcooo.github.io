# wilcooo.github.io
# TagPro Player Map

This is a proof-of-concept viewer for the TagPro Player Map.


Add a player via [this JotForm®](https://form.jotformeu.com/81933086201351) (linked to the Google Sheet)  

Database in [this Google® Sheet](https://docs.google.com/spreadsheets/d/1A0XlRE212GZ1holxOmjR5LBlQR7WBiovUBubFrKaEuk/edit?usp=sharing)

Access the database content in JSON via [this url](https://spreadsheets.google.com/feeds/list/1A0XlRE212GZ1holxOmjR5LBlQR7WBiovUBubFrKaEuk/3/public/values?alt=json) (I had to enable "publish on web" in the Google Sheet for this to work)

The map viewer on this github is a basic proof-of-concept using the "OpenLayers" api as a map provider (maps from OpenStreetMaps). Feel free to make your own better viewer, possibly with built-in pin-adder or something.

Alternative way of adding pins: send a POST request to [this url](https://script.google.com/macros/s/AKfycbwQgNJulIMS8j_qkfbwNxmqb-ALGI_3Q7zeCykbklwvBToZZbd-/exec). Example data:

    name: Ko
    lat: 69.696969
    long: 69.696969
    info: "This is a test"

(please don't POST false data, or I'll have to remove those lines manually in the Google Sheet)

Request edit access to the form or database sheet on reddit: /u/Wilcooo
