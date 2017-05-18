World Clock & Weather
=====================

Features
--------

* Show local time and weather conditions in more than 4000 places.
* Add your own places: Add a place in the same time zone and change its name and coordinates to your desired location to show the actual weather condition there!
* A compact clock widget, displaying the local time in your favorite locations.
* A widget showing the time and weather, which is re-sizable to show multiple locations on the home screen.
* Simple and clean UI
* Customizable widget colors (including transparent background)

The Internet connectivity permission is **only** used to retrieve current weather conditions.

Building
--------

AndroidStudio File - 'Import Project' and build

OpenWeatherMap API key
######################

Using the OpenWeatherMap API requires an API key. A default key is stored in the file ``./worldclockwidget/default_owm_api_key``. It can be overwritten by setting the Gradle project property ``owmApiKey``.

Libraries
---------

The app uses and includes the following libraries:

* `ColorPickerPreference <https://github.com/attenzione/android-ColorPickerPreference>`_
* `google-gson <https://code.google.com/p/google-gson/>`_
* `joda-time-android <https://github.com/dlew/joda-time-android>`_

Acknowledgements
----------------

* Special thanks to `vyick <http://vyick.wordpress.com/>`_ for beta testing and feature suggestions!
* Weather data is provided by `Open Weather Map <http://openweathermap.org/>`_.
* The weather icons are based on `Meteocons <http://www.alessioatzeni.com/meteocons/>`_ from Alessio Atzeni.
* Time zone and geographical data is provided by `GeoNames <http://www.geonames.org/>`_.

Screenshots
-----------

`1-Main.png   <https://github.com/swell-pixel/worldclockwidget/blob/f6c6a0997816ab59f7d7bda1e97b80ee873cca26/1-Main.png>`_
`2-Widget.png <https://github.com/swell-pixel/worldclockwidget/blob/f6c6a0997816ab59f7d7bda1e97b80ee873cca26/2-Widget.png>`_
`3-Add.png    <https://github.com/swell-pixel/worldclockwidget/blob/f6c6a0997816ab59f7d7bda1e97b80ee873cca26/3-Add.png>`_
`4-Select.png <https://github.com/swell-pixel/worldclockwidget/blob/f6c6a0997816ab59f7d7bda1e97b80ee873cca26/4-Select.png>`_
`5-Edit.png   <https://github.com/swell-pixel/worldclockwidget/blob/f6c6a0997816ab59f7d7bda1e97b80ee873cca26/5-Edit.png>`_
