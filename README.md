# karma-ng-html2js-preprocessor:
This preprocessor converts HTML files into JS strings and generates Angular modules. These modules, when loaded, puts these HTML files into the $templateCache and therefore Angular won't try to fetch them from the server.

# Loaded jQuery instead of using jqLite
If you have tests that require more complex selection than jqLite affords. For instance, if you want to select an element by element name and attribute value.
