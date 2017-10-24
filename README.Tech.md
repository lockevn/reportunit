# ReportUnit
ReportUnit is a report generator for the test-runner family. It uses stock reports from NUnit, MSTest and Gallio and converts them into attractive HTML reports with dashboards.

This fork tweaks the TestSuite class model to provide more information for NUnit parser.

### Tech info
/Parser contains parsers, parse the XML to Model

/Model are Model for the Razor engine
Use Razor engine to render the HTML output
Razor engine compiles Model and .cshtml template into HTML output
/Resources/Templates are Razor templates

