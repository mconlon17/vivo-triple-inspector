vivo-triple-inspector
=====================

Inspect VIVO triples related to a specified VIVO uri.

Simply open `inspector.html` in a web browser.

It presents a form to a user where the user can type in a VIVO URI. After
submitting the form, it creates a SPARQL query to return the triples that have
the specified URI as the subject. Display the triples using D3.js in three
columns:

    1. Show the predicate as a link to the predicate definition
    2. Show a second column which contains a "V" if the object is a resource
    and can be viewed in VIVO. The V is a link to display the object in VIVO.
    If the object is a literal, the second column is blank.
    3. Show a third column containing the object.  Show the literal value or
    show a link to an inspector-request for the the object.

# Styles

Styling is embedded within `inspector.html`.

# D3

`inspector.html` uses [D3.js](http://d3js.org) to display results. D3 is a
powerful Javascript library for data driven documents.

# License

    author       = "Michael Conlon"
    copyright    = "Copyright 2013, University of Florida"
    license      = "BSD 3-Clause license"
    version      = "01.0"

