---
layout: page
title: Mapping
permalink: /Mapping/
feature-img: ""
---


<div class="toc">
  

  <ul class="listContent">
    <li><a href="#hwgh">How we got here</a></li>
    <li> <a href="#pim">Problems in mapping</a></li>
    <li><a href="#wdtfl">Where does the future lead</a></li>
    <li><a href="#eac">Examples and code</a></li>
  </ul>
</div>

<h1 id="hwgh">How we got here</h1>

Early maps on parchment allowed travellers to mark their way, giving representation and rough relationships between distance and space.

The compass lead to a big step forward, as it meant there was a standard of measurement that anyone with a shiny compass could get a specific measurement of their positive relative to the North Pole. This lead to more accurate mapping.





<h1 id="pim">Problems in mapping</h1>

Early mapping had the problem of reproducibility. The printing press did not yet exist, so sharing a map, or recreating a map meant hand-copying, which is prone to mistakes, and created to big barrier to sharing geographic information.

When maps began becoming digital, it meant that using a shared geographic dataset, everyone could access the same mapping information.

While mobile browser engines are increasingly becoming more powerful and efficient, there is still a big benefit with respect to user experience to building a map feature into a native app versus a mobile web page.

Most phone operating systems allow developers to easily hook into the phone's core mapping API, and therefore give access to a user's phone location. 

Native apps allow for things to happen bases on a user's current location. Notifications or events can be triggered within a native app in the background, that can't yet be done on mobile because mobile browsers don't allow websites that background connections to a phone user's location. 



<h1 id="wdtfl">Where does the future lead</h1>

In 2005 Google made a big step forward in online mapping, when they released Google Maps. It was the first real test of using JavaScript in the browser to build a dynamic application.

As JavaScript the language has solidified its spot as a core piece of the web, many more mapping tools have been written in JavaScript, with many benefitting from mapping related data formats such as [GeoJSON](http://geojson.org/).

People are relying on maps as a core technology of mobile phones to find their way around the world, when travelling or commuting.

Currently mobile technology means performance is still better in native apps for phones, but the gap between mobile browsers and native applications for phones is closing as mobile browser engines because increasingly performant.


<h1 id="eac">Examples and code</h1>


**Mapbox**

![mapbox]( {{ site.baseurl }}/img/mapping/mapbox3.png)

Site: [mapbox.com](https://www.mapbox.com/)

Github: [github.com/mapbox](https://github.com/mapbox)

If you feel limited by Google Maps' styling, Mapbox's customizable maps are a great place to start playing. 

<div class="resources" markdown='1'>
* **Tutorials**
  * [Mapbox crashcourse](https://www.mapbox.com/tilemill/docs/crashcourse/introduction/)
  * [Mapbox studio tutorial](http://www.digital-geography.com/mapbox-studio-tutorial-1-installation-gui-first-map/#.VK45U2TF8m8)
* **Examples**
  * [What can you build with Mapbox](https://www.mapbox.com/showcase/)
</div>

**Leaflet**

![leaflet]( {{ site.baseurl }}/img/mapping/leaflet.png)

Site: [leafletjs.com](http://leafletjs.com/)

Github: [github.com/Leaflet](https://github.com/Leaflet/Leaflet)

Leaflet is a JavaScript library that makes mapping without advance GIS experience easy. Need to build interactions markers and create an interactive layer? Leaflet does that.

<div class="resources" markdown='1'>
* **Tutorials**
  * [Leaflet quick start](http://leafletjs.com/examples/quick-start.html)
  * [Lay group and layer control](http://leafletjs.com/examples/layers-control.html)
  * [Leaflet on mobile](http://leafletjs.com/examples/mobile.html)
  * [Setting up Leaflet with Basemap](http://giscollective.org/tutorials/web-mapping/leaflet-1/)
  * [Getting started with Leaflet](http://switch2osm.org/using-tiles/getting-started-with-leaflet/)
  * [Creating an interactive map with Leaflet and OpenStreetMap](http://asmaloney.com/2014/01/code/creating-an-interactive-map-with-leaflet-and-openstreetmap/)
  * [Ebook: Leaflet Tips and Tricks](https://leanpub.com/leaflet-tips-and-tricks/read)
* **Examples**
  * [Holiday lights 2012](http://www.spokesman.com/maps/holiday-lights-2012/)
  * [Where shooting occur in Chicago](http://crime.chicagotribune.com/chicago/shootings/)
</div>

**Tilemill**

![tilemill]( {{ site.baseurl }}/img/mapping/tilemill2.png)

Site: [mapbox.com/tilemill](https://www.mapbox.com/tilemill/)

Github: [github.com/mapbox/tilemill](https://github.com/mapbox/tilemill)

Tilemill is a layer that sits on top of Mapbox's mapping technology. It's goal is to make building beautiful interactive maps a really simple process whether you're a developer, journalist, or mapping hobbyist.


<div class="resources" markdown='1'>
* **Tutorials**
  * [The insanely illustrated guide to your first data-driven tilemill map](http://dataforradicals.com/the-insanely-illustrated-guide-to-your-first-tile-mill-map/)
  * [Video: Use TileMill with Open Data](http://vimeo.com/64578563)
  * [Cartography with TileMill](http://learnosm.org/en/map-design/tilemill/)
  * [Digital mapping with TileMill](http://www.lizhannaford.com/journalism/beginners-easy-guide-to-digital-mapping-with-tilemill/)
</div>

**QGIS**

![qgis]( {{ site.baseurl }}/img/mapping/qgis.png)

Site: [qgis.org](http://www.qgis.org/en/site/)

Github: [github.com/qgis](https://github.com/qgis/)

QGIS is an application that runs from your desktop that allows you to edit, view, and analyze GIS data.

<div class="resources" markdown='1'>

* **Tutorials**
	* [QGIS documentation](https://github.com/qgis/QGIS-Documentation)
	* [Havard QGIS 2.0 Workshop](http://maps.cga.harvard.edu/qgis/)
	* Video: [QGIS I - Introduction ](https://www.youtube.com/watch?v=59Oer-i6nVc)
	* Video: [QGIS II - Tools](https://www.youtube.com/watch?v=AsC_AEqtRRI)
	* Video: [QGIS III - Symbology](https://www.youtube.com/watch?v=duuYMufA-RU)
	* Video: [QGIS IV - Finding & Selecting Data](https://www.youtube.com/watch?v=ZbnCrfoWnNk)

</div>

<h1>Other Mapping links</h1>

[OpenStreetMap](http://www.openstreetmap.org/)
