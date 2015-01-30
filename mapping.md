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
    <li><a href="#wdtfl">Where does the future lead?</a></li>
    <li><a href="#eac">Examples and Code</a></li>
  </ul>
</div>

<h1 id="hwgh">How we got here</h1>

Early maps on parchment allowed travellers to find their way, representing landmarks and indicating relationships between distance and space.

The compass lead to a big step forward, as it meant there was a standard of direction. The compass needle always pointed toward the North Pole, enabling travellers to orient themselves. This lead to more accurate mapping.


<h1 id="pim">Problems in mapping</h1>

Early mapping had the problem of reproducibility. Before the invention of the printing press, sharing a map meant hand-copying, which is slow and prone to mistakes. This was a big barrier to sharing geographic information.

The advent of the printing press allowed many copies of a map to be created relatively quickly, but updating the information on a map still involved creating new printing plates. It was quicker than hand copying, but still kept control of what was shown on maps in the hands of just a few people. Now many maps are digital, with the geographic dataset widely available to the public. Now everyone can access and use the same mapping information.

While mobile browser engines are becoming increasingly powerful and efficient, there is still a big benefit with respect to user experience to building a map feature into a native app rather than using a mobile web page.

Most phone operating systems allow developers to easily hook into the phone's core mapping API, and therefore give access to a user's phone location. 

Native apps allow for things to happen based on the user's current location. Notifications or events can be triggered in the background, within a native app, but this can't yet be done on a mobile web page because mobile browsers don't allow websites to make background connections to a phone user's location. 



<h1 id="wdtfl">Where does the future lead?</h1>

In 2005 Google made a big step forward in online mapping when they released Google Maps. It was the first real test of using the language JavaScript in the browser to build a dynamic application.

As JavaScript has solidified its position as a core piece of the web, many more mapping tools have been written in JavaScript, many of which benefit from mapping-related data formats such as [GeoJSON](http://geojson.org/).

People increasingly rely on maps as a core technology of mobile phones to find their way around the world, when travelling or commuting.

Currently mobile technology means performance is still better in native apps than in mobile browsers for phones. However, the improved performance of mobile browser engines is starting to close the gap.


<h1 id="eac">Examples and Code</h1>


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

Leaflet is a JavaScript library that makes mapping easy even without advanced GIS experience. Need to build interactions markers and create an interactive layer? Leaflet does that.

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

Tilemill is a layer that sits on top of Mapbox's mapping technology. Its goal is to make the process of building beautiful interactive maps really simple, whether you're a developer, journalist, or mapping hobbyist.


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

QGIS is an application that runs from your desktop, allowing you to edit, view, and analyze GIS data.

<div class="resources" markdown='1'>

* **Tutorials**
	* [QGIS documentation](https://github.com/qgis/QGIS-Documentation)
	* [Havard QGIS 2.0 Workshop](http://maps.cga.harvard.edu/qgis/)
	* Video: [QGIS I - Introduction ](https://www.youtube.com/watch?v=59Oer-i6nVc)
	* Video: [QGIS II - Tools](https://www.youtube.com/watch?v=AsC_AEqtRRI)
	* Video: [QGIS III - Symbology](https://www.youtube.com/watch?v=duuYMufA-RU)
	* Video: [QGIS IV - Finding & Selecting Data](https://www.youtube.com/watch?v=ZbnCrfoWnNk)

</div>


**StoryMapJS**

![qgis]( {{ site.baseurl }}/img/mapping/storymap.png)

Site: [storymap.knightlab.com](http://storymap.knightlab.com/)

Github: [github.com/NUKnightLab/StoryMapJS](https://github.com/NUKnightLab/StoryMapJS)


<div class="resources" markdown='1'>
* **Tutorials**
	* [Setting up StoryMapJS on your own server](http://storymap.knightlab.com/advanced.html)
	* [StoryMap to take your readers on a journey](https://www.journalism.co.uk/skills/how-to-build-a-storymap-to-take-readers-on-a-journey/s7/a556486/)
		
* **Examples**
	* [ISIS carving a new country, W. Post](http://apps.washingtonpost.com/g/page/world/map-how-isis-is-carving-out-a-new-country/1095/)	
	* [Journey to nowhere, Al Jazeera](http://america.aljazeera.com/multimedia/2014/3/map-timeline-malaysiaairlinesflight370.html)	
	* [Life and death, CNBC](http://www.cnbc.com/id/101697417) 	
	* [Hockey, hip-hop, MinnPost](http://www.minnpost.com/stroll/2014/06/hockey-hip-hop-and-other-green-line-highlights)
</div>	
	
	
<h1>Other Mapping links</h1>

[OpenStreetMap](http://www.openstreetmap.org/)
