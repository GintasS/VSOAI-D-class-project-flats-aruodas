<div align="center">
  <h2>Vilnius School of AI - D class final project - Aruodas.lt flats listings</h2>
</div>

## Jump to...

  - [Intro](#intro)
  - [Features](#features)
  - [Libraries](#libraries)
  - [Column descriptions](#Columndescriptions)
  - [Media](#media)
  
## <a name="Intro"></a>Intro

<p>This is a final project for D class graduation, where I scraped <a href='https://www.aruodas.lt/' target='_blank'>aruodas.lt</a>, a lithuanian real estate website, for all available flat listings(ads).<br>Url for all flats: <a href='https://www.aruodas.lt/butai/' target='_blank'>https://www.aruodas.lt/butai/</a>.<br><br>
Scrap was conducted on <b>2019-08-24</b>.
</p>

## <a name="Features"></a>Features

<ul>
  <li>9687 rows</li>
  <li>27 columns(22 after cleaning)</li>
  <li>Data cleaning</li>
  <li>Charts</li>
  <li>Machine learning model:<br>
  <a href='https://en.wikipedia.org/wiki/K-nearest_neighbors_algorithm' target='_blank'>k-nearest neighbors</a> algorithm to predict       <b>Building Type</b>
  </li>
</ul>

## <a name="Libraries"></a>Libraries
<ul>
  <li>numpy</li>
  <li>pandas</li>
  <li>matplotlib</li>
  <li>seaborn</li>
  <li>folium</li>
  <li>scikit-learn</li>
</ul>

## <a name="Columndescriptions"></a>Column descriptions

<table>
  <tr>
    <th>Column name</th>
    <th>Description</th>
    <th>Example data</th>
  </tr>
  <tr><td>City</td><td>Content Cell</td><td>Vilnius</td></tr>
  <tr><td>County</td><td>Content Cell</td><td>Žirmūnai</td></tr>
  <tr><td>Street</td><td>Content Cell</td><td>Antakalnio g.</td></tr>
  <tr><td>HouseCount</td><td>Content Cell</td><td>https://www.aruodas.lt/</td></tr>
  <tr><td>Link</td><td>Content Cell</td><td>https://www.aruodas.lt/</td></tr>
  <tr><td>Price EUR</td><td>Content Cell</td><td>50000</td></tr>  
  <tr><td>Price per m2</td><td>Content Cell</td><td>5000</td></tr>
  <tr><td>Rooms</td><td>Content Cell</td><td>3</td></tr>  
  <tr><td>Area m2</td><td>Content Cell</td><td>45.10</td></tr>
  <tr><td>Floor</td><td>Content Cell</td><td>3</td></tr>  
  <tr><td>Total floors</td><td>Content Cell</td><td>5</td></tr>
  <tr><td>Flat number</td><td>Content Cell</td><td>5</td></tr>  
  <tr><td>House number</td><td>Content Cell</td><td>5A</td></tr>
  <tr><td>Year</td><td>Content Cell</td><td>1988</td></tr>
  <tr><td>Building type</td><td>Content Cell</td><td>Mūrinis</td></tr>
  <tr><td>Heating</td><td>Content Cell</td><td>Centrinis kolektorinis</td></tr>
  <tr><td>Installation type</td><td>Content Cell</td><td>Dalinė apdaila</td></tr>
  <tr><td>Specials</td><td>Content Cell</td><td>Nauja kanalizacija Nauja elektros instaliacija Uždaras kiemas Internetas Kabelinė televizija</td></tr>  
  <tr><td>Extra quarters</td><td>Content Cell</td><td>Balkonas</td></tr>
  <tr><td>Extra equipment</td><td>Content Cell</td><td>Plastikiniai vamzdžiai</td></tr>  
  <tr><td>Security</td><td>Content Cell</td><td>Šarvuotos durys Kodinė laiptinės spyna Videokameros</td></tr>
  <tr><td>Upload date</td><td>Content Cell</td><td>8/21/2019</td></tr>  
  <tr><td>Modify date</td><td>Content Cell</td><td>8/21/2019</td></tr>
  <tr><td>Memorized count</td><td>Content Cell</td><td>1</td></tr>   
  <tr><td>Views</td><td>Content Cell</td><td>345</td></tr>
  <tr><td>Telephone</td><td>Content Cell</td><td>37000000000</td></tr>
  <tr><td>Coordinates</td><td>Content Cell</td><td>54.000000 25.000000</td></tr>
 </table>
 
## <a name="Media"></a>Media

<a target="_blank" href="https://github.com/GintasS/VSOAI-D-class-project-FlatsAruodas/blob/master/charts/flat%20prices%20histogram.JPG">
  <img src="https://github.com/GintasS/VSOAI-D-class-project-FlatsAruodas/blob/master/charts/flat%20prices%20histogram.JPG" height="300" style="max-width:50%;"></img>
</a>
<blockquote>Flat price histograms.</blockquote>
<br>
<a target="_blank" href="https://github.com/GintasS/VSOAI-D-class-project-FlatsAruodas/blob/master/charts/flat%20uploads%20by%20date%20of%20week.JPG">
  <img src="https://github.com/GintasS/VSOAI-D-class-project-FlatsAruodas/blob/master/charts/flat%20uploads%20by%20date%20of%20week.JPG" height="300" style="max-width:50%;"></img>
</a>
<blockquote>Flats by day of week.</blockquote>
<br>
<a target="_blank" href="https://github.com/GintasS/VSOAI-D-class-project-FlatsAruodas/blob/master/charts/error%20rate%20k-value.JPG">
  <img src="https://github.com/GintasS/VSOAI-D-class-project-FlatsAruodas/blob/master/charts/error%20rate%20k-value.JPG" height="300" style="max-width:50%;"></img>
</a>
<blockquote>Error rate k value(for ML model).</blockquote>
<br>
<a target="_blank" href="https://github.com/GintasS/VSOAI-D-class-project-FlatsAruodas/blob/master/charts/flats%20by%20building%20type.JPG">
  <img src="https://github.com/GintasS/VSOAI-D-class-project-FlatsAruodas/blob/master/charts/flats%20by%20building%20type.JPG" height="300" style="max-width:50%;"></img>
</a>
<blockquote>Flats by building type.</blockquote>
<br>
<a target="_blank" href="https://github.com/GintasS/VSOAI-D-class-project-FlatsAruodas/blob/master/charts/old%20town%20districts%20in%20top-3%20biggest%20cities%20and%20their%20average%20flat%20prices.JPG">
  <img src="https://github.com/GintasS/VSOAI-D-class-project-FlatsAruodas/blob/master/charts/old%20town%20districts%20in%20top-3%20biggest%20cities%20and%20their%20average%20flat%20prices.JPG" height="300" style="max-width:50%;"></img>
</a>
<blockquote>Old town average flat prices in top-3 biggest cities/districts.</blockquote>
<br>
<a target="_blank" href="https://github.com/GintasS/VSOAI-D-class-project-FlatsAruodas/blob/master/charts/top-10%20cities%20and%20districts%20by%20flats.JPG">
  <img src="https://github.com/GintasS/VSOAI-D-class-project-FlatsAruodas/blob/master/charts/top-10%20cities%20and%20districts%20by%20flats.JPG" height="300" style="max-width:50%;"></img>
</a>
<blockquote>Top-10 cities and districts by flats.</blockquote>
<br>
<a target="_blank" href="https://github.com/GintasS/VSOAI-D-class-project-FlatsAruodas/blob/master/maps/flats%20map.gif">
  <img src="https://github.com/GintasS/VSOAI-D-class-project-FlatsAruodas/blob/master/maps/flats%20map.gif" height="400" style="max-width:50%;"></img>
</a>
<blockquote>Interactive flat map.</blockquote>
<br>
<a target="_blank" href="https://github.com/GintasS/VSOAI-D-class-project-FlatsAruodas/blob/master/maps/live%20map%20of%20flats%20listings%202019-08-18%20--%202019-08-24.gif">
  <img src="https://github.com/GintasS/VSOAI-D-class-project-FlatsAruodas/blob/master/maps/live%20map%20of%20flats%20listings%202019-08-18%20--%202019-08-24.gif" height="400" style="max-width:50%;"></img>
</a>
<blockquote>Interactive live flat map of flat listings in 2019-08-18 -- 2019-08-24.</blockquote>
<br>
<a target="_blank" href="https://github.com/GintasS/VSOAI-D-class-project-FlatsAruodas/blob/master/maps/ww2%20map.gif">
  <img src="https://github.com/GintasS/VSOAI-D-class-project-FlatsAruodas/blob/master/maps/ww2%20map.gif" height="400" style="max-width:50%;"></img>
</a>
<blockquote>Interactive flat map of flats built in WW2(1939-1945).</blockquote>


