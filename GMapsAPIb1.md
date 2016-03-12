# Introduction #

The GoogleMaps API for ActionScript 3.0 was deprecated in August of 2011 "forcing" developers to use different methods for integrating maps in mobile and desktop application projects. One solution for mobile applications is integrate Native Maps in Android and IOS, however create Native Extensions for AS3 is somewhat cumbersome and takes a lot of development time. The other method is load in the class "StageWebView" a HTML5 map hosted on our servers, using the guidelines given by Google for using their maps. The following AS3 library takes this approach and extends it to implement an efficient solution to load GoogleMaps in Mobile or Desktop projects using ActionScript 3.0.


# Details #

<b>BEFORE STARTED</b>

1.- The examples are developed using Flash Professional CS6, Adobe AIR 3.2 and FlashDevelop 4.

2.- The library works 100% for ActionScript 3.0, should be usable for Flash Professional CS5.5, Flash Builder 4.5.1, Flash Develop and any other development IDE ActionScript 3.0. But it has only been tested in Flash Professional CS6 and FlashDevelop.

3.- For any questions, or if you find a bug, or want to contribute to the realization of this library, please send an email to pcornejoas3@gmail.com.

4.- The library has been developed 100% by Patricio Cornejo A. and neither Google nor any member or the employer has participated in the realization of this library.

5.- This library is 100% FREE.

<b>GETTING STARTED</b>

To create a GoogleMap you must to instantiate the two primary classes:

- GoogleMaps: Manages the creation of the maps, you need at least two properties:

options: This property is required and identifies options Map. (GoogleMapsOptions).
viewport: This property is required and the position and size of the map. (Rectangle).

- GoogleMapsOptions: Maneja las opciones del Mapa. Esta Clase tiene estos métodos:

addProperty: Add properties to the map. These properties are described in the documentation of GoogleMaps https://developers.google.com/maps/documentation/javascript/reference?hl=es#MapOptions.

addControl: Ad Control to the Map. ZOOM, MAPTYPE, etc.

addControlOptions: Add Optiions to the Control Map.

returnProperty: Return the value of a property.