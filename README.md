# SP702 PythonForDataEngg Capstone
<i> Webscrapping and data cleaning project using Selenium </i>

<h1> <b> Capstone </b> </h1>
Overview of the Case </p>
A certain non-profit organization in the Philippines wants to collect data about hotels, restaurants, tourist sites, etc. for tourists. The organization hired data engineers to collect from different sources and to preprocess the collected data. The data will be used to provide information to tourist for them to create a better itinerary when they visit the Philippines.</p>

<b> Tasks </b>
<li> Gather data from different sources (at least 2 different sources) using python
<li> Enumerate the sources of your data (e.g. name of website - website, PSA - excel/csv, etc.)
<li> Make sure that your sources are credible
<li> Upload all the files (csv files and jupyter files)

<br>
<h3> <b> Task 1: Prepare hotel data </b> </h3>
<li> Extract hotel data(Note: at least 25 different hotels) 
<blockquote> 
<li> Name of hotel 
<li> Location of hotel (Note: Barangay, City/Municipality, Province)
<li> Amenities
<li> Price range (e.g. price per person, room or hour)
<li> Number of available rooms (e.g. number of rooms for two people)
<li> Other data
<li> Customer reviews per attribute of hotels from review sites ( e.g. customer review regarding the customer sercice of hotels). You need to gather at least 15 customer reviews. Make sure that each review is unique and posted by different users
</blockquote>
<li> Store the collected data in a csv file. File name format: Hotel.csv
<li> Please upload your Jupyter notebook file. Filename format: Extract_Hotel_Source.ipynb. Note that you might need to create different python code per source of data. Submit all code you used to extract data</li>
    

<br>
<h3> <b> Task 2: Prepare restaurant data </b> </h3>
<li> Extract hotel data(Note: at least 25 different hotels) 
<blockquote> 
<li> Name of restaurant 
<li> Location of restaurant(Note: Barangay, City/Municipality, Province)
<li> Price range
<li> Specialty (eg seafood)
<li> Other data
<li> Customer reviews per attribute of restaurant from review sites (e.g. customer review regarding the price of food). Makee sure that each review is unique and posted by different users 
</blockquote>
<li> Store the collected data in a csv file. File name format: Restaurant.csv
<li> Please upload your Jupyter notebook file. Filename format: Extract_Restaurant_Source.ipynb. Note that you might need to create different python code per source of data. Submit all code you used to extract data</li>
    

<br>
<h3> <b> Task 3: Prepare tourist site data</b> </h3>
<li> Extract tourist site data(Note: at least 25 different hotels) 
<blockquote> 
<li> Name of hotel 
<li> Classification(e.g. museum, park, zoo, etc.)
<li> Location(Note: Barangay, City/Municipality, Province)
<li> Number of visitors per year(Note: in thousands)
<li> Entrance fee (Note: Peso)
<li> Other data
<li> Customer reviews of tourist site 
</blockquote>
<li> Store the collected data in a csv file. File name format: Tourist_site.csv
<li> Please upload your Jupyter notebook file. Filename format: Extract_Tourist_site_Source.ipynb. Note that you might need to create different python code per source of data. Submit all code you used to extract data</li>
    

<br>
<h3> <b> Task 4: Prepare tourist data per location</b> </h3>
<li> Merge the collected data and group them per location (e.g. hotels, restaurants, and tourist sites in quezon city)
<li> Store the data in a csv file. One csv file per location. File name format: Location.csv
<li> Please upload your Jupyter notebook file. Filename format: Location.ipynb. </li>

<br>
<h3> <b> Task 5: Prepare Location Data</b> </h3>
<li> Given the location you considered in task 4, extract location data.
    <blockquote>
        <li> Location Name (Note: Barangay, CIty/Municipality, Province)
        <li> Population (NOte: Population must be in thousands)
        <li> Available transportation
        <li> Reviews/description of location
        <li> Primary language
        <li> Secondary language
        <li> Other data
    </blockquote>
<li> Store the data in a csv file. One csv file per location. File name format: Tourist_site.csv
<li> Please upload your Jupyter notebook file. Filename format: Extract_Location_Source.ipynb. </li>


<small>
    Sources: <br>
    <i> maps.google.com </i>
    <i> agoda.com </i>
</small>
