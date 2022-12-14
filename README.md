<h1>City-Hall-Data-Feeds</h1>
<p>This is an RSS feed with frequently updated content issued by the Mayor's Office (City Hall).</p>
====================


<h1>Import The Library</h1>

<b>To use the included Python Library, you must first import it:</b><br />
<code>import CityHall</code>

If the library fails to import, make sure python is set to search the directory that the file is located in. Then restart python and try again.


<h1> Create the CityHall Feed Object</h1>

<b>Creating a CityHall CHF object and setting the API Key/ID:</b><br />
<code>myobj = CityHall.CHF('API ID' , 'API Key') </code>


<b>Changing the API Key or ID for a CityHall CHF object that was already created: </b><br />
<code>
cityHallObj.setID('NewID')<br />
cityHallObj.setKey('NewKey')
</code>


<b>Getting the API Key or ID for a CityHall CHF object that was already created: </b><br />
<code>
cityHallObj.getID() <br />
cityHallObj.getKey()
</code>


<b> Get press releases from City hall using your Cityhall CHF object: </b><br />
<code>
pressReleases = cityHallObj.getCityHallFeed()
</code>


<b> To print the press releases in text format: </b><br />
<code>
print pressReleases.text
</code>

<b>For further documentation and examples, see the integrated help Doc in python:</b><br />
<code>help(CityHall) </code>


