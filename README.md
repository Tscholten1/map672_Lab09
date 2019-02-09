# MAP 672 Lab 09 (Electric power generation by fuel source)

This map displays data points of 6900 electrical generating power plants across the US obtained from the {EIA's form923] <a href="/">http://www.eia.gov/electricity/data/eia923/</a>. The data contain the total generating capacity of each plant, as well its fuel source(s), encoded as one or more of the following string values: "Hydro", "Coal", "Natural Gas", "Petroleum", "Nuclear", "Wind", "Pumped Storage", "Solar", "Geothermal", "Biomass", "Wood", "Other", or "Other Fossil Gasses.
Key interactive features include pop-up boxes with details on the point location, check boxes to select map layers.

<p>Key features of this map include:
  <ul>
  <li>Replacing simple point location markers with an SVG circle and using the Leaflet class “CircleMarker” to better visualize numerous point locations in very close proximity.</li>
  <li>Shows power plant power generation using proportional symbol size to encode visually the amount of power produced from a particular fuel source.</li>
  <li>Allows the user to compare easily 3 distinct fuel sources (of any amount of generating capacity) by visually encoding the proportional symbols with distinct colors (i.e., make the symbol for each fuel source a different color).</li>
  <li>Provides the user with a layer control to toggle on and off the visibility of various power plant data layers.</li>
  <li>Styles the label text within the layer control to correspond with the color used to encode a specific power fuel source.</li>
  <li>When the user clicks on the map once, the map display will change to only show plants within 500 km of the click event.</li>
  <li>After the user clicks on the map to filter by distance and then clicks on any power plant currently visible, a popup will show specific information about the plant. this information should include the plant's name, its fuel source, and the distance from the plant to the click point.</li>
   </ul>
