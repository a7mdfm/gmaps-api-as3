<h2>Google Maps API v3 for AS3</h2>


The GoogleMaps API for ActionScript 3.0 was deprecated in August of 2011 "forcing" developers to use different methods for integrating maps in mobile and desktop application projects. One solution for mobile applications is integrate Native Maps in Android and IOS, however create Native Extensions for AS3 is somewhat cumbersome and takes a lot of development time. The other method is load in the class "StageWebView" a HTML5 map hosted on our servers, using the guidelines given by Google for using their maps. The following AS3 library takes this approach and extends it to implement an efficient solution to load GoogleMaps in Mobile or Desktop projects using ActionScript 3.0.

<strong>BEFORE STARTED</strong>

1.- The examples are developed using Flash Professional CS6, Adobe AIR 3.2 and FlashDevelop 4.

2.- The library works 100% for ActionScript 3.0 for Adobe AIR (apps Mobile), should be usable for Flash Professional CS5.5, Flash Builder 4.5.1, Flash Develop and any other development IDE ActionScript 3.0. But it has only been tested in Flash Professional CS6 and FlashDevelop.

3.- For any questions, or if you find a bug, or want to contribute to the realization of this library, please send an email to <a href='mailto://pcornejoas3@gmail.com'>pcornejoas3@gmail.com</a>.

4.- The library has been developed 100% by Patricio Cornejo A. and neither Google nor any member or the employer has participated in the realization of this library.

5.- This library is 100% FREE.

<strong>GETTING STARTED</strong>

1.- Download the library: <strong>Google Maps v3 for AS3 - BETA 2.0</strong>

2.- Download the examples for ANDROID: <strong> Example BETA 2.0</strong>

In the<strong> BETA 2.0</strong> we include this Classes:

<strong>Base Package</strong>
<ul>
<blockquote><li><em>Map.as</em> / Create a google map.</li>
<li><em>MapOptions.as</em> / Personalize and edit a map.</li>
<li><em>MapType.as</em> / Define a map type.</li>
<li><em>LatLng.as</em> / Creates a LatLng object representing a geographic point</li>
<li><em>LatLngBounds.as</em> / Constructs a rectangle from the points at its south-west and north-east corners.</li>
</ul>
<strong>controls Package</strong>
<ul>
<li><em>ControlPosition.as</em> / Identifiers used to specify the placement of controls on the map.</li>
<li><em>MapTypeControlOptions.as</em> / Options for the rendering of the map type control.</li>
<li><em>OverviewMapControlOptions.as</em> / Options for the rendering of the Overview Map control.</li>
<li><em>PanControlOptions.as</em> / Options for the rendering of the pan control.</li>
<li><em>RotateControlOptions.as</em> / Options for the rendering of the rotate control.</li>
<li><em>ScaleControlOptions.as</em> / Options for the rendering of the scale control.</li>
<li><em>StreetViewControlOptions.as</em> / Options for the rendering of the Street View pegman control on the map.</li>
<li><em>ZoomControlOptions.as</em> / Options for the rendering of the zoom control.</li>
</ul>
<strong>events Package</strong>
<ul>
<li><em>MapsEvents.as</em> / Events for the Google Map</li>
<li><em>MarkerEvents.as</em> / Events for the Markers object</li>
</ul>
<strong>overlays Package</strong>
<ul>
<li><em>InfoWindow.as</em> / An overlay that looks like a bubble and is often connected to a marker.</li>
<li><em>InfoWindowOptions.as</em> / Options to the InfoWindow Object</li>
<li><em>Marker.as</em> / Creates a marker with the options specified.</li>
<li><em>MarkerOptions.as</em> / Options to the Marker Object</li>
<li><em>Polyline.as</em> / A polyline is a linear overlay of connected line segments on the map.</li>
<li><em>PolylineOptions.as</em> / Options to the Polyline Object</li>
</ul>
<strong>services Package</strong>
<ul>
<li><em>DirectionsLeg.as</em> / A single leg consisting of a set of steps in a DirectionsResult.</li>
<li><em>DirectionsRenderer.as</em> / Renders directions retrieved in the form of a DirectionsResult object retrieved from the DirectionsService.</li>
<li><em>DirectionsRendererOptions.as</em> / This object defines the properties that can be set on a DirectionsRenderer object.</li>
<li><em>DirectionsRequest.as</em> / A directions query to be sent to the DirectionsService.</li>
<li><em>DirectionsResult.as</em> / The directions response retrieved from the directions server.</li>
<li><em>DirectionsRoute.as</em> / A single route containing a set of legs in a DirectionsResult.</li>
<li><em>DirectionsService.as</em> / A service for computing directions between two or more places.</li>
<li><em>DirectionsStatus.as</em> / The status returned by the DirectionsService on the completion of a call to route()</li>
<li><em>DirectionsStep.as</em> / A single DirectionsStep in a DirectionsResult.</li>
<li><em>DirectionsWaypoint.as</em> / A DirectionsWaypoint represents a location between origin and destination through which the trip should be routed.</li>
<li><em>Distance.as</em> / A representation of distance as a numeric value and a display string.</li>
<li><em>Duration.as</em> / A representation of duration as a numeric value and a display string.</li>
<li><em>Geocoder.as</em> / A service for converting between an address and a LatLng.</li>
<li><em>GeocoderAddressComponent.as</em> / A single address component within a GeocoderResult. A full address may consist of multiple address components.</li>
<li><em>GeocoderGeometry.as</em> / Geometry information about this GeocoderResult</li>
<li><em>GeocoderLocationType.as</em> / Describes the type of location returned from a geocode.</li>
<li><em>GeocoderRequest.as</em> / The specification for a geocoding request to be sent to the Geocoder.</li>
<li><em>GeocoderResult.as</em> / A single geocoder result retrieved from the geocode server</li>
<li><em>GeocoderStatus.as</em> / The status returned by the Geocoder on the completion of a call to geocode().</li>
<li><em>TravelMode.as</em> / The valid travel modes that can be specified in a DirectionsRequest as well as the travel modes returned in a DirectionsStep.</li>
<li><em>UnitSystem.as</em> / The valid unit systems that can be specified in a DirectionsRequest.</li>
</ul>