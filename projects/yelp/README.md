advos
=====

<br />

Please check here for the commit : https://github.com/ben-nsng/advos

<br />

<p>Extraction from YELP</p>
<div>
First of all, we need to get the data from yelp. There is a bash script inside extraction folder, execute yelp.sh will download 10 pages from yelp, including the most rating 100 restaurants. Then the script will parse the html file and save the restaurant name, rating and address into extraction/result file. After downloading 10 pages, the script further downloads images link and caption for each restaurant. In total there will be thousands images storing into the extraction/result file.
</div>

<br />

<p>Import data to Database</p>

<div>
</div>

<br />

<p>GUI Interface</p>
<div>
GUI interface is written using PHP. The pages will show you which restaurants are in database and you can view more details, let say food images of a restaurant by clicking "view button" for each restaurant. The main page is index.php.
<br />
You can access the index page by this link: http://adv-os.elp-spot.net/
</div>

<br />

<p>Detail of restaurant</p>
<div>
You can view the detail of each restaurant, such as the map location, and all the food images. Here is an example of the detail view: http://adv-os.elp-spot.net/restaurant.php?id=0
</div>

<br />

<p>Result to show arrondissement with most rating restaurant</p>
<div>
The php script calculates which arrondissement has the most rating restaurant. After the calculation, it will show all the restaurant in the google map with markers. And the list of the restaurants will be shown below the map. You can click detail view of each of restaurant. You can access this page: http://adv-os.elp-spot.net/summary.php
</div>