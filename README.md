# HTML5 microdata testing tool #

To see this tool in action, visit [http://krofdrakula.github.com/microdata-tool](http://krofdrakula.github.com/microdata-tool).

This tool was written to aid in debugging and browsing HTML5 microdata.

To use this tool, simply include the script anywere after the inclusion
of the [jQuery](http://jquery.com) library. When you view the page, a list
will appear in the bottom left listing all the microdata objects detected
on the page.

In addition, you need to provide the schemas to validate against; some are already
implemented in `schemas.js` which is to be included immediately after the
`jquery.microdata.js` script. To add your own, you can use the
`$.microdata.addDefinition(url, fields)` function as used in `schemas.js`.

This tool is a work-in-progress and still doesn't adhere to the full specs (yet).
Plans to support the full microdata spec + data vocabulary validation are on
the drawing board. ;)