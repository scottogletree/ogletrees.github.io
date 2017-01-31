# Climate Plot for Clemson

Recently I can across a tutorial that sought to recreate Edward Tufte's climate plot for Dayton, OH. It was by Brad Boehnke and can be found [here](https://rpubs.com/bradleyboehmke/weather_graphic).

As I am always looking for a way to build up my R skills, I decided to try Brad's script for my local weather station. The Clemson area weather station is at a small airport, and it seems that they have data back to 1930 (nice!). I was able to figure out the [weatherunderground](weatherunderground.com) API and return csv output.

On inspection there are a few years missing in the 1990's, but with a 85 year timespan I ended up with 30122 records.
