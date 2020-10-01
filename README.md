# HTML5
HTML5 basic-1

<!DOCTYPE html>
<html lang="sv">
	<head>
		<meta charset="UTF-8">
		<title>1.1. Grunderna i HTML5</title>
	</head>
<body>

<h2>Struktur:</h2>
<p>body är en element som innehåller de synas sidansinnhehåll.</p>
<p>head är en element som innehåller meta inforrmation om dokumentet.</p>
<p>title är en element som specificcera en title for dokumentet.</p>
<p>html är en grund element av en html sida.</p>
<hr>

<h2>Metainformation:</h2>

<p>author definerar av författare av sidan</p>

<p>description definerar en beskrivning av din webbsida</p>

<p>generator är ett erktyg som generarar meta taggar för en sida</p>

<p>keywords definerar nyccklerprd för sökmotorer</p>

<p>robots kan används om man vill hindra indeering och hindra att den följer länkarna på sidan.</p>

<p>http-equiv används för att uppdatera dokument varje 30 sekunder</p>
<hr>

<h2>Text:</h2>

<p>blockquote anger ett avsnitt som citeras från en annan källa</p>


<p>h1 uppvisas med följande standardvärdena<br>
h1 { <br>
    display: block;<br>
    font-size: 2em;<br>
    margin-top: 0.67em;<br>
    margin-bottom: 0.67em;<br>
    margin-left: 0;<br>
    margin-right: 0;<br>
    font-weight: bold;<br>
}<br></p>

<p>h2<br>
h2 { <br>
    display: block;<br>
    font-size: 1.5em;<br>
    margin-top: 0.83em;<br>
    margin-bottom: 0.83em;<br>
    margin-left: 0;<br>
    margin-right: 0;<br>
    font-weight: bold;<br>
}<br></p>

<p>h3<br>
h3 { <br>
    display: block;<br>
    font-size: 1.17em;<br>
    margin-top: 1em;<br>
    margin-bottom: 1em;<br>
    margin-left: 0;<br>
    margin-right: 0;<br>
    font-weight: bold;<br>
}<br></p>

<p>h4<br>
h4 { <br>
    display: block;<br>
    font-size: 1em;<br>
    margin-top: 1.33em;<br>
    margin-bottom: 1.33em;<br>
    margin-left: 0;<br>
    margin-right: 0;<br>
    font-weight: bold;<br>
}<br></p>

<p>h5<br>
h5 { <br>
    display: block;<br>
    font-size: .83em;<br>
    margin-top: 1.67em;<br>
    margin-bottom: 1.67em;<br>
    margin-left: 0;<br>
    margin-right: 0;<br>
    font-weight: bold;<br>
}<br></p>

<p>h6<br>
h6 { <br>
    display: block;<br>
    font-size: 1em;<br>
    margin-top: 1.33em;<br>
    margin-bottom: 1.33em;<br>
    margin-left: 0;<br>
    margin-right: 0;<br>
    font-weight: bold;<br>
}<br></p>

<p>p tag definera en paragraph</p>

<pre>
Text i ett preelement
visas i en fast bredd
typsnitt, och det bevaras
både utrymmen och
radbrytningar
</pre>

<p>Taggen <span style="color:blue;font-weight:bold"> span </span>ger ett sätt att lägga till en krok i en del av en text eller en del av ett dokument.</p>
<hr>

<h2>Hypertext:</h2>
<p>a-taggen definierar en hyperlänk som används för att länka från en sida till en annan. T.ex om man vill länka till Google kan man använda a-taggen som det här. <a href="https://www.google.se/">Visit google.se!</a></p>
<hr>

<h2>Oordnad, ordnad och beskriven lista:</h2>
<p>dl-taggen definerar en beskrivingslista</p>
<dl>
  <dt>dt-taggen definerar ett namn i en beskrivningslista</dt>
  <dd>dd-Taggen används i kombination med dl och dt. <br>Inne i en dd-taggen kan du lägga punkter, rader, bilder, länkar, listor osv.</dd>
</dl>
<hr>

<h2>Tabell</h2>

<p>table-taggen definerar en html tabell. Tabellen innehller tr, th och td elementer</p>
<p>tr element definerar en tabell rad</p>

<table>
<caption>caption-taggen definerar en tabell rubrik</caption>
  <tr>
    <th>th element definerar en tabell ruburik</th>
  </tr>
  <tr>
    <td>td element definerar en tabell innehåll</td>
  </tr>
</table>

<p>img-taggen definerar en bild i en html sida. Den taggen kräver två attributer som är: src och allt</p>
</title>
Ett exempel av img-taggen är:
<img src="pictures/pic.jpg" alt="Sea" height="100" width="100">

<p>Alt specificerar en alternativ text för en bild. Src specificerar URL a en bild</p>


<p>map-taggen är använts för att definera en klient-sida bild-map. Den taggen kräver img element och det skapas en relation mellan en bild och en karta.</p>
<p>Map element innehåller ett antal av area element vilket definerar klickbara områden inom bildkarta.</p>

Ett exempel av area-taggen är:
<img src="pictures/pic.jpg" width="145" height="126" alt="sea"
usemap="#seamap">

<map name="seamap">
  <area shape="rect" coords="0,0,82,126" href="sun.htm" alt="Sun">
</map>

</body>
</html>
#try using classses instead of formatting tags
