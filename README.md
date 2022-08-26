# FMI's Open Data Resources

Contains additional recourses for FMI Open Data Portal.

For data visualization check out the
[MetOClient](https://github.com/fmidev/metoclient) JavaScript project.

## Folder Structure

* *[examples](./examples)* Code samples and tutorials etc.
* *[misc](./misc)* contains miscellaneous stuff like FMI Open Data logo etc.
* *[sld](./sld)* contains SLD [Styled Layer Descriptor](https://docs.geoserver.org/stable/en/user/styling/sld/index.html) style sheets which are used to visualize radar images
* *[symbols](./symbols)* Images to visualize weather with. Filenames match _WeatherSymbol3_ parameter values.

## What is different in this fork?

This fork is updated to be used with Python 3. It also has some extra features compared to the main repository:

* Supports query descriptions 
* Supports queries with place name

This fork uses [Beautiful Soup](https://www.crummy.com/software/BeautifulSoup/bs4/doc/) which can be installed with pip:

`
pip install beautifulsoup4
`