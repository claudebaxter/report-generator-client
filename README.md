# CityBucket Report Generator  

View an example of a generated report using the ''?report=x'
query like this:
https://claudebaxter.github.io/report-generator-client/view.html?report=transportation

Git clone this repository. From it's root directory, run
`python -m http.server`. You should then be able to view
the page at http://localhost:8000/view.html

For demo purposes, we have transportation and communication
reports available. The default view shows the Communication
Report. If you wish to see the Transportation report, add the
`?report=transportation` query parameter to the URL, i.e. go
to http://localhost:8000/view.html?report=transportation.
